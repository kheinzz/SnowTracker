# SnowTracker
A tool to superimpose a gpx track over recent satellite high-res images using free APIs (no back-end; no js framework). It was originally designed to easily assess the snow that could be on my next trek

# The data

- To retrieve the images dates we use STAC API as provided by [Copernicus](https://catalogue.dataspace.copernicus.eu/stac/collections/SENTINEL-2)

- We use Sentinel 2 images provided as WMS by [Sentinelhub](https://documentation.dataspace.copernicus.eu/APIs/SentinelHub/OGC/WMS.html)

- To know if there was snowfalls between the last image and the one you're looking at, we use [open-meteo-archive API](https://archive-api.open-meteo.com/v1/archive)

- Basemap provided by [Maptiler](https://cloud.maptiler.com/)

Mainly made using Claude Sonnet
