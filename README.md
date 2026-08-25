# Seafood Human Capital and Infrastructure Project (SHIP) - Seafood Processing

## About
The Seafood Human Capital and Infrastructure Project (SHIP) is an intra-agency effort designed to address
critical data gaps within the American seafood sector. Fisheries infrastructure (e.g., docks and vessels) and
human capital (e.g., fishing crews and processing workers in the seafood sector) are the key foci of this study. This repository focuses on the seafood processing sector.



## Repository Structure
```
|── ship-processing 
|└── README.md
|└── ship-processing.Rproj
|└── scripts
|  └── coastal-counties.qmd     # Analysis of coastal counties
|  └── data-axel-matching.qmd   # Matches data axel and processed products data based on company name
|  └── data-cleaning.qmd        # Cleans and geocodes processed products data (should be run first)
|  └── port-analysis.qmd        # Analysis of port groups
|└── scripts
|└── .gitignore  
|  └── data/
```


## Data

- [Processed Products](https://www.fisheries.noaa.gov/inport/item/20758) - Confidential data containing information on US Seafood Processors
- [ESRI Data Axle](https://doc.arcgis.com/en/esri-demographics/latest/arcgis-places/data-axle.htm) - Business location information on seafood processors using NAICS codes
- [ENOW Costal Counties](https://coast.noaa.gov/digitalcoast/training/enow-counties-list.html) - Coastal county shapefiles



