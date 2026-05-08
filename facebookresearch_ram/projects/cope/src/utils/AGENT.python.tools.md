# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cope/src/utils/checkpoint.py

Prompts

```
['add checkpoint-related CLI arguments to an ArgumentParser for save frequency and keep settings', 'save a training checkpoint with model, optimizer, logger, and tokenizer state to disk', 'load model weights from a checkpoint state dictionary with optional strict matching', 'load a full checkpoint including model, optimizer, logger, and tokenizer state from disk', 'load an existing checkpoint or initialize a model from a pre-trained file path', 'add distributed training CLI arguments like --distributed, --submitit, --rank, --world-size, and --fsdp to an ArgumentParser', 'initialize a PyTorch distributed process group using NCCL backend with submitit or file-based init', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training with specified device IDs', 'wrap a Llama model with FullyShardedDataParallel using FULL_SHARD strategy and transformer auto wrap policy', 'create a DummyWrapper module that proxies forward calls and load_state_dict with FSDP-compatible state dict fallback', 'create a Logger instance with wandb integration for tracking training metrics and experiments', 'setup a named metric with optional grouping, cumulative tracking, and division by another metric', 'record a metric value for the current step that will be aggregated and logged later', 'finalize current step metrics, print results, log to wandb, and reset for the next step', 'synchronize metric values across distributed processes using torch distributed all_reduce', 'create a SupervisedWorld instance with a model, optimizer, tokenizer, and logger for supervised training', 'run a supervised training episode on a batch and compute loss metrics including answer loss', 'compute NLL loss on model scores with configurable token type masks for answer, question, or context tokens', 'train a World instance on a batch with configurable updates per batch and optional eval mode', 'generate answer tokens from a batch of prompts using the model with configurable max generation length']
```

Usage

```
{'add_args': 'add checkpoint-related CLI arguments to an ArgumentParser for save frequency and keep settings', 'save': 'save a training checkpoint with model, optimizer, logger, and tokenizer state to disk', 'load_model': 'load model weights from a checkpoint state dictionary with optional strict matching', 'load_checkpoint': 'load a full checkpoint including model, optimizer, logger, and tokenizer state from disk', 'load': 'load an existing checkpoint or initialize a model from a pre-trained file path'}
```

## File: facebookresearch_ram/projects/cope/src/utils/distributed.py

Prompts

```
['add checkpoint-related CLI arguments to an ArgumentParser for save frequency and keep settings', 'save a training checkpoint with model, optimizer, logger, and tokenizer state to disk', 'load model weights from a checkpoint state dictionary with optional strict matching', 'load a full checkpoint including model, optimizer, logger, and tokenizer state from disk', 'load an existing checkpoint or initialize a model from a pre-trained file path', 'add distributed training CLI arguments like --distributed, --submitit, --rank, --world-size, and --fsdp to an ArgumentParser', 'initialize a PyTorch distributed process group using NCCL backend with submitit or file-based init', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training with specified device IDs', 'wrap a Llama model with FullyShardedDataParallel using FULL_SHARD strategy and transformer auto wrap policy', 'create a DummyWrapper module that proxies forward calls and load_state_dict with FSDP-compatible state dict fallback', 'create a Logger instance with wandb integration for tracking training metrics and experiments', 'setup a named metric with optional grouping, cumulative tracking, and division by another metric', 'record a metric value for the current step that will be aggregated and logged later', 'finalize current step metrics, print results, log to wandb, and reset for the next step', 'synchronize metric values across distributed processes using torch distributed all_reduce', 'create a SupervisedWorld instance with a model, optimizer, tokenizer, and logger for supervised training', 'run a supervised training episode on a batch and compute loss metrics including answer loss', 'compute NLL loss on model scores with configurable token type masks for answer, question, or context tokens', 'train a World instance on a batch with configurable updates per batch and optional eval mode', 'generate answer tokens from a batch of prompts using the model with configurable max generation length']
```

Usage

```
{'add_cmd_args': 'add distributed training CLI arguments like --distributed, --submitit, --rank, --world-size, and --fsdp to an ArgumentParser', 'init_process_group': 'initialize a PyTorch distributed process group using NCCL backend with submitit or file-based init', 'wrap_model_ddp': 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training with specified device IDs', 'wrap_model_fsdp': 'wrap a Llama model with FullyShardedDataParallel using FULL_SHARD strategy and transformer auto wrap policy', 'DummyWrapper': 'create a DummyWrapper module that proxies forward calls and load_state_dict with FSDP-compatible state dict fallback'}
```

