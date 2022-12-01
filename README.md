# README 
Final Project Group MMA

## Goal of the project
The goal of the current project is to explore the relation between explicit songs and female and male artists. For this, we used datasets containing statistics from Spotify
from 1999-2020. 
More specifically, we are investigating whether male or female artists have a higher ratio explicit songs, how the use of explicit songs has changed over the years for these
artists, what the effect of explicit songs has on popularity
    
## Reason for this project
In light of current social changes regarding acceptance and female liberty, we thought it would be interesting to see the changes in explicit content in songs of female artists. We were wondering wether men or women used more explicit language, how this was distributed along the genders, and how this had evolved over the years.

    
## Datasets used in this project
The datasets used for this project are taken from Kaggle. Our first dataset, Music data, was used to gain access to data on artists, their songs, their explicit usage, the year of publication and their popularity. Because this dataset only contained the stage name of artists, we were unsure of their gender. This is why we chose our Gender dataset, so we could combine the two datasets to include gender in our analysis.


## Methods
We used z-test to measure the significance of our findings. We compared male and female on different grounds, namely the ratio of their explicit and implicit songs. We compared these ratios using different genres, and on a timeline. 

## Results
We have created 2 piecharts showing male artists have roughly doule the explicit ratio than that of female artists. Besides this, when plotted on a timeline, we could see that women's explicit ratio is more volatile than men's, and that in both men and women there has been an increase in explicit songs. Using a 100% stcaked bar chart, we can see the different amount of explicit usage of men and women across genres, taken in total, so not including ratios. This way, we can see that in certain genres women have more explicit content than women do in other genres. We confirmed our results with a z-test. 

## Discussion
There are some limitations to this research. Firstly, because the gender dataset was much smaller than the music dataset, and because the artists between datasets were not fully overlapping, this resulted in a dramastic decrease of our sample size. Secondly, we included a 100% stacked bar graph on total amount of explicit songs between men and women. However, this did not take into account that men and women do not have similar amounts of songs in these genres and that this could vary greatly between genres. To combat this, future research could include a 100% stacked bar graph on total amount of songs in genres between men and women. Furthermore, we have way less information and data on female artists than we do on male artists. Needless to say, there is less information on non-conventional genres, as this research was based on popular songs. 


Link to datasets:

Gender dataset -> https://www.kaggle.com/datasets/jackharding/spotify-artist-metadata-top-10k 

Music data -> https://www.kaggle.com/code/shrishtivaish/descriptive-and-diagnostic-analysis-of-music/data

## Authors
This project was made by group MMA (Mattia Zuccollo, Maya Soeratram, and Annika Lauwen) from the Python for Data Science Workshop 2022 provided by TSU.
