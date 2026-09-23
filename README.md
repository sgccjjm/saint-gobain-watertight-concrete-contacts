# Saint-Gobain Watertight Concrete Contacts

An interactive map of 84 Tarmac concrete/readymix locations and their CHRYSO representative contacts.

## Website

https://sgccjjm.github.io/saint-gobain-watertight-concrete-contacts/

The site is a static `index.html` file published by GitHub Pages from the `main` branch, repository root. Commit an updated file to redeploy.

## Map background

The map uses Leaflet and standard OpenStreetMap tiles, with visible OpenStreetMap attribution. It does not require a CARTO API key. The previous CARTO endpoint returned blurred tiles marked “API KEY REQUIRED”, so it was replaced in September 2026.

An internet connection is required for tiles and CDN-hosted interface libraries. OpenStreetMap tile service is best-effort and subject to its [usage policy](https://operations.osmfoundation.org/policies/tiles/); this site uses normal interactive browser requests and caching, with no bulk or offline downloads.

## Data note

The 84 original location records, territory filters, plant search and representative contacts are retained. Coordinates are approximate locality centroids rather than verified plant-gate coordinates. Contact names, business telephone numbers and email addresses are visible in this public deployment.
