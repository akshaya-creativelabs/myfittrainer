# MyFitTrainer V1.8

This release fixes the saved-data migration issue that caused `db.sessions.filter` to fail in the iPhone Home Screen app. On startup and before saving, it normalizes missing `sets`, `measurements`, and `sessions` arrays while preserving existing valid records under the existing `myfittrainer_v1` storage key.

## Deploy
Replace `index.html`, `manifest.json`, `sw.js`, and `README.md` in the root of the existing GitHub Pages repository. Commit and wait for deployment. Open the V1.8 URL once in Safari, then fully close and reopen the Home Screen app. Do not clear website data.
