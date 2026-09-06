# Basic English Grammar V2 — GitHub Pages PWA

This version is prepared for GitHub Pages and can be installed as an app from a supported browser.

## Important: separate app identity
The PWA has a deliberately unique manifest `id`:
`./?pwa=basic-english-grammar-v2-2026`

This is intended to avoid the browser treating it as the same installed web app as an older version that used the previous/default identity.

## Upload to GitHub Pages
1. Create a new GitHub repository (for example `basic-english-grammar-v2`).
2. Upload **all files and folders** from this directory, keeping the `icons` folder.
3. In GitHub: Settings → Pages → Deploy from branch → choose `main` and `/ (root)` → Save.
4. Open the generated GitHub Pages link in Chrome on Android.
5. Use Chrome's **Install app / Add to home screen** option.

## Progress
Progress is saved in browser `localStorage`. No account or database is required. Clearing site/browser data can remove it.

## If an old copy is already installed
Because this version has a new PWA `id` and new app name, it is designed to install separately. If Chrome still shows the old copy, uninstall the old copy once and then install V2.
