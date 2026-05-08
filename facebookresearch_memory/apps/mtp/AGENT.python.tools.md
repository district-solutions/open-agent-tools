# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/mtp/eval.py

Prompts

```
['run evaluation of an MTP model using lm_eval harness with a config file', 'run launch_eval to load a consolidated MTP model and evaluate it with lm_eval', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that consolidates checkpoints, loads an LMTransformer, and runs lm_eval', 'review the main function that merges default, file, and CLI OmegaConf configs for evaluation', 'run the MTP transformer model training loop with config file via main CLI entry point', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and data loader state', 'validate TrainArgs configuration including vocab size, data paths, distributed parallelism, and probe frequency', 'run checkpoint saving for model, optimizer, and train state via CheckpointManager during training', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the number of FLOPs per token for attention computation given layers, sequence length, and dimension', 'compute total FLOPs per token including non-embedding parameters and attention operations for model estimation', 'build a language model transformer with multiple future heads, token embeddings, and RMSNorm for MTP training', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'run_eval_mtp_model': 'run evaluation of an MTP model using lm_eval harness with a config file', 'run_launch_eval': 'run launch_eval to load a consolidated MTP model and evaluate it with lm_eval', 'run_eval_cli': 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review_launch_eval': 'review the launch_eval function that consolidates checkpoints, loads an LMTransformer, and runs lm_eval', 'review_main_config_merge': 'review the main function that merges default, file, and CLI OmegaConf configs for evaluation'}
```

## File: facebookresearch_memory/apps/mtp/train.py

Prompts

```
['run evaluation of an MTP model using lm_eval harness with a config file', 'run launch_eval to load a consolidated MTP model and evaluate it with lm_eval', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that consolidates checkpoints, loads an LMTransformer, and runs lm_eval', 'review the main function that merges default, file, and CLI OmegaConf configs for evaluation', 'run the MTP transformer model training loop with config file via main CLI entry point', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and data loader state', 'validate TrainArgs configuration including vocab size, data paths, distributed parallelism, and probe frequency', 'run checkpoint saving for model, optimizer, and train state via CheckpointManager during training', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the number of FLOPs per token for attention computation given layers, sequence length, and dimension', 'compute total FLOPs per token including non-embedding parameters and attention operations for model estimation', 'build a language model transformer with multiple future heads, token embeddings, and RMSNorm for MTP training', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'run_train_mtp_model': 'run the MTP transformer model training loop with config file via main CLI entry point', 'build_train_args': 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create_train_state': 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and data loader state', 'validate_train_args': 'validate TrainArgs configuration including vocab size, data paths, distributed parallelism, and probe frequency', 'run_checkpoint_save': 'run checkpoint saving for model, optimizer, and train state via CheckpointManager during training'}
```

## File: facebookresearch_memory/apps/mtp/transformer.py

Prompts

```
['run evaluation of an MTP model using lm_eval harness with a config file', 'run launch_eval to load a consolidated MTP model and evaluate it with lm_eval', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that consolidates checkpoints, loads an LMTransformer, and runs lm_eval', 'review the main function that merges default, file, and CLI OmegaConf configs for evaluation', 'run the MTP transformer model training loop with config file via main CLI entry point', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and data loader state', 'validate TrainArgs configuration including vocab size, data paths, distributed parallelism, and probe frequency', 'run checkpoint saving for model, optimizer, and train state via CheckpointManager during training', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the number of FLOPs per token for attention computation given layers, sequence length, and dimension', 'compute total FLOPs per token including non-embedding parameters and attention operations for model estimation', 'build a language model transformer with multiple future heads, token embeddings, and RMSNorm for MTP training', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'create_causal_mask': 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate_attention_flops': 'calculate the number of FLOPs per token for attention computation given layers, sequence length, and dimension', 'calculate_total_flops': 'compute total FLOPs per token including non-embedding parameters and attention operations for model estimation', 'build_lm_transformer': 'build a language model transformer with multiple future heads, token embeddings, and RMSNorm for MTP training', 'build_fsdp_plan': 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually'}
```

