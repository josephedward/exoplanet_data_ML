# Description
Comparison of Models using NASA Kepler data


# Target
'koi_disposition' - The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED (i.e., likelihood that a given exoplanet is a true planet)


# Resources
* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)
* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)
* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)
* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)


# Preprocessing
* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separates the data into training and testing data with `TrainTestSplit`.


# Currently Supported Models
* Decision Tree - uses `GridSearch` to tune model parameters. 
[K-Nearest Neighbors, Support Vector Machine, Recurrent Neural Network - Keras/Tensorflow]


# Denouement 
1 . Decision tree ensemble (random forest) points to solar mass centroid offset of exoplanet mass as strongest predictor of planetary viability. 

