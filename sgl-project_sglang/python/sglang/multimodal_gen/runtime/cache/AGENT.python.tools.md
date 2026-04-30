# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/cache/cache_dit_integration.py

Prompts

```
['build a CacheDitConfig dataclass to configure cache-dit acceleration parameters for diffusion transformers', 'create a step computation mask list for cache-dit SCM caching policy using preset or custom bins', 'enable cache-dit on a single transformer module with DBCache and optional TaylorSeer calibrator', 'enable cache-dit on dual transformer modules using BlockAdapter for Wan2.2 models', 'refresh cache-dit context on a transformer with updated inference step count and SCM preset', 'build a DiT model class that inherits TeaCacheMixin to enable temporal similarity-based caching for diffusion inference', 'create a TeaCacheContext dataclass instance with current timestep, threshold, and CFG branch information for cache decisions', 'test the _compute_teacache_decision method to determine whether to compute or skip a diffusion timestep based on L1 distance', 'refactor the _compute_l1_and_decide method to compute relative L1 distance with polynomial rescaling and cache threshold logic', 'review the reset_teacache_state method to ensure all cache fields including CFG negative branch are properly cleared between generations']
```

Usage

```
{'build_cachedit_config': 'build a CacheDitConfig dataclass to configure cache-dit acceleration parameters for diffusion transformers', 'create_scm_mask': 'create a step computation mask list for cache-dit SCM caching policy using preset or custom bins', 'enable_cache_on_transformer': 'enable cache-dit on a single transformer module with DBCache and optional TaylorSeer calibrator', 'enable_cache_on_dual_transformer': 'enable cache-dit on dual transformer modules using BlockAdapter for Wan2.2 models', 'refresh_context_on_transformer': 'refresh cache-dit context on a transformer with updated inference step count and SCM preset'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/cache/teacache.py

Prompts

```
['build a CacheDitConfig dataclass to configure cache-dit acceleration parameters for diffusion transformers', 'create a step computation mask list for cache-dit SCM caching policy using preset or custom bins', 'enable cache-dit on a single transformer module with DBCache and optional TaylorSeer calibrator', 'enable cache-dit on dual transformer modules using BlockAdapter for Wan2.2 models', 'refresh cache-dit context on a transformer with updated inference step count and SCM preset', 'build a DiT model class that inherits TeaCacheMixin to enable temporal similarity-based caching for diffusion inference', 'create a TeaCacheContext dataclass instance with current timestep, threshold, and CFG branch information for cache decisions', 'test the _compute_teacache_decision method to determine whether to compute or skip a diffusion timestep based on L1 distance', 'refactor the _compute_l1_and_decide method to compute relative L1 distance with polynomial rescaling and cache threshold logic', 'review the reset_teacache_state method to ensure all cache fields including CFG negative branch are properly cleared between generations']
```

Usage

```
{'build_TeaCacheMixin': 'build a DiT model class that inherits TeaCacheMixin to enable temporal similarity-based caching for diffusion inference', 'create_TeaCacheContext': 'create a TeaCacheContext dataclass instance with current timestep, threshold, and CFG branch information for cache decisions', 'test__compute_teacache_decision': 'test the _compute_teacache_decision method to determine whether to compute or skip a diffusion timestep based on L1 distance', 'refactor__compute_l1_and_decide': 'refactor the _compute_l1_and_decide method to compute relative L1 distance with polynomial rescaling and cache threshold logic', 'review_TeaCacheMixin_reset_teacache_state': 'review the reset_teacache_state method to ensure all cache fields including CFG negative branch are properly cleared between generations'}
```

