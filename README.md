# NEXT SHIFT 2.0 — Free PWA starter

A static, installable Progressive Web App for hockey performance, planning, skill development, nutrition education and hockey IQ. Built with plain HTML, CSS and JavaScript. No paid API or external JavaScript dependencies.

## Features
- Dashboard with upcoming schedule and learning progress.
- Visual seven-day calendar, previous/next week navigation, activity icons, filters, add/remove events, and a transparent readiness-aware planning suggestion.
- Expanded off-ice exercise library across speed, power, strength, core, stability, mobility and recovery.
- Stickhandling drill library with on-ice/off-ice options and simple 5/10/15-minute session builder.
- Twelve Hockey IQ lessons, personal cue library, and interactive decision-making scenarios.
- Fuel & Recovery section with a simple daily drink log, in-app hydration check-ins, game-day checklist, and educational content about carbohydrates, protein, fats, micronutrients, hydration, and tournament fueling.
- Film-room prompts with outbound YouTube search links.
- Performance journal, JSON backup export/import, and local browser storage.
- PWA manifest and service worker for installability/offline shell.

## Important limitations
- Data is stored locally in each browser/device; cloud sync and accounts are not included.
- Hydration check-ins are in-app only. Reliable notifications while the app is closed are not implemented.
- Film links are searches, not a curated or automatically updated video feed.
- Planner guidance and exercise cards are general educational templates, not medical advice or a substitute for a coach/physio/sports dietitian.
- Nutrition content is general education, not a personalized diet plan. Fluid needs vary by athlete and conditions; this app intentionally avoids prescriptive fluid or calorie targets.
- Browser storage can be cleared. Export a JSON backup regularly, especially before changing files or devices.

## Publish with GitHub Pages
1. Back up the current app data using **Performance journal → Export backup** if you have data you need to keep.
2. Unzip this package.
3. Upload the *contents* of the `NEXT_SHIFT` folder to the root of your existing public `next-shift` GitHub repository, replacing files with the same names. Keep `index.html` at repository root.
4. Commit the changes to the `main` branch. GitHub Pages should redeploy automatically.
5. Wait for deployment, then refresh the existing website. If the Home Screen app shows the old version, fully close it and reopen; service-worker caches may take a moment to update.

## Local testing
Serve the folder from a local HTTP server (service workers do not work reliably from `file://`) and open `index.html` through that server.
