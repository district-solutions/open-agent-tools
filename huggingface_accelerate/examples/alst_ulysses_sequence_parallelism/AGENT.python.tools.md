# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/examples/alst_ulysses_sequence_parallelism/sp-alst.py

Prompts

```
['create a DeepSpeedSequenceParallelConfig with variable sequence length and SDPA attention implementation', 'build an Accelerator instance configured with DeepSpeed sequence parallelism backend', 'run a training loop with differentiable weighted per-shard loss aggregation across distributed ranks', 'prepare a model, optimizer, and dataloader for distributed sequence parallel training', 'aggregate distributed training losses using all_gather across sequence parallel device groups']
```

Usage

```
{'create_sequence_parallelism_config': 'create a DeepSpeedSequenceParallelConfig with variable sequence length and SDPA attention implementation', 'build_accelerator_with_parallelism': 'build an Accelerator instance configured with DeepSpeed sequence parallelism backend', 'run_training_loop_with_sp_aggregation': 'run a training loop with differentiable weighted per-shard loss aggregation across distributed ranks', 'prepare_model_optimizer_dataloader': 'prepare a model, optimizer, and dataloader for distributed sequence parallel training', 'aggregate_distributed_training_losses': 'aggregate distributed training losses using all_gather across sequence parallel device groups'}
```

