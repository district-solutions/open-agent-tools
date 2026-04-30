# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/examples/torch_native_parallelism/fsdp2_fp8.py

Prompts

```
['train a causal language model with FP8 precision using FSDP2 and torchao Float8LinearConfig', 'configure FullyShardedDataParallelPlugin with FSDP version 2, transformer-based wrap policy, and mixed precision', 'setup TorchDynamoPlugin with inductor backend and regional compilation for faster model compilation', 'create Float8LinearConfig with FSDP float8 all-gather enabled for parameter gathering in FP8', 'run a distributed training loop with Accelerator managing backward pass, optimizer step, and metrics logging', "run distributed LLM training with ND parallelism using accelerate's ParallelismConfig and FSDP2", 'build a ParallelismConfig with data parallel, tensor parallel, and context parallel shard sizes', 'train a causal language model with mixed precision bf16 and distributed data loading', 'run training with tensor parallelism enabled and auto TP plan across device mesh', 'run the nd_parallel_trainer script to train a causal language model with torch native 2D parallelism', 'build a device mesh from ParallelismConfig for a specified accelerator type like gpu', 'create a Trainer with TrainingArguments, model, tokenizer, and dataset then run training', 'parse command-line arguments for sequence length, checkpoint frequency, model name, save directory, and device type', 'create a packed TinyStories dataset with tokenized sequences and position ids for causal language modeling', 'calculate the estimated FLOPs per token for a causal language model given its config and sequence length', 'create a collate function that batches input_ids and shift_labels into tensors for training', 'track training performance metrics including tokens per second, steps per second, and TFLOPS with warmup handling', 'setup a Hugging Face tokenizer with proper padding token fallback to eos token', 'monitor GPU memory usage including active, allocated, and reserved memory in gigabytes']
```

Usage

```
{'train_model_fsdp2_fp8': 'train a causal language model with FP8 precision using FSDP2 and torchao Float8LinearConfig', 'configure_fsdp2_plugin': 'configure FullyShardedDataParallelPlugin with FSDP version 2, transformer-based wrap policy, and mixed precision', 'setup_torch_dynamo_compilation': 'setup TorchDynamoPlugin with inductor backend and regional compilation for faster model compilation', 'create_float8_linear_config': 'create Float8LinearConfig with FSDP float8 all-gather enabled for parameter gathering in FP8', 'run_training_loop_accelerator': 'run a distributed training loop with Accelerator managing backward pass, optimizer step, and metrics logging'}
```

## File: huggingface_accelerate/examples/torch_native_parallelism/nd_parallel.py

Prompts

```
['train a causal language model with FP8 precision using FSDP2 and torchao Float8LinearConfig', 'configure FullyShardedDataParallelPlugin with FSDP version 2, transformer-based wrap policy, and mixed precision', 'setup TorchDynamoPlugin with inductor backend and regional compilation for faster model compilation', 'create Float8LinearConfig with FSDP float8 all-gather enabled for parameter gathering in FP8', 'run a distributed training loop with Accelerator managing backward pass, optimizer step, and metrics logging', "run distributed LLM training with ND parallelism using accelerate's ParallelismConfig and FSDP2", 'build a ParallelismConfig with data parallel, tensor parallel, and context parallel shard sizes', 'train a causal language model with mixed precision bf16 and distributed data loading', 'run training with tensor parallelism enabled and auto TP plan across device mesh', 'run the nd_parallel_trainer script to train a causal language model with torch native 2D parallelism', 'build a device mesh from ParallelismConfig for a specified accelerator type like gpu', 'create a Trainer with TrainingArguments, model, tokenizer, and dataset then run training', 'parse command-line arguments for sequence length, checkpoint frequency, model name, save directory, and device type', 'create a packed TinyStories dataset with tokenized sequences and position ids for causal language modeling', 'calculate the estimated FLOPs per token for a causal language model given its config and sequence length', 'create a collate function that batches input_ids and shift_labels into tensors for training', 'track training performance metrics including tokens per second, steps per second, and TFLOPS with warmup handling', 'setup a Hugging Face tokenizer with proper padding token fallback to eos token', 'monitor GPU memory usage including active, allocated, and reserved memory in gigabytes']
```

Usage

```
{'run_nd_parallel_training': "run distributed LLM training with ND parallelism using accelerate's ParallelismConfig and FSDP2", 'build_parallelism_config': 'build a ParallelismConfig with data parallel, tensor parallel, and context parallel shard sizes', 'configure_fsdp2_plugin': 'configure a FullyShardedDataParallelPlugin with transformer-based auto wrap policy for model sharding', 'train_causal_lm_model': 'train a causal language model with mixed precision bf16 and distributed data loading', 'run_with_tensor_parallel': 'run training with tensor parallelism enabled and auto TP plan across device mesh'}
```

