# 🎵 My 2025 Spotify Listening History Analysis

## Project Overview
This project analyzes my Spotify listening history throughout 2025 to uncover music listening patterns, favorite artists and tracks, genre preferences, and listening habits. An interactive Tableau dashboard was created to visualize key insights.

## Objectives
- Identify the most-played artists and tracks.
- Analyze listening patterns by day and hour.
- Explore music mood characteristics and listening duration.

## Tools
- Python (Pandas, Matplotlib)
- Tableau

## Dataset
- Spotify Streaming History (Personal Data)
- Spotify Tracks Dataset (Kaggle)

## Data Preparation
- Converted Spotify Streaming History JSON files into a DataFrame.
- Converted timestamps to datetime format.
- Extracted day and time features.
- Filtered tracks played for more than 10 seconds.
- Removed local files, unknown tracks, and unknown artists to improve data quality.

## Key Insights
- Panic! At The Disco was the most-played artist throughout 2025.
- *I Know It's Over* by The Smiths was the most-played track.
- Listening activity peaked on Mondays at 2:00 PM, totaling over 824 minutes.
- Most tracks were categorized as **Angry/Turbulent** and **Happy/Joyful**, indicating a preference for energetic and emotional music.
- The difference between Top Artists and Top Tracks suggests strong loyalty to a few favorite artists while maintaining diverse music exploration.

## Dashboard
![alt text](Spotify-Listening-History-Analysis/dashboard/Spotify-Listening-Activity-Dashboard.png) 

https://public.tableau.com/views/ListeningHistoryDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
