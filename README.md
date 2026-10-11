# Launglon landslides 2026: drone tile sets (3)

Web-map tiles (512 px WebP, XYZ scheme; Leaflet `tileSize: 512, zoomOffset: -1`) for the dashboard at
https://geonet-myanmar.github.io/launglon-landslides-2026/, hosted separately so that site and the other tile repos
(launglon-landslides-tiles, launglon-landslides-tiles-2) stay under GitHub Pages' 1 GB limit.

| folder | survey | resolution |
|---|---|---|
| `oct11/` | San Hlan and Ti Zit village, Launglon Township, flown 11 Oct 2026 | 11.3 / 12.0 cm, tiles z13-z20 |
| `yankin/` | Yan Kin Taung, Launglon Township, flown 11 Oct 2026 | 7.1 cm, tiles z13-z21 |

Built by `scripts/10_tiles.py oct11|yankin` in the `launglon-landslides-2026` repo; do not edit by hand.
