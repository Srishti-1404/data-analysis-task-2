# Task 2 - Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a cleaned Netflix dataset from Task 1. The analysis focuses on understanding the structure of the dataset, identifying trends and patterns, calculating important statistics, and generating meaningful insights.

## Objective

The objective of this project is to explore the cleaned Netflix dataset using Python and identify useful patterns, trends, distributions, and anomalies through statistical analysis and data visualization.

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Dataset

The dataset contains information about Netflix movies and TV shows, including title, type, director, cast, country, date added, release year, rating, duration, category, and description.

## Analysis Performed

- Dataset overview and descriptive statistics
- Movies vs TV Shows analysis
- Top countries by number of titles
- Top Netflix content categories
- Release year trend analysis
- Content rating analysis
- Content duration analysis
- Duplicate record identification

## Key Insights

### 1. Content Type
Movies are the dominant content type in the dataset, with 6,131 movie titles compared with 2,676 TV shows. This shows that the Netflix catalog contains a significantly larger number of movies than TV shows.

### 2. Top Country
The United States is the leading country in the dataset, with 2,818 titles. This indicates that the United States contributes a major share of the content available in the Netflix dataset.

### 3. Popular Content Category
After separating multiple categories listed in the dataset, international movie content appears as one of the most common categories. This suggests that international content represents a significant part of Netflix's catalog.

### 4. Release Year Trend
The dataset shows strong growth in Netflix content during the late 2010s and early 2020s. The number of titles rises substantially compared with earlier release years, indicating rapid expansion of Netflix's content library during this period.

### 5. Content Rating
TV-MA is the most common content rating in the dataset, indicating that a large portion of the Netflix catalog is targeted toward mature audiences.

### 6. Duplicate Record
The exploratory analysis identified 1 exact duplicate row and 1 duplicate Show ID in the dataset. This was identified as an anomaly during the data quality check.

## Files

- `Netflix_Titles. - netflix_titles.csv (Clean).csv` - Cleaned Netflix dataset
- `EDA_Netflix.ipynb` - Python EDA notebook
- `README.md` - Project documentation
- `charts/` - Data visualizations
