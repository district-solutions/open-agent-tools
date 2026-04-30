# Agent Python Tools

- repo: shiyu-coder/Kronos
- repo_uri: https://github.com/shiyu-coder/Kronos

## File: shiyu-coder_Kronos/finetune_csv/config_loader.py

Prompts

```
['load a YAML config file and resolve dynamic model paths based on experiment name', 'get a nested config value using dot-separated key paths with optional defaults', 'update nested config values by merging a dictionary into the loaded configuration', 'get a complete configuration dictionary for tokenizer finetuning with all parameters', 'get a complete configuration dictionary for basemodel finetuning with all parameters', 'run the Kronos basemodel fine-tuning CLI with a YAML config file for financial kline data', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and DDP support', 'create train and validation DataLoaders from CSV kline data with time-based split and DistributedSampler', 'build a CustomKlineDataset PyTorch Dataset from OHLCV CSV with lookback and predict windows', 'setup distributed-aware RotatingFileHandler logging for multi-rank model training experiments', 'run the Kronos tokenizer fine-tuning script with a YAML config file via argparse CLI', 'train a Kronos tokenizer with gradient accumulation, DDP support, and validation loss tracking', 'get the total trainable parameter count of a PyTorch model formatted as K, M, or B', 'run the Kronos sequential fine-tuning trainer with a YAML config file via argparse CLI', 'train the Kronos tokenizer phase with optional pretrained loading and skip-existing support', 'train the Kronos basemodel predictor phase using the fine-tuned tokenizer', 'create a SequentialTrainer instance from a YAML config path for distributed training setup', 'setup torch.distributed process group with NCCL backend for multi-GPU training']
```

Usage

```
{'load_yaml_config': 'load a YAML config file and resolve dynamic model paths based on experiment name', 'get_nested_config_value': 'get a nested config value using dot-separated key paths with optional defaults', 'update_config_nested': 'update nested config values by merging a dictionary into the loaded configuration', 'get_tokenizer_finetune_config': 'get a complete configuration dictionary for tokenizer finetuning with all parameters', 'get_basemodel_finetune_config': 'get a complete configuration dictionary for basemodel finetuning with all parameters'}
```

## File: shiyu-coder_Kronos/finetune_csv/finetune_base_model.py

Prompts

```
['load a YAML config file and resolve dynamic model paths based on experiment name', 'get a nested config value using dot-separated key paths with optional defaults', 'update nested config values by merging a dictionary into the loaded configuration', 'get a complete configuration dictionary for tokenizer finetuning with all parameters', 'get a complete configuration dictionary for basemodel finetuning with all parameters', 'run the Kronos basemodel fine-tuning CLI with a YAML config file for financial kline data', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and DDP support', 'create train and validation DataLoaders from CSV kline data with time-based split and DistributedSampler', 'build a CustomKlineDataset PyTorch Dataset from OHLCV CSV with lookback and predict windows', 'setup distributed-aware RotatingFileHandler logging for multi-rank model training experiments', 'run the Kronos tokenizer fine-tuning script with a YAML config file via argparse CLI', 'train a Kronos tokenizer with gradient accumulation, DDP support, and validation loss tracking', 'get the total trainable parameter count of a PyTorch model formatted as K, M, or B', 'run the Kronos sequential fine-tuning trainer with a YAML config file via argparse CLI', 'train the Kronos tokenizer phase with optional pretrained loading and skip-existing support', 'train the Kronos basemodel predictor phase using the fine-tuned tokenizer', 'create a SequentialTrainer instance from a YAML config path for distributed training setup', 'setup torch.distributed process group with NCCL backend for multi-GPU training']
```

Usage

```
{'run_finetune_training': 'run the Kronos basemodel fine-tuning CLI with a YAML config file for financial kline data', 'train_model': 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and DDP support', 'create_dataloaders': 'create train and validation DataLoaders from CSV kline data with time-based split and DistributedSampler', 'build_CustomKlineDataset': 'build a CustomKlineDataset PyTorch Dataset from OHLCV CSV with lookback and predict windows', 'setup_logging': 'setup distributed-aware RotatingFileHandler logging for multi-rank model training experiments'}
```

