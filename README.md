# 🦈 cudas.party

Kettle Moraine State Forest camping trip site — June 12–14, 2026.

## Stack
- Static HTML/CSS/JS — hosted on CloudFront + S3
- MapLibre GL JS + PMTiles for interactive hillshade map
- OSM-derived POI data (campsites, toilets, showers, grocery, McMiller)
- Custom SVG icon set, light/dark theme

## Files
- `index.html` — main site
- `map.html` — standalone map page
- `pois.geojson` — OSM POIs (campsites, toilets, showers, grocery, McMiller)
- `roads_simplified.geojson` — simplified road network for the region
- `icons/` — SVG icon set (light + dark variants)
