# MyFitTrainer V2.9

## Update
Replace `index.html`, `manifest.json`, `sw.js`, and `README.md` in the root of the existing GitHub repository, then commit the changes and wait for GitHub Pages to publish.

## Changes in V2.9
- Adds lightweight, local animated SVG exercise cue illustrations in the Workout tab, with concise form reminders. No external image service is required.
- Reconstructs exercise history from saved session logs as well as the set index, using the session date where available. This helps show sets from newer sessions even if the set index is stale or the exercise name contains the assisted-pull-up suffix.
- Adds five horizontal reference lines and finer y-axis labels to the exercise graph.
- Keeps the existing collapsible history controls and calendar styling.

## Data safety
The app continues to use the existing localStorage key `myfittrainer_v1`. Do not clear Safari website data when updating.
