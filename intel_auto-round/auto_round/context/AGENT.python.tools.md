# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/context/base.py

Prompts

```
['create a singleton context instance by calling create_context on a BaseContext subclass', 'get the existing singleton context instance by calling get_context on a BaseContext subclass', 'reset and remove the singleton context instance by calling reset_context on a BaseContext subclass', 'build a singleton metaclass that wraps __init__ to skip re-initialization using AutoSkipInitMeta', 'review the BaseContext class and its singleton lifecycle methods for context management', 'create a CompressContext instance with default settings for model compression with low CPU memory usage', 'create a CompressContext instance with low GPU memory usage enabled to manage GPU memory during compression', 'create a CompressContext instance with a custom device map and output directory for compressed models', 'call clear_memory on a CompressContext instance to free GPU or CPU memory when low GPU memory mode is enabled', 'create a CompressContext instance with immediate packing and saving enabled along with torch compile support', 'create a ModelContext instance with a model and tokenizer for quantization on CPU', 'apply format-specific patches to the model structure before quantization post init', 'replace the forward function of all model modules with custom hook registration', 'recover the original forward function and remove all registered hook handles', 'load an MLLM or diffusion model with processor and pipe artifacts via ModelContext']
```

Usage

```
{'create_context': 'create a singleton context instance by calling create_context on a BaseContext subclass', 'get_context': 'get the existing singleton context instance by calling get_context on a BaseContext subclass', 'reset_context': 'reset and remove the singleton context instance by calling reset_context on a BaseContext subclass', 'build_singleton_metaclass': 'build a singleton metaclass that wraps __init__ to skip re-initialization using AutoSkipInitMeta', 'review_basecontext': 'review the BaseContext class and its singleton lifecycle methods for context management'}
```

## File: intel_auto-round/auto_round/context/compress.py

Prompts

```
['create a singleton context instance by calling create_context on a BaseContext subclass', 'get the existing singleton context instance by calling get_context on a BaseContext subclass', 'reset and remove the singleton context instance by calling reset_context on a BaseContext subclass', 'build a singleton metaclass that wraps __init__ to skip re-initialization using AutoSkipInitMeta', 'review the BaseContext class and its singleton lifecycle methods for context management', 'create a CompressContext instance with default settings for model compression with low CPU memory usage', 'create a CompressContext instance with low GPU memory usage enabled to manage GPU memory during compression', 'create a CompressContext instance with a custom device map and output directory for compressed models', 'call clear_memory on a CompressContext instance to free GPU or CPU memory when low GPU memory mode is enabled', 'create a CompressContext instance with immediate packing and saving enabled along with torch compile support', 'create a ModelContext instance with a model and tokenizer for quantization on CPU', 'apply format-specific patches to the model structure before quantization post init', 'replace the forward function of all model modules with custom hook registration', 'recover the original forward function and remove all registered hook handles', 'load an MLLM or diffusion model with processor and pipe artifacts via ModelContext']
```

Usage

```
{'create_compress_context_default': 'create a CompressContext instance with default settings for model compression with low CPU memory usage', 'create_compress_context_low_gpu_mem': 'create a CompressContext instance with low GPU memory usage enabled to manage GPU memory during compression', 'create_compress_context_custom_device': 'create a CompressContext instance with a custom device map and output directory for compressed models', 'clear_memory_compress_context': 'call clear_memory on a CompressContext instance to free GPU or CPU memory when low GPU memory mode is enabled', 'create_compress_context_immediate_packing': 'create a CompressContext instance with immediate packing and saving enabled along with torch compile support'}
```

## File: intel_auto-round/auto_round/context/model.py

Prompts

```
['create a singleton context instance by calling create_context on a BaseContext subclass', 'get the existing singleton context instance by calling get_context on a BaseContext subclass', 'reset and remove the singleton context instance by calling reset_context on a BaseContext subclass', 'build a singleton metaclass that wraps __init__ to skip re-initialization using AutoSkipInitMeta', 'review the BaseContext class and its singleton lifecycle methods for context management', 'create a CompressContext instance with default settings for model compression with low CPU memory usage', 'create a CompressContext instance with low GPU memory usage enabled to manage GPU memory during compression', 'create a CompressContext instance with a custom device map and output directory for compressed models', 'call clear_memory on a CompressContext instance to free GPU or CPU memory when low GPU memory mode is enabled', 'create a CompressContext instance with immediate packing and saving enabled along with torch compile support', 'create a ModelContext instance with a model and tokenizer for quantization on CPU', 'apply format-specific patches to the model structure before quantization post init', 'replace the forward function of all model modules with custom hook registration', 'recover the original forward function and remove all registered hook handles', 'load an MLLM or diffusion model with processor and pipe artifacts via ModelContext']
```

Usage

```
{'create_model_context': 'create a ModelContext instance with a model and tokenizer for quantization on CPU', 'apply_patches_model': 'apply format-specific patches to the model structure before quantization post init', 'replace_forward_hooks': 'replace the forward function of all model modules with custom hook registration', 'recover_forward_hooks': 'recover the original forward function and remove all registered hook handles', 'load_model_mllm_diffusion': 'load an MLLM or diffusion model with processor and pipe artifacts via ModelContext'}
```

