# Gut Tracker

A local-only Progressive Web App for iPhone and desktop browsers.

## Features
- Food, liquid, urine, stool, gas, abdominal discomfort, and body-weight logs
- Automatic timestamps
- Saved reusable food templates
- IndexedDB local storage
- Daily summary
- History + deletion
- CSV export
- JSON backup / restore
- Offline support after first load

## Run locally
A PWA service worker requires HTTP/HTTPS, not opening index.html directly with file://.

From this folder, for example:

python3 -m http.server 8000

Then open:
http://localhost:8000

## Use on iPhone
To install it on an iPhone, host these files on an HTTPS site such as GitHub Pages, Netlify, or Cloudflare Pages.

Then:
1. Open the site in Safari.
2. Tap Share.
3. Choose "Add to Home Screen".

Data stays in Safari/website storage on that device. Export JSON backups periodically because clearing Safari website data can erase local records.
