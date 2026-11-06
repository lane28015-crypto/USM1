# USM — Velocity GPS

A simple black-and-red checkerboard GPS handoff and phone-music app with white rose accents, theme settings, brightness control, and custom themes.

## Build an Android APK

GitHub Actions builds a debug APK automatically whenever code is pushed to `main`.

1. Open the [Actions page](https://github.com/lane28015-crypto/USM1/actions).
2. Select **Build USM Android APK**.
3. Open the newest successful run.
4. Under **Artifacts**, tap **USM-Android-debug-APK** to download the ZIP.
5. Open the ZIP on your Android phone and extract `app-debug.apk`.
6. Tap the APK to install it. If Android asks, allow your browser or file manager to install unknown apps, then retry.

The artifact is temporary and currently retained for 14 days. Only install builds from this repository that you trust.

## Current limitations

- Maps opens turn-by-turn directions in Google Maps; it does not embed Google Maps or provide a native Android Auto navigation service yet.
- Music plays audio files you choose from your phone. It does not sign in to Spotify/Apple Music or automatically scan the full music library.
- Brightness adjusts the app interface, not the phone's system brightness.
