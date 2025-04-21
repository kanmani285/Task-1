Netflix Data Cleaning & Exploration – Task 1

> “Exploration is the engine that drives innovation.”
This project isn’t just about cleaning data—it’s about discovering stories within it.



Overview

This notebook is part of Task 1 in a broader data science journey. Using the Netflix Movies & TV Shows dataset, I performed data cleaning, preprocessing, and a bit of exploratory data analysis to reveal hidden insights.


---

Project Steps

1. Setup

Imported necessary libraries: pandas, numpy, matplotlib, seaborn, and wordcloud

Configured visual styles for better plotting


2. Data Loading

Uploaded the original netflix_titles.csv dataset using Google Colab file tools


3. Initial Data Analysis

Explored data structure: shape, column types, and statistical summaries

Identified missing values and their percentages


4. Data Cleaning

Filled missing values in country, director, cast, duration, and rating with 'Unknown'

Removed entries with missing title or type

Dropped duplicates

Standardized text formats (e.g., title casing and uppercase for rating)

Converted date_added to datetime format

Extracted year_added and month_added from date_added

Cleaned duration column by splitting into duration_int and duration_type


5. Exploratory Data Analysis

Content type distribution: Movies vs. TV Shows

Top 10 countries by content count

Top ratings frequency

Content trends by release year and month added

Word cloud for popular words in titles


6. Export

Saved the cleaned dataset as netflix_titles_cleaned.csv

