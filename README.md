# MongoDB Data Analysis with Jupyter Notebook

## Description
This Jupyter notebook, `1Q_mongoDB.ipynb`, performs an in-depth analysis of movie data from a MongoDB collection. It includes data manipulation and aggregation to answer queries related to movie genres, comment patterns, and IMDB ratings.

## Contents
- Data retrieval from MongoDB using PyMongo.
- Aggregation pipelines to analyze the most and least commented movies.
- Genre-based comment distribution and IMDB rating analysis.
- Visualization of analytical results with Matplotlib.

## Requirements
- Python 3.x
- MongoDB running on localhost:27017
- Libraries: PyMongo, Pandas, Matplotlib

## Setup and Installation
1. Make sure MongoDB is active:
   ```shell
   mongod --port 27017

Usage
Run the cells sequentially to conduct the analysis. Commentary is provided to guide you through the process.

Data Overview
Analysis is conducted on the sample_mflix database which encompasses collections like movies, comments, users, theaters, and sessions.

Contributing
Fork this repository and submit pull requests to contribute. Make sure to document your changes and improvements.

License
This project is open-sourced under the MIT License.

Contact
Reach out to the repository owner for queries or feedback.
