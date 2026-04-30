# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/envs.py

Prompts

```
['create lazy environment variable getters with _lazy_str, _lazy_int, _lazy_float, and _lazy_bool factories', 'retrieve default cache and config roots using get_default_cache_root and get_default_config_root', 'access environment variables lazily via module-level __getattr__ and __dir__ attribute lookup', 'configure cache-dit acceleration parameters with primary and secondary transformer env vars', 'register environment variables in the environment_variables dictionary with typed lazy getters', 'get model info for a model path to resolve pipeline class, sampling params, and config', 'register config classes for a new model family with sampling params, pipeline config, and hf model paths', 'check if a model path is registered in the diffusion model registry', 'get pipeline config and sampling params classes for a pipeline by name', 'check if a model path is a known non-diffusers multimodal model', 'build an argument parser that supports YAML config files and underscore-dash interchangeable argument names', 'run a method on an object given a string name, callable, or serialized bytes payload', 'create binary masks for video frame generation that preserve the first input frame', 'build optimal output dimensions from a target area and aspect ratio with alignment constraints', 'test whether the VSA library is available in the current Python environment']
```

Usage

```
{'create_lazy_env_getters': 'create lazy environment variable getters with _lazy_str, _lazy_int, _lazy_float, and _lazy_bool factories', 'retrieve_cache_config_roots': 'retrieve default cache and config roots using get_default_cache_root and get_default_config_root', 'access_env_vars_lazy': 'access environment variables lazily via module-level __getattr__ and __dir__ attribute lookup', 'configure_cache_dit_params': 'configure cache-dit acceleration parameters with primary and secondary transformer env vars', 'register_env_variable': 'register environment variables in the environment_variables dictionary with typed lazy getters'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/registry.py

Prompts

```
['create lazy environment variable getters with _lazy_str, _lazy_int, _lazy_float, and _lazy_bool factories', 'retrieve default cache and config roots using get_default_cache_root and get_default_config_root', 'access environment variables lazily via module-level __getattr__ and __dir__ attribute lookup', 'configure cache-dit acceleration parameters with primary and secondary transformer env vars', 'register environment variables in the environment_variables dictionary with typed lazy getters', 'get model info for a model path to resolve pipeline class, sampling params, and config', 'register config classes for a new model family with sampling params, pipeline config, and hf model paths', 'check if a model path is registered in the diffusion model registry', 'get pipeline config and sampling params classes for a pipeline by name', 'check if a model path is a known non-diffusers multimodal model', 'build an argument parser that supports YAML config files and underscore-dash interchangeable argument names', 'run a method on an object given a string name, callable, or serialized bytes payload', 'create binary masks for video frame generation that preserve the first input frame', 'build optimal output dimensions from a target area and aspect ratio with alignment constraints', 'test whether the VSA library is available in the current Python environment']
```

Usage

```
{'get_model_info': 'get model info for a model path to resolve pipeline class, sampling params, and config', 'register_configs': 'register config classes for a new model family with sampling params, pipeline config, and hf model paths', 'has_registered_diffusion_model_path': 'check if a model path is registered in the diffusion model registry', 'get_pipeline_config_classes': 'get pipeline config and sampling params classes for a pipeline by name', 'is_known_non_diffusers_multimodal_model': 'check if a model path is a known non-diffusers multimodal model'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/utils.py

Prompts

```
['create lazy environment variable getters with _lazy_str, _lazy_int, _lazy_float, and _lazy_bool factories', 'retrieve default cache and config roots using get_default_cache_root and get_default_config_root', 'access environment variables lazily via module-level __getattr__ and __dir__ attribute lookup', 'configure cache-dit acceleration parameters with primary and secondary transformer env vars', 'register environment variables in the environment_variables dictionary with typed lazy getters', 'get model info for a model path to resolve pipeline class, sampling params, and config', 'register config classes for a new model family with sampling params, pipeline config, and hf model paths', 'check if a model path is registered in the diffusion model registry', 'get pipeline config and sampling params classes for a pipeline by name', 'check if a model path is a known non-diffusers multimodal model', 'build an argument parser that supports YAML config files and underscore-dash interchangeable argument names', 'run a method on an object given a string name, callable, or serialized bytes payload', 'create binary masks for video frame generation that preserve the first input frame', 'build optimal output dimensions from a target area and aspect ratio with alignment constraints', 'test whether the VSA library is available in the current Python environment']
```

Usage

```
{'build_parse_args_with_config': 'build an argument parser that supports YAML config files and underscore-dash interchangeable argument names', 'run_method_with_callable_or_bytes': 'run a method on an object given a string name, callable, or serialized bytes payload', 'create_mask_for_video_frames': 'create binary masks for video frame generation that preserve the first input frame', 'build_output_dimensions_from_area': 'build optimal output dimensions from a target area and aspect ratio with alignment constraints', 'test_is_vsa_available': 'test whether the VSA library is available in the current Python environment'}
```

