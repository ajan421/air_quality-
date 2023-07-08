# SIGAI-TASK


## Data Preprocessing

In this project, we performed data preprocessing on the dataset using the "sklearn.preprocessing" module from the scikit-learn library.

### Normalization

Normalisation is one of the methods used on the dataset. To scale all features to a similar range, usually between 0 and 1, normalisation is a technique. When the characteristics have varied scales and we want to make sure that no one feature dominates the others during analysis, it is especially helpful.

We utilised the "MinMaxScaler" class from the "sklearn.preprocessing" module to achieve normalisation. By deducting the minimum value and dividing by the range (highest value - minimum value) of each characteristic, this class scales each feature independently. The values that are obtained range from 0 to 1.


In our dataset, normalisation is used to scale down all numerical features to a similar level, allowing for fair comparisons and preventing the disproportionate influence of any particular feature.
