# StandUp Reminder
Android app that sends a stand-up notification every 20 minutes after you tap Start. A foreground service keeps the countdown running when the app is not open (subject to device battery restrictions). Android 8.0+.

## Build APK entirely online (no PC installs)
1. Create a GitHub repository (public repositories offer free GitHub-hosted Actions minutes).
2. Upload **all the contents of this ZIP**, including the hidden `.github` folder, to the repository root. GitHub's browser upload accepts folders when dragged into the upload area; alternatively create `.github/workflows/build-apk.yml` through GitHub's web editor.
3. Open the repository's **Actions** tab, select **Build Android APK**, then **Run workflow**. A push to main also starts a build automatically.
4. Open the completed run, under **Artifacts** download **StandUpReminder-APK**. Extract the ZIP to get `app-debug.apk`.
5. Transfer the APK to your Android phone and open it to install. Android may ask you to allow installation from the app you used to open the APK.

This is a debug APK for personal use, not a Play Store release. Grant notification permission when prompted. Some phones may need battery optimization disabled for reliable reminders.
