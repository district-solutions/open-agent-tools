# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/impute/tests/test_base.py

Prompts

```
['test _BaseImputer raises ValueError when _transform_indicator is called without _fit_indicator', 'test _BaseImputer raises ValueError when _fit_indicator and _transform_indicator are not properly implemented', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during fit', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during transform', 'test _assign_where copies values from X2 to X1 where mask is True for both array and dataframe inputs', 'test imputers handle missing values in test array without throwing errors', 'test imputers add missing value indicator columns when configured with add_indicator enabled', 'test imputers add missing value indicator columns on sparse matrix inputs', 'test imputers support pandas IntegerArray with pd.NA values for fitting and transforming', 'test imputers generate correct feature names output including missing indicator names', 'test SimpleImputer with mean, median, most_frequent, and constant strategies on dense and sparse arrays', 'test IterativeImputer with multiple estimators, clipping, and truncated normal posterior sampling', 'test KNNImputer with keep_empty_features parameter on arrays with missing values', 'test MissingIndicator to generate boolean masks for missing values in dense and sparse matrices', 'test SimpleImputer within a scikit-learn Pipeline with GridSearchCV for hyperparameter tuning', 'test KNNImputer shape output for different weights and number of neighbors', 'test KNNImputer raises ValueError when input contains infinity or NaN values', 'test KNNImputer with distance-weighted neighbor imputation and manual distance verification', 'test KNNImputer with a custom callable metric returning L1 norm', 'test KNNImputer correctly excludes samples with NaN distance from neighbor imputation']
```

Usage

```
{'test_base_imputer_not_fit': 'test _BaseImputer raises ValueError when _transform_indicator is called without _fit_indicator', 'test_base_imputer_not_transform': 'test _BaseImputer raises ValueError when _fit_indicator and _transform_indicator are not properly implemented', 'test_base_no_precomputed_mask_fit': 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during fit', 'test_base_no_precomputed_mask_transform': 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during transform', 'test_assign_where': 'test _assign_where copies values from X2 to X1 where mask is True for both array and dataframe inputs'}
```

## File: scikit-learn_scikit-learn/sklearn/impute/tests/test_common.py

Prompts

```
['test _BaseImputer raises ValueError when _transform_indicator is called without _fit_indicator', 'test _BaseImputer raises ValueError when _fit_indicator and _transform_indicator are not properly implemented', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during fit', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during transform', 'test _assign_where copies values from X2 to X1 where mask is True for both array and dataframe inputs', 'test imputers handle missing values in test array without throwing errors', 'test imputers add missing value indicator columns when configured with add_indicator enabled', 'test imputers add missing value indicator columns on sparse matrix inputs', 'test imputers support pandas IntegerArray with pd.NA values for fitting and transforming', 'test imputers generate correct feature names output including missing indicator names', 'test SimpleImputer with mean, median, most_frequent, and constant strategies on dense and sparse arrays', 'test IterativeImputer with multiple estimators, clipping, and truncated normal posterior sampling', 'test KNNImputer with keep_empty_features parameter on arrays with missing values', 'test MissingIndicator to generate boolean masks for missing values in dense and sparse matrices', 'test SimpleImputer within a scikit-learn Pipeline with GridSearchCV for hyperparameter tuning', 'test KNNImputer shape output for different weights and number of neighbors', 'test KNNImputer raises ValueError when input contains infinity or NaN values', 'test KNNImputer with distance-weighted neighbor imputation and manual distance verification', 'test KNNImputer with a custom callable metric returning L1 norm', 'test KNNImputer correctly excludes samples with NaN distance from neighbor imputation']
```

Usage

```
{'test_imputation_missing_value_in_test_array': 'test imputers handle missing values in test array without throwing errors', 'test_imputers_add_indicator': 'test imputers add missing value indicator columns when configured with add_indicator enabled', 'test_imputers_add_indicator_sparse': 'test imputers add missing value indicator columns on sparse matrix inputs', 'test_imputers_pandas_na_integer_array_support': 'test imputers support pandas IntegerArray with pd.NA values for fitting and transforming', 'test_imputers_feature_names_out_pandas': 'test imputers generate correct feature names output including missing indicator names'}
```

## File: scikit-learn_scikit-learn/sklearn/impute/tests/test_impute.py

