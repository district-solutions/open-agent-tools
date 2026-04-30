# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/sparsifier/base_sparsifier.py

Prompts

```
['create a BaseSparsifier instance with default sparsity configuration for a PyTorch model', 'prepare a PyTorch model by adding sparsity parametrizations based on tensor fqn config', 'run the sparsifier step to update masks across all configured tensors', 'squash sparse masks into model weights while optionally keeping sparse parameters', 'load sparsifier state from a state dict to restore previously saved sparsity configuration', 'create a NearlyDiagonalSparsifier instance with a specified nearliness value for weight pruning', 'build a nearly diagonal mask on a module tensor by calling update_mask with nearliness and tensor name', 'test the NearlyDiagonalSparsifier class to verify mask generation with odd nearliness values', 'refactor the update_mask method to support vectorized banded matrix generation instead of row-by-row loop', 'review the NearlyDiagonalSparsifier class and its update_mask method for correctness on non-square tensors', 'swap a dense PyTorch module to its sparse equivalent using a mapping dictionary', 'test whether a module contains a specific parametrization type', 'build a converter that returns the fully qualified name for a submodule within a PyTorch model', 'refactor a function that resolves a fully qualified name to its corresponding module or tensor', 'create a FakeSparsity parametrization that applies a mask to module weights during forward pass', 'create a WeightNormSparsifier with configurable sparsity_level, sparse_block_shape, and norm', 'test the _make_tensor_mask method to create a tensor-level mask from block norms', 'refactor the _make_block_mask method to zero smallest elements within sparse blocks', 'summarize the WeightNormSparsifier class that zeroes lowest-norm sparse blocks']
```

Usage

```
{'create_BaseSparsifier': 'create a BaseSparsifier instance with default sparsity configuration for a PyTorch model', 'prepare_model_sparsifier': 'prepare a PyTorch model by adding sparsity parametrizations based on tensor fqn config', 'run_sparsifier_step': 'run the sparsifier step to update masks across all configured tensors', 'squash_mask_sparsifier': 'squash sparse masks into model weights while optionally keeping sparse parameters', 'load_sparsifier_state': 'load sparsifier state from a state dict to restore previously saved sparsity configuration'}
```

## File: pytorch_pytorch/torch/ao/pruning/sparsifier/nearly_diagonal_sparsifier.py

Prompts

```
['create a BaseSparsifier instance with default sparsity configuration for a PyTorch model', 'prepare a PyTorch model by adding sparsity parametrizations based on tensor fqn config', 'run the sparsifier step to update masks across all configured tensors', 'squash sparse masks into model weights while optionally keeping sparse parameters', 'load sparsifier state from a state dict to restore previously saved sparsity configuration', 'create a NearlyDiagonalSparsifier instance with a specified nearliness value for weight pruning', 'build a nearly diagonal mask on a module tensor by calling update_mask with nearliness and tensor name', 'test the NearlyDiagonalSparsifier class to verify mask generation with odd nearliness values', 'refactor the update_mask method to support vectorized banded matrix generation instead of row-by-row loop', 'review the NearlyDiagonalSparsifier class and its update_mask method for correctness on non-square tensors', 'swap a dense PyTorch module to its sparse equivalent using a mapping dictionary', 'test whether a module contains a specific parametrization type', 'build a converter that returns the fully qualified name for a submodule within a PyTorch model', 'refactor a function that resolves a fully qualified name to its corresponding module or tensor', 'create a FakeSparsity parametrization that applies a mask to module weights during forward pass', 'create a WeightNormSparsifier with configurable sparsity_level, sparse_block_shape, and norm', 'test the _make_tensor_mask method to create a tensor-level mask from block norms', 'refactor the _make_block_mask method to zero smallest elements within sparse blocks', 'summarize the WeightNormSparsifier class that zeroes lowest-norm sparse blocks']
```

Usage

```
{'create_NearlyDiagonalSparsifier': 'create a NearlyDiagonalSparsifier instance with a specified nearliness value for weight pruning', 'build_update_mask': 'build a nearly diagonal mask on a module tensor by calling update_mask with nearliness and tensor name', 'test_NearlyDiagonalSparsifier': 'test the NearlyDiagonalSparsifier class to verify mask generation with odd nearliness values', 'refactor_update_mask': 'refactor the update_mask method to support vectorized banded matrix generation instead of row-by-row loop', 'review_NearlyDiagonalSparsifier': 'review the NearlyDiagonalSparsifier class and its update_mask method for correctness on non-square tensors'}
```

