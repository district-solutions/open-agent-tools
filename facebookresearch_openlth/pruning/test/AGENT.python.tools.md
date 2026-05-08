# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/pruning/test/test_mask.py

Prompts

```
['create an empty Mask object that behaves like a dictionary for storing numpy arrays', 'create a Mask from a dictionary of numpy arrays or torch tensors with string keys', "create a Mask with all-ones arrays matching a model's prunable layer shapes using Mask.ones_like", 'save a Mask to disk with Mask.save and reload it with Mask.load from a root path', 'check if a saved Mask file exists at a given root path using Mask.exists', 'test the PrunedModel forward pass with a ones mask on a PyTorch model', 'test the PrunedModel backward pass and optimizer step with a ones mask', 'test that PrunedModel raises ValueError for missing excess or incorrectly shaped mask values', 'test the PrunedModel forward and backward pass with a sparse binary mask', 'test the PrunedModel save state_dict load_state_dict and disk persistence methods', 'test the sparse global pruning strategy on a CIFAR ResNet-20 model with 20% pruning fraction', 'test iterative sparse global pruning to verify previously pruned weights remain pruned across rounds', 'test sparse global pruning with specific layers excluded from pruning via the layers_to_ignore parameter', 'test that Strategy.get_pruning_hparams returns the correct PruningHparams subclass for sparse global pruning', 'test that pruning masks match the tensor shapes of all prunable layers in the model']
```

Usage

```
{'create_empty_mask': 'create an empty Mask object that behaves like a dictionary for storing numpy arrays', 'create_mask_from_dict': 'create a Mask from a dictionary of numpy arrays or torch tensors with string keys', 'create_ones_like_mask': "create a Mask with all-ones arrays matching a model's prunable layer shapes using Mask.ones_like", 'save_and_load_mask': 'save a Mask to disk with Mask.save and reload it with Mask.load from a root path', 'check_mask_exists': 'check if a saved Mask file exists at a given root path using Mask.exists'}
```

## File: facebookresearch_openlth/pruning/test/test_pruned_model.py

Prompts

```
['create an empty Mask object that behaves like a dictionary for storing numpy arrays', 'create a Mask from a dictionary of numpy arrays or torch tensors with string keys', "create a Mask with all-ones arrays matching a model's prunable layer shapes using Mask.ones_like", 'save a Mask to disk with Mask.save and reload it with Mask.load from a root path', 'check if a saved Mask file exists at a given root path using Mask.exists', 'test the PrunedModel forward pass with a ones mask on a PyTorch model', 'test the PrunedModel backward pass and optimizer step with a ones mask', 'test that PrunedModel raises ValueError for missing excess or incorrectly shaped mask values', 'test the PrunedModel forward and backward pass with a sparse binary mask', 'test the PrunedModel save state_dict load_state_dict and disk persistence methods', 'test the sparse global pruning strategy on a CIFAR ResNet-20 model with 20% pruning fraction', 'test iterative sparse global pruning to verify previously pruned weights remain pruned across rounds', 'test sparse global pruning with specific layers excluded from pruning via the layers_to_ignore parameter', 'test that Strategy.get_pruning_hparams returns the correct PruningHparams subclass for sparse global pruning', 'test that pruning masks match the tensor shapes of all prunable layers in the model']
```

Usage

```
{'test_pruned_model_forward_pass': 'test the PrunedModel forward pass with a ones mask on a PyTorch model', 'test_pruned_model_backward_pass': 'test the PrunedModel backward pass and optimizer step with a ones mask', 'test_pruned_model_mask_validation': 'test that PrunedModel raises ValueError for missing excess or incorrectly shaped mask values', 'test_pruned_model_with_sparse_mask': 'test the PrunedModel forward and backward pass with a sparse binary mask', 'test_pruned_model_save_and_load': 'test the PrunedModel save state_dict load_state_dict and disk persistence methods'}
```

## File: facebookresearch_openlth/pruning/test/test_sparse_global.py

Prompts

```
['create an empty Mask object that behaves like a dictionary for storing numpy arrays', 'create a Mask from a dictionary of numpy arrays or torch tensors with string keys', "create a Mask with all-ones arrays matching a model's prunable layer shapes using Mask.ones_like", 'save a Mask to disk with Mask.save and reload it with Mask.load from a root path', 'check if a saved Mask file exists at a given root path using Mask.exists', 'test the PrunedModel forward pass with a ones mask on a PyTorch model', 'test the PrunedModel backward pass and optimizer step with a ones mask', 'test that PrunedModel raises ValueError for missing excess or incorrectly shaped mask values', 'test the PrunedModel forward and backward pass with a sparse binary mask', 'test the PrunedModel save state_dict load_state_dict and disk persistence methods', 'test the sparse global pruning strategy on a CIFAR ResNet-20 model with 20% pruning fraction', 'test iterative sparse global pruning to verify previously pruned weights remain pruned across rounds', 'test sparse global pruning with specific layers excluded from pruning via the layers_to_ignore parameter', 'test that Strategy.get_pruning_hparams returns the correct PruningHparams subclass for sparse global pruning', 'test that pruning masks match the tensor shapes of all prunable layers in the model']
```

Usage

```
{'test_sparse_global_pruning': 'test the sparse global pruning strategy on a CIFAR ResNet-20 model with 20% pruning fraction', 'test_iterative_pruning': 'test iterative sparse global pruning to verify previously pruned weights remain pruned across rounds', 'test_prune_layers_to_ignore': 'test sparse global pruning with specific layers excluded from pruning via the layers_to_ignore parameter', 'test_get_pruning_hparams': 'test that Strategy.get_pruning_hparams returns the correct PruningHparams subclass for sparse global pruning', 'test_prune_mask_shapes': 'test that pruning masks match the tensor shapes of all prunable layers in the model'}
```

