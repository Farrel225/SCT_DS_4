# Traffic Accident Pattern Analysis - Internship Task

This repository contains the analysis for the traffic accident data visualization task.

📝 Project Description

The goal of this project was to analyze a large dataset of US traffic accidents to identify key patterns and contributing factors. The analysis focused on how time of day, weather conditions, and road conditions correlate with accident occurrences. The project also involved visualizing geographical accident hotspots to identify high-risk areas.

📊 Key Insights & Visualizations

Here are the primary findings and the charts generated from the analysis:

1. Accidents Are More Frequent During the Day ☀️ The analysis clearly shows that a significantly higher number of accidents occur during daylight hours compared to nighttime. This is strongly correlated with higher traffic volumes during the day, particularly during morning and evening commutes.

<Image of 'Total Accidents: Day vs. Night' Bar Chart>

2. "Fair" Weather Sees the Most Accidents, but Adverse Conditions are Risky 🌧️ While the majority of accidents happen in "Fair" weather (likely because these are the most common driving conditions), adverse weather like Rain, Snow, and Fog are significant contributing factors. This suggests that while there are fewer accidents in bad weather overall, the risk per driver might be higher.

<Image of 'Top 10 Weather Conditions' Bar Chart>

3. Road Conditions Mirror Weather Patterns 🛣️ Similar to the weather analysis, most accidents occur on "Dry" roads. However, "Wet" and "Snowy/Icy" roads are the next most common conditions, highlighting their danger and impact on vehicle control.

<Image of 'Top 7 Road Conditions' Bar Chart>

4. Hotspots are Concentrated in Urban Areas 🗺️ The geographical visualization revealed that accident hotspots are heavily concentrated in and around major metropolitan areas and along critical highway corridors. This is expected due to the high population density and traffic congestion in these locations.

<Image of Folium Heatmap for Accident Hotspots>

🛠️ Tools & Libraries Used

    Python (as the primary programming language)

    Jupyter Notebook (as the development environment)

    Pandas (for data loading, cleaning, and manipulation)

    Matplotlib & Seaborn (for creating static charts and graphs)

    Folium (for generating the interactive geographical heatmap)
