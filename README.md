# High Numbers

An idle dispensary tycoon by Orchid-42. Grow flower, press hash, bake edibles and roll smokables, hire dealers to automate them, serve walk-in customers and go legit for Clout.

Play: https://orchid-42.github.io/HighNumbers/

- Pure HTML, no build step. `index.html` is the whole game.
- Sign-in and cross-device sync use the shared Orchid-42 Supabase project (table `saves`, game key `highnumbers`).
- Installable as a home screen app (manifest + service worker). After uploading a new `index.html`, bump `VERSION` in `sw.js` so phones pick up the update.
