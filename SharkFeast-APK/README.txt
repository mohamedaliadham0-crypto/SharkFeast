OPTION A - No Android Studio (GitHub, free):
1. Create a new GitHub repository, upload ALL files in this folder
   (keep the .github folder).
2. Open the "Actions" tab -> "Build APK" -> wait ~3-5 minutes.
3. Open the finished run, download the "SharkFeast-APK" artifact (zip),
   unzip it -> app-debug.apk. Install it on your phone.

OPTION B - Android Studio:
File > Open this folder, wait for Gradle sync, then
Build > Build APK(s). The APK is in app/build/outputs/apk/debug/.

To update the game later, replace app/src/main/assets/index.html.
