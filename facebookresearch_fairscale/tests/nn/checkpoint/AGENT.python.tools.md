# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/nn/checkpoint/test_checkpoint_activations.py

Prompts

```
['test the checkpoint_wrapper function on a basic FFN model to verify loss and gradient correctness', 'test the checkpoint_wrapper with cpu_offload enabled to verify GPU memory savings during activation checkpointing', 'test checkpoint_wrapper on a model with multiple inputs and outputs to verify correctness across configurations', 'test the disable_checkpointing context manager to verify checkpointing can be temporarily disabled during forward and backward passes', 'test checkpoint_wrapper behavior when some model layers have requires_grad set to False to verify selective recomputation', 'test checkpoint_wrapper with LayerNorm across cpu and cuda devices with mixed precision modes', 'test checkpoint_wrapper with BatchNorm2d across cpu and cuda devices with fp16 and call_half precision', 'create a Sequential model with Linear and norm layers optionally wrapped by checkpoint_wrapper', 'test checkpoint_wrapper with fp16 mixed precision by setting param data and buffers to half precision', 'test forward and backward pass of checkpointed model with SGD optimizer and gradient computation']
```

Usage

```
{'test_checkpoint_wrapper_basic': 'test the checkpoint_wrapper function on a basic FFN model to verify loss and gradient correctness', 'test_cpu_offload_memory': 'test the checkpoint_wrapper with cpu_offload enabled to verify GPU memory savings during activation checkpointing', 'test_multiin_multiout_checkpointing': 'test checkpoint_wrapper on a model with multiple inputs and outputs to verify correctness across configurations', 'test_disable_checkpointing': 'test the disable_checkpointing context manager to verify checkpointing can be temporarily disabled during forward and backward passes', 'test_checkpoint_requires_grad': 'test checkpoint_wrapper behavior when some model layers have requires_grad set to False to verify selective recomputation'}
```

## File: facebookresearch_fairscale/tests/nn/checkpoint/test_checkpoint_activations_norm.py

Prompts

```
['test the checkpoint_wrapper function on a basic FFN model to verify loss and gradient correctness', 'test the checkpoint_wrapper with cpu_offload enabled to verify GPU memory savings during activation checkpointing', 'test checkpoint_wrapper on a model with multiple inputs and outputs to verify correctness across configurations', 'test the disable_checkpointing context manager to verify checkpointing can be temporarily disabled during forward and backward passes', 'test checkpoint_wrapper behavior when some model layers have requires_grad set to False to verify selective recomputation', 'test checkpoint_wrapper with LayerNorm across cpu and cuda devices with mixed precision modes', 'test checkpoint_wrapper with BatchNorm2d across cpu and cuda devices with fp16 and call_half precision', 'create a Sequential model with Linear and norm layers optionally wrapped by checkpoint_wrapper', 'test checkpoint_wrapper with fp16 mixed precision by setting param data and buffers to half precision', 'test forward and backward pass of checkpointed model with SGD optimizer and gradient computation']
```

Usage

```
{'test_checkpoint_wrapper_with_layernorm': 'test checkpoint_wrapper with LayerNorm across cpu and cuda devices with mixed precision modes', 'test_checkpoint_wrapper_with_batchnorm2d': 'test checkpoint_wrapper with BatchNorm2d across cpu and cuda devices with fp16 and call_half precision', 'get_model_with_checkpointing': 'create a Sequential model with Linear and norm layers optionally wrapped by checkpoint_wrapper', 'test_norm_mixed_precision_fp16': 'test checkpoint_wrapper with fp16 mixed precision by setting param data and buffers to half precision', 'test_norm_backward_pass': 'test forward and backward pass of checkpointed model with SGD optimizer and gradient computation'}
```

