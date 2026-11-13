ANAYAT ARTS PWA — INSTALLATION

CONTENTS
- index.html: billing app
- manifest.webmanifest: install metadata
- sw.js: offline app-shell cache
- icon-192.png and icon-512.png: app icons

ANDROID
1. Publish ALL files in this folder to the root of an HTTPS website (GitHub Pages is one option).
2. Open the website in Chrome while online.
3. Allow camera access when prompted, if you want camera barcode scanning.
4. Open Chrome menu (⋮) and choose Install app / Add to Home screen.
5. Open the installed ANAYAT ARTS app. After its first successful online load, the app shell can work offline.

WINDOWS / PC
1. Open the HTTPS website in Chrome or Edge.
2. Use the install icon in the address bar or browser menu > Install this site as an app.

IMPORTANT DATA NOTES
- Billing data is stored locally in the browser/device using localStorage.
- The phone and PC do NOT automatically share or sync records.
- Use Reports & Backup > Download backup, then Restore backup on another device.
- Export backups regularly. Clearing browser/site data may erase records.
- This is a PWA website package, NOT an Android APK.
- Camera barcode detection depends on browser support for BarcodeDetector and HTTPS camera permission.
- USB/Bluetooth barcode scanners that type barcode digits into the focused input can be used as keyboard scanners.
