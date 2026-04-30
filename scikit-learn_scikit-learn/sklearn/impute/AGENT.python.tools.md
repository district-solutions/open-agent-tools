# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/impute/_base.py

Prompts

```
['create a SimpleImputer that replaces missing values with the mean of each column', 'create a SimpleImputer that replaces missing values with the median of each column', 'create a SimpleImputer that replaces missing values with the most frequent value in each column', 'create a SimpleImputer that replaces missing values with a constant fill value', 'create a MissingIndicator that generates binary masks for features with missing values', 'create an IterativeImputer to impute missing values by modeling each feature as a function of other features', 'fit an IterativeImputer on training data with missing values to learn imputation models for each feature', 'transform new data by imputing missing values using the fitted IterativeImputer models', 'impute missing values using IterativeImputer with BayesianRidge estimator for multivariate imputation', 'sample from the predictive posterior of the fitted estimator for multiple imputations with sample_posterior=True', 'create a KNNImputer instance with configurable n_neighbors, weights, and metric for imputing missing values', 'fit the KNNImputer on training data to learn neighbor distances and missing value patterns', 'transform data by imputing missing values using k-nearest neighbors from the fitted training set', 'get output feature names after KNNImputer transformation including missing value indicators', 'calculate imputed values for a single column using k-nearest neighbor weighted averaging']
```

Usage

```
{'create_SimpleImputer_mean': 'create a SimpleImputer that replaces missing values with the mean of each column', 'create_SimpleImputer_median': 'create a SimpleImputer that replaces missing values with the median of each column', 'create_SimpleImputer_most_frequent': 'create a SimpleImputer that replaces missing values with the most frequent value in each column', 'create_SimpleImputer_constant': 'create a SimpleImputer that replaces missing values with a constant fill value', 'create_MissingIndicator': 'create a MissingIndicator that generates binary masks for features with missing values'}
```

## File: scikit-learn_scikit-learn/sklearn/impute/_iterative.py

Prompts

```
['create a SimpleImputer that replaces missing values with the mean of each column', 'create a SimpleImputer that replaces missing values with the median of each column', 'create a SimpleImputer that replaces missing values with the most frequent value in each column', 'create a SimpleImputer that replaces missing values with a constant fill value', 'create a MissingIndicator that generates binary masks for features with missing values', 'create an IterativeImputer to impute missing values by modeling each feature as a function of other features', 'fit an IterativeImputer on training data with missing values to learn imputation models for each feature', 'transform new data by imputing missing values using the fitted IterativeImputer models', 'impute missing values using IterativeImputer with BayesianRidge estimator for multivariate imputation', 'sample from the predictive posterior of the fitted estimator for multiple imputations with sample_posterior=True', 'create a KNNImputer instance with configurable n_neighbors, weights, and metric for imputing missing values', 'fit the KNNImputer on training data to learn neighbor distances and missing value patterns', 'transform data by imputing missing values using k-nearest neighbors from the fitted training set', 'get output feature names after KNNImputer transformation including missing value indicators', 'calculate imputed values for a single column using k-nearest neighbor weighted averaging']
```

Usage

```
{'create_iterative_imputer': 'create an IterativeImputer to impute missing values by modeling each feature as a function of other features', 'fit_iterative_imputer': 'fit an IterativeImputer on training data with missing values to learn imputation models for each feature', 'transform_missing_data': 'transform new data by imputing missing values using the fitted IterativeImputer models', 'impute_with_bayesian_ridge': 'impute missing values using IterativeImputer with BayesianRidge estimator for multivariate imputation', 'sample_posterior_imputation': 'sample from the predictive posterior of the fitted estimator for multiple imputations with sample_posterior=True'}
```

## File: scikit-learn_scikit-learn/sklearn/impute/_knn.py

Prompts

```
['create a SimpleImputer that replaces missing values with the mean of each column', 'create a SimpleImputer that replaces missing values with the median of each column', 'create a SimpleImputer that replaces missing values with the most frequent value in each column', 'create a SimpleImputer that replaces missing values with a constant fill value', 'create a MissingIndicator that generates binary masks for features with missing values', 'create an IterativeImputer to impute missing values by modeling each feature as a function of other features', 'fit an IterativeImputer on training data with missing values to learn imputation models for each feature', 'transform new data by imputing missing values using the fitted IterativeImputer models', 'impute missing values using IterativeImputer with BayesianRidge estimator for multivariate imputation', 'sample from the predictive posterior of the fitted estimator for multiple imputations with sample_posterior=True', 'create a KNNImputer instance with configurable n_neighbors, weights, and metric for imputing missing values', 'fit the KNNImputer on training data to learn neighbor distances and missing value patterns', 'transform data by imputing missing values using k-nearest neighbors from the fitted training set', 'get output feature names after KNNImputer transformation including missing value indicators', 'calculate imputed values for a single column using k-nearest neighbor weighted averaging']
```

Usage

```
{'create_KNNImputer': 'create a KNNImputer instance with configurable n_neighbors, weights, and metric for imputing missing values', 'fit_KNNImputer': 'fit the KNNImputer on training data to learn neighbor distances and missing value patterns', 'transform_KNNImputer': 'transform data by imputing missing values using k-nearest neighbors from the fitted training set', 'get_feature_names_out_KNNImputer': 'get output feature names after KNNImputer transformation including missing value indicators', 'calc_impute_KNNImputer': 'calculate imputed values for a single column using k-nearest neighbor weighted averaging'}
```

