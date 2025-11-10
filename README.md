# Indentifying Impacts of Extreme Winter Storm in Houston, Texas

## Author: Kylie Newcomer
### Date Published: 11/10/2025

This project examines the impacts of the extreme winter storms that occurred in Texas in February 2021, resulting in a major power crisis. The number of homes in Houston that were impacted by the power outages was estimated and analyzed with the socioeconomic demographics of these areas.

## Repository Structure
```text
├── .gitignore
│   └──data
│     ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
│     ├── gis_osm_buildings_a_free_1.gpkg
│     ├── gis_osm_roads_free_1.gpkg
│     ├── gis_osm_roads_free_1.gpkg 2
│     └── VNP46A1
├── Impacts-of-Extreme-Winter-Storms-in-Texas.Rproj
├── README.md
└── texasfreezeanalysis.qmd
```


## Data
#### Night lights
Power outages were visualized using NASA's Worldview Visible Infared Imaging Radiometer Suite (VIIRS) data which can be found [here](https://ladsweb.modaps.eosdis.nasa.gov/search/). Data was selected to February 07, 2021, before the storm and February 16, 2021, after the storm. 

#### Roads
To account for the light that came from major roadways, data for the highways came from [OpenStreetMap (OSM)](https://download.geofabrik.de/). 

#### Houses
Data for houses in the Houston metropolitan is also from [OpenStreetMap (OSM)](https://download.geofabrik.de/).

#### Socioeconomic
The median income for each home came from the [U.S. Census Bureau’s American Community Survey](https://www.census.gov/programs-surveys/acs).

## Workflow
### Locations of blackouts


### Identify socioeconomic deomgraphics across blackout

## References
Román, M.O., Wang, Z., Sun, Q., Kalb, V., Miller, S.D., Molthan, A., Schultz, L., Bell, J., Stokes, E.C., Pandey, B. and Seto, K.C., et al. (2018). NASA's Black Marble nighttime lights product suite. Remote Sensing of Environment 210, 113-143. doi:10.1016/j.rse.2018.03.017.