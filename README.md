# Screen Print Calculator — PWA

This is a Progressive Web App version of your calculator. On iPhone, open the hosted page in Safari and use **Share → Add to Home Screen** to install it like an app. It works offline once opened at least once.

## Files
- `index.html` — the app UI
- `manifest.webmanifest` — PWA manifest
- `sw.js` — service worker for offline cache
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — app icons

## Hosting
Upload the folder to any static host (GitHub Pages, Netlify, Vercel, your own server). The app must be served over **HTTPS**.

## iPhone install
1. Open the URL in **Safari**.
2. Tap **Share** (square with arrow).
3. Tap **Add to Home Screen** → **Add**.
4. Launch from the home screen like a native app.

## Config
Inside `index.html`, edit the `CONFIG` object for VAT and pricing constants.
