# Signal Voice - APK build
1. Upload all these files to your GitHub repo (keep the .github folder).
2. Open the Actions tab > Build APK > Run workflow.
3. When it finishes, download "signal-voice-apk" (contains app-debug.apk) and install it on Android.
The APK serves the bundled page over http inside the WebView, so a plain http ESP32-CAM address (e.g. http://192.168.1.50) works on the same Wi-Fi.
