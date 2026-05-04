# Agent Python Tools

- repo: facebookresearch/audioseal
- repo_uri: https://github.com/facebookresearch/audioseal

## File: facebookresearch_audioseal/src/audioseal/libs/moshi/utils/compile.py

Prompts

```
['use the no_compile context manager to temporarily disable torch.compile in a code block', 'apply the torch_compile_lazy decorator to a function for lazy compilation on first call', 'use simple_checkpoint to wrap an nn.Module forward pass with activation checkpointing compatible with FSDP', 'use the no_cuda_graph context manager to deactivate CUDA graphing for a block of code', 'wrap a callable with cuda_graph to automatically CUDA graph it after warmup steps']
```

Usage

```
{'use_no_compile_context_manager': 'use the no_compile context manager to temporarily disable torch.compile in a code block', 'apply_torch_compile_lazy_decorator': 'apply the torch_compile_lazy decorator to a function for lazy compilation on first call', 'checkpoint_module_with_simple_checkpoint': 'use simple_checkpoint to wrap an nn.Module forward pass with activation checkpointing compatible with FSDP', 'disable_cuda_graph_with_context_manager': 'use the no_cuda_graph context manager to deactivate CUDA graphing for a block of code', 'wrap_function_with_cuda_graph': 'wrap a callable with cuda_graph to automatically CUDA graph it after warmup steps'}
```

