# Suave Droning Orthomosaic Viewer (Leaflet + Base Map)

This variant includes:
- A free OpenStreetMap base layer
- Your orthomosaic tiles as an overlay
- A layer toggle and an opacity slider

## Quick Start
1) Export your orthomosaic to `tiles/{z}/{x}/{y}.png` in Web Mercator (EPSG:3857).
2) Replace the empty `tiles/` folder with your exported tiles.
3) Push to GitHub and enable Pages (Settings → Pages → Deploy from branch → `main` → `/root`).

## Notes
- If your orthomosaic isn’t georeferenced correctly, it may not align with OSM. Ensure your export uses Web Mercator and correct georeferencing.
- If you just want your ortho without any base map, use the other template without a basemap.
