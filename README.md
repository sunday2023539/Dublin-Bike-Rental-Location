# Assignment 3: Creating a Simple Map with Folium and Python

## Introduction

This project demonstrates how to create an interactive web map using **Folium** and **Python**. Folium is a powerful Python library built on the Leaflet.js framework that allows users to visualize geospatial data on interactive maps. It supports the addition of markers, popups, choropleth maps, and other map elements with just a few lines of code.

The project also uses **Pandas**, an open-source Python library for data manipulation and analysis. Pandas makes it easy to load, clean, and process tabular data before visualizing it on a map.

Since the dataset contains geographic coordinates (latitude and longitude), it is ideal for demonstrating how location-based data can be displayed interactively. In this project, **Pandas** was used to process the dataset, while **Folium** was used to visualize the bike rental station locations on an interactive map.

---

## Geospatial Libraries

- **Folium** – https://python-visualization.github.io/folium/
- **Pandas** – https://pandas.pydata.org/

---

## Dataset

The dataset used in this project contains the locations of Dublin bike rental stations. It was obtained from the **Dublin Bikes API** provided by Smart Dublin.

**Dataset Source:**

https://data.smartdublin.ie/dataset/dublinbikes-api

---

## Objective

The objective of this assignment is to:

- Obtain bike rental station location data.
- Load and process the dataset using Pandas.
- Create an interactive map using Folium.
- Display each bike rental station as a marker on the map.
- Automatically fit the map to display all bike station locations.

---

## Methodology

1. Import the required Python libraries.
2. Load the Dublin Bikes dataset into a Pandas DataFrame.
3. Extract the latitude and longitude coordinates.
4. Create a Folium map centered on Dublin.
5. Add a marker for each bike station.
6. Adjust the map bounds to include all stations.
7. Export the interactive map as an HTML file.

---

## Output

The project generates an interactive HTML map that can be viewed in any modern web browser. Users can zoom, pan, and click on individual bike station markers to explore their locations.

**Live Interactive Map:**

👉 https://sunday2023539.github.io/Dublin-Bike-Rental-Location/dublin_bike_stations_map.html

---

## Technologies Used

- Python
- Pandas
- Folium
- Jupyter Notebook
- GitHub Pages

---

## Conclusion

This assignment demonstrates how Python can be used to create interactive web maps with minimal code. By combining **Pandas** for data processing and **Folium** for visualization, geographic datasets can be transformed into interactive maps that are easy to explore and share online. This workflow provides a simple introduction to web-based geospatial visualization and serves as a foundation for more advanced GIS and web mapping projects.
