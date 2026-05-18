# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/arcoating/core.py

Prompts

```
['create an ARCoating instance with 10 layers and 400nm depth for anti-reflective optimization', 'run impedance_pix to compute normalized impedance and reflection percentage for given layer permittivities', 'test the ARCoating _get_minimum_average_reflexion method to compute average reflection across wavelengths', 'review the ARCoating constructor to understand wavelength range and permittivity bound configuration', 'summarize the ARCoating evaluation_function method that evaluates optimizer recommendations and updates leaderboard', 'test the impedance_pix function that computes normalized impedance and reflection percentage for pixel layers', 'test the ARCoating parametrization recombination of child arrays with seeded random state', 'test the ARCoating class transform and call with standardized data near space boundaries', 'test the ARCoating evaluation_function method that computes loss and updates the leaderboard']
```

Usage

```
{'create_ARCoating': 'create an ARCoating instance with 10 layers and 400nm depth for anti-reflective optimization', 'run_impedance_pix': 'run impedance_pix to compute normalized impedance and reflection percentage for given layer permittivities', 'test_ARCoating_reflexion': 'test the ARCoating _get_minimum_average_reflexion method to compute average reflection across wavelengths', 'review_ARCoating_init': 'review the ARCoating constructor to understand wavelength range and permittivity bound configuration', 'summarize_ARCoating_evaluation': 'summarize the ARCoating evaluation_function method that evaluates optimizer recommendations and updates leaderboard'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/arcoating/test_core.py

Prompts

```
['create an ARCoating instance with 10 layers and 400nm depth for anti-reflective optimization', 'run impedance_pix to compute normalized impedance and reflection percentage for given layer permittivities', 'test the ARCoating _get_minimum_average_reflexion method to compute average reflection across wavelengths', 'review the ARCoating constructor to understand wavelength range and permittivity bound configuration', 'summarize the ARCoating evaluation_function method that evaluates optimizer recommendations and updates leaderboard', 'test the impedance_pix function that computes normalized impedance and reflection percentage for pixel layers', 'test the ARCoating parametrization recombination of child arrays with seeded random state', 'test the ARCoating class transform and call with standardized data near space boundaries', 'test the ARCoating evaluation_function method that computes loss and updates the leaderboard']
```

Usage

```
{'test_impedance_pix': 'test the impedance_pix function that computes normalized impedance and reflection percentage for pixel layers', 'test_ARCoating_reflexion': 'test the ARCoating class _get_minimum_average_reflexion method for computing average reflection across wavelengths', 'test_ARCoating_recombination': 'test the ARCoating parametrization recombination of child arrays with seeded random state', 'test_ARCoating_transform_and_call': 'test the ARCoating class transform and call with standardized data near space boundaries', 'test_ARCoating_evaluation_function': 'test the ARCoating evaluation_function method that computes loss and updates the leaderboard'}
```

