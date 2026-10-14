# MyFitTrainer V2.3

V2.3 updates the Home dashboard while retaining the existing `myfittrainer_v1` local-storage key.

## Home improvements
- Compact dashboard layout designed to bring today's plan, progress, and weekly plan into one mobile view where screen height permits.
- Seven-day horizontal plan strip; tap a day to expand its workout details and choose that workout.
- Current day highlighted in orange, completed workout days in blue, and missed past weekday sessions in red. Weekend days remain optional.
- Motivational welcome message based on saved completed-session dates and the current consecutive-day streak.
- Brighter blue, orange, cyan and purple accents.

## Deploy
Replace `index.html`, `manifest.json`, `sw.js`, and `README.md` in the root of the existing GitHub Pages repository. Commit and wait for Pages deployment. Open the versioned URL in Safari, then reopen the Home Screen app. Do not clear website data; workout data is stored locally.
