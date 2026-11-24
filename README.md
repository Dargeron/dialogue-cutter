# Dialogue Cutter (uncompiled prototype)
Android 8+; Media3 Transformer. Select movie, SRT tracks and output directory. Defaults 10-second gap, 2-second padding, 720p. All cues are used as dialogue markers. Keep the app open during export. Output subtitle names follow selection order. Output size and frame-accurate sync require device testing.

Build: upload the project contents (including .github/workflows/build.yml) to a GitHub repository, enable Actions, run Build APK, and download the Dialogue-Cutter-APK artifact. Alternatively run gradle assembleDebug with Gradle 8.9, JDK 17 and Android SDK 35. This source has not been compiled or tested on Android.
