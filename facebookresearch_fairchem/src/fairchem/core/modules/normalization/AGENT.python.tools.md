# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/modules/normalization/_load_utils.py

Prompts

```
['save a torch state dictionary to a checkpoint file in the specified directory', 'load normalizer or element reference modules from a config file and check for duplicate targets', 'load or fit normalizers from a config dictionary using a fit function and dataset', 'review the _load_check_duplicates function to understand how it detects duplicate normalization targets', 'refactor the _load_from_config function to support additional config options for fitting modules', 'fit linear element references for target properties using a dataset and least squares regression', 'create a LinearReferences module from a .pt or .npz file or state dictionary', 'subtract element reference values from a tensor using the ElementReferences apply_refs method', 'remove linear references from target tensors using the LinearReferences dereference method', 'load element references from a config dictionary using load_references_from_config with a dataset', 'create a Normalizer instance by providing explicit mean and rmsd float values', 'create a Normalizer by passing a tensor of target values to auto compute mean and rmsd', 'fit normalizers for multiple targets by computing mean and rmsd from a PyTorch dataset', 'load normalizers from a config dictionary with optional dataset fitting and checkpoint directory', 'normalize a tensor with Normalizer.norm and denormalize with Normalizer.denorm using stored mean and rmsd']
```

Usage

```
{'save_checkpoint_state': 'save a torch state dictionary to a checkpoint file in the specified directory', 'load_normalizers_from_file': 'load normalizer or element reference modules from a config file and check for duplicate targets', 'load_or_fit_from_config': 'load or fit normalizers from a config dictionary using a fit function and dataset', 'review_load_check_duplicates': 'review the _load_check_duplicates function to understand how it detects duplicate normalization targets', 'refactor_load_from_config': 'refactor the _load_from_config function to support additional config options for fitting modules'}
```

## File: facebookresearch_fairchem/src/fairchem/core/modules/normalization/element_references.py

Prompts

```
['save a torch state dictionary to a checkpoint file in the specified directory', 'load normalizer or element reference modules from a config file and check for duplicate targets', 'load or fit normalizers from a config dictionary using a fit function and dataset', 'review the _load_check_duplicates function to understand how it detects duplicate normalization targets', 'refactor the _load_from_config function to support additional config options for fitting modules', 'fit linear element references for target properties using a dataset and least squares regression', 'create a LinearReferences module from a .pt or .npz file or state dictionary', 'subtract element reference values from a tensor using the ElementReferences apply_refs method', 'remove linear references from target tensors using the LinearReferences dereference method', 'load element references from a config dictionary using load_references_from_config with a dataset', 'create a Normalizer instance by providing explicit mean and rmsd float values', 'create a Normalizer by passing a tensor of target values to auto compute mean and rmsd', 'fit normalizers for multiple targets by computing mean and rmsd from a PyTorch dataset', 'load normalizers from a config dictionary with optional dataset fitting and checkpoint directory', 'normalize a tensor with Normalizer.norm and denormalize with Normalizer.denorm using stored mean and rmsd']
```

Usage

```
{'fit_linear_references': 'fit linear element references for target properties using a dataset and least squares regression', 'create_element_references': 'create a LinearReferences module from a .pt or .npz file or state dictionary', 'apply_refs': 'subtract element reference values from a tensor using the ElementReferences apply_refs method', 'dereference_targets': 'remove linear references from target tensors using the LinearReferences dereference method', 'load_references_from_config': 'load element references from a config dictionary using load_references_from_config with a dataset'}
```

## File: facebookresearch_fairchem/src/fairchem/core/modules/normalization/normalizer.py

Prompts

```
['save a torch state dictionary to a checkpoint file in the specified directory', 'load normalizer or element reference modules from a config file and check for duplicate targets', 'load or fit normalizers from a config dictionary using a fit function and dataset', 'review the _load_check_duplicates function to understand how it detects duplicate normalization targets', 'refactor the _load_from_config function to support additional config options for fitting modules', 'fit linear element references for target properties using a dataset and least squares regression', 'create a LinearReferences module from a .pt or .npz file or state dictionary', 'subtract element reference values from a tensor using the ElementReferences apply_refs method', 'remove linear references from target tensors using the LinearReferences dereference method', 'load element references from a config dictionary using load_references_from_config with a dataset', 'create a Normalizer instance by providing explicit mean and rmsd float values', 'create a Normalizer by passing a tensor of target values to auto compute mean and rmsd', 'fit normalizers for multiple targets by computing mean and rmsd from a PyTorch dataset', 'load normalizers from a config dictionary with optional dataset fitting and checkpoint directory', 'normalize a tensor with Normalizer.norm and denormalize with Normalizer.denorm using stored mean and rmsd']
```

Usage

```
{'create_normalizer_from_mean_rmsd': 'create a Normalizer instance by providing explicit mean and rmsd float values', 'create_normalizer_from_tensor': 'create a Normalizer by passing a tensor of target values to auto compute mean and rmsd', 'fit_normalizers_from_dataset': 'fit normalizers for multiple targets by computing mean and rmsd from a PyTorch dataset', 'load_normalizers_from_config': 'load normalizers from a config dictionary with optional dataset fitting and checkpoint directory', 'normalize_and_denormalize_tensor': 'normalize a tensor with Normalizer.norm and denormalize with Normalizer.denorm using stored mean and rmsd'}
```

