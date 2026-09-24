# Gate Time Tracker — Android Studio Project

This project wraps the supplied `gate-time-tracker-FINAL.html` in an Android WebView.

## Build
1. Open this folder in Android Studio.
2. Let Gradle sync/download the Android Gradle Plugin and SDK components if prompted.
3. Select `app` and run on an Android device/emulator, or choose **Build > Build APK(s)**.
4. The generated debug APK will normally be under `app/build/outputs/apk/debug/`.

## Important
- The original HTML is bundled inside the APK and works offline.
- JavaScript and browser DOM storage are enabled, so the app's existing localStorage data model is preserved.
- JSON restore/import file selection is supported by the WebView wrapper.
- Android notification permission is requested on Android 13+.
- The app does not add cloud synchronization; the supplied HTML remains localStorage-based.
