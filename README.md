# The Road to Spotify Wrapped 2023 

<img src="https://github.com/hamdamoha/project1_spotify/blob/main/Readme%20images/Spotify_Logo_CMYK_Green.png" width="350">

This is a team-based project that explored the key characteristics of successful songs on Spotify. 

## Contents
* [Dataset](#dataset-header)
* [Project Outline](#project-header)
* [Example Plots](#example-header)
* [Findings Reports and Presentation](#reports-header)
* [Dependencies and Setup Required](#dependencies-header)
* [How to View / Run the code](#how-header)
* [Jupyter Notebooks File Guide](#which-header)
* [Repository Structure](#structure-header)
* [Team](#team-header)

## <a id="dataset-header"></a>Dataset
We used data we extracted from Spotify. Spotify allows you to create a developer account and then offers various end points that you can use to extract information.  
We used
* Get Playlist Items: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-playlists-tracks
* Get Artist: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-an-artist
* Get Track: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-track

Spotify produces playlists of the Top Tracks for each year based on their own analysis. 

Example playlist: https://open.spotify.com/playlist/37i9dQZF1DX18jTM2l2fJY?si=f2e8ffa41c1b4abc

<img src="https://github.com/hamdamoha/project1_spotify/blob/main/Readme%20images/topexample.jpg" width="200">

The data set was created using these playlists from 2012 – 2022 to create our dataset, which gave us data on 993 songs. A csv file was created for each year. These were merged into a final data frame, which is the main data used for all the investigation, analysis and plots. This can be found in the in the main repository. 

* [Final_Data_2012_2022.csv](https://github.com/hamdamoha/project1_spotify/blob/main/Final_Data_2012_2022.csv)

## <a id="project-header"></a>Project Outline
Our client question was **"What features would a song need to increase its chance of appearing in Spotify Wrapped 2023?"**. We looked at the types of data which we could extract from Spotify and from this we created a list of possible questions to investigate. Each member of the group took an area and used the main data to generate insights and recommendations for our clients - Penny Panda and Percy Python - aspiring musical superstars!

* Hypothesis 1: Recent years have a greater energy difference than later years. - Priscila
* Hypothesis 2: Speechiness does not influence the popularity of a song. - Lucie
* Hypothesis 3: There is a direct correlation between “energy” and “danceability” features. - Hamda
* Hypothesis 4: The number of followers an artist has an impact on their position in the top 50 (2022 only) – Jade 

For each hypotheses we created a number of visualisations and where appropriate have begun to explore some basic stastical measures. 
