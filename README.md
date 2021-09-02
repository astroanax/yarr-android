# Android app for yarr
* [yarr](https://github.com/nkanaev/yarr) is a feed reader. The app assumes yarr is running at http://127.0.0.1:7070/ (run it using termux). You can run any http server at port 7070 and access it through this app, but the icons were changed specifically for yarr.
* The url can be changed at `app/src/main/java/at/xtools/pwawrapper/Constants.java` before compilation.
* Compile using `./gradlew build`. apk will be at `app/build/outputs/apk/debug/` and `app/build/outputs/apk/release/`
* Credits to [Android-PWA-Wrapper](https://github.com/xtools-at/Android-PWA-Wrapper) and yarr for icons
