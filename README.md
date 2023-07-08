# SIGAI-TASK
In this task we performed data preprocessing on the given dataset, 'epa_air_quality_annual_summary.csv'. The following steps were taken:

- **Reading the CSV file:** We used the `pd.read_csv()` function to read the CSV file into a DataFrame named `df`.

- **Statistical Analysis:** To gain insights into the data, we conducted a statistical analysis using the `describe()` method. This provided summary statistics such as count, mean, standard deviation, minimum, maximum, and quartile values for the numerical columns in the DataFrame.

- **Checking for Null Values:** We checked for null values in the DataFrame using the `isnull()` function. By applying the `sum()` function, we obtained the count of null values in each column.

- **Removing Null Value Rows:** To handle missing data, we created a new DataFrame named `df2` by removing rows with null values using the `dropna()` function. The resulting DataFrame contains no null value rows.

<hr>

## Data Preprocessing

In this project, we performed data preprocessing on the dataset using the <span style="color:red;">`sklearn.preprocessing`</span> module from the scikit-learn library.

### Normalization

Normalisation is one of the methods used on the dataset. To scale all features to a similar range, usually between 0 and 1, normalisation is a technique. When the characteristics have varied scales and we want to make sure that no one feature dominates the others during analysis, it is especially helpful.

We utilised the <span style="color:red;">`MinMaxScaler`</span> class from the  <span style="color:red;">`sklearn.preprocessing`</span> module to achieve nomalisation. By deducting the minimum value and dividing by the range (highest value - minimum value) of each characteristic, this class scales each feature independently. The values that are obtained range from 0 to 1.


In our dataset, normalisation is used to scale down all numerical features to a similar level, allowing for fair comparisons and preventing the disproportionate influence of any particular feature.
Please refer to the [task.ipynb](https://github.com/ajan421/Ajan_S2/blob/main/task.ipynb) file for a complete implementation of the code and further details on other preprocessing steps.
