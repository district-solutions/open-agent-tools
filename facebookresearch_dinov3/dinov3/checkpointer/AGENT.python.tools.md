# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/checkpointer/checkpointer.py

Prompts

```
['save a PyTorch model and optimizer state to a distributed checkpoint directory with iteration tracking', 'load a PyTorch model and optimizer state from a distributed checkpoint directory with strict loading option', 'register state dict hooks to exclude specified frozen weights from being saved in checkpoints', 'initialize an FSDP2 model from a DCP or PyTorch standard checkpoint with optional key filtering', 'cleanup checkpoint directories based on a retention policy keeping only best or final checkpoints']
```

Usage

```
{'save_checkpoint': 'save a PyTorch model and optimizer state to a distributed checkpoint directory with iteration tracking', 'load_checkpoint': 'load a PyTorch model and optimizer state from a distributed checkpoint directory with strict loading option', 'register_dont_save_hooks': 'register state dict hooks to exclude specified frozen weights from being saved in checkpoints', 'init_fsdp_model_from_checkpoint': 'initialize an FSDP2 model from a DCP or PyTorch standard checkpoint with optional key filtering', 'cleanup_checkpoint': 'cleanup checkpoint directories based on a retention policy keeping only best or final checkpoints'}
```