## File: huggingface_accelerate/examples/torch_native_parallelism/nd_parallel_trainer.py

Prompts

```
['train a causal language model with FP8 precision using FSDP2 and torchao Float8LinearConfig', 'configure FullyShardedDataParallelPlugin with FSDP version 2, transformer-based wrap policy, and mixed precision', 'setup TorchDynamoPlugin with inductor backend and regional compilation for faster model compilation', 'create Float8LinearConfig with FSDP float8 all-gather enabled for parameter gathering in FP8', 'run a distributed training loop with Accelerator managing backward pass, optimizer step, and metrics logging', "run distributed LLM training with ND parallelism using accelerate's ParallelismConfig and FSDP2", 'build a ParallelismConfig with data parallel, tensor parallel, and context parallel shard sizes', 'train a causal language model with mixed precision bf16 and distributed data loading', 'run training with tensor parallelism enabled and auto TP plan across device mesh', 'run the nd_parallel_trainer script to train a causal language model with torch native 2D parallelism', 'build a device mesh from ParallelismConfig for a specified accelerator type like gpu', 'create a Trainer with TrainingArguments, model, tokenizer, and dataset then run training', 'parse command-line arguments for sequence length, checkpoint frequency, model name, save directory, and device type', 'create a packed TinyStories dataset with tokenized sequences and position ids for causal language modeling', 'calculate the estimated FLOPs per token for a causal language model given its config and sequence length', 'create a collate function that batches input_ids and shift_labels into tensors for training', 'track training performance metrics including tokens per second, steps per second, and TFLOPS with warmup handling', 'setup a Hugging Face tokenizer with proper padding token fallback to eos token', 'monitor GPU memory usage including active, allocated, and reserved memory in gigabytes']
```

Usage

```
{'run_nd_parallel_trainer': 'run the nd_parallel_trainer script to train a causal language model with torch native 2D parallelism', 'build_parallelism_config': 'build a ParallelismConfig to configure tensor parallelism and device mesh for multi-device training', 'build_device_mesh': 'build a device mesh from ParallelismConfig for a specified accelerator type like gpu', 'create_trainer_train': 'create a Trainer with TrainingArguments, model, tokenizer, and dataset then run training', 'parse_args_cli': 'parse command-line arguments for sequence length, checkpoint frequency, model name, save directory, and device type'}
```

## File: huggingface_accelerate/examples/torch_native_parallelism/utils.py

Prompts

```
['train a causal language model with FP8 precision using FSDP2 and torchao Float8LinearConfig', 'configure FullyShardedDataParallelPlugin with FSDP version 2, transformer-based wrap policy, and mixed precision', 'setup TorchDynamoPlugin with inductor backend and regional compilation for faster model compilation', 'create Float8LinearConfig with FSDP float8 all-gather enabled for parameter gathering in FP8', 'run a distributed training loop with Accelerator managing backward pass, optimizer step, and metrics logging', "run distributed LLM training with ND parallelism using accelerate's ParallelismConfig and FSDP2", 'build a ParallelismConfig with data parallel, tensor parallel, and context parallel shard sizes', 'train a causal language model with mixed precision bf16 and distributed data loading', 'run training with tensor parallelism enabled and auto TP plan across device mesh', 'run the nd_parallel_trainer script to train a causal language model with torch native 2D parallelism', 'build a device mesh from ParallelismConfig for a specified accelerator type like gpu', 'create a Trainer with TrainingArguments, model, tokenizer, and dataset then run training', 'parse command-line arguments for sequence length, checkpoint frequency, model name, save directory, and device type', 'create a packed TinyStories dataset with tokenized sequences and position ids for causal language modeling', 'calculate the estimated FLOPs per token for a causal language model given its config and sequence length', 'create a collate function that batches input_ids and shift_labels into tensors for training', 'track training performance metrics including tokens per second, steps per second, and TFLOPS with warmup handling', 'setup a Hugging Face tokenizer with proper padding token fallback to eos token', 'monitor GPU memory usage including active, allocated, and reserved memory in gigabytes']
```

Usage

```
{'create_dataset_tiny_stories': 'create a packed TinyStories dataset with tokenized sequences and position ids for causal language modeling', 'calculate_model_flops_per_token': 'calculate the estimated FLOPs per token for a causal language model given its config and sequence length', 'create_collate_fn_batching': 'create a collate function that batches input_ids and shift_labels into tensors for training', 'track_training_performance': 'track training performance metrics including tokens per second, steps per second, and TFLOPS with warmup handling', 'setup_tokenizer_padding': 'setup a Hugging Face tokenizer with proper padding token fallback to eos token', 'monitor_gpu_memory_usage': 'monitor GPU memory usage including active, allocated, and reserved memory in gigabytes'}
```

