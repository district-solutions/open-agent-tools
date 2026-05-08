# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/mtp/eval.py

Prompts

```
['run evaluation of a multi-token prediction model using lm_eval harness with a config file', 'run the launch_eval function to evaluate an LMTransformer model with consolidated checkpoints', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that loads checkpoints, runs lm_eval, and writes results to JSON', 'review the main function that merges default, file, and CLI config via OmegaConf', 'run the MTP transformer training loop with config file via train.py config=path/to/config.yaml', 'train an LMTransformer model using the lingua MTP training pipeline with gradient accumulation and checkpointing', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'build a TrainState object tracking optimizer steps, accumulation steps, scheduler, and data loader state', 'save and load MTP model checkpoints with optimizer state, training state, and device mesh via CheckpointManager', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the FLOPs per token for attention computation given model layers, sequence length, and dimension', 'compute total FLOPs per token combining non-embedding parameters and attention FLOPs for a transformer model', 'build a language model transformer with multiple future prediction heads, token embeddings, and RMSNorm normalization', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'run_MTP_model_evaluation': 'run evaluation of a multi-token prediction model using lm_eval harness with a config file', 'run_launch_eval': 'run the launch_eval function to evaluate an LMTransformer model with consolidated checkpoints', 'run_eval_cli': 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review_launch_eval': 'review the launch_eval function that loads checkpoints, runs lm_eval, and writes results to JSON', 'review_main_config_merge': 'review the main function that merges default, file, and CLI config via OmegaConf'}
```

## File: facebookresearch_lingua/apps/mtp/train.py

Prompts

```
['run evaluation of a multi-token prediction model using lm_eval harness with a config file', 'run the launch_eval function to evaluate an LMTransformer model with consolidated checkpoints', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that loads checkpoints, runs lm_eval, and writes results to JSON', 'review the main function that merges default, file, and CLI config via OmegaConf', 'run the MTP transformer training loop with config file via train.py config=path/to/config.yaml', 'train an LMTransformer model using the lingua MTP training pipeline with gradient accumulation and checkpointing', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'build a TrainState object tracking optimizer steps, accumulation steps, scheduler, and data loader state', 'save and load MTP model checkpoints with optimizer state, training state, and device mesh via CheckpointManager', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the FLOPs per token for attention computation given model layers, sequence length, and dimension', 'compute total FLOPs per token combining non-embedding parameters and attention FLOPs for a transformer model', 'build a language model transformer with multiple future prediction heads, token embeddings, and RMSNorm normalization', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'run_mtp_training': 'run the MTP transformer training loop with config file via train.py config=path/to/config.yaml', 'train_LMTransformer': 'train an LMTransformer model using the lingua MTP training pipeline with gradient accumulation and checkpointing', 'validate_TrainArgs': 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'build_TrainState': 'build a TrainState object tracking optimizer steps, accumulation steps, scheduler, and data loader state', 'checkpoint_MTP_model': 'save and load MTP model checkpoints with optimizer state, training state, and device mesh via CheckpointManager'}
```

## File: facebookresearch_lingua/apps/mtp/transformer.py

Prompts

```
['run evaluation of a multi-token prediction model using lm_eval harness with a config file', 'run the launch_eval function to evaluate an LMTransformer model with consolidated checkpoints', 'run eval.py with a config file and dot-list CLI overrides for EvalArgs', 'review the launch_eval function that loads checkpoints, runs lm_eval, and writes results to JSON', 'review the main function that merges default, file, and CLI config via OmegaConf', 'run the MTP transformer training loop with config file via train.py config=path/to/config.yaml', 'train an LMTransformer model using the lingua MTP training pipeline with gradient accumulation and checkpointing', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'build a TrainState object tracking optimizer steps, accumulation steps, scheduler, and data loader state', 'save and load MTP model checkpoints with optimizer state, training state, and device mesh via CheckpointManager', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate the FLOPs per token for attention computation given model layers, sequence length, and dimension', 'compute total FLOPs per token combining non-embedding parameters and attention FLOPs for a transformer model', 'build a language model transformer with multiple future prediction heads, token embeddings, and RMSNorm normalization', 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually']
```

Usage

```
{'create_causal_mask': 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'calculate_attention_flops': 'calculate the FLOPs per token for attention computation given model layers, sequence length, and dimension', 'calculate_total_flops': 'compute total FLOPs per token combining non-embedding parameters and attention FLOPs for a transformer model', 'build_lm_transformer': 'build a language model transformer with multiple future prediction heads, token embeddings, and RMSNorm normalization', 'build_fsdp_grouping_plan': 'build an FSDP grouping plan that separates token embeddings and groups transformer layers individually'}
```

