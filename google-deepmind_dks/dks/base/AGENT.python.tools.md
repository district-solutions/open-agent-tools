# Agent Python Tools

- repo: google-deepmind/dks
- repo_uri: https://github.com/google-deepmind/dks

## File: google-deepmind_dks/dks/base/activation_getter.py

Prompts

```
['get an activation function by name from the activation table using get_activation_function', 'apply the approximate GELU activation function to a NumPy array input', 'apply the exact GELU activation function using the error function to an input', 'apply the ELU activation function with configurable alpha and lambda parameters', 'apply the swish activation function which multiplies input by its sigmoid', 'get transformed activation functions using the DKS method for a given list of activation names', 'get transformed activation functions using the TAT method with leaky relu and smooth activation support', 'get untransformed activation functions by passing method untransformed to skip all DKS or TAT transformations', 'compute optimized activation function parameters to achieve target local C map and Q map slope values', 'estimate the mean of a function under a standard normal distribution using Gaussian quadrature']
```

Usage

```
{'get_activation_function_by_name': 'get an activation function by name from the activation table using get_activation_function', 'apply_gelu_approximation': 'apply the approximate GELU activation function to a NumPy array input', 'apply_gelu_exact': 'apply the exact GELU activation function using the error function to an input', 'apply_elu_activation': 'apply the ELU activation function with configurable alpha and lambda parameters', 'apply_swish_activation': 'apply the swish activation function which multiplies input by its sigmoid'}
```

## File: google-deepmind_dks/dks/base/activation_transform.py

Prompts

```
['get an activation function by name from the activation table using get_activation_function', 'apply the approximate GELU activation function to a NumPy array input', 'apply the exact GELU activation function using the error function to an input', 'apply the ELU activation function with configurable alpha and lambda parameters', 'apply the swish activation function which multiplies input by its sigmoid', 'get transformed activation functions using the DKS method for a given list of activation names', 'get transformed activation functions using the TAT method with leaky relu and smooth activation support', 'get untransformed activation functions by passing method untransformed to skip all DKS or TAT transformations', 'compute optimized activation function parameters to achieve target local C map and Q map slope values', 'estimate the mean of a function under a standard normal distribution using Gaussian quadrature']
```

Usage

```
{'get_transformed_activations_DKS': 'get transformed activation functions using the DKS method for a given list of activation names', 'get_transformed_activations_TAT': 'get transformed activation functions using the TAT method with leaky relu and smooth activation support', 'get_transformed_activations_untransformed': 'get untransformed activation functions by passing method untransformed to skip all DKS or TAT transformations', 'transform_activation_params': 'compute optimized activation function parameters to achieve target local C map and Q map slope values', 'estimate_gaussian_mean': 'estimate the mean of a function under a standard normal distribution using Gaussian quadrature'}
```

