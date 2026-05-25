# walden-shelf

A single-file progressive web app for tracking books, films, series, podcasts, and ideas.

All data stays in your browser's localStorage — no account, no server, no tracking.
Export and import via JSON for backup or device migration.

**Live → [walden-wpc.github.io/shelf](https://walden-wpc.github.io/shelf)**

---

## Features

**Tracking**
- Custom categories — books, films, series, podcasts, ideas, or anything you add
- Four statuses: 收藏 / 進行中 / 完成 / 封存
- Notes on every item
- Rating (1–10) for completed items

**Organisation**
- Colour-coded tags with group management
- Filter by category or status
- Sort by date added, rating, or title
- Full-text search across titles, notes, and tags

**Graph view**
- Force-directed relationship graph linking items to their tags
- Drag nodes, pinch to zoom, two-finger pan
- Toggle type nodes and status opacity

**App**
- Works offline after first visit (PWA)
- Light / dark / system theme
- Installable on Android and iOS via "Add to Home Screen"
- Single `.html` file — no build step, no dependencies

---

## Data & Privacy

All data is stored locally in your browser via `localStorage`.
Use **匯出 JSON** to back up. Use **匯入 JSON** on any device to restore.

> Clearing browser site data will erase your shelf. Back up regularly.

---

## Self-hosting

Download `index.html`, `manifest.json`, `sw.js`, and `icon.svg`.
Deploy to any static host (GitHub Pages, Cloudflare Pages, Netlify).

Update `manifest.json` and `sw.js` to point to your own path if not hosting at `/shelf/`.

---

## Stack

- Vanilla HTML / CSS / JavaScript
- [D3.js](https://d3js.org/) for the graph view
- PWA (Web App Manifest + Service Worker)
- No framework, no build tool, no dependencies beyond D3

---

## License

© Walden Chang — Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