## File: facebookresearch_ram/projects/cope/src/utils/logger.py

Prompts

```
['add checkpoint-related CLI arguments to an ArgumentParser for save frequency and keep settings', 'save a training checkpoint with model, optimizer, logger, and tokenizer state to disk', 'load model weights from a checkpoint state dictionary with optional strict matching', 'load a full checkpoint including model, optimizer, logger, and tokenizer state from disk', 'load an existing checkpoint or initialize a model from a pre-trained file path', 'add distributed training CLI arguments like --distributed, --submitit, --rank, --world-size, and --fsdp to an ArgumentParser', 'initialize a PyTorch distributed process group using NCCL backend with submitit or file-based init', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training with specified device IDs', 'wrap a Llama model with FullyShardedDataParallel using FULL_SHARD strategy and transformer auto wrap policy', 'create a DummyWrapper module that proxies forward calls and load_state_dict with FSDP-compatible state dict fallback', 'create a Logger instance with wandb integration for tracking training metrics and experiments', 'setup a named metric with optional grouping, cumulative tracking, and division by another metric', 'record a metric value for the current step that will be aggregated and logged later', 'finalize current step metrics, print results, log to wandb, and reset for the next step', 'synchronize metric values across distributed processes using torch distributed all_reduce', 'create a SupervisedWorld instance with a model, optimizer, tokenizer, and logger for supervised training', 'run a supervised training episode on a batch and compute loss metrics including answer loss', 'compute NLL loss on model scores with configurable token type masks for answer, question, or context tokens', 'train a World instance on a batch with configurable updates per batch and optional eval mode', 'generate answer tokens from a batch of prompts using the model with configurable max generation length']
```

Usage

```
{'setup_wandb_logging': 'create a Logger instance with wandb integration for tracking training metrics and experiments', 'setup_metric': 'setup a named metric with optional grouping, cumulative tracking, and division by another metric', 'record_metric_value': 'record a metric value for the current step that will be aggregated and logged later', 'step_and_log_metrics': 'finalize current step metrics, print results, log to wandb, and reset for the next step', 'dist_sync_metrics': 'synchronize metric values across distributed processes using torch distributed all_reduce'}
```

## File: facebookresearch_ram/projects/cope/src/utils/world.py

Prompts

```
['add checkpoint-related CLI arguments to an ArgumentParser for save frequency and keep settings', 'save a training checkpoint with model, optimizer, logger, and tokenizer state to disk', 'load model weights from a checkpoint state dictionary with optional strict matching', 'load a full checkpoint including model, optimizer, logger, and tokenizer state from disk', 'load an existing checkpoint or initialize a model from a pre-trained file path', 'add distributed training CLI arguments like --distributed, --submitit, --rank, --world-size, and --fsdp to an ArgumentParser', 'initialize a PyTorch distributed process group using NCCL backend with submitit or file-based init', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training with specified device IDs', 'wrap a Llama model with FullyShardedDataParallel using FULL_SHARD strategy and transformer auto wrap policy', 'create a DummyWrapper module that proxies forward calls and load_state_dict with FSDP-compatible state dict fallback', 'create a Logger instance with wandb integration for tracking training metrics and experiments', 'setup a named metric with optional grouping, cumulative tracking, and division by another metric', 'record a metric value for the current step that will be aggregated and logged later', 'finalize current step metrics, print results, log to wandb, and reset for the next step', 'synchronize metric values across distributed processes using torch distributed all_reduce', 'create a SupervisedWorld instance with a model, optimizer, tokenizer, and logger for supervised training', 'run a supervised training episode on a batch and compute loss metrics including answer loss', 'compute NLL loss on model scores with configurable token type masks for answer, question, or context tokens', 'train a World instance on a batch with configurable updates per batch and optional eval mode', 'generate answer tokens from a batch of prompts using the model with configurable max generation length']
```

Usage

```
{'create_supervised_world': 'create a SupervisedWorld instance with a model, optimizer, tokenizer, and logger for supervised training', 'run_supervised_episode': 'run a supervised training episode on a batch and compute loss metrics including answer loss', 'compute_loss_with_mask': 'compute NLL loss on model scores with configurable token type masks for answer, question, or context tokens', 'train_world_batch': 'train a World instance on a batch with configurable updates per batch and optional eval mode', 'generate_answers': 'generate answer tokens from a batch of prompts using the model with configurable max generation length'}
```

