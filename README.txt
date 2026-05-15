samd app APK path

This folder is a PWA-ready package prepared from your final design.
To convert it into an Android APK, the fastest official-style route is:
1. Host this folder online over HTTPS.
2. Verify the PWA opens correctly and installs from the browser.
3. Use Bubblewrap to generate an Android project and signed APK/AAB from the web manifest.
4. Or open the generated Android project in Android Studio and use Build > Generate Signed Bundle / APK.
