# Water Balance App

This is a [web mapping application](https://livingatlasdev.arcgis.com/waterbalance/) to visualize the worldwide climate data covers the last 17 years from NASA's Global Land Data Assimilation System ([GLDAS](https://ldas.gsfc.nasa.gov/)), which uses weather observations like temperature, humidity and rainfall.

#### This application was built using the following libraries:
- [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/index.html)
- [Calcite-Web](http://esri.github.io/calcite-web/)
- [D3.js](https://d3js.org/)
- [Moment.js](http://momentjs.com/)

#### GLDAS Data
All [five variables from GLDAS](http://www.arcgis.com/home/group.html?id=f615932f60094044b4abca4597444b4c#overview) (precipitation, runoff, evapotranspiration, soil moisture, and snowpack) used by this application are available to ArcGIS users through the [Living Atlas of the World](https://livingatlas.arcgis.com/en/#s=0&q=gldas) as image services .

#### How to use this app?

Click anywhere on the map to see how a chosen variable has changed over time, and click anywhere on the graph to switch the map to that month of interest. The water balance panel (on the left) shows how much recharge or depletion occurred during your chosen month, and how this compares to what’s normal. The trend analyzer panel (on the right) shows how your chosen variable was different in the same month during other years.
![gldas](https://blogs.esri.com/esri/arcgis/files/2017/09/gldas.gif)

---

This application was designed and developed by Esri' [Living Atlas Team](https://livingatlas.arcgis.com/en/#s=0) 

To learn more information about the GLDAS data and this application, please read this [blog](https://blogs.esri.com/esri/arcgis/2017/09/25/explore-climate-trends-with-the-water-balance-app/).
