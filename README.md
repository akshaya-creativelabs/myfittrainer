# MyFitTrainer V3.5.1

## What's new
- Logo refresh fix: icon assets use versioned filenames, and the manifest and service-worker cache are updated to request the fresh icon rather than a stale cached one.
- Added Backup & Restore on the Progress tab.
- Export includes measurements, exercise set logs, sessions and stored app data. On iPhone, use the share sheet and save the JSON file to iCloud Drive.
- Restore validates the JSON structure and shows record counts before asking for confirmation. It creates a local IndexedDB safety snapshot before replacing the current records.
- Preserves the existing `myfittrainer_v1` localStorage key. The app does not automatically upload data to a cloud service; saving an export to iCloud Drive is a user action.
- Retains the fitness logo files and existing workout/progress functionality.

## Deploy to GitHub Pages
1. Keep a copy of the current deployed files and, if possible, export a backup from the existing home-screen app before deploying.
2. Upload all files in this ZIP to the repository's Pages root, replacing the prior app files as a set.
3. Wait for GitHub Pages to publish. Open the website once in Safari to load V3.5.1.
4. In the home-screen app, open Progress → Backup & Restore → Export Backup. Save the resulting JSON file to iCloud Drive.
5. Verify the JSON backup exists in Files before relying on it.

## Important safety notes
- Do not clear Safari website data or change the storage key `myfittrainer_v1`.
- A backup exported from a browser/PWA contains that app context's data. Since Safari and the home-screen app may show different records, export from the home-screen app that contains the complete history.
- Local safety snapshots are stored on the same device and are not a substitute for the iCloud Drive export.
- Automatic background cloud backup is not included; it requires a separate authenticated backend.


## iPhone home-screen icon refresh
The updated icon files have new filenames to bypass stale icon caches. After deploying all files, first open the site in Safari. iOS may continue to display an already-saved home-screen icon; if it does, only after confirming your backup is safe, remove the old shortcut and use Safari Share → Add to Home Screen again. This does not require clearing website data, and the app data key remains `myfittrainer_v1`.
