# Restaurant Inspection Ratings in Seattle, WA

For this project, I found data on the King County GIS Open Data website surrounding [restaurant inspections.](https://gis-kingcounty.opendata.arcgis.com/datasets/9b1f71cb62c040ad9537e3c7e8578ed5_857/data?geometry=-122.444%2C47.640%2C-122.183%2C47.680&orderBy=DATE_INSPECTION&orderByAsc=false&where=CITY%20%3D%20%27Seattle%27%20AND%20DATE_INSPECTION%20%3E%3D%20TIMESTAMP%20%272020-01-01%2000%3A00%3A00%27%20AND%20DATE_INSPECTION%20%3C%3D%20TIMESTAMP%20%272020-12-31%2023%3A59%3A59%27) The data originally ranged from January 2006 through February 2021. Since the data was redundant (a restaurant can have several inspections of varying results over the span of 15 years), I decided to filter the data to focus on the year 2020. The goal of this web map is to raise knowledge of restaurant's health inspection ratings in Seattle, WA.

The web map was created using HTML, QGIS, Mapbox, and the Leaflet library. The basemap was created using Mapbox, and the data was loaded into QGIS to create the tilesets using the QMetaTiles plugin. HTML and Leaflet were then used to make this an webmap with a zoom control and interactive panel. Users can click a box on the panel to load the locations of restaurants around Seattle with the chosen rating.
The webpage can be found [here.](https://gracel54.github.io/restaurant-inspections/)

![Image of Webpage](/assets/webpageimg.png)
