# MyFitTrainer V3.4.2

## Update
Replace `index.html`, `manifest.json`, `sw.js`, `README.md`, and the new `glute-bridge.gif` in the root of the existing GitHub repository. Commit the changes and wait for GitHub Pages to publish.

## Changes in V3.4.2
- Adds the requested baseline measurement for 8 Oct 2026: 98 kg and 110 cm waist. If a record already exists for that date, it is corrected instead of duplicated. Existing later measurements and workout data are retained.
- Fixes the “Change Since First” calculation by sorting measurements chronologically; the baseline is used as the first record.
- Adds a Body Measurement Trends selector for weight, waist, or both in one chart. Combined mode uses separate scales because kg and cm are different units.
- Removes the generic animated stick-figure cues that could show the wrong movement. Uses the supplied demonstration GIF for Glute Bridge / Hip Thrust, and displays exercise-specific written cues for other exercises until verified matching demonstrations are added.

## Data safety
The app continues to use the existing localStorage key `myfittrainer_v1`. Do not clear Safari website data when updating.


V3.4.2 specifically fixes touch activation on body-measurement chart points by binding click and pointer-up directly to each point.
