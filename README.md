# Forehead Charades

A party guessing game for phones. Everyone joins a room from their own phone (no login),
adds their own words, and one player holds the word to their forehead while the others give hints.

- Static site: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, `vendor/supabase.js`
- Live sync: Supabase Realtime (broadcast + presence) on the `forehead-charades` project. No tables, nothing stored.
- One-phone mode works offline.

## Publish on GitHub Pages
Settings → Pages → Build and deployment → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
