# MyFitTrainer V3.5.0

## What's new
- Added Backup & Restore on the Progress tab.
- Export includes measurements, exercise set logs, sessions and stored app data. On iPhone, use the share sheet and save the JSON file to iCloud Drive.
- Restore validates the JSON structure and shows record counts before asking for confirmation. It creates a local IndexedDB safety snapshot before replacing the current records.
- Preserves the existing `myfittrainer_v1` localStorage key. The app does not automatically upload data to a cloud service; saving an export to iCloud Drive is a user action.
- Retains the fitness logo files and existing workout/progress functionality.

## Deploy to GitHub Pages
1. Keep a copy of the current deployed files and, if possible, export a backup from the existing home-screen app before deploying.
2. Upload all files in this ZIP to the repository's Pages root, replacing the prior app files as a set.
3. Wait for GitHub Pages to publish. Open the website once in Safari to load V3.5.0.
4. In the home-screen app, open Progress → Backup & Restore → Export Backup. Save the resulting JSON file to iCloud Drive.
5. Verify the JSON backup exists in Files before relying on it.

## Important safety notes
- Do not clear Safari website data or change the storage key `myfittrainer_v1`.
- A backup exported from a browser/PWA contains that app context's data. Since Safari and the home-screen app may show different records, export from the home-screen app that contains the complete history.
- Local safety snapshots are stored on the same device and are not a substitute for the iCloud Drive export.
- Automatic background cloud backup is not included; it requires a separate authenticated backend.
