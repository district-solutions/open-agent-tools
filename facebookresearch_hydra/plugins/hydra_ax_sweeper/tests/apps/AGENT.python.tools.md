# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/tests/apps/polynomial.py

Prompts

```
['run the polynomial function with Hydra config to compute 100*x^2 + 10*y + 1*z', 'test the polynomial function by passing a DictConfig with x, y, and z values', 'review the polynomial function and its Hydra config-driven entry point setup', 'refactor the polynomial function to use configurable coefficients instead of hardcoded a, b, c values', 'summarize the polynomial function that evaluates a quadratic expression using Hydra configuration', 'run the polynomial with constraint app that returns result and constraint_metric from Hydra config', 'run the hydra app to evaluate a polynomial using dict coefficients from config', 'run the hydra AX sweeper test app with polynomial coefficients x, y, and z', 'review the polynomial_with_dict_coefficients function that computes 100*x^2 + 10*y + 1*z', 'refactor the polynomial_with_dict_coefficients function to use configurable a, b, c weights from config', 'test the hydra app polynomial_with_dict_coefficients with various coefficient values from the config file', 'run the hydra app that evaluates a polynomial using list coefficients from config', 'test the polynomial_with_list_coefficients function that computes 100*x^2 + 10*y + 1*z from config', 'review the hydra decorated polynomial_with_list_coefficients function and its config-driven coefficient unpacking', 'refactor the polynomial_with_list_coefficients function to support a variable number of coefficients', 'summarize the polynomial_with_list_coefficients hydra app that evaluates a quadratic polynomial from config']
```

Usage

```
{'run_polynomial': 'run the polynomial function with Hydra config to compute 100*x^2 + 10*y + 1*z', 'test_polynomial': 'test the polynomial function by passing a DictConfig with x, y, and z values', 'review_polynomial': 'review the polynomial function and its Hydra config-driven entry point setup', 'refactor_polynomial': 'refactor the polynomial function to use configurable coefficients instead of hardcoded a, b, c values', 'summarize_polynomial': 'summarize the polynomial function that evaluates a quadratic expression using Hydra configuration'}
```

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/tests/apps/polynomial_with_constraint.py

Prompts

```
['run the polynomial function with Hydra config to compute 100*x^2 + 10*y + 1*z', 'test the polynomial function by passing a DictConfig with x, y, and z values', 'review the polynomial function and its Hydra config-driven entry point setup', 'refactor the polynomial function to use configurable coefficients instead of hardcoded a, b, c values', 'summarize the polynomial function that evaluates a quadratic expression using Hydra configuration', 'run the polynomial with constraint app that returns result and constraint_metric from Hydra config', 'run the hydra app to evaluate a polynomial using dict coefficients from config', 'run the hydra AX sweeper test app with polynomial coefficients x, y, and z', 'review the polynomial_with_dict_coefficients function that computes 100*x^2 + 10*y + 1*z', 'refactor the polynomial_with_dict_coefficients function to use configurable a, b, c weights from config', 'test the hydra app polynomial_with_dict_coefficients with various coefficient values from the config file', 'run the hydra app that evaluates a polynomial using list coefficients from config', 'test the polynomial_with_list_coefficients function that computes 100*x^2 + 10*y + 1*z from config', 'review the hydra decorated polynomial_with_list_coefficients function and its config-driven coefficient unpacking', 'refactor the polynomial_with_list_coefficients function to support a variable number of coefficients', 'summarize the polynomial_with_list_coefficients hydra app that evaluates a quadratic polynomial from config']
```

Usage

```
{'run_polynomial': 'run the polynomial function that computes a*x^2 + b*y + c*z using Hydra config', 'run_polynomial_with_constraint': 'run the polynomial with constraint app that returns result and constraint_metric from Hydra config', 'review_polynomial': 'review the polynomial function that evaluates a*x^2 + b*y + c*z with fixed coefficients', 'summarize_polynomial': 'summarize the polynomial function that computes result and constraint_metric from Hydra DictConfig', 'test_polynomial': 'test the polynomial function that returns result and constraint_metric using Hydra configuration'}
```

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/tests/apps/polynomial_with_dict_coefficients.py

