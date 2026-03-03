# Python_Visuals
Fun data visuals on various topics created using Python.

### Legalisation of Same-Sex Marriages
Compiling various data sources to try to create a map that shows the progression of same-sex marriages across countries.
[Link](https://github.com/sverma1012/Python_Visuals/tree/main/Same-Sex%20Marriage) <br> 
#### <b> Order of Files </b>
1. lat_log.ipynb <br>
   Loads the data on same-sex marriage legalisation and uses the Nomination API to get latitude and longitude values for each country.
2. ETL.ipynb <br>
   Combines the legalisation information with the geospatial information from lat_log.ipynb.
3. visualisation.ipynb <br>
   Creates a choropleth map based on the data. However, some countries are not showing up in the map or are not hoverable for the entire duration of the animation.
4. ETL2.ipynb <br>
   Ensures that the geospatial information is repeated for every row and adds a category for the legal status of same-sex marriages.
5. visualisation2.ipynb <br>
   Creates choropleth maps and describes the process and results.
