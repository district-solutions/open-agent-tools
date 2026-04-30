# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/post_training/scheduler_rl_debug_mixin.py

Prompts

```
['reset rollout debug tensors stored in a rollout session data object', 'append local rollout debug tensors (variance noise, sample means, noise std devs, model outputs) to a batch', 'consume and stack local rollout debug tensors from accumulated per-step buffers into batched tensors', 'collect and merge rollout debug tensors across all SP ranks into a single RolloutDebugTensors object', 'review the SchedulerRLDebugMixin class and its debug tensor helpers for rollout-enabled schedulers', 'prepare rollout session data on a batch before the denoising loop', 'run flow-matching SDE, CPS, or ODE sampling with log-prob computation per denoising step', 'collect accumulated rollout log-prob sums averaged over denoising steps for a batch', 'generate sharded variance noise for rollout using per-item generators', 'release rollout session data and buffers from a batch after denoising ends', 'test the python function should_do_sp_collective to determine if sequence parallel collective operations should be performed', 'build a call to gather_stacked_latents_for_sp to gather sharded latent tensors across sequence parallel ranks', 'run all_reduce_if_sp_sharded to perform an all-reduce on sharded tensors across sequence parallel ranks', 'run all_gather_if_sp_sharded to perform an all-gather on sharded tensors across sequence parallel ranks', 'summarize the python function maybe_trim_sp_rope_seq_for_batch that trims rope embeddings to match the raw latent sequence length']
```

Usage

```
{'reset_rollout_debug_tensors': 'reset rollout debug tensors stored in a rollout session data object', 'append_local_rollout_debug_tensors': 'append local rollout debug tensors (variance noise, sample means, noise std devs, model outputs) to a batch', 'consume_local_rollout_debug_tensors': 'consume and stack local rollout debug tensors from accumulated per-step buffers into batched tensors', 'collect_rollout_debug_tensors': 'collect and merge rollout debug tensors across all SP ranks into a single RolloutDebugTensors object', 'review_SchedulerRLDebugMixin': 'review the SchedulerRLDebugMixin class and its debug tensor helpers for rollout-enabled schedulers'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/post_training/scheduler_rl_mixin.py

Prompts

```
['reset rollout debug tensors stored in a rollout session data object', 'append local rollout debug tensors (variance noise, sample means, noise std devs, model outputs) to a batch', 'consume and stack local rollout debug tensors from accumulated per-step buffers into batched tensors', 'collect and merge rollout debug tensors across all SP ranks into a single RolloutDebugTensors object', 'review the SchedulerRLDebugMixin class and its debug tensor helpers for rollout-enabled schedulers', 'prepare rollout session data on a batch before the denoising loop', 'run flow-matching SDE, CPS, or ODE sampling with log-prob computation per denoising step', 'collect accumulated rollout log-prob sums averaged over denoising steps for a batch', 'generate sharded variance noise for rollout using per-item generators', 'release rollout session data and buffers from a batch after denoising ends', 'test the python function should_do_sp_collective to determine if sequence parallel collective operations should be performed', 'build a call to gather_stacked_latents_for_sp to gather sharded latent tensors across sequence parallel ranks', 'run all_reduce_if_sp_sharded to perform an all-reduce on sharded tensors across sequence parallel ranks', 'run all_gather_if_sp_sharded to perform an all-gather on sharded tensors across sequence parallel ranks', 'summarize the python function maybe_trim_sp_rope_seq_for_batch that trims rope embeddings to match the raw latent sequence length']
```

Usage

```
{'create_prepare_rollout': 'prepare rollout session data on a batch before the denoising loop', 'run_flow_sde_sampling': 'run flow-matching SDE, CPS, or ODE sampling with log-prob computation per denoising step', 'collect_rollout_log_probs': 'collect accumulated rollout log-prob sums averaged over denoising steps for a batch', 'create_rollout_variance_noise': 'generate sharded variance noise for rollout using per-item generators', 'release_rollout_resources': 'release rollout session data and buffers from a batch after denoising ends'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/post_training/sp_utils.py

Prompts

```
['reset rollout debug tensors stored in a rollout session data object', 'append local rollout debug tensors (variance noise, sample means, noise std devs, model outputs) to a batch', 'consume and stack local rollout debug tensors from accumulated per-step buffers into batched tensors', 'collect and merge rollout debug tensors across all SP ranks into a single RolloutDebugTensors object', 'review the SchedulerRLDebugMixin class and its debug tensor helpers for rollout-enabled schedulers', 'prepare rollout session data on a batch before the denoising loop', 'run flow-matching SDE, CPS, or ODE sampling with log-prob computation per denoising step', 'collect accumulated rollout log-prob sums averaged over denoising steps for a batch', 'generate sharded variance noise for rollout using per-item generators', 'release rollout session data and buffers from a batch after denoising ends', 'test the python function should_do_sp_collective to determine if sequence parallel collective operations should be performed', 'build a call to gather_stacked_latents_for_sp to gather sharded latent tensors across sequence parallel ranks', 'run all_reduce_if_sp_sharded to perform an all-reduce on sharded tensors across sequence parallel ranks', 'run all_gather_if_sp_sharded to perform an all-gather on sharded tensors across sequence parallel ranks', 'summarize the python function maybe_trim_sp_rope_seq_for_batch that trims rope embeddings to match the raw latent sequence length']
```

Usage

```
{'test_should_do_sp_collective': 'test the python function should_do_sp_collective to determine if sequence parallel collective operations should be performed', 'build_gather_stacked_latents_for_sp': 'build a call to gather_stacked_latents_for_sp to gather sharded latent tensors across sequence parallel ranks', 'run_all_reduce_if_sp_sharded': 'run all_reduce_if_sp_sharded to perform an all-reduce on sharded tensors across sequence parallel ranks', 'run_all_gather_if_sp_sharded': 'run all_gather_if_sp_sharded to perform an all-gather on sharded tensors across sequence parallel ranks', 'summarize_maybe_trim_sp_rope_seq_for_batch': 'summarize the python function maybe_trim_sp_rope_seq_for_batch that trims rope embeddings to match the raw latent sequence length'}
```

