# Visualizing fire scars through false color imagery 
## Eaton and Palisades Fires of January 2025

![[AP Photo/John Locher](https://www.carriermanagement.com/news/2025/01/24/270837.htm)](https://www.carriermanagement.com/assets/3-Moratoriums.jpg)


## Purpose
This creates false color imagery to visualize the fire scars of the Eaton and Palisades Fires in Los Angeles County that occurred in January 2025. This workflow involves integrating raster and vector data. Landsat 8 satellite imagery provides the spectral bands needed to best visualize the fire scars on the landscape, while the fire perimeter shapefiles show the spatial extent of the fires. When mapped together, the data reveal that the areas within the fire perimerters are now vastly distinct from areas that were unaffected by the fires. 


## Repository structure
The repository is structured as follows:
```
eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-GONZALEZ.ipynb
│--  .gitignore
```


## Data

* The satellite data used for this analysis comes from Microsoft's Landsat Collection 2 Level-2 Dataset. Data from this dataset is atmospherically corrected surface reflectance data that was collected by the Landsat 8 satllite. The Landsat image taken in January of 2025 contains 5 bands (red, green, blue, near-infrared, and shortwave infrared). The image was clipped to the greater Los Angeles County area which contains the fire perimeters. See more [here](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2).

* Data for the Eaton and Palisades Fire perimeters (vector data) were provided by the Los Angeles County. Specifically, the fire perimeters were extracted from CAL FIRE's Historical Perimeter dataset. They note that the boundary polygons were dissolved for each fire to create a single fire burn perimeter. See more [here](https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).

# References


County of Los Angeles. (2025). Palisades and Eaton Dissolved Fire Perimeters (2025) [Data set]. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c

Microsoft. (n.d.). Landsat Collection 2 Level-2. Microsoft Planetary Computer [Data set]. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

