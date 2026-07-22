# Assignment 3: Creating a Simple Map with Folium and Python

## 🌍 Live Interactive Map

Explore the interactive Dublin Bike Stations map:

👉 **https://sunday2023539.github.io/Dublin-Bike-Rental-Location/dublin_bike_stations_map.html**

> **Note:** If GitHub Pages is not enabled yet, this link will not work. Enable GitHub Pages in your repository settings first.

---

## 🗺️ Static Map Preview

Click the image below to open the **interactive map**.

[![Dublin Bike Stations Map](DublinBikeStation.PNG)](https://sunday2023539.github.io/Dublin-Bike-Rental-Location/dublin_bike_stations_map.html)

---

# Introduction

This project demonstrates how to create an interactive web map using **Folium** and **Python**.

Folium is a Python library built on the Leaflet.js framework that allows users to visualize geospatial data on interactive maps. It supports markers, popups, choropleth maps, and many other interactive features.

The project also uses **Pandas**, an open-source Python library for data manipulation and analysis. Pandas was used to load, process, and prepare the Dublin Bikes dataset before visualizing it on an interactive map.

Because the dataset contains geographic coordinates (latitude and longitude), it is well suited for interactive mapping. In this project, **Pandas** was used for data processing, while **Folium** was used to create the interactive visualization.

---

# Geospatial Libraries

- **Folium** – https://python-visualization.github.io/folium/
- **Pandas** – https://pandas.pydata.org/

---

# Dataset

The dataset contains the locations of Dublin Bike rental stations and was obtained from the Smart Dublin Open Data Portal.

Dataset Source:

https://data.smartdublin.ie/dataset/dublinbikes-api

---

# Objective

The objective of this assignment was to:

- Load Dublin Bike station data.
- Process the data using Pandas.
- Create an interactive map with Folium.
- Display each bike station as an interactive marker.
- Export the map as an HTML file.

---

# Methodology

1. Import the required Python libraries.
2. Load the Dublin Bike dataset into a Pandas DataFrame.
3. Extract the latitude and longitude coordinates.
4. Create a Folium map centred on Dublin.
5. Add a marker for each bike station.
6. Automatically fit the map to include all stations.
7. Export the interactive map as an HTML file.

---

# Output

The project produces an interactive web map that allows users to:

- Zoom in and out.
- Pan across Dublin.
- Click individual bike station markers.
- Explore bike station locations interactively.

---

# Repository Files

- `DublinbikeLocation.ipynb` – Jupyter Notebook containing the Python workflow.
- `dublin_bike_stations_map.html` – Interactive Folium map.
- `DublinBikeStation.PNG` – Static preview of the map.
- `README.md` – Project documentation.

---

# Conclusion

This assignment demonstrates how Python and Folium can be combined to transform geographic data into an interactive web map using only a few lines of code. It provides a simple introduction to web-based GIS visualization and serves as a foundation for more advanced geospatial mapping projects.
