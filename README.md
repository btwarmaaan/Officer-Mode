# OFFICER MODE 2.0 — ARMAN KHAN 
A mobile-first, local-first NDA 1 2027 study PWA.

## Files
- `index.html` — complete application (HTML, CSS and JavaScript)
- `manifest.webmanifest` — installable PWA metadata
- `sw.js` — offline app-shell cache
- `icon-192.png`, `icon-512.png` — app icons

## Run locally
For a quick preview, open `index.html` in a modern browser. PWA installation and service-worker offline caching require HTTPS or localhost.

## Install on Android
1. Upload all five app files to the root of a GitHub repository.
2. In GitHub, open Settings → Pages.
3. Choose Deploy from a branch, select `main` and `/(root)`, then Save.
4. Open the published HTTPS URL in Chrome on Android.
5. Open Chrome menu ⋮ → Install app (or Add to Home screen) → Install.
6. Open the installed app once while online so the service worker can cache the app shell.

## Data and backups
Study records are saved in this browser's LocalStorage on this device. Use Progress → Export backup regularly. Import backup restores the exported JSON. Clearing browser/site data can erase local records. The app does not upload personal study data.

## Alarm limitations
Alarm settings are stored locally. In-app timers are armed while the app's browser context remains active; Android may suspend timers or terminate the app in the background. Browser notifications are not exact-time alarms. Use the Android Clock app for critical wake-up alerts.

## Notes
- Daily schedule completion is never automatic.
- Completed scheduled minutes are used for the dashboard study-time total.
- GAT daily allocation in the timetable is 30 minutes current affairs, 60 minutes class, and 30 minutes MCQ/revision.
- Mock-test accuracy is correct ÷ (correct + incorrect); unattempted questions are excluded.
