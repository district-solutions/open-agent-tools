# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/examples/preprocessing/plot_all_scaling.py

Prompts

```
['create a StandardScaler to remove the mean and scale data to unit variance', 'create a MinMaxScaler to rescale feature values to the range [0, 1]', 'create a RobustScaler with percentile-based scaling robust to outliers', 'create a QuantileTransformer to map data to a uniform distribution', 'create a PowerTransformer with Yeo-Johnson method to normalize skewed data', 'create a sklearn pipeline with StandardScaler, KBinsDiscretizer, and LogisticRegression for feature discretization classification', 'run GridSearchCV on a discretized classification pipeline to tune n_bins and C hyperparameters', 'build a synthetic moons dataset with make_moons for testing linearly non-separable classification', 'test KBinsDiscretizer with one-hot encoding on concentric circles classification accuracy', 'summarize feature discretization performance comparison across linear and non-linear classifiers', 'build a pipeline that standardizes features using StandardScaler with mean 0 and standard deviation 1', 'train a KNeighborsClassifier on scaled and unscaled data to compare decision boundaries', 'apply PCA on scaled and unscaled data to compare principal component weights', 'visualize decision boundaries of a classifier using DecisionBoundaryDisplay with scatter plot overlay', 'evaluate LogisticRegressionCV with cross-validated C on scaled versus unscaled PCA-reduced data', 'build a sklearn pipeline using TargetEncoder to encode high-cardinality categorical features with continuous target', 'build a sklearn pipeline using OneHotEncoder with max_categories limit to encode categorical features', 'build a sklearn pipeline using OrdinalEncoder with unknown_value handling for categorical preprocessing', 'build a ColumnTransformer pipeline mixing passthrough numerical columns with encoded categorical columns', 'test a sklearn pipeline using cross_validate with neg_root_mean_squared_error scoring and 3 folds']
```

Usage

```
{'create_standard_scaler_transform': 'create a StandardScaler to remove the mean and scale data to unit variance', 'create_minmax_scaler_transform': 'create a MinMaxScaler to rescale feature values to the range [0, 1]', 'create_robust_scaler_transform': 'create a RobustScaler with percentile-based scaling robust to outliers', 'create_quantile_transformer_uniform': 'create a QuantileTransformer to map data to a uniform distribution', 'create_power_transformer_yeo_johnson': 'create a PowerTransformer with Yeo-Johnson method to normalize skewed data'}
```

## File: scikit-learn_scikit-learn/examples/preprocessing/plot_discretization_classification.py

Prompts

```
['create a StandardScaler to remove the mean and scale data to unit variance', 'create a MinMaxScaler to rescale feature values to the range [0, 1]', 'create a RobustScaler with percentile-based scaling robust to outliers', 'create a QuantileTransformer to map data to a uniform distribution', 'create a PowerTransformer with Yeo-Johnson method to normalize skewed data', 'create a sklearn pipeline with StandardScaler, KBinsDiscretizer, and LogisticRegression for feature discretization classification', 'run GridSearchCV on a discretized classification pipeline to tune n_bins and C hyperparameters', 'build a synthetic moons dataset with make_moons for testing linearly non-separable classification', 'test KBinsDiscretizer with one-hot encoding on concentric circles classification accuracy', 'summarize feature discretization performance comparison across linear and non-linear classifiers', 'build a pipeline that standardizes features using StandardScaler with mean 0 and standard deviation 1', 'train a KNeighborsClassifier on scaled and unscaled data to compare decision boundaries', 'apply PCA on scaled and unscaled data to compare principal component weights', 'visualize decision boundaries of a classifier using DecisionBoundaryDisplay with scatter plot overlay', 'evaluate LogisticRegressionCV with cross-validated C on scaled versus unscaled PCA-reduced data', 'build a sklearn pipeline using TargetEncoder to encode high-cardinality categorical features with continuous target', 'build a sklearn pipeline using OneHotEncoder with max_categories limit to encode categorical features', 'build a sklearn pipeline using OrdinalEncoder with unknown_value handling for categorical preprocessing', 'build a ColumnTransformer pipeline mixing passthrough numerical columns with encoded categorical columns', 'test a sklearn pipeline using cross_validate with neg_root_mean_squared_error scoring and 3 folds']
```

Usage

```
{'create_pipeline_feature_discretization': 'create a sklearn pipeline with StandardScaler, KBinsDiscretizer, and LogisticRegression for feature discretization classification', 'run_gridsearch_classification': 'run GridSearchCV on a discretized classification pipeline to tune n_bins and C hyperparameters', 'build_synthetic_moons_dataset': 'build a synthetic moons dataset with make_moons for testing linearly non-separable classification', 'test_discretization_accuracy': 'test KBinsDiscretizer with one-hot encoding on concentric circles classification accuracy', 'summarize_discretization_comparison': 'summarize feature discretization performance comparison across linear and non-linear classifiers'}
```

## File: scikit-learn_scikit-learn/examples/preprocessing/plot_scaling_importance.py

