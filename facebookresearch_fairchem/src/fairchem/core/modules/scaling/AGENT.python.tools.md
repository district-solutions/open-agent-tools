# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/modules/scaling/compat.py

Prompts

```
['load scale factors from a JSON file mapping scale factor names to values', 'load scale factors from a PyTorch pickled dictionary file', "load scale factors into a PyTorch module's ScaleFactor submodules from a file or dict", 'review the load_scales_compat function to understand how it matches scale factors to modules', 'refactor the _load_scale_dict function to support additional file formats beyond JSON and PT', 'run the compute_scaling_factors function to fit ScaleFactor modules in a FairChem model using training batches', 'run the fit.py CLI script with --checkpoint and config args to compute and save scaling factors', 'review the compute_scaling_factors function that fits all or unfitted ScaleFactor modules in computation order', 'refactor the _train_batch helper to run a forward pass and loss computation without gradients', 'summarize the _prefilled_input helper that uses readline to prefill an input prompt with default text', 'create a ScaleFactor nn.Module that scales input tensors by a learned scale factor parameter', 'use the fit_context_ context manager to collect variance stats then call fit_ to compute the scale', 'set the scale_factor parameter to a specific float value using the set_ method', 'reset the ScaleFactor scale_factor parameter back to zero using the reset_ method', 'check consistency of loaded state dict parameters against the current ScaleFactor using _check_consistency', 'check that all ScaleFactor modules in a PyTorch model are fitted before inference', 'warn instead of raising when ScaleFactor modules are not fitted in a model', 'review the ensure_fitted function to understand how it validates ScaleFactor modules', 'refactor ensure_fitted to support custom error messages for unfitted scale factors', 'test ensure_fitted with a model containing both fitted and unfitted ScaleFactor modules']
```

Usage

```
{'load_scale_dict_from_json': 'load scale factors from a JSON file mapping scale factor names to values', 'load_scale_dict_from_pt': 'load scale factors from a PyTorch pickled dictionary file', 'load_scales_compat': "load scale factors into a PyTorch module's ScaleFactor submodules from a file or dict", 'review_load_scales_compat': 'review the load_scales_compat function to understand how it matches scale factors to modules', 'refactor_load_scale_dict': 'refactor the _load_scale_dict function to support additional file formats beyond JSON and PT'}
```

## File: facebookresearch_fairchem/src/fairchem/core/modules/scaling/fit.py

Prompts

```
['load scale factors from a JSON file mapping scale factor names to values', 'load scale factors from a PyTorch pickled dictionary file', "load scale factors into a PyTorch module's ScaleFactor submodules from a file or dict", 'review the load_scales_compat function to understand how it matches scale factors to modules', 'refactor the _load_scale_dict function to support additional file formats beyond JSON and PT', 'run the compute_scaling_factors function to fit ScaleFactor modules in a FairChem model using training batches', 'run the fit.py CLI script with --checkpoint and config args to compute and save scaling factors', 'review the compute_scaling_factors function that fits all or unfitted ScaleFactor modules in computation order', 'refactor the _train_batch helper to run a forward pass and loss computation without gradients', 'summarize the _prefilled_input helper that uses readline to prefill an input prompt with default text', 'create a ScaleFactor nn.Module that scales input tensors by a learned scale factor parameter', 'use the fit_context_ context manager to collect variance stats then call fit_ to compute the scale', 'set the scale_factor parameter to a specific float value using the set_ method', 'reset the ScaleFactor scale_factor parameter back to zero using the reset_ method', 'check consistency of loaded state dict parameters against the current ScaleFactor using _check_consistency', 'check that all ScaleFactor modules in a PyTorch model are fitted before inference', 'warn instead of raising when ScaleFactor modules are not fitted in a model', 'review the ensure_fitted function to understand how it validates ScaleFactor modules', 'refactor ensure_fitted to support custom error messages for unfitted scale factors', 'test ensure_fitted with a model containing both fitted and unfitted ScaleFactor modules']
```

Usage

```
{'run_compute_scaling_factors': 'run the compute_scaling_factors function to fit ScaleFactor modules in a FairChem model using training batches', 'run_fit_cli': 'run the fit.py CLI script with --checkpoint and config args to compute and save scaling factors', 'review_compute_scaling_factors': 'review the compute_scaling_factors function that fits all or unfitted ScaleFactor modules in computation order', 'refactor_train_batch': 'refactor the _train_batch helper to run a forward pass and loss computation without gradients', 'summarize_prefilled_input': 'summarize the _prefilled_input helper that uses readline to prefill an input prompt with default text'}
```

