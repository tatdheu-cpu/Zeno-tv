# ZENO TV Android TV

Android TV WebView wrapper for the existing ZENO TV demonstration page:
https://tatdheu-cpu.github.io/Zeno-tv/zeno_demo.html

## Build APK
Upload **the contents** of this folder (not the ZIP itself) into a GitHub repository.
Open GitHub Actions > Build ZENO TV APK > Run workflow, then download artifact `ZENO-TV-debug-APK` and extract `app-debug.apk`.
Alternatively open the project in Android Studio and Build APK.

This is an unsigned-for-release debug APK, not a Play Store release. It displays the existing demo website, with no included channels. D-pad focus, playback formats, and remote interaction still require testing on the Sony TV. Streaming may fail for CORS, unsupported codecs, or provider restrictions.
