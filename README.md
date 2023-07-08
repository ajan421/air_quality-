# SIGAI-TASK
We used the pd.read_csv() function to read the CSV file into a DataFrame named df.

We conducted a statistical analysis of the DataFrame using the describe() method. This provided summary statistics such as count, mean, standard deviation, minimum, maximum, and quartile values for the numerical columns in the DataFrame.
We checked for null values in the DataFrame using the isnull() function, followed by the sum() function to count the number of null values in each column


We created a new DataFrame named df2 by removing rows with null values using the dropna() function. The resulting DataFrame contains no null value rows and was displayed

## Data Preprocessing

In this project, we performed data preprocessing on the dataset using the "sklearn.preprocessing" module from the scikit-learn library.

### Normalization

Normalisation is one of the methods used on the dataset. To scale all features to a similar range, usually between 0 and 1, normalisation is a technique. When the characteristics have varied scales and we want to make sure that no one feature dominates the others during analysis, it is especially helpful.

We utilised the "MinMaxScaler" class from the "sklearn.preprocessing" module to achieve normalisation. By deducting the minimum value and dividing by the range (highest value - minimum value) of each characteristic, this class scales each feature independently. The values that are obtained range from 0 to 1.


In our dataset, normalisation is used to scale down all numerical features to a similar level, allowing for fair comparisons and preventing the disproportionate influence of any particular feature.
