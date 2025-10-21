# Traffic Accident Pattern Analysis - Internship Task

This repository contains the analysis for the traffic accident data visualization task.

📝 Project Description

The goal of this project was to analyze a large dataset of US traffic accidents to identify key patterns and contributing factors. The analysis focused on how time of day, weather conditions, and road conditions correlate with accident occurrences. The project also involved visualizing geographical accident hotspots to identify high-risk areas.

📊 Key Insights & Visualizations

Here are the primary findings and the charts generated from the analysis:

1. Accidents Are More Frequent During the Day ☀️ The analysis clearly shows that a significantly higher number of accidents occur during daylight hours compared to nighttime. This is strongly correlated with higher traffic volumes during the day, particularly during morning and evening commutes.

<img width="798" height="835" alt="image" src="https://github.com/user-attachments/assets/61cf246f-b7d4-4b15-96cb-2259122902f9" />

2. "Fair" Weather Sees the Most Accidents, but Adverse Conditions are Risky 🌧️ While the majority of accidents happen in "Fair" weather (likely because these are the most common driving conditions), adverse weather like Rain, Snow, and Fog are significant contributing factors. This suggests that while there are fewer accidents in bad weather overall, the risk per driver might be higher.

<img width="1303" height="833" alt="image" src="https://github.com/user-attachments/assets/ec186b23-e940-42d6-804d-bdba11d9a0fb" />

I used the python library - Folium to display accidents hotspot in the global map.

What is Folium?
At its core, Folium is a Python wrapper for a popular JavaScript mapping library called Leaflet.js.

Think of it this way:

Folium is the bridge 🌉 that lets you use simple Python commands to control the JavaScript engine. It takes your data (like coordinates and values) and writes the necessary HTML, CSS, and JavaScript code to generate a complete, interactive map.

**Key Features and What They Do**

Folium's power comes from its ability to easily add different layers to a base map. Base Maps: You can choose your map style right away. The default is OpenStreetMap, but you can easily switch to others like Stamen Terrain (for topography) or CartoDB darkmatter (for a sleek, dark look).

Markers (Markers & Popups): This is the most basic function. You can place a pin at a specific latitude and longitude. You can also add a popup (which appears when you click the marker) or a tooltip (which appears when you hover).

Heatmaps: This is exactly what we used in your project. It's perfect for showing the density or concentration of points. You give it a long list of coordinates, and it creates that "hotspot" effect, showing where the points are most clustered.

The best part, you can save and export this self-contained HTML file that works completely offline and can be saved in your device.

3. Hotspots are Concentrated in Urban Areas 🗺️ The geographical visualization revealed that accident hotspots are heavily concentrated in and around major metropolitan areas and along critical highway corridors. This is expected due to the high population density and traffic congestion in these locations.
**(The Observation is of a particular country from the used dataset, which is mainly the USA.)**
<img width="1717" height="813" alt="image" src="https://github.com/user-attachments/assets/bf3629dd-6d96-40ee-9e17-ea3eef17a717" />
<img width="1718" height="810" alt="image" src="https://github.com/user-attachments/assets/fac32fec-fb7c-4c83-8343-0500c3f2f701" />
<img width="1715" height="799" alt="image" src="https://github.com/user-attachments/assets/dcf0dfd4-bb82-4bb5-bd4b-aa2e5d00eaaa" />


🛠️ Tools & Libraries Used

    Python & Jupyter Notebook (primary programming language from the development environment)
    Pandas (for data loading, cleaning, and manipulation), 
    Matplotlib & Seaborn (for creating static charts and graphs), 
    Folium (for generating the interactive geographical heatmap)
