# Prioritizing Potential Aquaculture Zones along the United States West Coast 

The purpose of this repository is to prioritize Economic Exclusive Zones along the west coast of the U.S. for aquaculture of several species of oyster and the California Spiny Lobster (Panulirus interruptus). Raster data for bathymetry and sea surface temperature is processed and combined to calculate the area in each zone that would be suitable for aquaculture. 

Content:
└─── README.md
└─── qmd/Rmd/Proj files
└─── aquaculture_analysis.qmd 
|   .gitignore
    └───data
        └─── wc_regions_clean.shp
        └─── depth.tif
        └─── average_annual_sst_2008.tif
        └─── average_annual_sst_2009.tif
        └─── average_annual_sst_2010.tif
        └─── average_annual_sst_2011.tif
        └─── average_annual_sst_2012.tif

Data Access: 

The data used in this repository is housed here: (https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view)

Author: Joaquin Sandoval 

References/Acknowledgements: 

Average annual sea surface temperature (SST) from the years 2008 to 2012 was obtained from NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.

Bathymetry data was obtained from: General Bathymetric Chart of the Oceans (GEBCO). 

Maritime boundaries using Exclusive Economic Zones off of the west coast of US were obtained from Marineregions.org.

Panulirus interruptus depth and temperature ranges were acquired from https://www.sealifebase.se/summary/Panulirus-interruptus.html
