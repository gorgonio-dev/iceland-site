# Iceland South Coast — 8-Day Route

Interactive campervan itinerary: map with highlighted daily driving route,
satellite overlay, drone zones, volcanoes and campsites.

## Deploy on Render (free)

1. Push this folder to a GitHub repo (index.html + render.yaml at the root).
2. In Render: **New → Static Site** → connect the repo.
3. Build command: leave empty. Publish directory: `.`
4. Deploy — you get a public URL like `https://iceland-south-coast.onrender.com`.

(The `render.yaml` lets you skip step 3 via **New → Blueprint** instead.)

## Run locally

Just open `index.html` in a browser, or:

    python3 -m http.server 8000

then visit http://localhost:8000

## Notes

- Map tiles load retina (@2x) versions automatically on high-DPI screens.
- Satellite = Esri World Imagery; dark basemap = CARTO. Both free-tier,
  no API key needed.
- Everything is one self-contained HTML file — edit the DAYS array at the
  top of the script to change stops.
