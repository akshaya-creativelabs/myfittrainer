# MyFitTrainer V1.5

Updated workout navigation, set logging/editing, rest timer refresh, workout restoration, parking reminder, and a separate restart-session control.

## Deploy
Upload `index.html`, `manifest.json`, `sw.js`, and `README.md` to the root of the existing GitHub Pages repository, replacing the existing files, then commit. Open the Pages URL with `?v=15` to request the latest page.

## Data
Workout records remain in browser local storage under `myfittrainer_v1`. Do not clear site data during updates. Refresh reloads the app and does not intentionally clear stored records.
