# blogpost-datascientist-nanodegree

libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements.

## Installations
* numpy
* pandas
* matplotlib
* sklearn

## Project Motivation
The project was part of the Udacity Data Scientist Nanodegree. Specifically, the idea was to analyse song data and to (a) determine whether commercial success in the music industry became more predictable than in earlier decades and (b) to use this knowledge to find out what musical features and genres are associated with commercial success.<br>
To answer the first part of the project I compared song data from the 1970s and 2010s by predicting hit songs in each decade. Next, I used the song data from the 2010s to run a regression model to find out what musical attributes correlate strongly with commercial success. Lastly, I used the 2010s data to build a clustering model in order to find out what genres were popular and commercially successful these were.

## File Descriptions
The repositary contains three files next to this README file.
* A juypter notebook containing the code and technical process of the project (datascientist-nanodregree-project1.ipynb)
* A csv file with the 1970s song data (dataset-of-70s.csv)
* A csv file with the 2010s song data (dataset-of-10s.csv)

## Analysis Results
These are the core results of the analysis
* Commercial success in the 2010s is consistently more predictable than in the 1970s
* High danceability, low energy, low acousticness (electronically produced) and low instrumentalness (high share of vocal content) are on average associated with commercial success in the music industry in the 2010s
* The most common and commercially succesful genre in the 2010s was Dance Music (which is high on danceability, low on acousticness and instrumentalness; yet also high on energy)

## Licensing, Authors and Acknowledgements
Thanks to
* Spotify - for providing the API from which the song data was sources
* Kaggle - for providing a platform to publish the song data
* Farooq Ansari - for publishing the song data on Kaggle
