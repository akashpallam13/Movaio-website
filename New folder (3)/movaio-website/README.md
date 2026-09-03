# Movaio Website

Responsive static marketing website for Movaio, designed as a standalone alternative to the Gamma landing page reference.

## Included
- `index.html` — complete website structure and content
- `styles.css` — responsive design, desktop/tablet/mobile layouts, animations
- `script.js` — mobile menu, reveal animations, dynamic year
- `manifest.webmanifest` — optional installable/PWA metadata
- `assets/movaio-logo.png` — Movaio logo artwork

## Run locally
Open `index.html` directly in a browser, or serve the folder with any static web server.

Example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish
This folder can be deployed as a static site to Netlify, Vercel, GitHub Pages, Cloudflare Pages, Hostinger, or any normal web host.

## Before launch
Replace `hello@movaio.in` in `index.html` with the final business email and connect the CTA/contact flow to your preferred form backend or CRM.
