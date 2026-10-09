# MyFitTrainer V1.2

A mobile-friendly installable web app for tracking gym sessions, sets, measurements and progress.

## Deploy/update with GitHub Pages
1. Extract this ZIP.
2. Upload `index.html`, `manifest.json`, and `sw.js` to the root of your existing `myfittrainer` repository, replacing the old files.
3. Commit the changes and wait for the GitHub Pages deployment to finish.
4. Open `https://akshaya-creativelabs.github.io/myfittrainer/?v=12` and refresh once.

## Notes
- Workout data is stored locally in the browser on the device; it is not synced to a server.
- The weekly target starts at 97.6 kg for a 98 kg starting weight, then aims for roughly 0.4 kg per week toward 90 kg. It will not be shown above the latest recorded weight.


Version 1.3 update: strengthened the Day summary button handler, prevented default button behavior, and added a recovery message if no active session is available. Service worker cache version bumped so the new files refresh.
