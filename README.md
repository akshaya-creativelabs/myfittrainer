# MyFitTrainer V3.1

## Update
Replace `index.html`, `manifest.json`, `sw.js`, and `README.md` in the root of the existing GitHub repository, then commit the changes and wait for GitHub Pages to publish.

## Changes in V3.1
- Uses cleaner, rounded vertical-axis intervals with at least five scale intervals where the graph range permits, while retaining thin horizontal reference lines.
- Fixes graph-point popups with delegated SVG click/keyboard handling and a larger invisible touch target around each orange dot, making taps easier on iPhone. The popup displays the exact value, unit, and date below the graph.
- Retains V2.9 exercise-history reconstruction, animated exercise cues, collapsible history controls, and calendar styling.

## Data safety
The app continues to use the existing localStorage key `myfittrainer_v1`. Do not clear Safari website data when updating.

- Keeps the existing `myfittrainer_v1` localStorage key and all previous features.
