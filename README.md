# Two's Complement - Mealy Machine (PWA)

A 2-state right-to-left Mealy machine that computes the two's complement of a binary string.
Installable PWA that works offline.

## Files
- `index.html` - the whole app (HTML + CSS + JS)
- `manifest.json` - PWA metadata (name, icons, colours)
- `service-worker.js` - offline caching (bump `CACHE_VERSION` after edits)
- `icons/` - 192, 512 and maskable 512 PNG icons
- `netlify.toml` - Netlify headers so the service worker updates promptly

## Run locally
Service workers need http://localhost or https (not file://).
Use VS Code "Live Server", or run `python -m http.server 8000` in this folder.

## Deploy
Push to GitHub; Netlify redeploys automatically. Then use pwabuilder.com with your Netlify URL to generate the APK.
