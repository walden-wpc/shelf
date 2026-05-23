# walden-shelf

A single-file progressive web app for tracking books, films, series, podcasts, and ideas.

All data stays in your browser's localStorage — no account, no server, no tracking.
Export and import via JSON for backup or device migration.

**Live → [walden-wpc.github.io/shelf](https://walden-wpc.github.io/shelf)**

## Features

- Custom categories (books, films, series, podcasts, ideas...)
- Four statuses: 收藏 / 進行中 / 完成 / 封存
- Colour-coded tags
- Rating (1–10) for completed items
- Notes on every item
- Filter by category or status — sort by date, rating, or title
- Search across titles, notes, and tags
- Light / dark / system theme
- Offline-capable after first visit (PWA)
- Single `.html` file — no build step, no dependencies

## Data & Privacy

All data is stored locally via `localStorage`.  
Export as JSON to back up. Import on any device to restore.

## License

© Walden Chang — Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)