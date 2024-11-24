# False Color Image of the Thomas Fire (2017)

## About
The purpose of this repository is to visualize the burn scar of the Thomas Fire (2017) using remote sensing techniques.
- Isolate Thomas fire perimeter
- Create a false color image of landsat data
- Create a map of landsat data within the Thomas fire perimeter

## Repository struture
```bash
eds220-hwk4
│   README.md
|   hwk4-task2-fire-perimeter-TORRES.ipynb
│   hwk4-task2-false-color-TORRES.ipynb
|   .gitignore
│
└───data
    │   thomas_fire
    |   California_Fire_Perimeters_9021497757356455187
    |   hwk4_landsat_data
```

## Data
The landsat dataset was retrieved from the Microsoft Planetary Computer data catalogue and pre-processed to remove data outside land and coarsen the spatial resolution. It can be accessed below:

```bash
/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc
```

The California fire perimeters dataset and the Thomas fire shapefile are downloaded and stored in the data folder.

## References
California Department of Forestry and Fire Protection. (n.d.). California fire perimeters (all) [Dataset]. Data.gov. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436

Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6