# Build the APK from your Android phone

You do not need Android Studio on your phone for this route. GitHub Actions can run the Gradle build on a hosted runner and save the APK as an artifact.

1. Create/sign in to a GitHub account in Chrome.
2. Create a new repository, for example `Mughal-Muscat-Car-Bid`.
3. Upload the extracted project files/folders into the repository (including `.github/workflows/build-apk.yml`).
4. Open the repository's **Actions** tab.
5. Choose **Build Android APK** and tap **Run workflow**.
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run, find **Artifacts**, and download `mughal-muscat-car-bid-debug-apk`.
8. Unzip the downloaded artifact if necessary and install `app-debug.apk` on your Android phone.

GitHub's documentation confirms that Actions can build code on GitHub-hosted virtual machines and that workflow artifacts can be downloaded after a run.

This produces a debug APK for testing. A Play Store release needs a signed release build and Play App Signing setup.
