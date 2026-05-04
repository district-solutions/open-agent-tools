# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/utils/common.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU training', 'generate a video from a list of numpy images and save to disk or tensorboard', 'resize an image tensor so the shortest edge matches a target size while preserving aspect ratio', 'create a GaussianNet module for continuous action policy output with configurable std and activation', 'compute a coordinate ascent lagrangian loss to enforce a constraint threshold on a value', 'extract scalar values from a single gym environment info dictionary filtering non-scalar metrics', 'extract scalar values from a list of gym environment info dictionaries into grouped lists', 'filter out non-scalar metrics like top_down_map and collisions from environment info dictionaries', 'flatten nested environment info dictionary keys into dot-separated scalar key-value pairs', 'customize which info dictionary keys to exclude when extracting scalar values from gym env info', 'create a Timing dict instance to track elapsed time for multiple named keys', 'use a TimingContext as a context manager or decorator to time a code block', 'use add_time on a Timing instance to accumulate elapsed time for a key', 'use avg_time on a Timing instance to track a running average of elapsed time', 'use the global g_timer singleton to record and report timing metrics']
```

Usage

```
{'batch_observations_for_rl': 'batch a list of observation dicts into a TensorDict for GPU training', 'generate_video_from_images': 'generate a video from a list of numpy images and save to disk or tensorboard', 'resize_image_shortest_edge': 'resize an image tensor so the shortest edge matches a target size while preserving aspect ratio', 'create_gaussian_policy_net': 'create a GaussianNet module for continuous action policy output with configurable std and activation', 'compute_lagrangian_loss': 'compute a coordinate ascent lagrangian loss to enforce a constraint threshold on a value'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/utils/info_dict.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU training', 'generate a video from a list of numpy images and save to disk or tensorboard', 'resize an image tensor so the shortest edge matches a target size while preserving aspect ratio', 'create a GaussianNet module for continuous action policy output with configurable std and activation', 'compute a coordinate ascent lagrangian loss to enforce a constraint threshold on a value', 'extract scalar values from a single gym environment info dictionary filtering non-scalar metrics', 'extract scalar values from a list of gym environment info dictionaries into grouped lists', 'filter out non-scalar metrics like top_down_map and collisions from environment info dictionaries', 'flatten nested environment info dictionary keys into dot-separated scalar key-value pairs', 'customize which info dictionary keys to exclude when extracting scalar values from gym env info', 'create a Timing dict instance to track elapsed time for multiple named keys', 'use a TimingContext as a context manager or decorator to time a code block', 'use add_time on a Timing instance to accumulate elapsed time for a key', 'use avg_time on a Timing instance to track a running average of elapsed time', 'use the global g_timer singleton to record and report timing metrics']
```

Usage

```
{'extract_scalars_from_single_info': 'extract scalar values from a single gym environment info dictionary filtering non-scalar metrics', 'extract_scalars_from_multiple_infos': 'extract scalar values from a list of gym environment info dictionaries into grouped lists', 'filter_non_scalar_metrics': 'filter out non-scalar metrics like top_down_map and collisions from environment info dictionaries', 'flatten_nested_info_dict': 'flatten nested environment info dictionary keys into dot-separated scalar key-value pairs', 'customize_ignore_keys': 'customize which info dictionary keys to exclude when extracting scalar values from gym env info'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/utils/timing.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU training', 'generate a video from a list of numpy images and save to disk or tensorboard', 'resize an image tensor so the shortest edge matches a target size while preserving aspect ratio', 'create a GaussianNet module for continuous action policy output with configurable std and activation', 'compute a coordinate ascent lagrangian loss to enforce a constraint threshold on a value', 'extract scalar values from a single gym environment info dictionary filtering non-scalar metrics', 'extract scalar values from a list of gym environment info dictionaries into grouped lists', 'filter out non-scalar metrics like top_down_map and collisions from environment info dictionaries', 'flatten nested environment info dictionary keys into dot-separated scalar key-value pairs', 'customize which info dictionary keys to exclude when extracting scalar values from gym env info', 'create a Timing dict instance to track elapsed time for multiple named keys', 'use a TimingContext as a context manager or decorator to time a code block', 'use add_time on a Timing instance to accumulate elapsed time for a key', 'use avg_time on a Timing instance to track a running average of elapsed time', 'use the global g_timer singleton to record and report timing metrics']
```

Usage

```
{'create_timing_dict': 'create a Timing dict instance to track elapsed time for multiple named keys', 'use_timing_context': 'use a TimingContext as a context manager or decorator to time a code block', 'add_additive_time': 'use add_time on a Timing instance to accumulate elapsed time for a key', 'use_avg_time': 'use avg_time on a Timing instance to track a running average of elapsed time', 'use_global_timer': 'use the global g_timer singleton to record and report timing metrics'}
```