Prompts

```
['run the polynomial function with Hydra config to compute 100*x^2 + 10*y + 1*z', 'test the polynomial function by passing a DictConfig with x, y, and z values', 'review the polynomial function and its Hydra config-driven entry point setup', 'refactor the polynomial function to use configurable coefficients instead of hardcoded a, b, c values', 'summarize the polynomial function that evaluates a quadratic expression using Hydra configuration', 'run the polynomial with constraint app that returns result and constraint_metric from Hydra config', 'run the hydra app to evaluate a polynomial using dict coefficients from config', 'run the hydra AX sweeper test app with polynomial coefficients x, y, and z', 'review the polynomial_with_dict_coefficients function that computes 100*x^2 + 10*y + 1*z', 'refactor the polynomial_with_dict_coefficients function to use configurable a, b, c weights from config', 'test the hydra app polynomial_with_dict_coefficients with various coefficient values from the config file', 'run the hydra app that evaluates a polynomial using list coefficients from config', 'test the polynomial_with_list_coefficients function that computes 100*x^2 + 10*y + 1*z from config', 'review the hydra decorated polynomial_with_list_coefficients function and its config-driven coefficient unpacking', 'refactor the polynomial_with_list_coefficients function to support a variable number of coefficients', 'summarize the polynomial_with_list_coefficients hydra app that evaluates a quadratic polynomial from config']
```

Usage

```
{'run_polynomial_evaluation': 'run the hydra app to evaluate a polynomial using dict coefficients from config', 'run_hydra_sweeper_test_app': 'run the hydra AX sweeper test app with polynomial coefficients x, y, and z', 'review_polynomial_function': 'review the polynomial_with_dict_coefficients function that computes 100*x^2 + 10*y + 1*z', 'refactor_polynomial_coefficients': 'refactor the polynomial_with_dict_coefficients function to use configurable a, b, c weights from config', 'test_polynomial_with_dict_coefficients': 'test the hydra app polynomial_with_dict_coefficients with various coefficient values from the config file'}
```

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/tests/apps/polynomial_with_list_coefficients.py

Prompts

```
['run the polynomial function with Hydra config to compute 100*x^2 + 10*y + 1*z', 'test the polynomial function by passing a DictConfig with x, y, and z values', 'review the polynomial function and its Hydra config-driven entry point setup', 'refactor the polynomial function to use configurable coefficients instead of hardcoded a, b, c values', 'summarize the polynomial function that evaluates a quadratic expression using Hydra configuration', 'run the polynomial with constraint app that returns result and constraint_metric from Hydra config', 'run the hydra app to evaluate a polynomial using dict coefficients from config', 'run the hydra AX sweeper test app with polynomial coefficients x, y, and z', 'review the polynomial_with_dict_coefficients function that computes 100*x^2 + 10*y + 1*z', 'refactor the polynomial_with_dict_coefficients function to use configurable a, b, c weights from config', 'test the hydra app polynomial_with_dict_coefficients with various coefficient values from the config file', 'run the hydra app that evaluates a polynomial using list coefficients from config', 'test the polynomial_with_list_coefficients function that computes 100*x^2 + 10*y + 1*z from config', 'review the hydra decorated polynomial_with_list_coefficients function and its config-driven coefficient unpacking', 'refactor the polynomial_with_list_coefficients function to support a variable number of coefficients', 'summarize the polynomial_with_list_coefficients hydra app that evaluates a quadratic polynomial from config']
```

Usage

```
{'run_polynomial_with_list_coefficients': 'run the hydra app that evaluates a polynomial using list coefficients from config', 'test_polynomial_with_list_coefficients': 'test the polynomial_with_list_coefficients function that computes 100*x^2 + 10*y + 1*z from config', 'review_polynomial_with_list_coefficients': 'review the hydra decorated polynomial_with_list_coefficients function and its config-driven coefficient unpacking', 'refactor_polynomial_with_list_coefficients': 'refactor the polynomial_with_list_coefficients function to support a variable number of coefficients', 'summarize_polynomial_with_list_coefficients': 'summarize the polynomial_with_list_coefficients hydra app that evaluates a quadratic polynomial from config'}
```

