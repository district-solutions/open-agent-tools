# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/utils/pytorch/layer_mask.py

Prompts

```
['create a LayerParamMasking instance and add a boolean mask buffer to a PyTorch parameterized layer', 'setup a boolean mask tensor for a PyTorch parameter with shape and dtype validation', 'update an existing layer mask buffer in-place with a new boolean tensor', 'apply a layer mask to weights and gradients during forward and backward passes', 'enable or disable all active layer masks on a LayerParamMasking instance', 'create a pruning mask creator using the PruningMaskFactory with a mask structure string like unstructured or channel', 'run unstructured pruning to create a boolean mask that zeros out the lowest-scoring individual elements based on sparsity', 'run channel pruning to mask out entire channels by aggregating scores across spatial dimensions and removing the lowest-scoring channels', 'run filter pruning to mask out entire filters by aggregating scores across input dimensions and removing the lowest-scoring filters', 'run block pruning to mask out contiguous blocks of weights by unfolding tensor dimensions and removing the lowest-scoring blocks']
```

Usage

```
{'create_layer_mask': 'create a LayerParamMasking instance and add a boolean mask buffer to a PyTorch parameterized layer', 'setup_mask_param': 'setup a boolean mask tensor for a PyTorch parameter with shape and dtype validation', 'update_layer_mask': 'update an existing layer mask buffer in-place with a new boolean tensor', 'apply_mask_weight_gradient': 'apply a layer mask to weights and gradients during forward and backward passes', 'enable_disable_masks': 'enable or disable all active layer masks on a LayerParamMasking instance'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/utils/pytorch/mask_factory.py

Prompts

```
['create a LayerParamMasking instance and add a boolean mask buffer to a PyTorch parameterized layer', 'setup a boolean mask tensor for a PyTorch parameter with shape and dtype validation', 'update an existing layer mask buffer in-place with a new boolean tensor', 'apply a layer mask to weights and gradients during forward and backward passes', 'enable or disable all active layer masks on a LayerParamMasking instance', 'create a pruning mask creator using the PruningMaskFactory with a mask structure string like unstructured or channel', 'run unstructured pruning to create a boolean mask that zeros out the lowest-scoring individual elements based on sparsity', 'run channel pruning to mask out entire channels by aggregating scores across spatial dimensions and removing the lowest-scoring channels', 'run filter pruning to mask out entire filters by aggregating scores across input dimensions and removing the lowest-scoring filters', 'run block pruning to mask out contiguous blocks of weights by unfolding tensor dimensions and removing the lowest-scoring blocks']
```

Usage

```
{'create_mask_creator': 'create a pruning mask creator using the PruningMaskFactory with a mask structure string like unstructured or channel', 'run_unstructured_pruning': 'run unstructured pruning to create a boolean mask that zeros out the lowest-scoring individual elements based on sparsity', 'run_channel_pruning': 'run channel pruning to mask out entire channels by aggregating scores across spatial dimensions and removing the lowest-scoring channels', 'run_filter_pruning': 'run filter pruning to mask out entire filters by aggregating scores across input dimensions and removing the lowest-scoring filters', 'run_block_pruning': 'run block pruning to mask out contiguous blocks of weights by unfolding tensor dimensions and removing the lowest-scoring blocks'}
```

