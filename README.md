# Scorekeeper4 (Android Java)

- 4 players, names + score buttons (+5/+10/+20/+40, -10/-20/-40)
- Reset Only Points / Reset ALL
- Dark theme (DayNight) and autosave via SharedPreferences
- GitHub Actions builds APK for you

## How to use
1. Upload all files to a GitHub repo (root keeps `settings.gradle`, `build.gradle`, `.github/workflows/android.yml`, and `app/...`).
2. Go to Actions → run "Android CI (assembleDebug)".
3. Download artifact `app-debug.apk`.
