# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/baselines/linear_baseline.py

Prompts

```
['create a LinearBaseline instance with env_spec and optional input type and regularization coefficient', 'fit the LinearBaseline model to trajectory paths using regularized least squares regression', 'predict baseline values for a single trajectory path using fitted LinearBaseline coefficients', 'extract linear and time polynomial features from trajectory paths for baseline fitting', 'review the LinearBaseline class and its fit and predict methods for value baseline estimation', 'build an MLPBaseline model with custom hidden sizes and learning rate for value function approximation', 'fit the MLPBaseline model on trajectory paths to learn a value function baseline', 'predict value estimates for a single trajectory path using the trained MLPBaseline model', 'review the MLPBaseline _features method that extracts observation and time polynomial features from paths', 'refactor the MLPBaseline fit method to support GPU training with configurable batch size and epochs', 'build a QuadraticBaseline instance with an env_spec and optional input dimension for RL baseline fitting', 'fit the QuadraticBaseline to trajectory paths using regularized least squares regression on quadratic features', 'predict baseline returns for a single trajectory path using the fitted QuadraticBaseline coefficients', 'extract linear, quadratic, and time polynomial features from trajectory paths for baseline regression', 'review the QuadraticBaseline fit method to understand regularization and error return behavior', 'create a ZeroBaseline instance with an env_spec that has an observation_dim attribute', 'fit the ZeroBaseline on a list of trajectory paths and optionally return error metrics', 'predict zero-valued baseline returns for a trajectory path using the ZeroBaseline predict method', 'review the ZeroBaseline class which always returns zeros as baseline predictions for RL algorithms', 'summarize the ZeroBaseline class a trivial baseline that returns zero for all state-value predictions']
```

Usage

