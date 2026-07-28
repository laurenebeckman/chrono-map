# ChronoMap

**Interactive global historical map overlays** — explore how the world has changed over time by comparing OpenHistoricalMap data with modern basemaps.

Free web / PWA tool for research *and* rabbit-hole exploration.

## Features (v0.1 MVP)

- Global coverage via [OpenHistoricalMap](https://www.openhistoricalmap.org/) vector tiles
- Year / date filtering (prevents anachronisms)
- Clean research-oriented UI with prominent date display
- Shareable URLs that preserve location + year
- Modern basemap toggle
- Mobile-friendly foundation

## Live Demo

Open `index.html` directly or deploy the repo to Vercel / GitHub Pages / Netlify.

## Quick Start (local)

```bash
npx serve .
# or just open index.html in a modern browser
```

## Tech

- [MapLibre GL JS](https://maplibre.org/)
- [OpenHistoricalMap](https://www.openhistoricalmap.org/) tiles + styles
- [`@openhistoricalmap/maplibre-gl-dates`](https://www.npmjs.com/package/@openhistoricalmap/maplibre-gl-dates) for date filtering
- Pure static HTML/JS/CSS (no build step for MVP)

## Attribution

Map data © [OpenHistoricalMap](https://www.openhistoricalmap.org/) contributors  
Modern basemaps © OpenStreetMap / OpenFreeMap contributors  
Built for exploration and research.

## Roadmap ideas

- Opacity / swipe comparison modes
- Selected raster historical map overlays (e.g. public-domain sheets)
- Search + geolocation
- Multi-year side-by-side or simple animation
- Export / citation helpers
- Full PWA install + offline support

---

Created July 2026. Feedback and contributions welcome!