## File: pytorch_pytorch/torch/ao/pruning/sparsifier/utils.py

Prompts

```
['create a BaseSparsifier instance with default sparsity configuration for a PyTorch model', 'prepare a PyTorch model by adding sparsity parametrizations based on tensor fqn config', 'run the sparsifier step to update masks across all configured tensors', 'squash sparse masks into model weights while optionally keeping sparse parameters', 'load sparsifier state from a state dict to restore previously saved sparsity configuration', 'create a NearlyDiagonalSparsifier instance with a specified nearliness value for weight pruning', 'build a nearly diagonal mask on a module tensor by calling update_mask with nearliness and tensor name', 'test the NearlyDiagonalSparsifier class to verify mask generation with odd nearliness values', 'refactor the update_mask method to support vectorized banded matrix generation instead of row-by-row loop', 'review the NearlyDiagonalSparsifier class and its update_mask method for correctness on non-square tensors', 'swap a dense PyTorch module to its sparse equivalent using a mapping dictionary', 'test whether a module contains a specific parametrization type', 'build a converter that returns the fully qualified name for a submodule within a PyTorch model', 'refactor a function that resolves a fully qualified name to its corresponding module or tensor', 'create a FakeSparsity parametrization that applies a mask to module weights during forward pass', 'create a WeightNormSparsifier with configurable sparsity_level, sparse_block_shape, and norm', 'test the _make_tensor_mask method to create a tensor-level mask from block norms', 'refactor the _make_block_mask method to zero smallest elements within sparse blocks', 'summarize the WeightNormSparsifier class that zeroes lowest-norm sparse blocks']
```

Usage

```
{'swap_module_dense_to_sparse': 'swap a dense PyTorch module to its sparse equivalent using a mapping dictionary', 'test_module_contains_param': 'test whether a module contains a specific parametrization type', 'build_module_to_fqn_converter': 'build a converter that returns the fully qualified name for a submodule within a PyTorch model', 'refactor_fqn_to_module_lookup': 'refactor a function that resolves a fully qualified name to its corresponding module or tensor', 'create_fake_sparsity_parametrization': 'create a FakeSparsity parametrization that applies a mask to module weights during forward pass'}
```

## File: pytorch_pytorch/torch/ao/pruning/sparsifier/weight_norm_sparsifier.py

Prompts

```
['create a BaseSparsifier instance with default sparsity configuration for a PyTorch model', 'prepare a PyTorch model by adding sparsity parametrizations based on tensor fqn config', 'run the sparsifier step to update masks across all configured tensors', 'squash sparse masks into model weights while optionally keeping sparse parameters', 'load sparsifier state from a state dict to restore previously saved sparsity configuration', 'create a NearlyDiagonalSparsifier instance with a specified nearliness value for weight pruning', 'build a nearly diagonal mask on a module tensor by calling update_mask with nearliness and tensor name', 'test the NearlyDiagonalSparsifier class to verify mask generation with odd nearliness values', 'refactor the update_mask method to support vectorized banded matrix generation instead of row-by-row loop', 'review the NearlyDiagonalSparsifier class and its update_mask method for correctness on non-square tensors', 'swap a dense PyTorch module to its sparse equivalent using a mapping dictionary', 'test whether a module contains a specific parametrization type', 'build a converter that returns the fully qualified name for a submodule within a PyTorch model', 'refactor a function that resolves a fully qualified name to its corresponding module or tensor', 'create a FakeSparsity parametrization that applies a mask to module weights during forward pass', 'create a WeightNormSparsifier with configurable sparsity_level, sparse_block_shape, and norm', 'test the _make_tensor_mask method to create a tensor-level mask from block norms', 'refactor the _make_block_mask method to zero smallest elements within sparse blocks', 'summarize the WeightNormSparsifier class that zeroes lowest-norm sparse blocks']
```

Usage

```
{'create_WeightNormSparsifier': 'create a WeightNormSparsifier with configurable sparsity_level, sparse_block_shape, and norm', 'build_update_mask': "build a sparsity mask by calling update_mask on a module's weight tensor", 'test_make_tensor_mask': 'test the _make_tensor_mask method to create a tensor-level mask from block norms', 'refactor_make_block_mask': 'refactor the _make_block_mask method to zero smallest elements within sparse blocks', 'summarize_WeightNormSparsifier': 'summarize the WeightNormSparsifier class that zeroes lowest-norm sparse blocks'}
```

