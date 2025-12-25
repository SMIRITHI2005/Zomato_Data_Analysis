Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on the Zomato restaurant dataset for Bengaluru city.
The objective is to understand restaurant trends, customer preferences, pricing patterns, ratings behavior, and service availability to derive meaningful business insights useful for food delivery platforms like Zomato and Swiggy.

 Objectives

* Explore and understand restaurant data in Bengaluru
* Clean and preprocess a real-world, large dataset
* Analyze online ordering and table booking trends
* Study relationships between ratings, cost, location, and restaurant type
* Identify popular restaurant chains and best locations
* Derive actionable business insights

 Dataset Description

* Source: Zomato Bengaluru Restaurants Dataset
* Rows: ~50,000
* Columns: 17

 Columns

* url – Restaurant Zomato URL
* address – Restaurant address
* name – Restaurant name
* online_order – Online delivery availability (Yes/No)
* book_table – Table booking availability (Yes/No)
* rate – Restaurant rating
* votes – Number of user votes
* phone – Contact number
* location – Restaurant locality
* rest_type– Type of restaurant
* dish_liked – Popular dishes
* cuisines – Cuisine types
* approx_cost(for two people) – Average cost for two
* reviews_list – Customer reviews
* menu_item– Menu items
* listed_in(type) – Type of service
* listed_in(city)– City category

Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

Data Exploration

* Loaded and inspected dataset
* Identified numerical and categorical features
* Checked missing values and data types

Data Cleaning

* Dropped redundant columns
* Renamed columns for clarity
* Removed duplicates
* Cleaned rating and cost columns
* Handled missing values
* Converted data types for analysis

Data Visualization & Analysis

* Online order availability
* Table booking analysis
* Rating vs table booking
* Location-wise restaurant distribution
* Rating trends by location
* Restaurant type analysis
* Cost vs rating analysis
* Most popular restaurant chains

Key Visual Analysis Performed

* Restaurants delivering online vs offline
* Restaurants allowing table booking
* Table booking vs rating comparison
* Best locations by restaurant count
* Relationship between location and rating
* Distribution of restaurant types
* Gaussian distribution of ratings
* Cost distribution of restaurants
* Most famous restaurant chains in Bengaluru

Key Insights

* Online ordering is widely adopted across Bengaluru
* Restaurants offering table booking generally have higher ratings
* Certain locations dominate restaurant density
* Cost does not directly correlate with higher ratings
* Casual Dining and Quick Bites are the most common restaurant types
* A few restaurant chains dominate customer preference

Business Problems This Dataset Can Solve

* Identifying the best location to open a new restaurant
* Understanding whether online delivery increases ratings
* Deciding optimal pricing strategies
* Finding high-demand restaurant types
* Competitive analysis for food delivery platforms
* Customer preference and market trend analysis

Repository Structure

zomato-restaurant-analysis/
├── data/
│   └── zomato.csv
├── notebooks/
│   └── zomato_eda.ipynb
├── images/
│   └── visualizations.png
├── README.md

Future Enhancements

* Sentiment analysis on customer reviews
* Predictive modeling for restaurant ratings
* Power BI / Tableau dashboard
* Cuisine-level demand forecasting

Author

Smirithi
Aspiring Data Scientist / Data Analyst

Conclusion

This project demonstrates the complete data analysis lifecycle, from raw data cleaning to visualization and business insight generation. It reflects real-world problem-solving skills relevant to the food-tech industry.

