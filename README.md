# Floodplain-Inundation-Mapping
Archived version of an ArcPy script that takes HEC-RAS hydraulic model output and creates ArcGIS raster file of predicted floodplain extents.
Used to assist US Geological Survey flood early warning system. The data flow is as follows:
1. NOAA weather precipitation forecasts fetched from web.
2. Preiciptation data is fed to HEC-RAS hydraulic modeling software.
3. **Floodplain inundation mapping script creates raster data from HEC-RAS output.**
4. Raster data is packaged and pushed to flood early warning website, mapping predicted flood extents based on original NOAA forecast.
