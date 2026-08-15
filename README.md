# 🧊 Fridge Ledger · 冰箱台账

A minimal, no-backend web app for tracking food in your fridge and knowing what's about to expire — before it goes bad.

一个纯前端的冰箱食材管理工具，帮你记录购买日期和保质期，按剩余天数自动排序、按分类筛选，快过期的食材会自动标红提醒。

## Features

- **Add items** with name, category, purchase date, and shelf life (days)
- **Smart presets** — type a common food name (milk, eggs, leafy greens...) and shelf life + category auto-fill
- **Auto-sorted by urgency** — items closest to expiring always float to the top
- **Color-coded status** — green (fresh), amber (expiring soon), red (expired)
- **Category filtering** — filter by 蔬菜水果 / 肉类海鲜 / 蛋奶豆制品 / 主食烘焙 / etc., with live counts
- **Zero setup** — no server, no database, no build step. Just open the HTML file.

## Tech stack

- Plain HTML, CSS, and JavaScript — no frameworks, no dependencies
- Data persistence via the browser's `localStorage` API
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), [Inter](https://fonts.google.com/specimen/Inter) (loaded from Google Fonts)

## Getting started

No installation needed.

1. Clone or download this repo
2. Open `fridge-tracker.html` in any modern browser
3. Start adding food

```bash
git clone https://github.com/<your-username>/fridge-ledger.git
cd fridge-ledger
open fridge-tracker.html   # or just double-click the file
```

### Optional: host it online for free

Enable **GitHub Pages** in your repo settings (`Settings → Pages → Source: main branch`), and the app will be live at:

```
https://<your-username>.github.io/fridge-ledger/fridge-tracker.html
```

## Data & privacy

All data lives in your browser's `localStorage` — nothing is sent to a server. This means:

- ✅ No account, no setup, fully private
- ⚠️ Data doesn't sync across devices or browsers
- ⚠️ Clearing browser data will erase your list

## Roadmap

- [ ] Edit existing items (currently delete-and-re-add)
- [ ] Browser notifications for expiring items
- [ ] Backend + database for cross-device sync
- [ ] Barcode scanning for faster entry
- [ ] Consumption stats / waste tracking dashboard

## License

MIT — free to use, modify, and share.
