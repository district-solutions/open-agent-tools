# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/accelerate/utils/other.py

Prompts

```
['compile a PyTorch model using regional compilation to speed up cold start for LLMs and Transformers', 'compile a DeepSpeed-wrapped PyTorch model using regional compilation with inplace module.compile', 'check whether a PyTorch module was compiled with torch.compile and returns a boolean', 'check whether a PyTorch module has any submodules compiled with torch.compile', 'check whether a PyTorch module is a ModuleList with all children of the same class', "convert a PyTorch model's linear layers to transformer_engine FP8 modules for HPU inference", 'check if the transformer_engine FP8 library is available on the current HPU system', 'create a transformer_engine FP8 delayed scaling recipe with custom format and parameters', "wrap a model's gradient checkpointing function with transformer_engine activation checkpointing for FP8 training", 'check whether a given model already contains transformer_engine FP8 linear layers']
```

Usage

```
{'compile_regions_model': 'compile a PyTorch model using regional compilation to speed up cold start for LLMs and Transformers', 'compile_regions_deepspeed_model': 'compile a DeepSpeed-wrapped PyTorch model using regional compilation with inplace module.compile', 'check_is_compiled_module': 'check whether a PyTorch module was compiled with torch.compile and returns a boolean', 'check_has_compiled_regions': 'check whether a PyTorch module has any submodules compiled with torch.compile', 'check_is_repeated_blocks': 'check whether a PyTorch module is a ModuleList with all children of the same class'}
```

## File: huggingface_optimum-habana/optimum/habana/accelerate/utils/transformer_engine.py

Prompts

```
['compile a PyTorch model using regional compilation to speed up cold start for LLMs and Transformers', 'compile a DeepSpeed-wrapped PyTorch model using regional compilation with inplace module.compile', 'check whether a PyTorch module was compiled with torch.compile and returns a boolean', 'check whether a PyTorch module has any submodules compiled with torch.compile', 'check whether a PyTorch module is a ModuleList with all children of the same class', "convert a PyTorch model's linear layers to transformer_engine FP8 modules for HPU inference", 'check if the transformer_engine FP8 library is available on the current HPU system', 'create a transformer_engine FP8 delayed scaling recipe with custom format and parameters', "wrap a model's gradient checkpointing function with transformer_engine activation checkpointing for FP8 training", 'check whether a given model already contains transformer_engine FP8 linear layers']
```

Usage

```
{'convert_model_to_fp8': "convert a PyTorch model's linear layers to transformer_engine FP8 modules for HPU inference", 'check_fp8_availability': 'check if the transformer_engine FP8 library is available on the current HPU system', 'create_fp8_recipe': 'create a transformer_engine FP8 delayed scaling recipe with custom format and parameters', 'wrap_gradient_checkpointing_for_fp8': "wrap a model's gradient checkpointing function with transformer_engine activation checkpointing for FP8 training", 'check_transformer_engine_layers': 'check whether a given model already contains transformer_engine FP8 linear layers'}
```