```
{'create_linear_baseline': 'create a LinearBaseline instance with env_spec and optional input type and regularization coefficient', 'fit_linear_baseline': 'fit the LinearBaseline model to trajectory paths using regularized least squares regression', 'predict_baseline_values': 'predict baseline values for a single trajectory path using fitted LinearBaseline coefficients', 'extract_features_from_paths': 'extract linear and time polynomial features from trajectory paths for baseline fitting', 'review_linear_baseline_class': 'review the LinearBaseline class and its fit and predict methods for value baseline estimation'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/baselines/mlp_baseline.py

Prompts

```
['create a LinearBaseline instance with env_spec and optional input type and regularization coefficient', 'fit the LinearBaseline model to trajectory paths using regularized least squares regression', 'predict baseline values for a single trajectory path using fitted LinearBaseline coefficients', 'extract linear and time polynomial features from trajectory paths for baseline fitting', 'review the LinearBaseline class and its fit and predict methods for value baseline estimation', 'build an MLPBaseline model with custom hidden sizes and learning rate for value function approximation', 'fit the MLPBaseline model on trajectory paths to learn a value function baseline', 'predict value estimates for a single trajectory path using the trained MLPBaseline model', 'review the MLPBaseline _features method that extracts observation and time polynomial features from paths', 'refactor the MLPBaseline fit method to support GPU training with configurable batch size and epochs', 'build a QuadraticBaseline instance with an env_spec and optional input dimension for RL baseline fitting', 'fit the QuadraticBaseline to trajectory paths using regularized least squares regression on quadratic features', 'predict baseline returns for a single trajectory path using the fitted QuadraticBaseline coefficients', 'extract linear, quadratic, and time polynomial features from trajectory paths for baseline regression', 'review the QuadraticBaseline fit method to understand regularization and error return behavior', 'create a ZeroBaseline instance with an env_spec that has an observation_dim attribute', 'fit the ZeroBaseline on a list of trajectory paths and optionally return error metrics', 'predict zero-valued baseline returns for a trajectory path using the ZeroBaseline predict method', 'review the ZeroBaseline class which always returns zeros as baseline predictions for RL algorithms', 'summarize the ZeroBaseline class a trivial baseline that returns zero for all state-value predictions']
```

Usage

```
{'build_MLPBaseline': 'build an MLPBaseline model with custom hidden sizes and learning rate for value function approximation', 'fit_MLPBaseline': 'fit the MLPBaseline model on trajectory paths to learn a value function baseline', 'predict_MLPBaseline': 'predict value estimates for a single trajectory path using the trained MLPBaseline model', 'review_MLPBaseline__features': 'review the MLPBaseline _features method that extracts observation and time polynomial features from paths', 'refactor_MLPBaseline_fit': 'refactor the MLPBaseline fit method to support GPU training with configurable batch size and epochs'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/baselines/quadratic_baseline.py

Prompts

```
['create a LinearBaseline instance with env_spec and optional input type and regularization coefficient', 'fit the LinearBaseline model to trajectory paths using regularized least squares regression', 'predict baseline values for a single trajectory path using fitted LinearBaseline coefficients', 'extract linear and time polynomial features from trajectory paths for baseline fitting', 'review the LinearBaseline class and its fit and predict methods for value baseline estimation', 'build an MLPBaseline model with custom hidden sizes and learning rate for value function approximation', 'fit the MLPBaseline model on trajectory paths to learn a value function baseline', 'predict value estimates for a single trajectory path using the trained MLPBaseline model', 'review the MLPBaseline _features method that extracts observation and time polynomial features from paths', 'refactor the MLPBaseline fit method to support GPU training with configurable batch size and epochs', 'build a QuadraticBaseline instance with an env_spec and optional input dimension for RL baseline fitting', 'fit the QuadraticBaseline to trajectory paths using regularized least squares regression on quadratic features', 'predict baseline returns for a single trajectory path using the fitted QuadraticBaseline coefficients', 'extract linear, quadratic, and time polynomial features from trajectory paths for baseline regression', 'review the QuadraticBaseline fit method to understand regularization and error return behavior', 'create a ZeroBaseline instance with an env_spec that has an observation_dim attribute', 'fit the ZeroBaseline on a list of trajectory paths and optionally return error metrics', 'predict zero-valued baseline returns for a trajectory path using the ZeroBaseline predict method', 'review the ZeroBaseline class which always returns zeros as baseline predictions for RL algorithms', 'summarize the ZeroBaseline class a trivial baseline that returns zero for all state-value predictions']
```

Usage

```
{'build_quadratic_baseline': 'build a QuadraticBaseline instance with an env_spec and optional input dimension for RL baseline fitting', 'fit_quadratic_baseline': 'fit the QuadraticBaseline to trajectory paths using regularized least squares regression on quadratic features', 'predict_baseline_returns': 'predict baseline returns for a single trajectory path using the fitted QuadraticBaseline coefficients', 'extract_quadratic_features': 'extract linear, quadratic, and time polynomial features from trajectory paths for baseline regression', 'review_quadratic_baseline_fit': 'review the QuadraticBaseline fit method to understand regularization and error return behavior'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/baselines/zero_baseline.py

Prompts

```
['create a LinearBaseline instance with env_spec and optional input type and regularization coefficient', 'fit the LinearBaseline model to trajectory paths using regularized least squares regression', 'predict baseline values for a single trajectory path using fitted LinearBaseline coefficients', 'extract linear and time polynomial features from trajectory paths for baseline fitting', 'review the LinearBaseline class and its fit and predict methods for value baseline estimation', 'build an MLPBaseline model with custom hidden sizes and learning rate for value function approximation', 'fit the MLPBaseline model on trajectory paths to learn a value function baseline', 'predict value estimates for a single trajectory path using the trained MLPBaseline model', 'review the MLPBaseline _features method that extracts observation and time polynomial features from paths', 'refactor the MLPBaseline fit method to support GPU training with configurable batch size and epochs', 'build a QuadraticBaseline instance with an env_spec and optional input dimension for RL baseline fitting', 'fit the QuadraticBaseline to trajectory paths using regularized least squares regression on quadratic features', 'predict baseline returns for a single trajectory path using the fitted QuadraticBaseline coefficients', 'extract linear, quadratic, and time polynomial features from trajectory paths for baseline regression', 'review the QuadraticBaseline fit method to understand regularization and error return behavior', 'create a ZeroBaseline instance with an env_spec that has an observation_dim attribute', 'fit the ZeroBaseline on a list of trajectory paths and optionally return error metrics', 'predict zero-valued baseline returns for a trajectory path using the ZeroBaseline predict method', 'review the ZeroBaseline class which always returns zeros as baseline predictions for RL algorithms', 'summarize the ZeroBaseline class a trivial baseline that returns zero for all state-value predictions']
```

Usage

```
{'create_zero_baseline': 'create a ZeroBaseline instance with an env_spec that has an observation_dim attribute', 'fit_zero_baseline': 'fit the ZeroBaseline on a list of trajectory paths and optionally return error metrics', 'predict_zero_baseline': 'predict zero-valued baseline returns for a trajectory path using the ZeroBaseline predict method', 'review_zero_baseline_class': 'review the ZeroBaseline class which always returns zeros as baseline predictions for RL algorithms', 'summarize_zero_baseline': 'summarize the ZeroBaseline class a trivial baseline that returns zero for all state-value predictions'}
```

