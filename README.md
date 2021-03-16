# Grocery Store Access in King County

## Project Description
Grocery Store Access in King County offers a visualization of the relationships between grocery facilities throughout King County and a person's ability to access them. Through this mapping project, users can compare the relationships between grocery stores alongside factors such as median household income, percent people of color, public transit routes, and the total population for a census tract.

## Project Goal
Oftentimes, a person's accessibility for healthy food is limited by their whether or not they have access to transportation, or certain types of stores may be located in more affluent areas. This project attempts to allow users to come to explore these relationships and come to their own conclusions.

## Data Sources
Much of this data can be found on the King County Open GIS Data website, which consolidated census data from the US Census American Community Survey, or data the county tracks themselves. Although there are no dates for this data, most were last updated in 2020.
- [Transit Routes](https://gis-kingcounty.opendata.arcgis.com/datasets/transit-routes-for-king-county-metro-transitroute-line/data?geometry=-122.470%2C47.467%2C-121.816%2C47.548&orderBy=CURRENT_NEXT_CODE)
- [Median Household Income from the American Community Survey](https://gis-kingcounty.opendata.arcgis.com/datasets/median-household-income/data?geometry=-127.019%2C46.778%2C-116.566%2C48.078)
- [Percent People of Color from the American Community Survey](https://gis-kingcounty.opendata.arcgis.com/datasets/percent-people-of-color/data?geometry=-123.099%2C47.269%2C-120.486%2C47.594)
- [Food Facilities, King County Dept of Health Restaurant Inspection database, 2018](https://gis-kingcounty.opendata.arcgis.com/datasets/food-facilites-multiple-classes-for-king-county-food-facilities-point/data?orderBy=SEAT_CAP&page=14)
- [Total Population from the American Community Survey, 2013-2017](https://gis-kingcounty.opendata.arcgis.com/datasets/acs-total-population-acs-b01003-totalpop/data?geometry=-124.412%2C47.106%2C-119.186%2C47.757)

Additional data for grocery stores was found utilizing [Phantombuster](https://phantombuster.com/), a site that allows for data extraction from web searches.

## Applied Libraries and Web Services
- Leaflet
  - Interactive JavaScript map library
  - [L.Control.MousePosition plugin](https://github.com/ardhi/Leaflet.MousePosition)
- FlatIcon
  - Web icon sets and toolkits; source of grocery bag icon
- JQuery
  - JavaScript library for HTML document traversal and manipulation, event handling, animation, etc.
- Chroma.js
  - Javascript library for color conversions and color scales
- CartoDB
  - SaaS cloud computing platform that provides GIS, web mapping, and spatial data science tools. Provided grayscale and streets basemap for this project.
- ArcGIS
  - Cloud-based mapping GIS. Provided satellite basemap for this project.
- Bootstrap
  - Framework for building responsive, mobile-first sites, with [BootstrapCDN and a template starter page](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
- GitHub
  - Internet hosting for software development and version control using Git

## Other Information
Inspiration for this project came from the [Healthy Food Availability and Food Bank Network Report](https://www.kingcounty.gov/depts/health/data/~/media/depts/health/data/documents/healthy-food-availability-report.ashx) put out in February 2019. However, considering there is very limited data on what the researchers define as "healthy" food, and other information such as travel time to these locations, further work is needed to fully understand the implications this visualization may have.

## Acknowledgement
Much of the code for this project was sourced from previous labs for Professor Bo Zhao's class at the University of Washington, Geography 458: Advanced Digital Geographies. Special thank you to Tyler McCrea as well, for their continued support throughout the quarter on these projects. Additionally, thank you to [Monkik on FlatIcon](https://www.flaticon.com/authors/monkik) for the grocery bag icon.
