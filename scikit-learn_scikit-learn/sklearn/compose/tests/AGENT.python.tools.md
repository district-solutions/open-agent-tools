# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/compose/tests/test_column_transformer.py

Prompts

```
['test the ColumnTransformer applies different transformers to specified column groups and concatenates results', 'test the ColumnTransformer selects columns by string names from pandas or polars dataframes', 'test make_column_selector filters columns by dtype patterns on pandas dataframes', 'test ColumnTransformer generates verbose feature names with transformer prefixes on get_feature_names_out', 'test ColumnTransformer routes sample_weight and metadata to sub-estimators via enable_metadata_routing', 'test TransformedTargetRegressor with func and inverse_func for log/exp transformations', 'test TransformedTargetRegressor with a transformer like StandardScaler or FunctionTransformer', 'test TransformedTargetRegressor with multi-output target arrays', 'test TransformedTargetRegressor raises errors for conflicting params and missing inverse_func', 'test TransformedTargetRegressor passes fit and predict kwargs to the underlying regressor']
```

Usage

```
{'test_ColumnTransformer_basic_transform': 'test the ColumnTransformer applies different transformers to specified column groups and concatenates results', 'test_ColumnTransformer_dataframe_selection': 'test the ColumnTransformer selects columns by string names from pandas or polars dataframes', 'test_make_column_selector_dtype_filtering': 'test make_column_selector filters columns by dtype patterns on pandas dataframes', 'test_ColumnTransformer_feature_names_out': 'test ColumnTransformer generates verbose feature names with transformer prefixes on get_feature_names_out', 'test_ColumnTransformer_metadata_routing': 'test ColumnTransformer routes sample_weight and metadata to sub-estimators via enable_metadata_routing'}
```

## File: scikit-learn_scikit-learn/sklearn/compose/tests/test_target.py

Prompts

```
['test the ColumnTransformer applies different transformers to specified column groups and concatenates results', 'test the ColumnTransformer selects columns by string names from pandas or polars dataframes', 'test make_column_selector filters columns by dtype patterns on pandas dataframes', 'test ColumnTransformer generates verbose feature names with transformer prefixes on get_feature_names_out', 'test ColumnTransformer routes sample_weight and metadata to sub-estimators via enable_metadata_routing', 'test TransformedTargetRegressor with func and inverse_func for log/exp transformations', 'test TransformedTargetRegressor with a transformer like StandardScaler or FunctionTransformer', 'test TransformedTargetRegressor with multi-output target arrays', 'test TransformedTargetRegressor raises errors for conflicting params and missing inverse_func', 'test TransformedTargetRegressor passes fit and predict kwargs to the underlying regressor']
```

Usage

```
{'test_transform_target_regressor_functions': 'test TransformedTargetRegressor with func and inverse_func for log/exp transformations', 'test_transform_target_regressor_transformer': 'test TransformedTargetRegressor with a transformer like StandardScaler or FunctionTransformer', 'test_transform_target_regressor_multioutput': 'test TransformedTargetRegressor with multi-output target arrays', 'test_transform_target_regressor_error': 'test TransformedTargetRegressor raises errors for conflicting params and missing inverse_func', 'test_transform_target_regressor_pass_fit_parameters': 'test TransformedTargetRegressor passes fit and predict kwargs to the underlying regressor'}
```

