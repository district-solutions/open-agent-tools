# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/compose/_column_transformer.py

Prompts

```
['build a ColumnTransformer to apply different transformers to different columns of heterogeneous data', 'create a shorthand ColumnTransformer using make_column_transformer with auto-generated transformer names', 'create a callable column selector using make_column_selector to select columns by dtype or regex pattern', 'test the ColumnTransformer fit_transform method to fit and transform data with concatenated outputs', 'review the ColumnTransformer transform method to transform data separately per transformer and concatenate results', 'create a TransformedTargetRegressor with a regressor and log/exp functions to apply non-linear transformation to regression targets', 'fit a TransformedTargetRegressor on training data X and transformed target y using func or transformer', 'predict using a fitted TransformedTargetRegressor and apply inverse transformation to return predictions to original target space', 'create a FunctionTransformer with custom func and inverse_func to transform regression targets', 'check that transform followed by inverse_transform returns original targets in TransformedTargetRegressor']
```

Usage

```
{'build_column_transformer': 'build a ColumnTransformer to apply different transformers to different columns of heterogeneous data', 'create_make_column_transformer': 'create a shorthand ColumnTransformer using make_column_transformer with auto-generated transformer names', 'create_make_column_selector': 'create a callable column selector using make_column_selector to select columns by dtype or regex pattern', 'test_column_transformer_fit_transform': 'test the ColumnTransformer fit_transform method to fit and transform data with concatenated outputs', 'review_column_transformer_transform': 'review the ColumnTransformer transform method to transform data separately per transformer and concatenate results'}
```

## File: scikit-learn_scikit-learn/sklearn/compose/_target.py

Prompts

```
['build a ColumnTransformer to apply different transformers to different columns of heterogeneous data', 'create a shorthand ColumnTransformer using make_column_transformer with auto-generated transformer names', 'create a callable column selector using make_column_selector to select columns by dtype or regex pattern', 'test the ColumnTransformer fit_transform method to fit and transform data with concatenated outputs', 'review the ColumnTransformer transform method to transform data separately per transformer and concatenate results', 'create a TransformedTargetRegressor with a regressor and log/exp functions to apply non-linear transformation to regression targets', 'fit a TransformedTargetRegressor on training data X and transformed target y using func or transformer', 'predict using a fitted TransformedTargetRegressor and apply inverse transformation to return predictions to original target space', 'create a FunctionTransformer with custom func and inverse_func to transform regression targets', 'check that transform followed by inverse_transform returns original targets in TransformedTargetRegressor']
```

Usage

```
{'create_transformed_target_regressor': 'create a TransformedTargetRegressor with a regressor and log/exp functions to apply non-linear transformation to regression targets', 'fit_transformed_target_regressor': 'fit a TransformedTargetRegressor on training data X and transformed target y using func or transformer', 'predict_transformed_target_regressor': 'predict using a fitted TransformedTargetRegressor and apply inverse transformation to return predictions to original target space', 'create_function_transformer': 'create a FunctionTransformer with custom func and inverse_func to transform regression targets', 'check_inverse_transformed_target': 'check that transform followed by inverse_transform returns original targets in TransformedTargetRegressor'}
```

