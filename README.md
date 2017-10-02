# ASTER GED Scripts 
-----------------------------------------------------------------------------------------------------------------------|
This repository contains R and Python scripts for processing Advanced Spaceborne Thermal Emission and Reflection   
Radiometer (ASTER) Global Emissivity Dataset (GED) for version 3 and 4.1 ASTER GED products. The scripts convert ASTER   
GED files from Hierarchical Data Format Version 5 (HDF5, .h5) file format into georeferenced GeoTIFFs. The scripts  
output GeoTIFF files for each science dataset contained in the original ASTER GED file. All results are output in the  
Geographic (latitude/longitude) WGS84 coordinate system.   

## Prerequisites:
#### R (tested in Version 3.3)  

Library   | Minimum Version          
----------| --------------- 
rhdf5     | N/A   
rgdal     | N/A          
raster    | N/A 

#### Python (tested in Version 2.7 & 3.4)  

Library                   | Minimum Version          
--------------------------| --------------- 
h5py                      | 2.6.0   
numpy                     | 1.11.0        
osgeo (with gdal and osr) | 1.11.1
## Procedures:
#### R
1. Copy or clone ASTER GED R script from the LP DAAC Data User Resources Repository  
2. Download ASTER GED data from the LP DAAC to a local directory. See [Data Access](https://lpdaac.usgs.gov/data_access) for information on downloading data.   
3. Start an R session and open ASTER GED R script  
4. Change in_dir to the directory where the ASTER GED files are stored on your operating system  
5. Run script  
#### Python 
1. Copy or clone ASTER GED Py script from the LP DAAC Data User Resources Repository
2. Download ASTER GED data from the LP DAAC to a local directory. See [Data Access](https://lpdaac.usgs.gov/data_access) for information on downloading data.    
3. Start a Python session and open ASTER GED Py script
4. Change inFileLoc to the input ASTER GED file (including the path)  
5. Run script  

## Additional Information:
[ASTER GED V3 Tutorial](https://lpdaac.usgs.gov/user_resources/e_learning/how_convert_aster_ged_v3_science_datasets_georeferenced) 
[ASTER GED V4.1 Tutorial](https://lpdaac.usgs.gov/user_resources/e_learning/how_convert_aster_ged_v4_science_datasets_georeferenced) 
[ASTER GED Products List](https://lpdaac.usgs.gov/dataset_discovery/community/community_products_table)
#### Authors:
Aaron Friesz^1 & Cole Krehbiel^1  
^1 Innovate!, Inc., contractor to the U.S. Geological Survey, Earth Resources Observation and Science (EROS) Center,  
 Sioux Falls, South Dakota, USA. Work performed under USGS contract G15PD00766 for LP DAAC^2.
^2 LP DAAC Work performed under NASA contract NNG14HH33I.

Contact: LPDAAC@usgs.gov 