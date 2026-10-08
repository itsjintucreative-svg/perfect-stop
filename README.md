# Perfect Stop 🎯

A minimalist mobile timing game.

## Fastest way to build the APK

1. Create a GitHub repository named `perfect-stop`.
2. Upload all files from this project.
3. Commit/push to the `main` branch.
4. GitHub Actions will automatically build the APK.
5. Open the Actions tab to download the APK artifact.
6. A GitHub Release is also created automatically after a successful build.

## Files

- `www/index.html` — complete game
- `capacitor.config.json` — Android app configuration
- `.github/workflows/android.yml` — cloud APK build
- `package.json` — Capacitor dependencies

## App ID

`com.phinu.perfectstop`

## Important

The workflow creates a **debug APK** suitable for testing and direct download.

For Google Play Store publishing, create a properly signed **release AAB** later.
