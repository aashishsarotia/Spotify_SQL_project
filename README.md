# Spotify_Data_Analysis_SQL_Project

This project involves the exploration and analysis of a Spotify dataset using SQL. The dataset contains over 20,000 records of tracks, albums, and associated metadata, sourced from Kaggle. Key attributes include track features such as danceability, energy, and loudness, as well as engagement metrics like streams, likes, and comments.

## Dataset Overview

The dataset contains the following key columns:
- **Artist**: Name of the performing artist.
- **Track**: Title of the track.
- **Album**: Album the track belongs to.
- **Album Type**: Whether the track is part of an album or a single.
- **Audio Features**: Danceability, energy, loudness, speechiness, etc.
- **Engagement Metrics**: Streams, likes, views, comments.
- **Platform**: Where the track was most played (Spotify/YouTube).

## SQL Analysis

The analysis covers a wide range of tasks aimed at uncovering insights from the data:

### 1. Data Cleaning
- Removed entries with invalid duration (e.g., tracks with zero duration).
- Identified and rectified anomalies in the dataset, such as inconsistent album types.

### 2. Exploratory Data Analysis (EDA)
- Total number of artists and albums.
- Distribution of track durations.
- Identification of tracks most played on specific platforms (e.g., Spotify vs. YouTube).

### 3. Analytical Queries
- **Top Streams**: Retrieved tracks with over 1 billion streams.
- **Albums and Artists**: Listed all unique albums with their respective artists.
- **Engagement**: Analyzed total comments for licensed tracks.
- **Singles Identification**: Filtered tracks classified as singles.
- **Artist Activity**: Counted the number of tracks for each artist.

## Key Insights
- Several tracks in the dataset exceeded 1 billion streams, highlighting the popularity of certain artists.
- The platform distribution (Spotify vs. YouTube) shows different patterns of engagement for specific tracks.
- The analysis of licensed content revealed significant engagement, with comments playing a key role in audience interaction.

## Technologies Used
- **SQL**: For data querying and analysis.
- **PostgreSQL**: Database management.
- **Kaggle**: Dataset source.

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset).
2. Import the data into your SQL environment.
3. Run the provided SQL queries to perform analysis and extract insights.