Prompts

```
['create a StandardScaler to remove the mean and scale data to unit variance', 'create a MinMaxScaler to rescale feature values to the range [0, 1]', 'create a RobustScaler with percentile-based scaling robust to outliers', 'create a QuantileTransformer to map data to a uniform distribution', 'create a PowerTransformer with Yeo-Johnson method to normalize skewed data', 'create a sklearn pipeline with StandardScaler, KBinsDiscretizer, and LogisticRegression for feature discretization classification', 'run GridSearchCV on a discretized classification pipeline to tune n_bins and C hyperparameters', 'build a synthetic moons dataset with make_moons for testing linearly non-separable classification', 'test KBinsDiscretizer with one-hot encoding on concentric circles classification accuracy', 'summarize feature discretization performance comparison across linear and non-linear classifiers', 'build a pipeline that standardizes features using StandardScaler with mean 0 and standard deviation 1', 'train a KNeighborsClassifier on scaled and unscaled data to compare decision boundaries', 'apply PCA on scaled and unscaled data to compare principal component weights', 'visualize decision boundaries of a classifier using DecisionBoundaryDisplay with scatter plot overlay', 'evaluate LogisticRegressionCV with cross-validated C on scaled versus unscaled PCA-reduced data', 'build a sklearn pipeline using TargetEncoder to encode high-cardinality categorical features with continuous target', 'build a sklearn pipeline using OneHotEncoder with max_categories limit to encode categorical features', 'build a sklearn pipeline using OrdinalEncoder with unknown_value handling for categorical preprocessing', 'build a ColumnTransformer pipeline mixing passthrough numerical columns with encoded categorical columns', 'test a sklearn pipeline using cross_validate with neg_root_mean_squared_error scoring and 3 folds']
```

Usage

```
{'build_scale_features': 'build a pipeline that standardizes features using StandardScaler with mean 0 and standard deviation 1', 'train_knn_scaled': 'train a KNeighborsClassifier on scaled and unscaled data to compare decision boundaries', 'apply_pca_scaling': 'apply PCA on scaled and unscaled data to compare principal component weights', 'visualize_decision_boundary': 'visualize decision boundaries of a classifier using DecisionBoundaryDisplay with scatter plot overlay', 'evaluate_logistic_regression': 'evaluate LogisticRegressionCV with cross-validated C on scaled versus unscaled PCA-reduced data'}
```

## File: scikit-learn_scikit-learn/examples/preprocessing/plot_target_encoder.py

Prompts

```
['create a StandardScaler to remove the mean and scale data to unit variance', 'create a MinMaxScaler to rescale feature values to the range [0, 1]', 'create a RobustScaler with percentile-based scaling robust to outliers', 'create a QuantileTransformer to map data to a uniform distribution', 'create a PowerTransformer with Yeo-Johnson method to normalize skewed data', 'create a sklearn pipeline with StandardScaler, KBinsDiscretizer, and LogisticRegression for feature discretization classification', 'run GridSearchCV on a discretized classification pipeline to tune n_bins and C hyperparameters', 'build a synthetic moons dataset with make_moons for testing linearly non-separable classification', 'test KBinsDiscretizer with one-hot encoding on concentric circles classification accuracy', 'summarize feature discretization performance comparison across linear and non-linear classifiers', 'build a pipeline that standardizes features using StandardScaler with mean 0 and standard deviation 1', 'train a KNeighborsClassifier on scaled and unscaled data to compare decision boundaries', 'apply PCA on scaled and unscaled data to compare principal component weights', 'visualize decision boundaries of a classifier using DecisionBoundaryDisplay with scatter plot overlay', 'evaluate LogisticRegressionCV with cross-validated C on scaled versus unscaled PCA-reduced data', 'build a sklearn pipeline using TargetEncoder to encode high-cardinality categorical features with continuous target', 'build a sklearn pipeline using OneHotEncoder with max_categories limit to encode categorical features', 'build a sklearn pipeline using OrdinalEncoder with unknown_value handling for categorical preprocessing', 'build a ColumnTransformer pipeline mixing passthrough numerical columns with encoded categorical columns', 'test a sklearn pipeline using cross_validate with neg_root_mean_squared_error scoring and 3 folds']
```

Usage

```
{'build_TargetEncoder_pipeline': 'build a sklearn pipeline using TargetEncoder to encode high-cardinality categorical features with continuous target', 'build_OneHotEncoder_pipeline': 'build a sklearn pipeline using OneHotEncoder with max_categories limit to encode categorical features', 'build_OrdinalEncoder_pipeline': 'build a sklearn pipeline using OrdinalEncoder with unknown_value handling for categorical preprocessing', 'build_ColumnTransformer_pipeline': 'build a ColumnTransformer pipeline mixing passthrough numerical columns with encoded categorical columns', 'test_cross_validate_pipeline': 'test a sklearn pipeline using cross_validate with neg_root_mean_squared_error scoring and 3 folds'}
```

