### This code can clip and resample the input raster files.
It provides following two main operations.
- Clip and resample an input raster file to match a reference raster.
- Resample an input raster file to an arbitrary resolution and a region.

Example of situations that this code might be helpful:
- We have many files that must have a same dimention and CRS as a reference raster. For example, combined use of MODIS products that have different spatial resolutions.
- We want to reduce the region of interest to a smaller scale. 
- We want to change the resolution to a different scale. 
