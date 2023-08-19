# Small-data-project-with-climate-and-geographical-data
Data science project

In this notebook, an evaluation of climate data will be carried out from the database of the Spanish Meteorological Agency, [AEMET](https://www.aemet.es/es/datos_abiertos), specifically a time series of precipitation and temperature provided by this entity and coming from any of the active meteorological stations closest to a certain point or point of interest. 

This information provided by AEMET for users is done through an API for public use and accessible through API-KEY, so to reproduce this code it will be necessary to register [here](https://opendata.aemet.es/centrodedescargas/altaUsuario).

**Objective**

Present a collection of functions and processes representing a very common workflow of a data science project, from extraction, to data transformation, figures generation and some preliminar statistic analysis, within the context of climate change and geographical data. 

**Methodology**

1. Import libraries.

2. Defining access variables.

3. Map display with folium: point of interest selection (PI) and closest stations (CS):

   *  [Point of interest](folium_maps/point_of_interest.gif) 

5. Requests of climate data through API interaction.

6. Data processing and application of the necessary transformations. 

7. Figure generation to graphically describe the evolution of temperature and rainfall variables within a previously selected time frame.

8. Automation of the comparative analysis to assess whether there have been significant changes in rainfall between the different years of dataset coverage.

9. Conclusions

* **NOTE**: github does not allow html display, as jupyter notebooks are hosted as an static file in git repos. Nevertheless in this repository you'll find the html files for the two maps (point_of_interest.html, with the initial point of interest all_geo_elements.html, with the geographical elements calculated through the previous steps) and an interactive version of the jupyter notebook hosted in binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SalvaRGb/Data_Science_proj_Small-data-project-with-climate-and-geographical-data/master?labpath=Small%20data%20project%20with%20climate%20and%20geographical%20data.ipynb)
