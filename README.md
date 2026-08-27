# Gym Tracker Pro V3

A new offline-first React + Vite + Capacitor fitness tracker.

## V3 highlights
- Detailed workout runner with editable sets, reps, weight, completion and per-exercise rest.
- Add/remove/reorder program exercises and duplicate programs.
- Estimated 1RM via Epley formula plus max weight/reps/volume PRs and PR history data.
- Weekly and monthly workout statistics, calendar and frequency trends.
- Exercise library with favorites and custom exercises; deleting an exercise keeps historical sessions intact.
- Profile, body-weight logging, bilingual Arabic/English RTL/LTR, themes, backup/restore.
- Rest timer presets, sound, vibration and local notifications.
- Local persistence with migration from `gym-tracker-pro-v2` and `gym-data-v4`.
- GitHub Actions workflow for Android debug APK.

## Run
```bash
npm install
npm run dev
```

## Android
```bash
npm run build
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug --no-daemon
```

For GitHub Actions, push to `main` or run the Android workflow manually.
