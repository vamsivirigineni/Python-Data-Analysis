# Spotify Music Dataset Analysis

## Project Overview

This project focuses on analyzing Spotify music data using Python. The objective is to explore track popularity, music genres, song duration, and audio characteristics through data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization.

## Objectives

- Clean and preprocess the Spotify dataset.
- Explore track popularity and music characteristics.
- Analyze popularity across different music genres.
- Investigate relationships between audio features.
- Compare song duration and popularity distributions.
- Create visualizations to identify patterns and trends.

## Dataset Description

The dataset contains Spotify track information, including:

- Track name and artist
- Album name
- Music genre
- Popularity score
- Song duration
- Danceability
- Energy
- Loudness
- Acousticness
- Instrumentalness
- Speechiness
- Liveness
- Valence
- Tempo

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

### 1. Data Loading and Inspection
Loaded the Spotify dataset into Google Colab and inspected its structure.

### 2. Data Cleaning
- Handled missing values.
- Removed duplicate records.
- Removed an unnecessary index column.
- Checked data types and numerical ranges.
- Created a song duration column in minutes.

### 3. Exploratory Data Analysis
Explored popularity, genres, song duration, and audio characteristics.

### 4. Data Visualization
Created visualizations including:
- Bar charts
- Histograms
- Scatter plots
- Box plots
- Violin plots
- Correlation heatmaps

### 5. Statistical Analysis
Calculated average popularity, track duration, and correlations between selected audio features.

## Key Analysis Questions

- Which genres have the highest average popularity?
- How is track popularity distributed?
- Is danceability related to popularity?
- How do audio features correlate with each other?
- How does song duration vary across genres?
- Do explicit and non-explicit tracks have different popularity distributions?
- Is popularity associated with energy or tempo?

## Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, statistical analysis, and visualization using Python.

The analysis explored Spotify track characteristics and relationships between music features and popularity.

## How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Upload the Spotify dataset as `dataset.csv`.
3. Run the notebook cells sequentially.
4. Review the resulting analysis and visualizations.
