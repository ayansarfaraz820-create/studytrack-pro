STUDYTRACK PRO - PWA PACKAGE

Files
- index.html: the StudyTrack Pro app
- manifest.json: install and display settings
- sw.js: offline caching
- icon.svg, icon-192.png, icon-512.png: app icons

IMPORTANT: A service worker and PWA installation require HTTPS or localhost. Opening index.html directly as a file will run the app, but will NOT enable PWA installation or offline service-worker caching.

Recommended next step
1. Publish the contents of this folder to a static HTTPS host (for example, GitHub Pages). Upload the files themselves, not the ZIP as a single file.
2. Open the published site in Chrome or Edge while online.
3. Wait for the page to finish loading, then use the browser's Install app option (usually shown in the address bar or browser menu).
4. Open StudyTrack Pro once while online so the app files and the PDF library can be cached.
5. In Settings, use Backup & restore -> Export backup regularly. Keep a copy somewhere safe.

Data is stored in this browser on this device. Cloud sync from the original Claude-hosted environment is not available in this standalone version. Export a JSON backup before clearing browser data or changing browsers/devices.

PDF generation uses the original jsPDF CDN script. It requires internet on first load; after the library has loaded successfully, the browser may cache it, but offline PDF export is not guaranteed until verified.