Prompts

```
['test _BaseImputer raises ValueError when _transform_indicator is called without _fit_indicator', 'test _BaseImputer raises ValueError when _fit_indicator and _transform_indicator are not properly implemented', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during fit', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during transform', 'test _assign_where copies values from X2 to X1 where mask is True for both array and dataframe inputs', 'test imputers handle missing values in test array without throwing errors', 'test imputers add missing value indicator columns when configured with add_indicator enabled', 'test imputers add missing value indicator columns on sparse matrix inputs', 'test imputers support pandas IntegerArray with pd.NA values for fitting and transforming', 'test imputers generate correct feature names output including missing indicator names', 'test SimpleImputer with mean, median, most_frequent, and constant strategies on dense and sparse arrays', 'test IterativeImputer with multiple estimators, clipping, and truncated normal posterior sampling', 'test KNNImputer with keep_empty_features parameter on arrays with missing values', 'test MissingIndicator to generate boolean masks for missing values in dense and sparse matrices', 'test SimpleImputer within a scikit-learn Pipeline with GridSearchCV for hyperparameter tuning', 'test KNNImputer shape output for different weights and number of neighbors', 'test KNNImputer raises ValueError when input contains infinity or NaN values', 'test KNNImputer with distance-weighted neighbor imputation and manual distance verification', 'test KNNImputer with a custom callable metric returning L1 norm', 'test KNNImputer correctly excludes samples with NaN distance from neighbor imputation']
```

Usage

```
{'test_simple_imputer': 'test SimpleImputer with mean, median, most_frequent, and constant strategies on dense and sparse arrays', 'test_iterative_imputer': 'test IterativeImputer with multiple estimators, clipping, and truncated normal posterior sampling', 'test_knn_imputer': 'test KNNImputer with keep_empty_features parameter on arrays with missing values', 'test_missing_indicator': 'test MissingIndicator to generate boolean masks for missing values in dense and sparse matrices', 'test_imputation_pipeline': 'test SimpleImputer within a scikit-learn Pipeline with GridSearchCV for hyperparameter tuning'}
```

## File: scikit-learn_scikit-learn/sklearn/impute/tests/test_knn.py

Prompts

```
['test _BaseImputer raises ValueError when _transform_indicator is called without _fit_indicator', 'test _BaseImputer raises ValueError when _fit_indicator and _transform_indicator are not properly implemented', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during fit', 'test _BaseImputer raises ValueError when precomputed is True but input data is not a mask during transform', 'test _assign_where copies values from X2 to X1 where mask is True for both array and dataframe inputs', 'test imputers handle missing values in test array without throwing errors', 'test imputers add missing value indicator columns when configured with add_indicator enabled', 'test imputers add missing value indicator columns on sparse matrix inputs', 'test imputers support pandas IntegerArray with pd.NA values for fitting and transforming', 'test imputers generate correct feature names output including missing indicator names', 'test SimpleImputer with mean, median, most_frequent, and constant strategies on dense and sparse arrays', 'test IterativeImputer with multiple estimators, clipping, and truncated normal posterior sampling', 'test KNNImputer with keep_empty_features parameter on arrays with missing values', 'test MissingIndicator to generate boolean masks for missing values in dense and sparse matrices', 'test SimpleImputer within a scikit-learn Pipeline with GridSearchCV for hyperparameter tuning', 'test KNNImputer shape output for different weights and number of neighbors', 'test KNNImputer raises ValueError when input contains infinity or NaN values', 'test KNNImputer with distance-weighted neighbor imputation and manual distance verification', 'test KNNImputer with a custom callable metric returning L1 norm', 'test KNNImputer correctly excludes samples with NaN distance from neighbor imputation']
```

Usage

```
{'test_knn_imputer_shape': 'test KNNImputer shape output for different weights and number of neighbors', 'test_knn_imputer_invalid_input': 'test KNNImputer raises ValueError when input contains infinity or NaN values', 'test_knn_imputer_weight_distance': 'test KNNImputer with distance-weighted neighbor imputation and manual distance verification', 'test_knn_imputer_callable_metric': 'test KNNImputer with a custom callable metric returning L1 norm', 'test_knn_imputer_nan_distance': 'test KNNImputer correctly excludes samples with NaN distance from neighbor imputation'}
```

