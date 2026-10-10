PBG Tracker — free installable web app (PWA)

Files:
- index.html: the app
- manifest.json: install metadata
- sw.js: app-shell offline cache
- icon.svg: app icon

Quick test:
1. Open index.html in a modern browser. OCR requires internet access for PDF.js/Tesseract CDN libraries.
2. For installation as an app, publish these files to a static HTTPS host such as GitHub Pages.
3. On Android Chrome, open the HTTPS URL, then menu ⋮ → Install app / Add to Home screen.

Important:
- Records are stored in this browser on this device; export JSON backups regularly.
- No cloud sync, user login, or guaranteed background push alerts in this starter version.
- OCR suggestions are not authoritative. Verify all values and especially PBG number, amount, expiry date, and claim deadline against the original guarantee.
- Do not use this starter version as the sole official record without testing and following your department's information-security rules.
