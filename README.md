# Balat Blocks (بلاط)

A portrait Android block-puzzle game. The game UI and logic are bundled locally in a WebView so the core game works offline. Google Fonts are optional and fall back to system fonts.

## Features
- Classic endless mode and 30 adventure levels
- 8×8 board, drag-and-drop pieces, row/column clears, combos and score records
- Undo, hints, gem objectives and saved progress
- Six automatically rotating visual worlds with beveled, glossy cube tiles
- Synthesized sound effects and optional vibration; no external sound files
- Arabic and English UI

## Build locally
Requires JDK 17 and Android SDK Platform 34 / Build Tools 34.0.0.

```bash
chmod +x ./gradlew
./gradlew assembleDebug
```

APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Build on GitHub
Push the repository to `main` or `master`, or run **Build Balat Blocks APK** from the Actions tab. Download the `balat-blocks-apk-*` artifact from the completed run. To also create a GitHub Release with the APK attached, push a version tag such as `v1.1.0`.

## Package
`com.balat.blocks`
