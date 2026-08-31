# 🎃 Pumpkinfest 2026 GPS Map

GPS-enabled map overlay for the North Smithfield High School Pumpkinfest event, built with **MapLibre GL JS**.

## Features
- 📍 **Live GPS tracking** with smooth-drift animation (pings every ¼ sec, eases toward the newest fix)
- 🎚 **Georeferenced event overlay** (2026 Pumpkinfest map, aligned with its rotation)
- 📌 **Tap-to-place pins** with categories (Food, ER, Parking, Generator, etc.), saved to your browser
- 🛰 **Satellite / map toggle**
- 🔄 **Rotate & tilt** — two-finger twist rotates the view, drag up/down tilts for 3D
- 📡 **GPS diagnostics page** (`diagnostics.html`)

## How to use
1. Open the map (must be **HTTPS** for GPS to work in the browser)
2. Allow location access, tap **GPS** to track
3. Tap **📍 Pin**, then tap the map to place a marker

## Tech
- [MapLibre GL JS](https://maplibre.org/) v5.12.0
- Free vector tiles via [OpenFreeMap](https://openfreemap.org) (no API key)
- Overlay georeferenced from the Pumpkinfest 2026 KMZ

## Live site
Served via GitHub Pages: `https://zvrmeatball.github.io/pumpkinfest2026/`