## File: shiyu-coder_Kronos/finetune_csv/finetune_tokenizer.py

Prompts

```
['load a YAML config file and resolve dynamic model paths based on experiment name', 'get a nested config value using dot-separated key paths with optional defaults', 'update nested config values by merging a dictionary into the loaded configuration', 'get a complete configuration dictionary for tokenizer finetuning with all parameters', 'get a complete configuration dictionary for basemodel finetuning with all parameters', 'run the Kronos basemodel fine-tuning CLI with a YAML config file for financial kline data', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and DDP support', 'create train and validation DataLoaders from CSV kline data with time-based split and DistributedSampler', 'build a CustomKlineDataset PyTorch Dataset from OHLCV CSV with lookback and predict windows', 'setup distributed-aware RotatingFileHandler logging for multi-rank model training experiments', 'run the Kronos tokenizer fine-tuning script with a YAML config file via argparse CLI', 'train a Kronos tokenizer with gradient accumulation, DDP support, and validation loss tracking', 'get the total trainable parameter count of a PyTorch model formatted as K, M, or B', 'run the Kronos sequential fine-tuning trainer with a YAML config file via argparse CLI', 'train the Kronos tokenizer phase with optional pretrained loading and skip-existing support', 'train the Kronos basemodel predictor phase using the fine-tuned tokenizer', 'create a SequentialTrainer instance from a YAML config path for distributed training setup', 'setup torch.distributed process group with NCCL backend for multi-GPU training']
```

Usage

```
{'run_tokenizer_finetuning': 'run the Kronos tokenizer fine-tuning script with a YAML config file via argparse CLI', 'create_dataloaders': 'create train and validation data loaders for tokenizer training from a custom kline dataset', 'train_tokenizer': 'train a Kronos tokenizer with gradient accumulation, DDP support, and validation loss tracking', 'setup_logging': 'setup distributed training logging with rotating file handlers and console output for rank 0', 'get_model_size': 'get the total trainable parameter count of a PyTorch model formatted as K, M, or B'}
```

## File: shiyu-coder_Kronos/finetune_csv/train_sequential.py

Prompts

```
['load a YAML config file and resolve dynamic model paths based on experiment name', 'get a nested config value using dot-separated key paths with optional defaults', 'update nested config values by merging a dictionary into the loaded configuration', 'get a complete configuration dictionary for tokenizer finetuning with all parameters', 'get a complete configuration dictionary for basemodel finetuning with all parameters', 'run the Kronos basemodel fine-tuning CLI with a YAML config file for financial kline data', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and DDP support', 'create train and validation DataLoaders from CSV kline data with time-based split and DistributedSampler', 'build a CustomKlineDataset PyTorch Dataset from OHLCV CSV with lookback and predict windows', 'setup distributed-aware RotatingFileHandler logging for multi-rank model training experiments', 'run the Kronos tokenizer fine-tuning script with a YAML config file via argparse CLI', 'train a Kronos tokenizer with gradient accumulation, DDP support, and validation loss tracking', 'get the total trainable parameter count of a PyTorch model formatted as K, M, or B', 'run the Kronos sequential fine-tuning trainer with a YAML config file via argparse CLI', 'train the Kronos tokenizer phase with optional pretrained loading and skip-existing support', 'train the Kronos basemodel predictor phase using the fine-tuned tokenizer', 'create a SequentialTrainer instance from a YAML config path for distributed training setup', 'setup torch.distributed process group with NCCL backend for multi-GPU training']
```

Usage

```
{'run_sequential_finetuning': 'run the Kronos sequential fine-tuning trainer with a YAML config file via argparse CLI', 'train_tokenizer_phase': 'train the Kronos tokenizer phase with optional pretrained loading and skip-existing support', 'train_basemodel_phase': 'train the Kronos basemodel predictor phase using the fine-tuned tokenizer', 'create_sequential_trainer': 'create a SequentialTrainer instance from a YAML config path for distributed training setup', 'setup_distributed_training': 'setup torch.distributed process group with NCCL backend for multi-GPU training'}
```

