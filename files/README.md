# Flowtime

A time-awareness tracker, not a habit tracker. The timer never stops — there's always
a category running, even "Untracked" — so you always see where your time actually went,
not just checked boxes.

## Features
- Continuous timer: no start/stop, only switching categories
- "What were you doing?" reassignment prompt when you switch
- Manual entry for numbers pulled from tools like a browser Webtime Tracker extension
- Today view with a live flow ribbon (continuous timeline, no gaps)
- History with per-day blocks, manual add/edit/delete
- Stats: day / week / month / year views, category bars, goals, month heatmap, period-over-period comparison
- Light/dark theme toggle
- Installable PWA, fully offline, data stored locally (localStorage)
- Export/Import JSON backup

## Run locally
Just open `index.html` in a browser, or serve the folder with any static server:

```
npx serve .
```

## Deploy to GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo Settings → Pages → Deploy from branch → `main` / root.
3. Open the published URL on your phone and "Add to Home Screen" for the full app feel.

## Data & backups
All data lives only in your browser's localStorage on that device. Use
Settings → Export to download a `.json` backup periodically, and Import to restore it
(e.g. after clearing browser data or switching devices).
