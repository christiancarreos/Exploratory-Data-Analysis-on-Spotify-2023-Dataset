# Carreos 2ECE-C

# Exploratory-Data-Analysis-on-Spotify-2023-Dataset

# Objectives
The main objective is to perform an exploratory data analysis (EDA) on the dataset containing information about popular tracks on Most Streamed Spotify Songs 2023. This task aims to analyze, visualize, and interpret the data to extract meaningful insights.

1. Understand the structure of the data given.
2. Check the dataset for missing values in preparation for analysis.
3. Calculate the summary statistics to gain insights into streaming and musical patterns.
4. Visualize trends and patterns in a given period and based on the different musical attributes given on the dataset.
5. Analyze and explore the correlations between the variables to understand its relationship.
6. Identify the top performers and the top most streamed tracks.
7. Compare the appearance of tracks on different streaming platforms.

# Libraries used for the code
1. pandas
2. matplot
3. seaborn




## Overview of Dataset
The rows and columns of the dataset, data types of each column, and if there are missing values.

## Basic Descriptive Statistics
1. The mean, median, and standard deviation of the streams column.
2. The distribution of released_year and artist_count
3. Analysis if there are noticeable trends or outliers

## Top Performers
1. The top 5 most streamed tracks
2. The top 5 most frequent artists based on the number of tracks in the dataset
 
## Temporal Trends
1. Analysis of the trends in the number of tracks released over time and the plotted number of tracks released per year.
2. Month with the most releases

## Genre and Music Characteristics
1. The correlation between streams and musical attributes like bpm, danceability_%, and energy_%.
2. The correlation between danceability_% and energy_%.
3. The correlation between valence_% and acousticness_%.

## Platform Popularity
1. Comparison of number of tracks in in_spotify_playlists, in_spotify_charts, and in_apple_playlists
2. Platform that seems to favor the most popular tracks.
 
## Advanced Analysis
1. Analysis of data of patterns among tracks with same key or mode.
2. Analysis that compare the most frequently appearing artists in playlists or charts

## Challenges faced while coding
1. Missing values on the given dataset.
2. Analyzing large datasets slowed down the coding process
3. Analyzing the relationships of the given variables with necessary plotting and visualization.
4. Determining the appropriate codes in order to execute what is being asked to do for the Exploratory Data Analysis.


## Summary:
The Spotify 2023 dataset contains 953 rows and 23 columns.<br/> <br/>
The data types of each column are:<br/>
object: track_name, artist(s)_name, key<br/>
int64: artist_count, released_year, released_month, released_day, in_spotify_playlists, in_spotify_charts, in_apple_playlists, in_apple_charts, in_deezer_playlists, in_deezer_charts, bpm, danceablity_%,valence_%, energy_%, acousticness_%, instrumentalness_%, liveness_%, speechiness_% <br/>

Mean of streams column: 514137424.93907565 <br/>
Median of streams column: 290530915.0 <br/>
Standard deviation of streams column: 566856949.0388832 <br/> <br/>

The distribution of release years shows an upward trend in the recent years. Most of the tracks are from the last decade and it peaked near the year of 2020. This implies that there is an increase in the number of releases in the recent years.<br/>
The majority of the tracks have single artists. The plot shows a downward trend or a decline in the total number of tracks as the artist count increases. This implies that solo artists are more common than collaborations. <br/> <br/>

The track with the highest number of streams in the Spotify 2023 dataset is “Blinding Lights” by The Weeknd, with approximately 3.70 billion streams. <br/>
<br/>
The Top 5 most frequent artists based on the number of tracks in the Spotify 2023 dataset: <br/>
Taylor Swift: 34 tracks<br/>
The Weeknd: 22 tracks<br/>
Bad Bunny: 19 tracks<br/>
SZA: 19 tracks<br/>
Harry Styles: 17 trackstracks<br/><br/>

January is the month that has the most number of track released.<br/><br/>

None of the attributes (bpm, danceability_%, energy_%) seems to influence "streams" significantly but the highest correlation among the other attributes is with "danceability_%" at -0.11 which is still low. <br/><br/>

Correlation between danceability_% and energy_%<br/>
-The correlation between danceability and energy is is 0.198485 or 0.2, which shows a low positive correlation. This shows that as danceability increases, the energy has a tendency to increase slightly.<br/><br/>

Correlation between valence_% and acousticness_%<br/>
-The correlation between valence and acousticness is -0.081161, which shows a very low negative correlation. This shows that as valence increases, acousticness has a tendency to decrease slightly.<br/><br/>

The platform that seems to favor the most popular tracks is the Spotify playlists. The number of tracks in spotify playlists are 4952842, spotify charts has 11445, and apple playlists has 64609.<br/><br/>

C# Major has the highest number of tracks (73), the 2nd highest number of tracks are D Major and G Major (66 each). B Minor has the highest count among minor keys (46), followed b they C# Minor (47. C# is the most popular key when combining both Major and Minor modes (120 tracks).<br/><br/>

Certain artists consistenly appear in more playlists or charts. The Weeknd appeared the most among the other artists, He appeared with a total of 154809 times across all platforms' charts and playlists. <br/><br/>




 
