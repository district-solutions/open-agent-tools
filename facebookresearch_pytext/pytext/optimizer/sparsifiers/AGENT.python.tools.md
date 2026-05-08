# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/optimizer/sparsifiers/blockwise_sparsifier.py

Prompts

```
['create a BlockwiseMagnitudeSparsifier instance with sparsity, block_size, and columnwise_blocking config', 'get all 2D trainable parameters from a PyTorch model for blockwise sparsification', "get the current sparsity ratio of a model's 2D trainable parameters", 'compute a blockwise magnitude-based pruning mask for a 2D tensor parameter', 'get sparsification masks for all 2D trainable parameters in a PyTorch model', 'build an L0 projection sparsifier with 90% sparsity starting at epoch 2 with layerwise pruning', 'create a CRF L1 soft thresholding sparsifier with lambda 0.001 for transition matrix sparsification', 'create a CRF magnitude thresholding sparsifier with 90% sparsity using row-wise grouping', 'run sensitivity analysis sparsifier on a pre-trained model to find prunable weight tensors', 'get the current sparsity ratio of a model by counting nonzero trainable parameters']
```

Usage

```
{'create_blockwise_sparsifier': 'create a BlockwiseMagnitudeSparsifier instance with sparsity, block_size, and columnwise_blocking config', 'get_sparsifiable_params': 'get all 2D trainable parameters from a PyTorch model for blockwise sparsification', 'get_current_sparsity': "get the current sparsity ratio of a model's 2D trainable parameters", 'compute_param_mask': 'compute a blockwise magnitude-based pruning mask for a 2D tensor parameter', 'get_masks': 'get sparsification masks for all 2D trainable parameters in a PyTorch model'}
```

## File: facebookresearch_pytext/pytext/optimizer/sparsifiers/sparsifier.py

Prompts

```
['create a BlockwiseMagnitudeSparsifier instance with sparsity, block_size, and columnwise_blocking config', 'get all 2D trainable parameters from a PyTorch model for blockwise sparsification', "get the current sparsity ratio of a model's 2D trainable parameters", 'compute a blockwise magnitude-based pruning mask for a 2D tensor parameter', 'get sparsification masks for all 2D trainable parameters in a PyTorch model', 'build an L0 projection sparsifier with 90% sparsity starting at epoch 2 with layerwise pruning', 'create a CRF L1 soft thresholding sparsifier with lambda 0.001 for transition matrix sparsification', 'create a CRF magnitude thresholding sparsifier with 90% sparsity using row-wise grouping', 'run sensitivity analysis sparsifier on a pre-trained model to find prunable weight tensors', 'get the current sparsity ratio of a model by counting nonzero trainable parameters']
```

Usage

```
{'build_L0_projection_sparsifier': 'build an L0 projection sparsifier with 90% sparsity starting at epoch 2 with layerwise pruning', 'create_CRF_L1_SoftThresholding': 'create a CRF L1 soft thresholding sparsifier with lambda 0.001 for transition matrix sparsification', 'create_CRF_MagnitudeThresholding': 'create a CRF magnitude thresholding sparsifier with 90% sparsity using row-wise grouping', 'run_SensitivityAnalysisSparsifier': 'run sensitivity analysis sparsifier on a pre-trained model to find prunable weight tensors', 'get_current_sparsity_Sparsifier': 'get the current sparsity ratio of a model by counting nonzero trainable parameters'}
```

