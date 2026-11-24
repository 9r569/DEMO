MUST Venue Finder — Installable PWA demo

Files:
- index.html: demo page structure
- style.css: mobile layout + desktop layout
- app.js: install prompt and interactions
- manifest.json: app name, icon, standalone display mode
- sw.js: basic offline caching
- icons/: app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost during development). Opening index.html directly as a file will not enable installation.

Quick test:
1. Upload this folder to a static HTTPS host (for example GitHub Pages or Netlify).
2. Open the deployed URL in Android Chrome.
3. Use the Install button if Chrome displays it, or Chrome menu > Install app / Add to Home screen.
4. Launch the installed icon. It should open without the normal Chrome address bar and show the fixed bottom navigation.

This is a visual/installation demo only. Building cards and search are sample content, not connected to a database.
