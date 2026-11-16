# Map library

MapLibre GL JS 4.7.1, served from this site so the Sidestreet app does not have to fetch it from a public
CDN. The app loads `4.7.1/maplibre-gl.js` and `4.7.1/maplibre-gl.css` into the map screen (see
`lib/mapHtml.ts` in the app).

Each version keeps its own folder, so an older build of the app keeps working after a newer one is added.

MapLibre GL JS is BSD-3-Clause licensed; `LICENSE.txt` is the licence as shipped with the library.
