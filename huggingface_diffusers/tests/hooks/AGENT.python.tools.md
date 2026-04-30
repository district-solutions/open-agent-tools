# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/hooks/test_group_offloading.py

Prompts

```
['test that group offloading produces correct outputs with block_level and leaf_level offload types', "test conditionally executed modules don't cause device mismatch when using streams with group offloading", 'test that parameters from non-computational layers in nested containers are handled correctly with group offloading', 'test VAE-like AutoencoderKL model with block-level group offloading without streams for output correctness', 'test that applying model or sequential CPU offloading on a group offloaded module raises a ValueError', 'register AddHook and MultiplyHook on a model using HookRegistry', 'create a StatefulAddHook that increments its value on each forward pass', 'test SkipLayerHook to skip or pass through a model layer', 'reset all stateful hooks in the registry to their initial state', 'verify the pre_forward and post_forward invocation order of registered hooks', 'test that MagCacheConfig raises ValueError when mag_ratios are missing and calibrate is False', 'test that MagCache correctly calculates residuals and skips transformer blocks when conditions are met', 'test that retention_ratio prevents block skipping even when accumulated error is below threshold', 'test MagCache compatibility with Flux-like models that return tuples of hidden and encoder hidden states', 'test that MagCache calibration mode records residual ratios across inference steps before resetting state']
```

Usage

```
{'test_group_offloading_forward_pass': 'test that group offloading produces correct outputs with block_level and leaf_level offload types', 'test_conditional_modules_with_stream': "test conditionally executed modules don't cause device mismatch when using streams with group offloading", 'test_nested_container_parameters_offloading': 'test that parameters from non-computational layers in nested containers are handled correctly with group offloading', 'test_vae_like_model_without_streams': 'test VAE-like AutoencoderKL model with block-level group offloading without streams for output correctness', 'test_error_raised_if_conflicting_offloading': 'test that applying model or sequential CPU offloading on a group offloaded module raises a ValueError'}
```

## File: huggingface_diffusers/tests/hooks/test_hooks.py

Prompts

```
['test that group offloading produces correct outputs with block_level and leaf_level offload types', "test conditionally executed modules don't cause device mismatch when using streams with group offloading", 'test that parameters from non-computational layers in nested containers are handled correctly with group offloading', 'test VAE-like AutoencoderKL model with block-level group offloading without streams for output correctness', 'test that applying model or sequential CPU offloading on a group offloaded module raises a ValueError', 'register AddHook and MultiplyHook on a model using HookRegistry', 'create a StatefulAddHook that increments its value on each forward pass', 'test SkipLayerHook to skip or pass through a model layer', 'reset all stateful hooks in the registry to their initial state', 'verify the pre_forward and post_forward invocation order of registered hooks', 'test that MagCacheConfig raises ValueError when mag_ratios are missing and calibrate is False', 'test that MagCache correctly calculates residuals and skips transformer blocks when conditions are met', 'test that retention_ratio prevents block skipping even when accumulated error is below threshold', 'test MagCache compatibility with Flux-like models that return tuples of hidden and encoder hidden states', 'test that MagCache calibration mode records residual ratios across inference steps before resetting state']
```

Usage

```
{'register_hooks_on_model': 'register AddHook and MultiplyHook on a model using HookRegistry', 'create_stateful_add_hook': 'create a StatefulAddHook that increments its value on each forward pass', 'test_skip_layer_hook': 'test SkipLayerHook to skip or pass through a model layer', 'reset_stateful_hooks': 'reset all stateful hooks in the registry to their initial state', 'verify_hook_invocation_order': 'verify the pre_forward and post_forward invocation order of registered hooks'}
```

## File: huggingface_diffusers/tests/hooks/test_mag_cache.py

Prompts

```
['test that group offloading produces correct outputs with block_level and leaf_level offload types', "test conditionally executed modules don't cause device mismatch when using streams with group offloading", 'test that parameters from non-computational layers in nested containers are handled correctly with group offloading', 'test VAE-like AutoencoderKL model with block-level group offloading without streams for output correctness', 'test that applying model or sequential CPU offloading on a group offloaded module raises a ValueError', 'register AddHook and MultiplyHook on a model using HookRegistry', 'create a StatefulAddHook that increments its value on each forward pass', 'test SkipLayerHook to skip or pass through a model layer', 'reset all stateful hooks in the registry to their initial state', 'verify the pre_forward and post_forward invocation order of registered hooks', 'test that MagCacheConfig raises ValueError when mag_ratios are missing and calibrate is False', 'test that MagCache correctly calculates residuals and skips transformer blocks when conditions are met', 'test that retention_ratio prevents block skipping even when accumulated error is below threshold', 'test MagCache compatibility with Flux-like models that return tuples of hidden and encoder hidden states', 'test that MagCache calibration mode records residual ratios across inference steps before resetting state']
```

Usage

```
{'test_mag_cache_validation': 'test that MagCacheConfig raises ValueError when mag_ratios are missing and calibrate is False', 'test_mag_cache_skipping_logic': 'test that MagCache correctly calculates residuals and skips transformer blocks when conditions are met', 'test_mag_cache_retention': 'test that retention_ratio prevents block skipping even when accumulated error is below threshold', 'test_mag_cache_tuple_outputs': 'test MagCache compatibility with Flux-like models that return tuples of hidden and encoder hidden states', 'test_mag_cache_calibration': 'test that MagCache calibration mode records residual ratios across inference steps before resetting state'}
```

