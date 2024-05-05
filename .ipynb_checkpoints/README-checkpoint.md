# Music-Recommender-System

## Description
This project will be a music recommendation system suggesting artists to a user based on their listening history. This project uses Apache Spark and Python. A docker container was used to be able to use PySpark locally. The container came from the following [all spark notebook](https://hub.docker.com/r/jupyter/all-spark-notebook/) image.

## Dataset
The dataset is a public song dataset from Audioscrobbler that contains profiles for 150,000 real people. The dataset has the artists each person listens to as well as a counter for how often a user played each artist. The data is in the data folder. Detailed information about the dataset is given in the ReadMe file in the data folder.

## Recommender Model

The 