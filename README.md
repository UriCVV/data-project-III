# Office Location Analysis for a Gaming Company (Geospatial data)

## Table of Contents
1. [Introduction](#introduction)
2. [Criteria Weighting](#criteria-weighting)
3. [Data Analysis](#data-analysis)
   - [Startups Analysis](#startups-analysis)
   - [Design Industry Analysis](#design-industry-analysis)
   - [District Scoring Maps](#district-scoring-maps)
   - [Venue Mapping](#venue-mapping)
   - [Final District Selection](#final-district-selection)
4. [Tools Used](#tools-used)
5. [Findings and Conclusion](#findings-and-conclusion)
6. [Data Sources](#data-sources)

## Introduction
This project identifies the best location for a new office for a gaming company. It's a data-driven approach that considers the needs and preferences of the employees.

## Criteria Weighting
The office location is chosen based on these weighted criteria:

- Proximity to design companies: 15%
- School density for employees' children: 20%
- Nearby tech startups: 15%
- Starbucks proximity: 10%
- Travel hubs: 15%
- Entertainment venues: 10%
- Vegan options: 5%
- Basketball stadium: 5%
- Pet groomer: 5%

## Data Analysis

### Startups Analysis
The first plot shows the number of startups per city. Cities with more startups might offer better networking and partnership opportunities.

![alt text](https://raw.githubusercontent.com/UriCVV/data-project-III/main/img/top_cities_startups.png)

### Design Industry Analysis
The second bar plot displays the number of design-related companies in each city. This information is crucial as our designers prefer to be near a vibrant design community.

![alt text](https://raw.githubusercontent.com/UriCVV/data-project-III/main/img/top_cities_design.png)

### District Scoring Maps
Two GeoJSON maps provide a visual score for districts within New York City and San Francisco. The scores are based on our weighted criteria, with color gradients representing the suitability of each district.

![alt text](https://raw.githubusercontent.com/UriCVV/data-project-III/main/img/scores_ny.png)
![alt text](https://raw.githubusercontent.com/UriCVV/data-project-III/main/img/scores_sf.png)

### Venue Mapping
An interactive map highlights venues around the potential office location in SoMa, San Francisco. This map ensures that the chosen location has nearby amenities like coffee shops, restaurants, and other services.

![alt text](https://raw.githubusercontent.com/UriCVV/data-project-III/main/img/soma_venues.png)

### Final District Selection
The final plot compares the top five districts across the selected cities, scored on our criteria. This visual helps in making the final decision on the best district for the office.

## Tools Used
- [Jupyter Notebook](https://jupyter.org/)
- [Foursquare API](https://developer.foursquare.com/)
- [Google Maps API](https://developers.google.com/maps)
- [MongoDB Geospatial Queries](https://docs.mongodb.com/manual/geospatial-queries/)
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Folium](https://python-visualization.github.io/folium/)


## Findings and Conclusion
The analysis concludes with the South of Market (SoMa) district in San Francisco as the top location for the new office. This district scored highest on our criteria and offers a rich array of amenities.

## Data Sources
GeoJSON data for the district maps was obtained from:
- [NYC Open Data](https://opendata.cityofnewyork.us/)
- [DataSF](https://datasf.org/)

