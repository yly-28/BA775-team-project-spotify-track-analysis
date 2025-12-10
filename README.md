# BA775-team-project-spotify-track-analysis# 
🎵 Spotify Streaming Analytics
BA775 – Business Analytics Toolbox Final Project
Boston University
⸻

## 📄 Project Overview

This project analyzes nearly one million Spotify streaming records to understand the drivers behind track popularity, artist success, regional listening behavior, and long-term chart performance.
Using Google BigQuery (SQL) for data engineering and Tableau for visualization, we developed a comprehensive multi-part exploratory analysis covering audio features, temporal dynamics, artist behavior, and cross-market differences.

Our goal was to answer:

What makes a track globally successful on streaming platforms, and how do these patterns vary across regions, features, and time?

## 🗂️ Data Sources

All data comes from a consolidated dataset hosted on BigQuery:
'ba775-fall25-b03.dataset.final_merged_data'
The dataset includes:
* Track metadata
* Audio features (danceability, valence, energy, acousticness, etc.)
* Streaming counts across regions
* Artist popularity & catalog info
* Daily chart data
* Release dates & album information

We also generated intermediate tables in BigQuery for:
* Popularity tier transitions
* Cluster assignments
* Monthly streaming aggregates
