# Thai ↔ English Translator Pro — GitHub Pages

## Publish on GitHub Pages
1. Create or open a GitHub repository.
2. Upload **all four files** from this folder (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) into the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish, then open the published HTTPS URL.

## iPhone
Open the published URL in Safari → Share → Add to Home Screen. First load needs internet. Translation needs internet; the app shell and interface are cached after first load.

## Features
- Thai ↔ English translation with a second service fallback
- Speech recognition when supported by the browser
- Spoken translation, voice selection and speed control
- Automatic translation while typing, plus manual Translate now
- Phrasebook, local history and saved phrases
- Export/import JSON backups
- Installable PWA shell and responsive iPhone layout
- Keyboard shortcut: Ctrl/⌘ + Enter to translate

## Important limitations
- Translation services are third-party public endpoints, not an official guaranteed API. Availability, rate limits and translation quality can vary.
- Speech recognition availability differs by browser/device and may send audio to the browser provider for processing.
- The service worker caches the app interface only; translating still requires internet.
- History is stored in this browser on this device. Export a backup before clearing site data.
