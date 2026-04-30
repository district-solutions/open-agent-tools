# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/base_data_sparsifier.py

Prompts

```
['create a BaseDataSparsifier instance with a list of named tensors and default sparsity configuration', 'add a new named tensor to an existing sparsifier with optional sparsity level and mask reuse', 'get the sparsified (masked) version of a named tensor from the sparsifier container', 'squash all sparse masks into the underlying tensors and remove parametrizations', 'save and load the complete state of a data sparsifier including masks, configs, and container state', 'create a DataNormSparsifier instance with L1 norm, 50% sparsity, and 1x4 block shape', 'build a DataNormSparsifier instance using L2 norm with custom sparse block shape and zeros per block', 'test the update_mask method to generate sparsity masks from 2-D tensor data', 'refactor the __get_block_level_mask method to zero out the smallest absolute value elements within each sparse block', 'summarize the __get_data_level_mask method that computes data-level sparsity masks by sorting block norms', 'run post_training_sparse_quantize to sparsify and quantize embedding modules in a PyTorch model', 'fetch all Embedding and EmbeddingBag modules from a PyTorch model', 'test post_training_sparse_quantize with sparsify_first=True to sparsify then quantize embeddings', 'refactor post_training_sparse_quantize to support sparsify_first=False for quantize then sparsify embeddings', 'review _fetch_all_embeddings to verify it correctly traverses and returns all embedding modules']
```

Usage

```
{'create_data_sparsifier': 'create a BaseDataSparsifier instance with a list of named tensors and default sparsity configuration', 'add_data_to_sparsifier': 'add a new named tensor to an existing sparsifier with optional sparsity level and mask reuse', 'get_sparsified_data': 'get the sparsified (masked) version of a named tensor from the sparsifier container', 'squash_sparsifier_masks': 'squash all sparse masks into the underlying tensors and remove parametrizations', 'save_load_sparsifier_state': 'save and load the complete state of a data sparsifier including masks, configs, and container state'}
```

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/data_norm_sparsifier.py

Prompts

```
['create a BaseDataSparsifier instance with a list of named tensors and default sparsity configuration', 'add a new named tensor to an existing sparsifier with optional sparsity level and mask reuse', 'get the sparsified (masked) version of a named tensor from the sparsifier container', 'squash all sparse masks into the underlying tensors and remove parametrizations', 'save and load the complete state of a data sparsifier including masks, configs, and container state', 'create a DataNormSparsifier instance with L1 norm, 50% sparsity, and 1x4 block shape', 'build a DataNormSparsifier instance using L2 norm with custom sparse block shape and zeros per block', 'test the update_mask method to generate sparsity masks from 2-D tensor data', 'refactor the __get_block_level_mask method to zero out the smallest absolute value elements within each sparse block', 'summarize the __get_data_level_mask method that computes data-level sparsity masks by sorting block norms', 'run post_training_sparse_quantize to sparsify and quantize embedding modules in a PyTorch model', 'fetch all Embedding and EmbeddingBag modules from a PyTorch model', 'test post_training_sparse_quantize with sparsify_first=True to sparsify then quantize embeddings', 'refactor post_training_sparse_quantize to support sparsify_first=False for quantize then sparsify embeddings', 'review _fetch_all_embeddings to verify it correctly traverses and returns all embedding modules']
```

Usage

```
{'create_data_norm_sparsifier': 'create a DataNormSparsifier instance with L1 norm, 50% sparsity, and 1x4 block shape', 'build_data_norm_sparsifier_l2': 'build a DataNormSparsifier instance using L2 norm with custom sparse block shape and zeros per block', 'test_update_mask': 'test the update_mask method to generate sparsity masks from 2-D tensor data', 'refactor_get_block_level_mask': 'refactor the __get_block_level_mask method to zero out the smallest absolute value elements within each sparse block', 'summarize_get_data_level_mask': 'summarize the __get_data_level_mask method that computes data-level sparsity masks by sorting block norms'}
```

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/quantization_utils.py

Prompts

```
['create a BaseDataSparsifier instance with a list of named tensors and default sparsity configuration', 'add a new named tensor to an existing sparsifier with optional sparsity level and mask reuse', 'get the sparsified (masked) version of a named tensor from the sparsifier container', 'squash all sparse masks into the underlying tensors and remove parametrizations', 'save and load the complete state of a data sparsifier including masks, configs, and container state', 'create a DataNormSparsifier instance with L1 norm, 50% sparsity, and 1x4 block shape', 'build a DataNormSparsifier instance using L2 norm with custom sparse block shape and zeros per block', 'test the update_mask method to generate sparsity masks from 2-D tensor data', 'refactor the __get_block_level_mask method to zero out the smallest absolute value elements within each sparse block', 'summarize the __get_data_level_mask method that computes data-level sparsity masks by sorting block norms', 'run post_training_sparse_quantize to sparsify and quantize embedding modules in a PyTorch model', 'fetch all Embedding and EmbeddingBag modules from a PyTorch model', 'test post_training_sparse_quantize with sparsify_first=True to sparsify then quantize embeddings', 'refactor post_training_sparse_quantize to support sparsify_first=False for quantize then sparsify embeddings', 'review _fetch_all_embeddings to verify it correctly traverses and returns all embedding modules']
```

Usage

```
{'run_post_training_sparse_quantize': 'run post_training_sparse_quantize to sparsify and quantize embedding modules in a PyTorch model', 'fetch_all_embeddings': 'fetch all Embedding and EmbeddingBag modules from a PyTorch model', 'test_post_training_sparse_quantize': 'test post_training_sparse_quantize with sparsify_first=True to sparsify then quantize embeddings', 'refactor_post_training_sparse_quantize': 'refactor post_training_sparse_quantize to support sparsify_first=False for quantize then sparsify embeddings', 'review_fetch_all_embeddings': 'review _fetch_all_embeddings to verify it correctly traverses and returns all embedding modules'}
```

