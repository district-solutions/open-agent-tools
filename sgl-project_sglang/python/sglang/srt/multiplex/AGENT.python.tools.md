# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/multiplex/multiplexing_mixin.py

Prompts

```
['initialize pd-multiplexing with stream groups and SM counts from a config file', 'adjust CUDA stream groups based on decode batch size and manual or automatic divisions', 'create a split prefill batch from the new prefill batch and set its forward mode', 'run the pd-multiplexing scheduler event loop with split prefill and decode across CUDA streams', 'review the SchedulerMultiplexMixin class and its pd-multiplexing scheduling logic', 'load pdmux configuration from a YAML file into a PDMuxConfig dataclass', 'initialize CUDA stream groups for prefill and decode SM partitioning on a GPU', 'divide GPU SMs into prefill and decode partitions based on architecture constraints', 'get minimum partition size and alignment multiple for a given GPU compute capability', 'set the current stream group index for switching between prefill and decode contexts']
```

Usage

```
{'init_pdmux': 'initialize pd-multiplexing with stream groups and SM counts from a config file', 'adjust_stream_groups': 'adjust CUDA stream groups based on decode batch size and manual or automatic divisions', 'update_split_prefill_batch': 'create a split prefill batch from the new prefill batch and set its forward mode', 'event_loop_pdmux': 'run the pd-multiplexing scheduler event loop with split prefill and decode across CUDA streams', 'review_SchedulerMultiplexMixin': 'review the SchedulerMultiplexMixin class and its pd-multiplexing scheduling logic'}
```

## File: sgl-project_sglang/python/sglang/srt/multiplex/pdmux_context.py

Prompts

```
['initialize pd-multiplexing with stream groups and SM counts from a config file', 'adjust CUDA stream groups based on decode batch size and manual or automatic divisions', 'create a split prefill batch from the new prefill batch and set its forward mode', 'run the pd-multiplexing scheduler event loop with split prefill and decode across CUDA streams', 'review the SchedulerMultiplexMixin class and its pd-multiplexing scheduling logic', 'load pdmux configuration from a YAML file into a PDMuxConfig dataclass', 'initialize CUDA stream groups for prefill and decode SM partitioning on a GPU', 'divide GPU SMs into prefill and decode partitions based on architecture constraints', 'get minimum partition size and alignment multiple for a given GPU compute capability', 'set the current stream group index for switching between prefill and decode contexts']
```

Usage

```
{'load_pdmux_config': 'load pdmux configuration from a YAML file into a PDMuxConfig dataclass', 'initialize_stream_groups': 'initialize CUDA stream groups for prefill and decode SM partitioning on a GPU', 'divide_sm': 'divide GPU SMs into prefill and decode partitions based on architecture constraints', 'get_arch_constraints': 'get minimum partition size and alignment multiple for a given GPU compute capability', 'set_current_stream_idx': 'set the current stream group index for switching between prefill and decode contexts'}
```

