# Tarmac concrete plants and CHRYSO representatives

A static, interactive Leaflet map showing 84 Tarmac concrete/readymix locations and the corresponding CHRYSO representative coverage.

## Website

The site is a single static `index.html` file. It uses CDN-hosted Leaflet, Bootstrap and map-control libraries, so visitors need an internet connection for the map tiles and interface assets.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `chryso-tarmac-coverage-map`.
2. Upload all files from this package to the repository root and commit them to `main`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

The public address will normally be:

`https://YOUR-GITHUB-USERNAME.github.io/chryso-tarmac-coverage-map/`

## Maintenance

Replace `index.html` with a regenerated map and retain the filename. GitHub Pages will redeploy after the commit.

## Data note

Plant marker coordinates in this map are approximate locality centroids rather than verified plant-gate coordinates. Contact names, telephone numbers and email addresses are visible to anyone who can access a public deployment.
