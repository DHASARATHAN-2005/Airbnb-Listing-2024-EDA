# Airbnb Listing 2024 - Exploratory Data Analysis (EDA)
## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Airbnb Listing 2024 dataset. The objective is to analyze Airbnb listings, identify patterns, understand pricing trends, and extract meaningful business insights through data visualization.

## Objectives
Understand the structure of the Airbnb dataset.
Perform data cleaning and preprocessing.
Analyze listing prices and availability.
Explore relationships between room types, locations, and prices.
Visualize trends and patterns using charts and graphs.
Generate insights that can help hosts and customers make informed decisions.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

## Dataset Features

The dataset contains information such as:

Listing ID
Neighbourhood Group
Room Type
Price
Minimum Nights
Number of Reviews
Reviews Per Month
Availability (365 days)
Latitude & Longitude
Beds
## Project Workflow

1. Data Loading
Imported the Airbnb dataset into a Pandas DataFrame.
2. Initial Exploration
Viewed dataset structure using:
head()
tail()
shape
info()
describe()
3. Data Cleaning
Checked missing values.
Identified duplicate records.
Prepared data for analysis.
4. Exploratory Data Analysis

## Performed various analyses including:

## Price Analysis
Box Plot for price distribution.
Histogram to understand price frequency.
## Availability Analysis
Distribution of availability_365.
## Neighbourhood & Room Type Analysis
Compared average prices across neighbourhood groups and room types.
## Review Analysis
Examined the relationship between number of reviews and listing prices.
## Feature Relationship Analysis
Pair Plot for:
Availability
Minimum Nights
Number of Reviews
Price
## Geographic Analysis
Visualized listing locations using latitude and longitude.
## Correlation Analysis
Generated a correlation heatmap to identify relationships among numerical features.
## Key Insights
Price distribution is highly skewed with a few expensive listings.
Room type significantly impacts listing price.
Availability varies across listings and neighbourhoods.
Review count does not always correlate with higher prices.
Geographic location influences pricing and listing density.
## Visualizations Included
Box Plot
Histogram
Bar Plot
Scatter Plot
Pair Plot
Heatmap
## Conclusion

The analysis provides valuable insights into Airbnb listings by exploring pricing patterns, availability trends, customer reviews, and geographical distribution. These findings can support better decision-making for property owners, travelers, and business stakeholders.

## Author

Dhasarathan M
Aspiring Data Analyst