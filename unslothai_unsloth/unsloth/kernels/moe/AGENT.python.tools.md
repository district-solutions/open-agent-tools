# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/autotune_cache.py

Prompts

```
['get or autotune MoE kernel configurations for given model parameters, returning forward and backward configs', 'load cached MoE kernel configuration from disk for a given cache key, validating device capability', 'save MoE kernel configurations to disk cache with timestamp, device capability, and metadata', 'clear all in-memory MoE kernel configuration caches and autotune completion markers', 'check whether autotuning has already been completed for a given cache key']
```

Usage

```
{'get_or_autotune_moe_kernels': 'get or autotune MoE kernel configurations for given model parameters, returning forward and backward configs', 'load_cached_config': 'load cached MoE kernel configuration from disk for a given cache key, validating device capability', 'save_cached_config': 'save MoE kernel configurations to disk cache with timestamp, device capability, and metadata', 'clear_cache': 'clear all in-memory MoE kernel configuration caches and autotune completion markers', 'is_autotuning_completed': 'check whether autotuning has already been completed for a given cache key'}
```

