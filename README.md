# NEXT SHIFT — 3.1 update

A free, static hockey-development PWA for GitHub Pages. No paid APIs, accounts or subscriptions are required.

## What's new in 3.1
- Your hand-drawn NEXT SHIFT logo is included as `logo.jpg`; the app header and PWA icon use the new red/black hockey identity.
- Daily original mindset quote, favourite toggle and daily reflection.
- Calendar sessions open an editor: change name, type, date, time, duration and RPE without deleting/recreating the session.
- Each calendar session has a training log. Gym logs support rows for exercise, sets, reps, weight and focus; skill sessions support drill, duration, repetitions and focus.
- Off-ice exercise cards include a movement sketch, general muscle-group tags, execution cues, hockey connection and scaling/safety notes.
- Service-worker cache is bumped to `next-shift-v4` so GitHub Pages clients fetch the new files.

## Preserving your data
The app keeps the existing `nextShiftData_v1` localStorage key and extends its data structure. Existing records are not intentionally reset. Before updating, open Journal & Backup and export a JSON backup. Keep the backup until you have checked the updated app.

## Publish with GitHub Pages
1. Download and unzip this package.
2. In your existing repository, upload/replace all files at the repository root (not inside a nested folder): `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `logo.jpg`, and `README.md`.
3. Commit directly to your Pages branch (usually `main`).
4. Wait for the Pages deployment to finish. Reopen the app; if it still shows an old version, open the Pages URL in a private tab once to refresh the service-worker cache.

## Data and limitations
- Data is stored locally in the browser on that device. Export backups regularly; there is no cloud sync.
- The exercise movement sketch is a general visual cue, not a precise anatomical or technique demonstration. Follow the written cues, coaching and qualified medical/physio guidance for individual restrictions.
- Muscle groups are broad educational guides; exact contribution depends on technique and individual anatomy.
- Heart-rate screenshot preview is local to the current page session. Enter Polar values manually; the app does not automatically read the graph or diagnose recovery/readiness.
- The daily quotes are original NEXT SHIFT reminders rather than attributed quotations, avoiding incorrect attribution.
