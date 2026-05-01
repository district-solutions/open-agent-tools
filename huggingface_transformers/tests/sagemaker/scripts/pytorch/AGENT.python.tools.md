# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/sagemaker/scripts/pytorch/run_ddp.py

Prompts

```
['run a PyTorch DDP distributed training job on SageMaker using torch.distributed.launch with multi-node or single-node GPU support', 'parse unknown CLI arguments dynamically by registering them on-the-fly before re-parsing all arguments', 'launch a multi-node distributed training command with nnodes, node_rank, master_addr, and master_port flags', 'launch a single-node distributed training command with nproc_per_node set to the number of available GPUs', 'review the main function that reads SM_NUM_GPUS, SM_HOSTS, and SM_CURRENT_HOST environment variables to configure distributed training', 'run fine-tuning of a pre-trained transformer model on a GLUE benchmark task for sequence classification', 'create data training arguments with task name, max sequence length, and file paths for GLUE dataset loading', 'create model arguments specifying pretrained model name, config, tokenizer, and cache directory for fine-tuning', 'preprocess GLUE dataset by tokenizing sentences with padding and truncation to max sequence length', 'compute GLUE evaluation metrics including accuracy, combined score, or MSE depending on task type']
```

Usage

```
{'run_ddp_training': 'run a PyTorch DDP distributed training job on SageMaker using torch.distributed.launch with multi-node or single-node GPU support', 'parse_args_dynamic': 'parse unknown CLI arguments dynamically by registering them on-the-fly before re-parsing all arguments', 'launch_multinode_ddp': 'launch a multi-node distributed training command with nnodes, node_rank, master_addr, and master_port flags', 'launch_single_node_ddp': 'launch a single-node distributed training command with nproc_per_node set to the number of available GPUs', 'review_main_sagemaker_env': 'review the main function that reads SM_NUM_GPUS, SM_HOSTS, and SM_CURRENT_HOST environment variables to configure distributed training'}
```

## File: huggingface_transformers/tests/sagemaker/scripts/pytorch/run_glue_model_parallelism.py

Prompts

```
['run a PyTorch DDP distributed training job on SageMaker using torch.distributed.launch with multi-node or single-node GPU support', 'parse unknown CLI arguments dynamically by registering them on-the-fly before re-parsing all arguments', 'launch a multi-node distributed training command with nnodes, node_rank, master_addr, and master_port flags', 'launch a single-node distributed training command with nproc_per_node set to the number of available GPUs', 'review the main function that reads SM_NUM_GPUS, SM_HOSTS, and SM_CURRENT_HOST environment variables to configure distributed training', 'run fine-tuning of a pre-trained transformer model on a GLUE benchmark task for sequence classification', 'create data training arguments with task name, max sequence length, and file paths for GLUE dataset loading', 'create model arguments specifying pretrained model name, config, tokenizer, and cache directory for fine-tuning', 'preprocess GLUE dataset by tokenizing sentences with padding and truncation to max sequence length', 'compute GLUE evaluation metrics including accuracy, combined score, or MSE depending on task type']
```

Usage

```
{'run_glue_sequence_classification': 'run fine-tuning of a pre-trained transformer model on a GLUE benchmark task for sequence classification', 'create_data_training_arguments': 'create data training arguments with task name, max sequence length, and file paths for GLUE dataset loading', 'create_model_arguments': 'create model arguments specifying pretrained model name, config, tokenizer, and cache directory for fine-tuning', 'preprocess_glue_dataset': 'preprocess GLUE dataset by tokenizing sentences with padding and truncation to max sequence length', 'compute_glue_metrics': 'compute GLUE evaluation metrics including accuracy, combined score, or MSE depending on task type'}
```

