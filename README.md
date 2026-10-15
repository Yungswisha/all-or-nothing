# All or Nothing — Mobile Training App

A static, mobile-friendly training dashboard with selectable Push, Pull, Legs, Upper, and Lower days, a seven-week progression schedule, core finishers, and exercise checkboxes.

## Publish on GitHub Pages

1. Create a GitHub repository (for example `all-or-nothing`).
2. **Extract this ZIP**, then upload **all files and the `icons` folder** to the **root** of the repository. GitHub does not automatically publish a ZIP uploaded as one file.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Visit `https://YOUR-USERNAME.github.io/all-or-nothing/` once GitHub Pages finishes deploying.
5. On iPhone, open the URL in Safari → Share → **Add to Home Screen**.

## Offline use and saved progress

Once visited online and installed/loaded, the service worker caches the dashboard for subsequent offline access. Checkboxes and selected week/day use browser local storage **on that device/browser only**. They do not sync between devices and may be lost if browser site data is cleared. After publishing updates, revisit online to receive the new version.

## Contents

- `index.html`: dashboard
- `manifest.webmanifest`: installable app metadata
- `sw.js`: offline caching
- `icons/`: home-screen icons

No build tools, hosting service other than GitHub Pages, or third-party JavaScript dependencies are required.
