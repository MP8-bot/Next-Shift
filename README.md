# NEXT SHIFT — free PWA starter

A responsive, installable-style hockey development web app. The current starter includes:
- Dashboard and daily hockey cue
- Weekly planner with schedule-aware, readiness-aware rule-based guidance
- Off-ice exercise library
- Six editable-progress Hockey IQ lesson cards
- Position-specific film-study prompts and outbound YouTube searches
- Performance journal
- Local browser storage plus JSON export/import backup
- PWA manifest and service worker for basic offline access after first load

## Important current limitation
**Cloud sync is not connected in this starter.** Data is stored in the browser on each device. Export/import lets you move a backup manually. Cross-device sync requires setting up a cloud database and authentication (for example, Firebase Spark with email authentication and Firestore within its no-cost quotas) and adding secure user-specific access rules. Do not add private data until access rules are configured and tested.

## Run locally
Open `index.html` in a browser for a quick preview. PWA installation and service-worker caching require serving it over HTTPS or localhost.

## Publish at no cost
A free static hosting provider can serve these files. GitHub Pages supports static HTML/CSS/JS from a public repository on its free plan. Check current provider terms and limits before publishing. Do not commit secrets or API keys to a public repository.

## iPhone / iPad
After publishing to HTTPS, open the site in Safari → Share → Add to Home Screen.

## Data safety
Use Export backup periodically. Browser storage can be cleared by the user or the operating system. This is a starter project, not a medical device or substitute for a coach/physio. Exercise recommendations are generic and should be scaled for fatigue, pain, injury and coach/physio restrictions.
