
name: Build ALGAIDA NAG WORK APK

on:
  push:
    branches:
      - main
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Repository
        uses: actions/checkout@v4

      - name: Setup Node
        uses: actions/setup-node@v4
        with:
          node-version: 22

      - name: Setup Java
        uses: actions/setup-java@v4
        with:
          distribution: temurin
          java-version: 17

      - name: Setup Android SDK
        uses: android-actions/setup-android@v3

      - name: Install Android SDK Packages
        run: |
          sdkmanager "platform-tools" "platforms;android-35" "build-tools;35.0.0"

      - name: Prepare Web App
        run: |
          mkdir -p www
          cp index.html www/index.html
          if [ -f manifest.webmanifest ]; then cp manifest.webmanifest www/; fi
          if [ -f sw.js ]; then cp sw.js www/; fi

      - name: Install Capacitor
        run: |
          npm init -y
          npm install @capacitor/core@7 @capacitor/cli@7 @capacitor/android@7

      - name: Configure Android App
        run: |
          cat > capacitor.config.json <<'EOF'
          {
            "appId": "com.algaidanagwork.app",
            "appName": "ALGAIDA NAG WORK",
            "webDir": "www"
          }
          EOF

      - name: Create Android Project
        run: npx cap add android

      - name: Sync Android Project
        run: npx cap sync android

      - name: Build APK
        run: |
          cd android
          chmod +x gradlew
          ./gradlew assembleDebug

      - name: Upload APK
        uses: actions/upload-artifact@v4
        with:
          name: ALGAIDA-NAG-WORK-APK
          path: android/app/build/outputs/apk/debug/app-debug.apk
