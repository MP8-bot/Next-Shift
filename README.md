# NEXT SHIFT 3.0 — free hockey development PWA

This is an additive upgrade to NEXT SHIFT 2.0. It preserves the existing planner, off-ice exercise library, stickhandling, 12 Hockey IQ lessons, film room, fuel & recovery, journal and local backup/import.

## New in 3.0
- Shooting Academy: shot-type drills, on/off-ice ideas, short session builder and technique checkpoints.
- Mindset Academy: focus, resets, visualization, confidence and a pre-game checklist.
- Elite Habits: daily habit check-in and a rolling 7-day consistency snapshot.
- Performance Analysis: Polar screenshot preview plus manual HR session entry, transparent average-HR × duration estimate, and a 60-second HR drop calculation when both values are supplied.

## Important limitations
- Completely free, no account, subscription or paid API.
- Data is stored in this browser on this device. Export a JSON backup before changing devices or browser data. Import remains available in Journal & Backup.
- The Polar image is preview-only and is not stored. This version does not automatically interpret graph pixels, detect hockey shifts or infer exact recovery from a screenshot. Enter values from Polar yourself.
- HR calculations are descriptive estimates, not medical advice or a readiness diagnosis. Compare sessions only when conditions and measurement methods are similar.
- The habit tracker is a supportive reflection tool, not a score of personal worth.

## Update on GitHub Pages
1. In the current app, open Journal & Backup → Export backup. Keep the JSON file somewhere safe.
2. Open your existing GitHub repository.
3. Upload and replace the seven files at the repository root: `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `icon.svg`, and `README.md`. Do not put them inside an extra nested folder.
4. Commit the changes. Wait for GitHub Pages to publish.
5. Open the app in Safari. If the old version remains, close it and reopen; if needed, visit the Pages URL in a Private tab once to refresh the service worker cache.
6. Your old local data should remain because the storage key is unchanged (`nextShiftData_v1`). If anything looks missing, import the backup you exported in step 1.

## Local testing
Open `index.html` via a local web server for full PWA/service-worker behavior.
