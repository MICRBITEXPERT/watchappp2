Option A (no Android Studio): push to a GitHub repo -> Actions tab -> Build APK -> download artifact.
Option B: open folder in Android Studio -> Build > Build APK(s).
Install: adb connect <watch-ip:port> ; adb install -r app-debug.apk
