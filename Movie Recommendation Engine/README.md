# Movie Recommendation Engine

## Overall Task:
Build Movies Recommender System

## Dataset:
Metadata on over 45,000 movies, 26 million ratings from over 270,000 users ([link](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?datasetId=3405&sortBy=voteCount))

### Context:
These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.

This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

### Content:
This dataset consists of the following files:

- movies_metadata.csv: The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.

- keywords.csv: Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.

- credits.csv: Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.

- links.csv: The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.

- links_small.csv: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.

- ratings_small.csv: The subset of 100,000 ratings from 700 users on 9,000 movies.

The Full MovieLens Dataset consisting of 26 million ratings and 750,000 tag applications from 270,000 users on all the 45,000 movies in this dataset can be accessed here

## Table of Contents:

### [1. Initialization](https://github.com/91104311/Portfolio/blob/main/Movie%20Recommendation%20Engine/1.%20Initialization%20-%20Movie%20Recommendation%20Engine.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 1.1. Import Libraries
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.2 Loading Data



### [2. Recommendation Systems](https://github.com/91104311/Portfolio/blob/main/Movie%20Recommendation%20Engine/2.%20Recommendation%20Systems%20-%20Movie%20Recommendation%20Engine.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 2.1. Demographic Filtering
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.2. Content Filtering
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.3. Collaborative Filtering

