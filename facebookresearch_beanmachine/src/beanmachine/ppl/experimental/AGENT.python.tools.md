# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/experimental/torch_jit_backend.py

Prompts

```
['get the Torch JIT backend by passing nnc_compile and experimental_inductor_compile boolean flags', 'compile a callable function using TorchInductor via functorch aot_function for optimized execution', 'jit compile a callable using the selected TorchJITBackend (NNC, INDUCTOR, or NONE fallback)', 'review the TorchJITBackend enum values NONE, NNC, and INDUCTOR for backend selection', 'summarize the jit_compile function which dispatches to nnc_jit or inductor_jit based on backend']
```

Usage

```
{'get_backend_select': 'get the Torch JIT backend by passing nnc_compile and experimental_inductor_compile boolean flags', 'inductor_jit_compile': 'compile a callable function using TorchInductor via functorch aot_function for optimized execution', 'jit_compile_dispatch': 'jit compile a callable using the selected TorchJITBackend (NNC, INDUCTOR, or NONE fallback)', 'review_TorchJITBackend_enum': 'review the TorchJITBackend enum values NONE, NNC, and INDUCTOR for backend selection', 'summarize_jit_compile': 'summarize the jit_compile function which dispatches to nnc_jit or inductor_jit based on backend'}
```

