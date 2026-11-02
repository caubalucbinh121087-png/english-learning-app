# IT English Learning App

GitHub Pages app for English learning and IT Infrastructure interview practice.

## Files
- `index.html` - web app
- `lessons.json` - online lesson database

## GitHub Pages
Keep `index.html` and `lessons.json` in the repository root. Configure GitHub Pages to deploy from the `main` branch and `/ (root)`.

## Updating lessons
Edit `lessons.json` and commit the changes. The app fetches a fresh copy when it opens.

## Learning progress
Learned/review state is currently stored in the browser's `localStorage`, so progress is per device/browser.
