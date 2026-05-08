# Agent Python Tools

- repo: facebookresearch/llm-qat
- repo_uri: https://github.com/facebookresearch/llm-qat

## File: facebookresearch_llm-qat/utils/datautils.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'create a KDTrainer instance that extends HuggingFace Trainer for knowledge distillation training', 'compute the cross-entropy KL divergence loss between student and teacher model logits', 'compute the MSE loss between student and teacher model logits', 'compute the knowledge distillation training loss using teacher and student model outputs', 'wrap a model with FSDP, ShardedDDP, or DDP for distributed knowledge distillation training', 'run process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure quantization bits for weights, activations, and KV cache', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and knowledge distillation options', 'review the ModelArguments dataclass fields for quantization bit settings and model input output paths', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback', 'review the utility functions for logging, model saving, and distributed rank retrieval', 'summarize the utils module providing logging setup, model saving, and rank utilities']
```

Usage

```
{'set_seed': 'set the random seed for numpy and torch using set_seed(seed)', 'get_train_val_dataset': 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create_CustomJsonDataset': 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize_function': 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'jload': 'load a JSON file into a dictionary using jload(filename)'}
```

## File: facebookresearch_llm-qat/utils/kd_trainer.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'create a KDTrainer instance that extends HuggingFace Trainer for knowledge distillation training', 'compute the cross-entropy KL divergence loss between student and teacher model logits', 'compute the MSE loss between student and teacher model logits', 'compute the knowledge distillation training loss using teacher and student model outputs', 'wrap a model with FSDP, ShardedDDP, or DDP for distributed knowledge distillation training', 'run process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure quantization bits for weights, activations, and KV cache', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and knowledge distillation options', 'review the ModelArguments dataclass fields for quantization bit settings and model input output paths', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback', 'review the utility functions for logging, model saving, and distributed rank retrieval', 'summarize the utils module providing logging setup, model saving, and rank utilities']
```

Usage

```
{'create_KDTrainer': 'create a KDTrainer instance that extends HuggingFace Trainer for knowledge distillation training', 'compute_ce_loss_KDTrainer': 'compute the cross-entropy KL divergence loss between student and teacher model logits', 'compute_mse_loss_KDTrainer': 'compute the MSE loss between student and teacher model logits', 'compute_loss_train_KDTrainer': 'compute the knowledge distillation training loss using teacher and student model outputs', 'wrap_model_KDTrainer': 'wrap a model with FSDP, ShardedDDP, or DDP for distributed knowledge distillation training'}
```

## File: facebookresearch_llm-qat/utils/process_args.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'create a KDTrainer instance that extends HuggingFace Trainer for knowledge distillation training', 'compute the cross-entropy KL divergence loss between student and teacher model logits', 'compute the MSE loss between student and teacher model logits', 'compute the knowledge distillation training loss using teacher and student model outputs', 'wrap a model with FSDP, ShardedDDP, or DDP for distributed knowledge distillation training', 'run process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure quantization bits for weights, activations, and KV cache', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and knowledge distillation options', 'review the ModelArguments dataclass fields for quantization bit settings and model input output paths', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback', 'review the utility functions for logging, model saving, and distributed rank retrieval', 'summarize the utils module providing logging setup, model saving, and rank utilities']
```

Usage

```
{'run_process_args': 'run process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create_model_arguments': 'create a ModelArguments dataclass to configure quantization bits for weights, activations, and KV cache', 'create_data_arguments': 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create_training_arguments': 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and knowledge distillation options', 'review_model_arguments': 'review the ModelArguments dataclass fields for quantization bit settings and model input output paths'}
```

## File: facebookresearch_llm-qat/utils/utils.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'create a KDTrainer instance that extends HuggingFace Trainer for knowledge distillation training', 'compute the cross-entropy KL divergence loss between student and teacher model logits', 'compute the MSE loss between student and teacher model logits', 'compute the knowledge distillation training loss using teacher and student model outputs', 'wrap a model with FSDP, ShardedDDP, or DDP for distributed knowledge distillation training', 'run process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure quantization bits for weights, activations, and KV cache', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and knowledge distillation options', 'review the ModelArguments dataclass fields for quantization bit settings and model input output paths', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback', 'review the utility functions for logging, model saving, and distributed rank retrieval', 'summarize the utils module providing logging setup, model saving, and rank utilities']
```

Usage

```
{'get_logger': 'create a logger with INFO level and console handler for a given logger name', 'safe_save_model_for_hf_trainer': 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get_local_rank': 'get the local rank from environment variable or torch distributed fallback', 'review_utils_functions': 'review the utility functions for logging, model saving, and distributed rank retrieval', 'summarize_utils_module': 'summarize the utils module providing logging setup, model saving, and rank utilities'}
```

