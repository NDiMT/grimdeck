# GrimDeck

Android roguelike deckbuilder prototype built with Kotlin and Jetpack Compose.

## Build APK

The repository includes a GitHub Actions workflow. Push to `main`, then open **Actions → Build APK** and download the `GrimDeck-debug-apk` artifact.

Local build:

```bash
gradle wrapper --gradle-version=8.5
./gradlew assembleDebug
```

APK output:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Notes

The app is set up to build without Android Studio. The large PNG sprite pack from the original zip is not committed here yet, so this version uses procedural/Compose visuals and placeholders for a reliable Android build.