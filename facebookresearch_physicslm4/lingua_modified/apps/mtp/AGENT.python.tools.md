# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/mtp/eval.py

Prompts

```
['run evaluation of a multi-token prediction LMTransformer model using lm-eval harness with a config file', 'launch distributed evaluation by loading consolidated checkpoints and running simple_evaluate on the model', 'run the eval CLI by passing a config file path and dot-list overrides like model.dim=64', 'review the launch_eval function that handles checkpoint consolidation, model loading, and metric logging', 'review the main function that merges default, file, and CLI OmegaConf arguments before calling launch_eval', 'run the MTP transformer training loop with config file via OmegaConf CLI arguments', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize the LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'build a multi-token prediction transformer model with configurable future heads and vocabulary size', 'run the LMTransformer forward pass with token values and optional targets for training or inference', 'calculate the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings and transformer layers']
```

Usage

```
{'run_eval_mtp_model': 'run evaluation of a multi-token prediction LMTransformer model using lm-eval harness with a config file', 'run_launch_eval': 'launch distributed evaluation by loading consolidated checkpoints and running simple_evaluate on the model', 'run_main_cli': 'run the eval CLI by passing a config file path and dot-list overrides like model.dim=64', 'review_launch_eval': 'review the launch_eval function that handles checkpoint consolidation, model loading, and metric logging', 'review_main': 'review the main function that merges default, file, and CLI OmegaConf arguments before calling launch_eval'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/mtp/train.py

Prompts

```
['run evaluation of a multi-token prediction LMTransformer model using lm-eval harness with a config file', 'launch distributed evaluation by loading consolidated checkpoints and running simple_evaluate on the model', 'run the eval CLI by passing a config file path and dot-list overrides like model.dim=64', 'review the launch_eval function that handles checkpoint consolidation, model loading, and metric logging', 'review the main function that merges default, file, and CLI OmegaConf arguments before calling launch_eval', 'run the MTP transformer training loop with config file via OmegaConf CLI arguments', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize the LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'build a multi-token prediction transformer model with configurable future heads and vocabulary size', 'run the LMTransformer forward pass with token values and optional targets for training or inference', 'calculate the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings and transformer layers']
```

Usage

```
{'run_mtp_training': 'run the MTP transformer training loop with config file via OmegaConf CLI arguments', 'build_train_args': 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create_train_state': 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate_train_args': 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize_lm_model': 'parallelize the LMTransformer model using FSDP and tensor parallelism across a device mesh'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/mtp/transformer.py

Prompts

```
['run evaluation of a multi-token prediction LMTransformer model using lm-eval harness with a config file', 'launch distributed evaluation by loading consolidated checkpoints and running simple_evaluate on the model', 'run the eval CLI by passing a config file path and dot-list overrides like model.dim=64', 'review the launch_eval function that handles checkpoint consolidation, model loading, and metric logging', 'review the main function that merges default, file, and CLI OmegaConf arguments before calling launch_eval', 'run the MTP transformer training loop with config file via OmegaConf CLI arguments', 'build a TrainArgs dataclass to configure model, data, optimizer, distributed, and checkpoint settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, dump dir, data paths, and distributed parallelism configuration', 'parallelize the LMTransformer model using FSDP and tensor parallelism across a device mesh', 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'build a multi-token prediction transformer model with configurable future heads and vocabulary size', 'run the LMTransformer forward pass with token values and optional targets for training or inference', 'calculate the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build an FSDP grouping plan for token embeddings and transformer layers']
```

Usage

```
{'create_causal_mask': 'create a causal attention mask for xformers, sdpa, or flex_attention with optional sliding window support', 'build_lmtransformer': 'build a multi-token prediction transformer model with configurable future heads and vocabulary size', 'run_lmtransformer_forward': 'run the LMTransformer forward pass with token values and optional targets for training or inference', 'calculate_flops_per_token': 'calculate the number of FLOPs per token given model parameters, layers, dimension, and sequence length', 'build_fsdp_grouping_plan': 'build an FSDP grouping plan for token embeddings and transformer layers'}
```

