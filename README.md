# Exploring GeoTiff Files
This repository is to download variables data from GeoTiff files.

I was working on measuring canopy conductance of wild barleys. Further, I needed to see how these traits correlate with their environmental variables such as precipitation, maximum and minimum temperature, altitude, water vapor pressure etc at the center of origin.

I have latitude and longitude coordinates of the center of origin of these wild barleys. Further, the environmental data are available at worldclim.org/version2 (Fick and Hijmans, 2017, https://doi.org/10.1002/joc.5086) at different spatial resolution.

However, the data in worldclim.org are in GeoTiff format which needs to be extracted using softwares such as ArcGis or use R with packages such as raster.

# Files in this repository
1. Map where these 25 Wild Barley's originite
2. Csv file with coordinates data of these 25 barleys
3. R code to extract the data and compile

However, I am not including the data from worldclim.org since it can be downloaded freely and it is a huge file.

# ABOUT THESE WILD BARLEYS
These 25 Wild Barleys are selected by Dr. Gary's lab, Dept Agron Plant Genet, UMN as Minnesota Wild Barley Diversity Collection and crossed with Rasmussen, a commercial barley of Minnesota.

These seeds were freely provided by Dr. Gary's lab (Nice et al 2016, https://doi: 10.1534/genetics.116.190736)
Coordinates data were obtained from Dr. Brian's lab, Dept Plant Patho, UMN (Russell et al 2014, https://doi:10.1371/journal.pone.0086021)
