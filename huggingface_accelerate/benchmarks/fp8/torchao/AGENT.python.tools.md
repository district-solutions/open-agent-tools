# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/benchmarks/fp8/torchao/ddp.py

Prompts

```
['run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review the train_baseline function that wraps a model with DDP and torchao float8 training', 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation', 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor get_training_utilities to support a custom dataset or different optimizer configuration', 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs', 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration']
```

Usage

```
{'run_train_baseline': 'run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run_train_integration': 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test_evaluate_model': 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor_filter_linear_layers': 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review_train_baseline': 'review the train_baseline function that wraps a model with DDP and torchao float8 training'}
```

## File: huggingface_accelerate/benchmarks/fp8/torchao/distrib_deepspeed.py

Prompts

```
['run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review the train_baseline function that wraps a model with DDP and torchao float8 training', 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation', 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor get_training_utilities to support a custom dataset or different optimizer configuration', 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs', 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model with raw torchao float8 and DeepSpeed', 'run_train_integration': 'run the train_integration function to train a BERT model using accelerate with fp8 mixed precision and DeepSpeed', 'run_distrib_deepspeed_benchmark': 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review_filter_linear_layers': 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test_train_baseline': 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation'}
```

## File: huggingface_accelerate/benchmarks/fp8/torchao/fp8_utils.py

Prompts

```
['run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review the train_baseline function that wraps a model with DDP and torchao float8 training', 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation', 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor get_training_utilities to support a custom dataset or different optimizer configuration', 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs', 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration']
```

Usage

```
{'get_dataloaders': 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'get_training_utilities': 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'get_named_parameters': 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'evaluate_model': 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor_get_training_utilities': 'refactor get_training_utilities to support a custom dataset or different optimizer configuration'}
```

## File: huggingface_accelerate/benchmarks/fp8/torchao/fsdp.py

Prompts

```
['run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review the train_baseline function that wraps a model with DDP and torchao float8 training', 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation', 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor get_training_utilities to support a custom dataset or different optimizer configuration', 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs', 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration']
```

Usage

```
{'run_FSDP_fp8_benchmark': 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test_filter_linear_layers': 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test_evaluate_model': 'test the evaluate_model function that runs a model on a dataloader and computes evaluation metrics', 'test_train_baseline': 'test the train_baseline function that trains a BERT model with raw torchao FSDP and fp8 conversion', 'test_train_integration': 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs'}
```

## File: huggingface_accelerate/benchmarks/fp8/torchao/non_distributed.py

Prompts

```
['run the baseline DDP training with raw torchao FP8 conversion on a BERT model', 'run the accelerate integration DDP training with FP8 mixed precision on a BERT model', 'test the evaluate_model function that computes accuracy and F1 metrics on a dataloader', 'refactor the filter_linear_layers function to customize which linear layers are excluded from FP8 conversion', 'review the train_baseline function that wraps a model with DDP and torchao float8 training', 'run the distrib_deepspeed script to benchmark accelerate against raw torchao across DeepSpeed ZERO stages 1, 2, and 3', 'review the filter_linear_layers function that filters linear layers by feature divisibility and skips first and last layers', 'test the train_baseline function to verify float8 training with DeepSpeed initialization and model evaluation', 'create train and eval dataloaders for the MRPC GLUE dataset using a given model name and batch size', 'build a complete training setup with model, optimizer, dataloaders, and LR scheduler for MRPC classification', 'extract a dictionary of named parameters from a model wrapped in parallel training wrappers', 'run a model evaluation loop over a dataloader and compute metrics with multi-process gathering support', 'refactor get_training_utilities to support a custom dataset or different optimizer configuration', 'run the FSDP fp8 benchmark comparing raw torchao baseline against accelerate integration', 'test the filter_linear_layers function that filters linear layers by feature alignment and first/last layer exclusion', 'test the train_integration function that trains a BERT model using accelerate with FSDP plugin and AORecipeKwargs', 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model with raw torchao FP8 conversion', 'run_train_integration': 'run the train_integration function to train a BERT model using accelerate with FP8 mixed precision', 'run_evaluate_model': 'run the evaluate_model function to compute accuracy and F1 metrics on a validation dataloader', 'test_filter_linear_layers': 'test the filter_linear_layers function to skip first and last linear layers for FP8 stability', 'run_benchmark_comparison': 'run the main block to compare baseline torchao FP8 training results against accelerate FP8 integration'}
```

