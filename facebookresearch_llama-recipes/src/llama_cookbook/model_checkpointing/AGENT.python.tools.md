# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/src/llama_cookbook/model_checkpointing/checkpoint_handler.py

Prompts

```
['save an FSDP model and optional optimizer as a sharded state dict checkpoint to disk', 'load an FSDP model from a sharded state dict checkpoint directory using FileSystemReader', 'save a full non-sharded FSDP model checkpoint to a single .pt file on rank 0', 'load a full model checkpoint from a .pt file onto rank 0 CPU before FSDP wrapping', 'save a PEFT model checkpoint using save_pretrained with FSDP-aware full state dict options']
```

Usage

```
{'save_model_sharded': 'save an FSDP model and optional optimizer as a sharded state dict checkpoint to disk', 'load_model_sharded': 'load an FSDP model from a sharded state dict checkpoint directory using FileSystemReader', 'save_full_checkpoint': 'save a full non-sharded FSDP model checkpoint to a single .pt file on rank 0', 'load_model_checkpoint': 'load a full model checkpoint from a .pt file onto rank 0 CPU before FSDP wrapping', 'save_peft_checkpoint': 'save a PEFT model checkpoint using save_pretrained with FSDP-aware full state dict options'}
```

