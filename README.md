
name: Build ALGAIDA NAG WORK APK

on:
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  build:
    name: Build Android APK
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Repository
        uses: actions/checkout@v4

      - name: Setup Java 17
        uses: actions/setup-java@v4
        with:
          distribution: temurin
          java-version: '17'

      - name: Setup Gradle
        uses: gradle/actions/setup-gradle@v4

      - name: Build APK
        run: gradle --no-daemon assembleDebug

      - name: Upload APK
        uses: actions/upload-artifact@v4
        with:
          name: ALGAIDA-NAG-WORK-APK
          path: app/build/outputs/apk/debug/app-debug.apk
          if-no-files-found: error
