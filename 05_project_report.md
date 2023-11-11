# Billboard Data Collection Report

## Overview
In this project, I set out to collect data on the Billboard Year-End Top 100 Singles, spanning from 2000 to 2023. The core of my work involved developing two datasets: a basic dataset (`billboard_basic.csv`) and an advanced dataset (`billboard_advanced.csv`). The basic dataset compiles essential song information like title, artist, and album. The advanced dataset expands on this by incorporating various audio features such as tempo, energy, and danceability.

To compile this comprehensive data, I utilized the Spotify API for accessing song information. However, as Spotify lacks any official playlists correlating to Billboard data, it was necessary to establish a "ground truth" for comparison. To achieve this, I scraped song data (titles, artists, and rankings) from Wikipedia. After a long and arduous process of correction and cross-referencing, the complete datasets were generated. My plan is to employ this dataset for various projects, aiming to shed light on trends in song data and, more broadly, pop culture over time.

## Methods

My approach to this project was to divide it into four distinct sections:

### Collecting Data from Wikipedia
- I used web scraping to gather data on song titles, artists, and their rankings from Wikipedia.
### Collecting Data from Spotify
- I found public user-created Spotify playlists, which I scraped to collect basic song data.
- This data was then meticulously compared and adjusted against the Wikipedia data.
### Creating the Basic Dataset
- With the data collected from Spotify, I compiled the billboard_basic.csv, which included fundamental song details.
### Creating the Advanced Dataset
- Finally, I created the billboard_advanced.csv by accessing Spotify's various audio features for each song.

## Reflection
This project was not only a good exercise in web scraping and utilizing the Spotify API, but was also a good opportunity to practice handling JSON files for data collection. It 
provided me with more experience developing methods to efficiently gather large data volumes without risking data loss or system crashes.

Looking ahead, I am excited to use this dataset for future projects. Additionally, I plan to expand on this work by collecting more diverse song data using the code and methodologies developed in this project.