## File: facebookresearch_fairchem/src/fairchem/core/modules/scaling/scale_factor.py

Prompts

```
['load scale factors from a JSON file mapping scale factor names to values', 'load scale factors from a PyTorch pickled dictionary file', "load scale factors into a PyTorch module's ScaleFactor submodules from a file or dict", 'review the load_scales_compat function to understand how it matches scale factors to modules', 'refactor the _load_scale_dict function to support additional file formats beyond JSON and PT', 'run the compute_scaling_factors function to fit ScaleFactor modules in a FairChem model using training batches', 'run the fit.py CLI script with --checkpoint and config args to compute and save scaling factors', 'review the compute_scaling_factors function that fits all or unfitted ScaleFactor modules in computation order', 'refactor the _train_batch helper to run a forward pass and loss computation without gradients', 'summarize the _prefilled_input helper that uses readline to prefill an input prompt with default text', 'create a ScaleFactor nn.Module that scales input tensors by a learned scale factor parameter', 'use the fit_context_ context manager to collect variance stats then call fit_ to compute the scale', 'set the scale_factor parameter to a specific float value using the set_ method', 'reset the ScaleFactor scale_factor parameter back to zero using the reset_ method', 'check consistency of loaded state dict parameters against the current ScaleFactor using _check_consistency', 'check that all ScaleFactor modules in a PyTorch model are fitted before inference', 'warn instead of raising when ScaleFactor modules are not fitted in a model', 'review the ensure_fitted function to understand how it validates ScaleFactor modules', 'refactor ensure_fitted to support custom error messages for unfitted scale factors', 'test ensure_fitted with a model containing both fitted and unfitted ScaleFactor modules']
```

Usage

```
{'create_ScaleFactor_module': 'create a ScaleFactor nn.Module that scales input tensors by a learned scale factor parameter', 'fit_ScaleFactor_with_context': 'use the fit_context_ context manager to collect variance stats then call fit_ to compute the scale', 'set_ScaleFactor_value': 'set the scale_factor parameter to a specific float value using the set_ method', 'reset_ScaleFactor': 'reset the ScaleFactor scale_factor parameter back to zero using the reset_ method', 'check_ScaleFactor_consistency': 'check consistency of loaded state dict parameters against the current ScaleFactor using _check_consistency'}
```

## File: facebookresearch_fairchem/src/fairchem/core/modules/scaling/util.py

Prompts

```
['load scale factors from a JSON file mapping scale factor names to values', 'load scale factors from a PyTorch pickled dictionary file', "load scale factors into a PyTorch module's ScaleFactor submodules from a file or dict", 'review the load_scales_compat function to understand how it matches scale factors to modules', 'refactor the _load_scale_dict function to support additional file formats beyond JSON and PT', 'run the compute_scaling_factors function to fit ScaleFactor modules in a FairChem model using training batches', 'run the fit.py CLI script with --checkpoint and config args to compute and save scaling factors', 'review the compute_scaling_factors function that fits all or unfitted ScaleFactor modules in computation order', 'refactor the _train_batch helper to run a forward pass and loss computation without gradients', 'summarize the _prefilled_input helper that uses readline to prefill an input prompt with default text', 'create a ScaleFactor nn.Module that scales input tensors by a learned scale factor parameter', 'use the fit_context_ context manager to collect variance stats then call fit_ to compute the scale', 'set the scale_factor parameter to a specific float value using the set_ method', 'reset the ScaleFactor scale_factor parameter back to zero using the reset_ method', 'check consistency of loaded state dict parameters against the current ScaleFactor using _check_consistency', 'check that all ScaleFactor modules in a PyTorch model are fitted before inference', 'warn instead of raising when ScaleFactor modules are not fitted in a model', 'review the ensure_fitted function to understand how it validates ScaleFactor modules', 'refactor ensure_fitted to support custom error messages for unfitted scale factors', 'test ensure_fitted with a model containing both fitted and unfitted ScaleFactor modules']
```

Usage

```
{'ensure_fitted_check': 'check that all ScaleFactor modules in a PyTorch model are fitted before inference', 'ensure_fitted_warn': 'warn instead of raising when ScaleFactor modules are not fitted in a model', 'review_ensure_fitted': 'review the ensure_fitted function to understand how it validates ScaleFactor modules', 'refactor_ensure_fitted': 'refactor ensure_fitted to support custom error messages for unfitted scale factors', 'test_ensure_fitted': 'test ensure_fitted with a model containing both fitted and unfitted ScaleFactor modules'}
```

