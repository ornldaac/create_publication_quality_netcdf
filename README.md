# NetCDF Why and How: Creating Publication Quality NetCDF
Demonstrations from the NASA Earthdata webinar presented by ORNL DAAC in September 2019.

**Author:** ORNL DAAC       
**Date:** September 4, 2019       
**Contact for the ORNL DAAC:** support-ornl.gov@earthdata.nasa.gov       

**Keywords:** netCDF, Data Management, Python, OPeNDAP, Web Service, NCO, GDAL       

## Overview       

These tutorials introduce step-by-step methods, software, and tools used to create, visualize, and standardize netCDF files to archive ready formats. The netCDF file format is a recommended format for archival and distribution of multi-dimensional and gridded geospatial data. In the tutorials presented here, daily geoTIFF files are converted to a single multidimensional netCDF file that follows Climate and Forecast (CF) Conventions. Separate tutorials exist demonstrating command line utilities as well as popular programming software are demonstrated.

<img src="images\TimeSeriesSnowDepth_horizontal_crop.png" width="750" style="display:block;margin-left: auto; margin-right:auto;">

## Demonstration Data

Download the geoTIFF demonstration data here:     
https://daac.ornl.gov/resources/tutorials/create_publication_quality_netcdf/singleband.zip

**Archived Dataset**
The learning materials provided in this repository work with data from the *ABoVE: Dall Sheep Response to Snow and Landscape Covariates* data published by the ORNL DAAC. View the User Guide for this dataset: 
https://daac.ornl.gov/ABOVE/guides/Dall_Sheep_Snowpack.html

Mahoney, P., G. Liston, B. Mangipane, and L.R. Prugh. 2018. ABoVE: Dall Sheep Response to Snow and Landscape Covariates, Alaska, 2005-2008. ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/1602

## Webinar
The content in this repository was presented during a NASA Earthdata webinar in September 2019. More information can be found at the following link:
https://daac.ornl.gov/resources/tutorials/create_publication_quality_netcdf/

## Prerequisites

**Command line utilities:** GDAL, NCO, ncdump, nccopy        

**Python packages:** netCDF4, gdal, pyproj

## Procedure

Link to the Command Line (GDAL, NCO) demonstration presented in this webinar:        
[NCO_Demo.ipynb](NCO_Demo.ipynb)

Link to the Python demonstration (Jupyter Notebook) presented in this webinar:         
[Python_Demo.ipynb](Python_Demo.ipynb)

## Related Tutorials
More tutorials related to ORNL DAAC data and web services can be found at the [ORNL DAAC Resources](https://daac.ornl.gov/resources/) page.