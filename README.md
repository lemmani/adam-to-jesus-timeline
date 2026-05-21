# Adam to Jesus — Biblical & World History Timeline

Interactive D3.js timeline mapping Biblical genealogy from Adam to Jesus alongside world history events, historical figures, civilizations, dominant world powers, and wars by continent.

## Features

- **60 generations** of Biblical genealogy with lifespan bars and begat connectors
- **243 historical figures** (pre- and post-Jesus) across Political, Science, Arts, Military, Religious, and Exploration categories
- **153 major events** plotted on a compressed-then-linear time axis
- **18 dominant world powers** from Sumerian City-States through the United States
- **44 prominent civilizations** distributed across 6 continents
- **1,282 wars** plotted by continent
- **Compressed deep-time** zone (pre-Adam) and linear post-Adam scale
- Pan & zoom with clamping, mini-map, era jump-pills, layer toggles, tooltips

## Run locally

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Tech

Single static HTML file using D3.js v7 (loaded from CDN). No build step.
