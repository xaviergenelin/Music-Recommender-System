# Music-Recommender-System

## Description
This project will be a music recommendation system suggesting artists to a user based on their listening history. This project uses Apache Spark and Python. A docker container was used to be able to use PySpark locally. The container came from the following [all spark notebook](https://hub.docker.com/r/jupyter/all-spark-notebook/) image. 

## Dataset
The dataset is a public song dataset from the following [github repository](https://github.com/lhandal/audioscrobbler_music_recommender_pyspark) that contains profiles for around 150,000 real people from Audioscrobbler. The dataset has the artists each person listens to as well as a counter for how often a user played each artist. The data is in the data folder. Detailed information about the dataset is given in the ReadMe file in the data folder.

## Recommender Model

This project used an Alternating Least Squares recommender system to generate artist suggestions based on a user's listening history. This started by splitting the data into training, testing, and validation datasets. Then training the model and tuning the ranking parameter. 
