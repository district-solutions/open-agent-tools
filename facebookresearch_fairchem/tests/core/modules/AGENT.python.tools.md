# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/modules/test_element_references.py

Prompts

```
['fit linear element references from a dataset using least squares regression with configurable batch size and seed', 'create LinearReferences object from a PyTorch state dict or saved .pt file', 'create LinearReferences object from a numpy .npz file with element reference coefficients', 'remove element references from energy values to isolate residual energy within noise bounds', 'test that fitting linear references with the same seed produces reproducible results', 'test the MAELoss class by computing mean absolute error on energy and force predictions', 'test the MSELoss class by computing mean squared error on energy and force predictions', 'test the PerAtomMAELoss class by computing per-atom normalized mean absolute error on energy predictions', 'test the L2NormLoss class by computing L2 vector norm of force prediction residuals', 'test the DDPLoss class with mae, mse, or l2norm loss and mean or sum reduction modes', 'test the Normalizer norm and denorm methods verify mean and rmsd calculations', 'test create_normalizer from state dict, file, tensor, and direct mean rmsd values', 'fit normalizers for energy and forces targets on a dataset with override values', 'create a Normalizer from a saved pt or npz file using create_normalizer', 'create a Normalizer by computing mean and rmsd directly from a PyTorch tensor']
```

Usage

```
{'fit_linear_references': 'fit linear element references from a dataset using least squares regression with configurable batch size and seed', 'create_element_references_from_state_dict': 'create LinearReferences object from a PyTorch state dict or saved .pt file', 'create_element_references_from_npz': 'create LinearReferences object from a numpy .npz file with element reference coefficients', 'dereference_energy': 'remove element references from energy values to isolate residual energy within noise bounds', 'test_fit_seed_reproducibility': 'test that fitting linear references with the same seed produces reproducible results'}
```

## File: facebookresearch_fairchem/tests/core/modules/test_loss.py

Prompts

```
['fit linear element references from a dataset using least squares regression with configurable batch size and seed', 'create LinearReferences object from a PyTorch state dict or saved .pt file', 'create LinearReferences object from a numpy .npz file with element reference coefficients', 'remove element references from energy values to isolate residual energy within noise bounds', 'test that fitting linear references with the same seed produces reproducible results', 'test the MAELoss class by computing mean absolute error on energy and force predictions', 'test the MSELoss class by computing mean squared error on energy and force predictions', 'test the PerAtomMAELoss class by computing per-atom normalized mean absolute error on energy predictions', 'test the L2NormLoss class by computing L2 vector norm of force prediction residuals', 'test the DDPLoss class with mae, mse, or l2norm loss and mean or sum reduction modes', 'test the Normalizer norm and denorm methods verify mean and rmsd calculations', 'test create_normalizer from state dict, file, tensor, and direct mean rmsd values', 'fit normalizers for energy and forces targets on a dataset with override values', 'create a Normalizer from a saved pt or npz file using create_normalizer', 'create a Normalizer by computing mean and rmsd directly from a PyTorch tensor']
```

Usage

```
{'test_MAELoss': 'test the MAELoss class by computing mean absolute error on energy and force predictions', 'test_MSELoss': 'test the MSELoss class by computing mean squared error on energy and force predictions', 'test_PerAtomMAELoss': 'test the PerAtomMAELoss class by computing per-atom normalized mean absolute error on energy predictions', 'test_L2NormLoss': 'test the L2NormLoss class by computing L2 vector norm of force prediction residuals', 'test_DDPLoss': 'test the DDPLoss class with mae, mse, or l2norm loss and mean or sum reduction modes'}
```

## File: facebookresearch_fairchem/tests/core/modules/test_normalizer.py

Prompts

```
['fit linear element references from a dataset using least squares regression with configurable batch size and seed', 'create LinearReferences object from a PyTorch state dict or saved .pt file', 'create LinearReferences object from a numpy .npz file with element reference coefficients', 'remove element references from energy values to isolate residual energy within noise bounds', 'test that fitting linear references with the same seed produces reproducible results', 'test the MAELoss class by computing mean absolute error on energy and force predictions', 'test the MSELoss class by computing mean squared error on energy and force predictions', 'test the PerAtomMAELoss class by computing per-atom normalized mean absolute error on energy predictions', 'test the L2NormLoss class by computing L2 vector norm of force prediction residuals', 'test the DDPLoss class with mae, mse, or l2norm loss and mean or sum reduction modes', 'test the Normalizer norm and denorm methods verify mean and rmsd calculations', 'test create_normalizer from state dict, file, tensor, and direct mean rmsd values', 'fit normalizers for energy and forces targets on a dataset with override values', 'create a Normalizer from a saved pt or npz file using create_normalizer', 'create a Normalizer by computing mean and rmsd directly from a PyTorch tensor']
```

Usage

```
{'test_norm_denorm': 'test the Normalizer norm and denorm methods verify mean and rmsd calculations', 'test_create_normalizers': 'test create_normalizer from state dict, file, tensor, and direct mean rmsd values', 'fit_normalizers_energy_forces': 'fit normalizers for energy and forces targets on a dataset with override values', 'create_normalizer_from_file': 'create a Normalizer from a saved pt or npz file using create_normalizer', 'create_normalizer_from_tensor': 'create a Normalizer by computing mean and rmsd directly from a PyTorch tensor'}
```

