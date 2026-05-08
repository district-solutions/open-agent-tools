# Agent Python Tools

- repo: facebookresearch/paretoq
- repo_uri: https://github.com/facebookresearch/paretoq

## File: facebookresearch_paretoq/utils/datautils.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'call process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure model input/output paths and quantization bit width', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and model max length support', 'review the process_args function that parses CLI args, creates output directories, and sets the output model local path', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback']
```

Usage

```
{'set_seed': 'set the random seed for numpy and torch using set_seed(seed)', 'get_train_val_dataset': 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create_CustomJsonDataset': 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize_function': 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'jload': 'load a JSON file into a dictionary using jload(filename)'}
```

## File: facebookresearch_paretoq/utils/process_args.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'call process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure model input/output paths and quantization bit width', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and model max length support', 'review the process_args function that parses CLI args, creates output directories, and sets the output model local path', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback']
```

Usage

```
{'process_args_parse_cli': 'call process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create_ModelArguments_dataclass': 'create a ModelArguments dataclass to configure model input/output paths and quantization bit width', 'create_DataArguments_dataclass': 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create_TrainingArguments_dataclass': 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and model max length support', 'review_process_args_workflow': 'review the process_args function that parses CLI args, creates output directories, and sets the output model local path'}
```

## File: facebookresearch_paretoq/utils/utils.py

Prompts

```
['set the random seed for numpy and torch using set_seed(seed)', 'load a JSONL file and split into train and validation datasets using get_train_val_dataset', 'create a PyTorch IterableDataset that tokenizes and groups text into fixed-size blocks using CustomJsonDataset', 'tokenize a text example using the CustomJsonDataset tokenize_function method', 'load a JSON file into a dictionary using jload(filename)', 'call process_args to parse CLI arguments into ModelArguments, DataArguments, and TrainingArguments dataclasses', 'create a ModelArguments dataclass to configure model input/output paths and quantization bit width', 'create a DataArguments dataclass to configure training and evaluation data paths and sample limits', 'create a TrainingArguments dataclass extending HuggingFace TrainingArguments with QAT and model max length support', 'review the process_args function that parses CLI args, creates output directories, and sets the output model local path', 'create a logger with INFO level and console handler for a given logger name', 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get the local rank from environment variable or torch distributed fallback']
```

Usage

```
{'get_logger': 'create a logger with INFO level and console handler for a given logger name', 'safe_save_model_for_hf_trainer': 'save a HuggingFace Trainer model state dict to disk excluding teacher keys', 'get_local_rank': 'get the local rank from environment variable or torch distributed fallback'}
```

