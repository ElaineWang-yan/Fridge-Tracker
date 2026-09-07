# 🧊 Fridge Ledger

A minimal, no-backend web app for tracking food in your fridge and knowing what's about to expire — before it goes bad.


## Features

- **Add items** with name, category, purchase date, and shelf life (days)
- **Smart presets** — type a common food name (milk, eggs, leafy greens...) and shelf life + category auto-fill
- **Auto-sorted by urgency** — items closest to expiring always float to the top
- **Color-coded status** — green (fresh), amber (expiring soon), red (expired)
- **Category filtering** — filter by vegetables/ seafood / dairy / etc., with live counts
- **Zero setup** — no server, no database, no build step. Just open the HTML file.

## Tech stack

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies
- Data persistence via the browser's `localStorage` API
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), [Inter](https://fonts.google.com/specimen/Inter) (loaded from Google Fonts)

## Roadmap

- [ ] Edit existing items (currently delete-and-re-add)
- [ ] Browser notifications for expiring items
- [ ] Backend + database for cross-device sync
- [ ] Barcode scanning for faster entry
- [ ] Consumption stats / waste tracking dashboard

