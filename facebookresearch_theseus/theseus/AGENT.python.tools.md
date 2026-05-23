# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/_version.py

Prompts

```
['use lt_version to compare two version strings and return True if the first is less than the second', 'use lt_version to check if the current torch version is less than a required minimum version', 'review the lt_version function to understand how it parses and compares semantic version strings', 'summarize the lt_version function which converts version strings to tuples and compares them lexicographically', 'test the lt_version function with various version string pairs to verify correct comparison logic', 'set Theseus global parameters like so2_norm_eps_float32 or fast_approx_local_jacobians using a dictionary of options', 'get the epsilon tolerance value for a given Lie group type, attribute, and torch dtype', 'reset all Theseus global parameters back to their default epsilon values', 'check whether a given torch dtype is supported by Theseus (float32 or float64 only)', 'configure the fast_approx_local_jacobians flag to enable or disable fast approximate local Jacobian computation', 'create a TheseusLayer from an Optimizer instance to wrap optimization as a differentiable PyTorch module', 'run the forward pass of a TheseusLayer with input tensors and optional optimizer kwargs', 'compute multivariate normal samples from a linear solver using Cholesky decomposition of the Hessian approximation', 'verify Jacobian correctness for all cost functions in the objective using numerical checks', 'create a DLMPerturbation cost function to add gradient-based perturbation terms for direct loss minimization backward mode']
```

Usage

```
{'lt_version_compare': 'use lt_version to compare two version strings and return True if the first is less than the second', 'lt_version_check_torch': 'use lt_version to check if the current torch version is less than a required minimum version', 'review_lt_version': 'review the lt_version function to understand how it parses and compares semantic version strings', 'summarize_lt_version': 'summarize the lt_version function which converts version strings to tuples and compares them lexicographically', 'test_lt_version': 'test the lt_version function with various version string pairs to verify correct comparison logic'}
```

## File: facebookresearch_theseus/theseus/global_params.py

Prompts

```
['use lt_version to compare two version strings and return True if the first is less than the second', 'use lt_version to check if the current torch version is less than a required minimum version', 'review the lt_version function to understand how it parses and compares semantic version strings', 'summarize the lt_version function which converts version strings to tuples and compares them lexicographically', 'test the lt_version function with various version string pairs to verify correct comparison logic', 'set Theseus global parameters like so2_norm_eps_float32 or fast_approx_local_jacobians using a dictionary of options', 'get the epsilon tolerance value for a given Lie group type, attribute, and torch dtype', 'reset all Theseus global parameters back to their default epsilon values', 'check whether a given torch dtype is supported by Theseus (float32 or float64 only)', 'configure the fast_approx_local_jacobians flag to enable or disable fast approximate local Jacobian computation', 'create a TheseusLayer from an Optimizer instance to wrap optimization as a differentiable PyTorch module', 'run the forward pass of a TheseusLayer with input tensors and optional optimizer kwargs', 'compute multivariate normal samples from a linear solver using Cholesky decomposition of the Hessian approximation', 'verify Jacobian correctness for all cost functions in the objective using numerical checks', 'create a DLMPerturbation cost function to add gradient-based perturbation terms for direct loss minimization backward mode']
```

Usage

```
{'set_global_params': 'set Theseus global parameters like so2_norm_eps_float32 or fast_approx_local_jacobians using a dictionary of options', 'get_eps': 'get the epsilon tolerance value for a given Lie group type, attribute, and torch dtype', 'reset_global_params': 'reset all Theseus global parameters back to their default epsilon values', 'check_dtype_supported': 'check whether a given torch dtype is supported by Theseus (float32 or float64 only)', 'configure_approx_jacobians': 'configure the fast_approx_local_jacobians flag to enable or disable fast approximate local Jacobian computation'}
```

## File: facebookresearch_theseus/theseus/theseus_layer.py

Prompts

```
['use lt_version to compare two version strings and return True if the first is less than the second', 'use lt_version to check if the current torch version is less than a required minimum version', 'review the lt_version function to understand how it parses and compares semantic version strings', 'summarize the lt_version function which converts version strings to tuples and compares them lexicographically', 'test the lt_version function with various version string pairs to verify correct comparison logic', 'set Theseus global parameters like so2_norm_eps_float32 or fast_approx_local_jacobians using a dictionary of options', 'get the epsilon tolerance value for a given Lie group type, attribute, and torch dtype', 'reset all Theseus global parameters back to their default epsilon values', 'check whether a given torch dtype is supported by Theseus (float32 or float64 only)', 'configure the fast_approx_local_jacobians flag to enable or disable fast approximate local Jacobian computation', 'create a TheseusLayer from an Optimizer instance to wrap optimization as a differentiable PyTorch module', 'run the forward pass of a TheseusLayer with input tensors and optional optimizer kwargs', 'compute multivariate normal samples from a linear solver using Cholesky decomposition of the Hessian approximation', 'verify Jacobian correctness for all cost functions in the objective using numerical checks', 'create a DLMPerturbation cost function to add gradient-based perturbation terms for direct loss minimization backward mode']
```

Usage

```
{'create_TheseusLayer': 'create a TheseusLayer from an Optimizer instance to wrap optimization as a differentiable PyTorch module', 'run_TheseusLayer_forward': 'run the forward pass of a TheseusLayer with input tensors and optional optimizer kwargs', 'compute_TheseusLayer_samples': 'compute multivariate normal samples from a linear solver using Cholesky decomposition of the Hessian approximation', 'verify_TheseusLayer_jacobians': 'verify Jacobian correctness for all cost functions in the objective using numerical checks', 'create_DLMPerturbation': 'create a DLMPerturbation cost function to add gradient-based perturbation terms for direct loss minimization backward mode'}
```

