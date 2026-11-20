# YOJA Care

A lightweight, installable skin-care journal based on your supplied Skin Log HTML app, rebranded with a sunflower identity.

## Files in this package
- `index.html` — the YOJA Care application
- `manifest.webmanifest` — installable app metadata
- `sw.js` — service worker for offline app-shell caching
- `assets/yoja-mark.svg` — sunflower logo
- `assets/icon-192.png` and `assets/icon-512.png` — app icons
- `.nojekyll` — GitHub Pages static-site marker

## Publish with GitHub Pages
1. Download and extract this ZIP on your device.
2. Open the extracted `yoja-care` folder. Upload the **contents of that folder** to the root of a GitHub repository (not the ZIP file itself). `index.html` must be at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/`.
7. Open the URL in Safari on your iPhone. Use **Share → Add to Home Screen**.

For a repository named `YOUR-GITHUB-USERNAME.github.io`, the URL is `https://YOUR-GITHUB-USERNAME.github.io/`.

## Data, privacy, and backups
- This is a static website. It does not require a server, database account, API key, or build step.
- Journal entries, product lists, and photos are stored locally in the browser on the device where they are entered. They do **not** automatically sync between devices.
- Use the app's backup/export feature regularly and keep the backup somewhere private and safe. Restore from that backup if needed.
- Clearing Safari website data can erase locally stored entries and photos. Back up before clearing browser data or changing devices.
- GitHub Pages serves the website files publicly. Journal data is not sent to GitHub by this app, but never commit personal journal exports or photos to a public repository.
- YOJA Care is a personal tracking journal, not a medical device or a substitute for professional medical advice.

## Notes
- No hosting setup can guarantee zero issues on every device/browser. The included files have been checked for basic package structure, JSON validity, and JavaScript syntax; test the published site on your own iPhone before relying on it.
- If an installed copy shows an older version after an update, close and reopen it after GitHub Pages finishes deploying.
