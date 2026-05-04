# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/acceleration/checkpoint.py

Prompts

```
['set gradient checkpointing on a PyTorch model to reduce memory usage during training', 'set gradient checkpointing on a model with FP32 attention enabled for numerical stability', 'set gradient checkpointing on a model with a custom gc_step value for sequential checkpointing', 'call a module with automatic gradient checkpointing enabled based on its grad_checkpointing attribute', 'call a sequence of modules with gradient checkpointing applied at a specified step interval']
```

Usage

```
{'set_grad_checkpoint_on_model': 'set gradient checkpointing on a PyTorch model to reduce memory usage during training', 'set_grad_checkpoint_with_fp32_attention': 'set gradient checkpointing on a model with FP32 attention enabled for numerical stability', 'set_grad_checkpoint_with_custom_step': 'set gradient checkpointing on a model with a custom gc_step value for sequential checkpointing', 'auto_grad_checkpoint_call_module': 'call a module with automatic gradient checkpointing enabled based on its grad_checkpointing attribute', 'auto_grad_checkpoint_sequential_modules': 'call a sequence of modules with gradient checkpointing applied at a specified step interval'}
```

