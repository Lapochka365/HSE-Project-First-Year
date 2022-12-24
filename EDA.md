__The dataset represents the typical medical one in these regards__:
- we have quite a lot of features for samples to begin with
- there aren't many samples (only 1700)
- there are missing values in dataset (two columns were dropped due to this)
- a lot of categorical features have outliers in them; meaning that the distribution of feature is highly displaced towards one common value for such feature
- most of the target features include the problem of categorical features distributions (we have only a few positive cases for target features)

__In order to make our lives easier we have processed the dataset__:
- Filled NaN values for categorical columns with Mode of that column
- Filled NaN values with KNNImputer for numeric columns
- Scaled Dataset for easier use with Linear Models in the future
