# automated-data-preprocessing

Automating the trivial, frequently occurring data preparation tasks to simplify the data preprocessing endeavor.

Automating the following tasks:

  - Identify Missing Data
      Explanation: Identify missing values in the data set and replace them with the sentinel NaN value.
  - Impute Missing Data
      Explanation: Mean for continuous features, mode for categorical features.
  - Remove Statistical Outliers
      Explanation: Remove Only true outliers based on assumption that data follows a normal distribution.
  - Encode Categorical Features
      Explanation: Encode categorical features using a one-hot encoding schema.