# MyFitTrainer V1

A phone-first Progressive Web App for the personal training programme.

## V1 features
- Monday-Friday workout plan
- Set-by-set weight/reps logging
- Previous performance shown for each exercise
- "Use previous weights" shortcut
- Body-weight and waist tracking
- Workout history
- Local browser storage (no account/server)
- PWA manifest + service worker

## Running on iPhone
The app must be served over HTTPS (or localhost) for PWA/service-worker features. The simplest Windows-friendly approach is to publish this folder to a static HTTPS host such as GitHub Pages, then open the URL in Safari and use Share -> Add to Home Screen.

## Important
V1 stores data in the browser's local storage. Clearing Safari website data can remove the log, so this version should not yet be treated as the only copy of your fitness records.
