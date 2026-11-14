# Daymark — Personal Health Tracker

A no-account, offline-first personal health tracker designed for private use.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for the Pages deployment to finish. The site URL should be:

   https://linz6.github.io/health-tracker/

## Install on iPhone

1. Open the published URL in Safari.
2. Tap **Share → Add to Home Screen**.
3. Launch Daymark from the Home Screen.

The app caches its core files for offline use after the first successful load.

## Privacy and data

- Daily entries and baseline notes are stored in the browser's local storage on the device.
- The app has no server, account, analytics, advertising, external libraries, or AI/API calls.
- Data is not synchronized between devices.
- Export a JSON backup regularly. Clearing Safari website data, removing browser data, or losing the device can erase records.
- This is a personal tracking tool, not a diagnostic instrument or substitute for medical care.

## Files

- `index.html` — app interface, local data handling, scoring, charts, backup/restore, and handoff summary.
- `manifest.json` — installable web app metadata.
- `sw.js` — offline caching service worker.

## Personal baseline

This repository is public. Personal symptoms, substance-use information, and lab results are intentionally **not** embedded in the public source. Add private baseline context inside the app on your own device under **Settings → Private baseline notes**. It stays in local browser storage unless you explicitly include it in an exported backup or handoff summary.
