# marseille_climate_trend
In this script I show how to extract climate data of an area of interest from E-OBS data.
E-OBS data can be downloaded from the Copernicus platform using this link : https://cds.climate.copernicus.eu/cdsapp#!/dataset/insitu-gridded-observations-europe?tab=form
The spatial coverage of E-OBS data is the entire Europe. Temporal coverage is from 1950 to now.

When downloading the data from the Copernicus platfrom, the data from the entire Europe is downloaded in a NetCDF format. Therefore, if you are interested in working with a specific point, you will need to extract data for that point. The purpose of this script is to show how to precisely do that.

You will need latitude and longitude information of your point of interest. Here we are using longitude = 5.4516 , latitude = 43.2541 which correspond to a point in the city of Marseille

The script was written on Python 3.9 using Jupyter Notebook on VS Code
