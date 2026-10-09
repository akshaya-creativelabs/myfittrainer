# MyFitTrainer V1.7

Targeted iPhone Home Screen rendering update. Avoids transforming the document body, replaces the workout content container after updates, forces a fresh WebKit layout, applies the same repaint handling to Day Summary, and surfaces save errors instead of failing silently. Bumps service-worker cache version. Existing local storage key remains `myfittrainer_v1`.

Deploy `index.html`, `manifest.json`, `sw.js`, and `README.md` to the root of the existing GitHub Pages repository.
