## Movie Recommendation System
The year of release, genres , number of votes and the average rating are taken as the features and the rating given by the user as the label.


### Data Collection and Cleaning
The data about the movies is collected from the IMDb: https://www.imdb.com/interfaces/ 

* title.akas.tsv
* title.basic.tsv
* title.rating.tsv

All the movies with incomplete data are removed

### Recommendation Model
The data for prediction is selected based on the genres the user has watched before
The Neural Network predicts the probability of the user liking the movie