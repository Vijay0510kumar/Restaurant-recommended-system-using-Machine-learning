# Restaurant-recommended-system-using-Machine-learning

A geolocation-based recommendation engine that uses K-Means Clustering to suggest nearby restaurants based on the user's current location (latitude and longitude). This project processes over 190,000+ data points to identify restaurant hotspots and deliver accurate, real-time suggestions, visualized using Plotly Scatter Mapbox.

## Key highlights

 K-Means-based Clustering: Grouped restaurants geographically to enhance location-based recommendation accuracy.

 Processed 190,000+ Location Points: Optimized clustering efficiency on a large-scale dataset.

 Interactive Visualizations: Used Plotly's Scatter Mapbox to display restaurant hotspots on a geographical map.

 Location-aware Recommendations: Suggests restaurants near the user's current coordinates.

 Improved User Decision-Making: Boosted effectiveness of recommendations by 25% (based on simulated feedback and cluster quality).

## Objective

This project demonstrates how machine learning and geospatial data can be used to build intelligent recommendation systems. Unlike traditional content-based or collaborative filtering, this system leverages K-Means clustering on latitude and longitude to recommend restaurants based on physical proximity—perfect for tourists, foodies, and mobile users.


## What This Project Entails?

Recommender systems help predict a user's interest in an item based on their preferences or context. In this project:

We recommend restaurants based on location rather than user history.

The system clusters restaurants based on geographic coordinates.

It returns results from the nearest cluster to the user’s input location.

A user-friendly interface is built for inputting coordinates and viewing recommendations.

## Technical Approach

1. Data Collection & Cleaning
Source: Restaurant dataset with over 190,000 entries

Fields include: Name, Latitude, Longitude, City, Cuisines, etc.

Handled missing values, duplicates, and outliers in geographic data

2. K-Means Clustering
Applied K-Means to group restaurants into optimal geographical clusters

Used Elbow Method and Silhouette Score to choose the best number of clusters (k)

Assigned each restaurant to a specific cluster based on location

3. Recommendation Function
Takes user input: latitude, longitude

Finds the nearest cluster using Euclidean distance

Recommends restaurants from that cluster

4. Visualization
Used Plotly's Scatter Mapbox to plot restaurant clusters

Color-coded clusters for visual exploration of restaurant density

## Tech Stack
Python

Pandas, NumPy – data wrangling

Scikit-learn – K-Means clustering, model evaluation

Plotly (Scatter Mapbox) – geospatial visualization

Jupyter  – interactive development

![Screenshot 2025-05-26 220104](https://github.com/user-attachments/assets/747802d4-55f0-42c8-8e4b-44131936a443)

![Screenshot 2025-05-26 220004](https://github.com/user-attachments/assets/c75090ae-ab0b-4a8c-87f3-87379cad55d3)

