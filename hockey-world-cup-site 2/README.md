# Hockey World Cup 2026

A static browser game that can be hosted with GitHub Pages.

## Files
- `index.html` — game entry point, including responsive iPhone/mobile layout.
- `manifest.webmanifest` — PWA/app metadata for Add to Home Screen.
- `sw.js` — service worker for app-style caching.
- `icons/` — home-screen icons.

## GitHub Pages
Upload the contents of this folder to the root of a GitHub repository, then use **Settings → Pages → Deploy from a branch → main → /(root)**.

## iPhone
Open the published GitHub Pages URL in Safari and choose **Share → Add to Home Screen**. The game includes iPhone-safe-area support, touch controls, responsive menus, and layouts designed to keep the game's features accessible on narrow screens.

## Multiplayer
The current game is a browser/local-state game. Public hosting does not by itself add real-time multiplayer; that would require a backend/realtime service and shared game state.
