# Home Ownership Rates by State (2025)

## About This Map
This map uses US Census data to visualize home ownership rates by state. It uses a choropleth symbolization with 5 classes and the natural breaks classification method. When you hover over a state the border is bolded to show that you have selected it and a popup that displays the state name and homeownership rate appears.

### Author
**Blythe Crady** 

**Data:** U.S. Census Bureau, Housing Vacancies and Homeownership (CPS/HVS), Annual Statistics: 2025. Table 15, “Homeownership Rates by State.” [Census HVS Dataset URL](https://www.census.gov/housing/hvs/files/annual25/ann25t_15.xlsx)

## How This Map Was Made
This map uses the javascript library Leaflet, the ESRI World Light Gray basemap, a shapefile from the US Census Bureau Cartographic Boundary files page, as well as the font Helvetica. I used google sheets to clean the dataset, then used ArcGIS to join the dataset to the state file on the field State Name. Then used GeoJSON.io to export the joined shapefile as a geoJSON file which I could then display.
