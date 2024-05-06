# ArcGIS Pro Geocoding Study

## Introduction
This study contains a demonstration of geocoding postsecondary school locations using the Arcpy API.

## Materials
### Postsecondary School Location Data
The source data is located at `https://nces.ed.gov/programs/edge/data/EDGE_GEOCODE_POSTSECSCH_2223.zip`.  The source data is put into the `materials` directory.

## Methods
### `main.ipynb`
`main.ipynb` performs the following primary tasks:

1. Remove previous geocoding outputs.
2. Geocode the addresses in `.\materials\EDGE_GEOCODE_POSTSECSCH_2223\EDGE_GEOCODE_POSTSECSCH_2223.xlsx\IPEDS22_GEOLOAD_230217`.
3. Save the results to `./results/geocode_results.pkl`.

### `clean.ipynb`
`clean.ipynb` removes ArcGIS Pro artifacts from the project and map.

## Results
### `geocode_IPEDS22_GEOLOAD_230217.pkl`
The geocoding results are saved into the `results` directory.

## License
`LICENSE` applies to the respository code.  Please see the relevant license for the repository materials.