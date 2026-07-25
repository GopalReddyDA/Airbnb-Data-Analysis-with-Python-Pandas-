# 🏠 Airbnb Data Analysis with Python

## Project Overview :

### Situation :
Airbnb has thousands of listings across different neighborhoods, room types, and price ranges. Guests often struggle to find the best place within their budget, while hosts need to understand how their listings compare with others.

### Task :
The goal of this project was to analyze Airbnb listing data and answer key business questions, including:

- Which neighborhoods have the highest prices?
- Which room types are the most popular?
- How available are listings throughout the year?
- Are there unusual price outliers?
- What insights can help guests and hosts make better decisions?


## Dataset :

The dataset contains **20,765 Airbnb listings** with **22 columns**.

### Main Features

- **ID** – Unique listing ID
- **Listing Name** – Airbnb property title
- **Host Name** – Name of the host
- **Neighborhood Group** – Borough where the property is located
- **Latitude & Longitude** – Property location
- **Price** – Nightly rental price
- **Room Type** – Entire home, private room, or shared room
- **Reviews per Month** – Average monthly reviews
- **Availability_365** – Number of available days in a year



# Project Workflow :

## 1. Data Cleaning

- Removed missing values from important columns.
- Converted the **last_review** column into datetime format.
- Handled extreme price values by capping listings above **$1,000** to reduce the impact of outliers during analysis.



## 2. Exploratory Data Analysis (EDA)

Performed analysis to understand listing patterns and business trends.

- Analyzed the distribution of room types.
- Compared average prices across neighborhoods.
- Studied yearly availability of listings.
- Explored relationships between price, reviews, availability, and beds.
- Identified hosts managing multiple listings.



## 3. Data Visualization

Created different charts to better understand the data.

- Bar Charts
- Histograms
- Boxplots
- Heatmaps
- Pair Plots



# Key Insights :

## Price Analysis

- Manhattan has the highest average listing prices.
- Brooklyn is the second most expensive neighborhood.
- Entire homes cost much more than private or shared rooms.


## Room Type Analysis
- Entire Home/Apartment is the most common room type.
- Private Rooms are a budget-friendly option for travelers.



## Price Outliers :

- A small number of listings were priced above **$10,000**.
- Removing or capping these outliers improved the accuracy of the analysis and visualizations.



## Availability Trends

- Listings with higher yearly availability often receive more reviews.
- Lower-priced listings tend to be available for more days.



## Host Analysis

- Some hosts manage multiple Airbnb properties.
- This indicates that many listings are operated by professional hosts instead of individual homeowners.



# Results

### For Guests
- Identify affordable neighborhoods.
- Compare room types based on budget.
- Find listings with better availability.

### For Hosts

- Understand local pricing trends.
- Compare listings with competitors.
- Improve pricing and availability strategies.



# Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook



# Conclusion : 

This project demonstrates how Python and Exploratory Data Analysis (EDA) can transform raw Airbnb listing data into meaningful business insights. By cleaning the data, analyzing trends, and creating visualizations, the project helps both guests and hosts make better decisions based on real data.
