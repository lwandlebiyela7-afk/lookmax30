# LookMax 30 — free Android-first PWA

## What's included
- 30-day daily checklist and roadmap
- Beginner bodyweight workout guidance
- Grooming, skin care, style, posture, nutrition and sleep habits
- Day completion and overall progress
- Per-day mood and notes journal
- JSON progress export and reset
- Offline caching once hosted over HTTPS
- No login, paid products, backend, or tracking

## Important limitation
Progress is saved in the browser's local storage. It is not synced between devices and can be erased by clearing browser data. Export a backup from the Journal tab. This is a PWA, not a signed native APK.

## Fastest free setup from an Android phone
1. Download and extract `lookmax30.zip` using your phone's file manager.
2. Create a free account at https://github.com if you don't already have one.
3. Create a **public** repository named `lookmax30`.
4. In the repository, upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` from this folder (not the ZIP itself).
5. In repository **Settings → Pages**, set deployment source to **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
6. Wait for GitHub Pages to publish the site. Its URL will look like `https://YOUR-USERNAME.github.io/lookmax30/`.
7. Open that URL in Chrome on Android. Use Chrome's menu → **Add to Home screen** or **Install app** if offered.
8. Open it once online; the service worker caches the core app for offline use.

## Local preview
You can open `index.html` directly to preview most features, but installability and offline caching require hosting over HTTPS (or localhost).

## Safety
The app is not medical advice. Use gentle skin care, broad-spectrum SPF 30+ when outdoors, balanced meals, sufficient sleep and safe exercise. Do not use crash diets, unregulated supplements, skin bleaching, or painful facial/jaw exercises. Stop exercise if you experience pain, dizziness, or unusual symptoms.
