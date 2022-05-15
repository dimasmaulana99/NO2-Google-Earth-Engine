# NO2-Google-Earth-Engine
This is GEE code for loading NO2 data from Sentinel-5p imagery

## Used ImageCollection
This data using Sentinel-5p imagery with NO2 band, use _`ee.ImageCollection("MODIS/006/MOD11A1") <https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD11A1/>`___ 

## Spatial bounds
Make a geometry for spatial bounds used in .filterBounds and .clip row
