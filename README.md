# Sentinel2-DSWE

Code for automatically detecting water using the Dynamic Surface Water Extent algorithm.
Originally by John W. Jones of the USGS. Used to create Landsat 8 Level 3 images. I have adapted it for use with Sentinel-2 imagery. 
Compatible with any Sentinel-2 Level 2A image. Utilizes five tests with different threholds to determine degree of confidence of water.
Also creates a cloud mask for reducing error from clouds. 
