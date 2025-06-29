# Spotify-Music-Insights (1976-2025)

[Introduction](#Introduction)

[Objective](#Objective)

[Tools and Methods](#ToolsandMetods)

[Key Metrics and Dimensions](#KeyMetricsandDimensions)

[Key Observations](#KeyObservations)

[Recommendations](#Recommendations)

[Conclusion](#Conclusion)

## Introduction

This report presents an analytical overview of Spotify music data spanning the years 1976 to 2025. The dashboard developed using Power BI explores patterns in track popularity, artist
performance, and musical durations to uncover key insights in the evolving music industry.

### Objective

The objective of this project was to develop an interactive and insightful Power BI dashboard that transforms raw Spotify music data (spanning from 1976 to 2025) into actionable business intelligence. The dashboard was designed to:

* Uncover patterns in artist popularity and track duration.

* Analyze music performance by year, album, and individual track.

* Provide recommendations based on listener engagement and output trends.

## Project Scope

### Spotify Dashboard Overview

![SpotifyDashboard](https://raw.githubusercontent.com/Busayoilesanmi/Spotify-Music-Insights-1976-2025-/main/SpotifyDashboard.png)

Focused on analyzing:

* Total tracks released per artist

* Average popularity per artist and by track

* Duration metrics by album and artist

* Popularity trends across decades

* Key track-level data such as name, duration, and popularity classification

### Links to the Excel Document and Screenshot

https://drive.google.com/file/d/100yxJOtJ97IqLxpF7oCIM5cVBMywkPqP/view?usp=drive_link

https://drive.google.com/file/d/1vXv-gYQ4y3aMQK6BFFISkHvOs_FspBgx/view?usp=drive_link

## Tools and Methods

### Tools Used

* Power BI: For data modeling, DAX calculations, and interactive visualizations

* Power Query: For data extraction, cleaning, and structuring

* DAX Measures: For calculating popularity averages, total tracks, and track durations

* Link to the dataset used: https://www.kaggle.com/datasets/kunalgp/top-1000-most-played-spotify-songs-of-all-time

### Data Preparations

* Cleaned and standardized artist, album, and track fields

* Created custom columns for duration in minutes and popularity levels (Low, Moderate, High)

* Mapped track release years to enable trend analysis

* Built relationships across album, artist, and track tables

## Key Metrics and Dimensions

### Metrics:

* Total Tracks

* Average Popularity

* Average Track Duration (in minutes)

* Track Popularity per Artist

* Total Duration by Artist

### Dimensions:

* Artist

* Album

* Track Name

* Release Year (1976–2025)

* Popularity Category

* Duration (in minutes)

## Key Observations

* Total Tracks Analyzed: 1,000 tracks
  
* Average Track Popularity: 56.67

* Average Track Duration: 3.32 minutes
  
* Gracie Abrams is the most popular artist (score: 97), followed by ROSÉ (96) and Arctic Monkeys (93).
  
* The Weeknd has the highest number of released tracks (26), followed closely by Taylor Swift (25).
  
* The track “Make Me Not” is the most popular (popularity score: 224).
  
* FERRARI F… and LIVE FORE… are albums with the longest average track durations (~1.43 mins).
  
* Popularity trends peaked between 2020 and 2022, followed by a slight decline.
  
* Tracks classified as “Low Popularity” generally have shorter or longer durations than average.
  
* Artists like Avril Lavigne and Alan Walker show high output but moderate popularity, indicating opportunity for engagement improvement.
  
## Recommendations

* Promote High-Popularity Artists: Focus on boosting the visibility of top performers like Gracie Abrams and ROSÉ.
  
* Leverage Duration Data: Encourage production of tracks within the 3–3.5-minute range, aligned with listener preference.
  
* Feature Underrated Tracks: Use playlisting to promote longer tracks with low popularity scores.
  
* Analyze 2020–2022 Spike: Investigate factors that contributed to the popularity peak and replicate for upcoming releases.
  
* Support Consistent Artists: Provide marketing and release support to artists with high track volumes but lower popularity (e.g., Alan Walker).
  
*Optimize for Playlist Placement: Highlight songs like “Make Me Not” in curated mood or genre-based playlists.

*Duration-Based Personalization: Use track duration as a segmentation factor in recommendation engines.

* Enable Listener Feedback Loops: Track engagement metrics for low-performing songs to understand skip rates or completion trends.
  
* Year-Based Thematic Campaigns: Design campaigns based on release decades to tap into nostalgia-driven audiences.
  
## Limitations

* The dataset does not include listener demographic or geographical data.

* Popularity scores may be influenced by algorithmic bias or temporary trends.

* The data does not account for marketing spend, label influence, or external promotion.
  
* Duration data is limited to track length and not audio characteristics like tempo or genre.

## Conclusion
This project delivered a comprehensive dashboard analyzing Spotify music insights across nearly five decades. With a balance of quantitative metrics and trend visuals, it provides valuable direction for artist promotion, track optimization, and audience targeting. The dashboard is dynamic, data-driven, and adaptable for future datasets or strategic decisions in the music streaming industry.
