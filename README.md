# us-census-tracts-shapefiles-and-geojson
Title's pretty clear :- US Census Bureau sourced tract shapefiles converted to GeoJSON for mapping purposes

## How these files were made:

### Pipeline:
1. Downloaded from the US Census bureau (state wise shapefiles) (https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2019&layergroup=Census+Tracts I think, or something similar.) 
2. Unzipped them all to one folder
3. went to MAPSHAPER.ORG, uploaded them all and downloaded them as geojson
4. wrote a python script to add a variable name so that I can just include it into the index.html (this is the geojson-js folder)

I m pretty sure I've covered the continental United States, I may be missing a state or territory, feel free to open an issue to report it and I'll add the relevant geojson.

Like the nice folks at [world.geo.json](https://github.com/mehrotrasan16/world.geo.json), I am not sure if I'm violating some census bureau terms and conditions by leaving this out for everyone.

And A good place to test these is on https://geojsonlint.com/, they've got bunch of sample GeoJsons too.
