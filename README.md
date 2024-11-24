# Tokyo Airbnb Data Analysis 🏯📊
Project Overview
This project dives into Tokyo's Airbnb market using real-world data to uncover trends, visualize patterns, and predict pricing. The aim is to better understand the dynamics of short-term rentals in one of the world’s most visited cities.

By analyzing anonymized Airbnb data, I identify key insights, map hotspots, and use ML to predict pricing.

Key Features
Data Exploration : Cleaned and analyzed datasets to uncover trends in availability, pricing, and seasonality.

Interactive Maps : Used Folium to create geographic heatmaps, highlighting popular neighborhoods and pricing patterns.

Seasonality Analysis : Explored how availability and pricing change across the year, identifying high-demand periods in Tokyo.

Predictive Modeling : Built MLM like Decision Trees, Random Forests, and XGBoost to predict listing prices.

Data Visualizations : Leveraged Seaborn and Matplotlib to create visuals that communicate key insights effectively.

Technologies Used
Data Tools: Pandas, Numpy for data manipulation and cleaning.
Visualization: Matplotlib, Seaborn, Folium for charts, graphs, and interactive maps.
Machine Learning: Decision Trees, Random Forest, XGBoost.

Future Improvements :
 - Categorize latitude and longitude values into distance-based groups relative to Tokyo’s city center.
 - Explore improved feature engineering techniques to enhance the R² score of the XGBoost model.
 - Simplify the model by reducing the number of parameters to focus on data that is personally relevant. For example, exclude columns related to host details (e.g., profile picture or number of properties in their portfolio). If I were planning a visit to Tokyo, I would prioritize features like property type rather than host-specific information.
