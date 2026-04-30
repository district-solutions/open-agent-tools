# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/benchmarks/fsdp2/main.py

Prompts

```
['run the train function to perform a training loop with model, optimizer, dataloader, and accelerator', 'run the evaluate function to train a model and report loss and peak memory usage', 'run the main FSDP2 benchmark comparing optimizer placement strategies with Accelerate', 'review the train function that iterates over batches calling zero_grad, forward, backward, and step', 'review the evaluate function that initializes components via init_fn, trains, and prints memory stats', 'create a MemoryTracker instance to monitor GPU and CPU memory usage for a PyTorch device', 'start the MemoryTracker to begin collecting allocated, reserved, and virtual memory data in a background thread', 'stop the MemoryTracker and save memory usage data as JSON and optional snapshot pickle files', 'get the peak allocated memory value in megabytes from the MemoryTracker after stopping tracking', 'get the peak reserved memory value in megabytes from the MemoryTracker after stopping tracking', 'prepare a PyTorch model with FSDP2 fully_shard and mixed precision for benchmarking', 'prepare an Accelerate model with FSDP2 plugin for distributed training benchmarking', 'get a dictionary mapping model parameter names to their data pointers or tensors', 'replace optimizer parameters with empty tensors before applying fully_shard to the model', 'swap optimizer parameters back to sharded ones after fully_shard is applied', 'run the script to generate allocated and reserved memory comparison plots from JSON data', 'run filter_data to remove low-memory data points below a threshold in the first partition', 'run compare_memory_usage to generate matplotlib figures comparing allocated and reserved memory across datasets', 'review parse_args to understand the CLI arguments for directory, memory threshold, and filter partition', 'refactor compare_memory_usage to support a dynamic number of datasets beyond the hardcoded four colors']
```

Usage

```
{'run_train_function': 'run the train function to perform a training loop with model, optimizer, dataloader, and accelerator', 'run_evaluate_function': 'run the evaluate function to train a model and report loss and peak memory usage', 'run_main_benchmark': 'run the main FSDP2 benchmark comparing optimizer placement strategies with Accelerate', 'review_train_function': 'review the train function that iterates over batches calling zero_grad, forward, backward, and step', 'review_evaluate_function': 'review the evaluate function that initializes components via init_fn, trains, and prints memory stats'}
```

## File: huggingface_accelerate/benchmarks/fsdp2/measure_utils.py

Prompts

```
['run the train function to perform a training loop with model, optimizer, dataloader, and accelerator', 'run the evaluate function to train a model and report loss and peak memory usage', 'run the main FSDP2 benchmark comparing optimizer placement strategies with Accelerate', 'review the train function that iterates over batches calling zero_grad, forward, backward, and step', 'review the evaluate function that initializes components via init_fn, trains, and prints memory stats', 'create a MemoryTracker instance to monitor GPU and CPU memory usage for a PyTorch device', 'start the MemoryTracker to begin collecting allocated, reserved, and virtual memory data in a background thread', 'stop the MemoryTracker and save memory usage data as JSON and optional snapshot pickle files', 'get the peak allocated memory value in megabytes from the MemoryTracker after stopping tracking', 'get the peak reserved memory value in megabytes from the MemoryTracker after stopping tracking', 'prepare a PyTorch model with FSDP2 fully_shard and mixed precision for benchmarking', 'prepare an Accelerate model with FSDP2 plugin for distributed training benchmarking', 'get a dictionary mapping model parameter names to their data pointers or tensors', 'replace optimizer parameters with empty tensors before applying fully_shard to the model', 'swap optimizer parameters back to sharded ones after fully_shard is applied', 'run the script to generate allocated and reserved memory comparison plots from JSON data', 'run filter_data to remove low-memory data points below a threshold in the first partition', 'run compare_memory_usage to generate matplotlib figures comparing allocated and reserved memory across datasets', 'review parse_args to understand the CLI arguments for directory, memory threshold, and filter partition', 'refactor compare_memory_usage to support a dynamic number of datasets beyond the hardcoded four colors']
```

Usage

```
{'create_memory_tracker': 'create a MemoryTracker instance to monitor GPU and CPU memory usage for a PyTorch device', 'start_memory_tracking': 'start the MemoryTracker to begin collecting allocated, reserved, and virtual memory data in a background thread', 'stop_memory_tracking': 'stop the MemoryTracker and save memory usage data as JSON and optional snapshot pickle files', 'get_peak_allocated_memory': 'get the peak allocated memory value in megabytes from the MemoryTracker after stopping tracking', 'get_peak_reserved_memory': 'get the peak reserved memory value in megabytes from the MemoryTracker after stopping tracking'}
```

## File: huggingface_accelerate/benchmarks/fsdp2/utils.py

Prompts

```
['run the train function to perform a training loop with model, optimizer, dataloader, and accelerator', 'run the evaluate function to train a model and report loss and peak memory usage', 'run the main FSDP2 benchmark comparing optimizer placement strategies with Accelerate', 'review the train function that iterates over batches calling zero_grad, forward, backward, and step', 'review the evaluate function that initializes components via init_fn, trains, and prints memory stats', 'create a MemoryTracker instance to monitor GPU and CPU memory usage for a PyTorch device', 'start the MemoryTracker to begin collecting allocated, reserved, and virtual memory data in a background thread', 'stop the MemoryTracker and save memory usage data as JSON and optional snapshot pickle files', 'get the peak allocated memory value in megabytes from the MemoryTracker after stopping tracking', 'get the peak reserved memory value in megabytes from the MemoryTracker after stopping tracking', 'prepare a PyTorch model with FSDP2 fully_shard and mixed precision for benchmarking', 'prepare an Accelerate model with FSDP2 plugin for distributed training benchmarking', 'get a dictionary mapping model parameter names to their data pointers or tensors', 'replace optimizer parameters with empty tensors before applying fully_shard to the model', 'swap optimizer parameters back to sharded ones after fully_shard is applied', 'run the script to generate allocated and reserved memory comparison plots from JSON data', 'run filter_data to remove low-memory data points below a threshold in the first partition', 'run compare_memory_usage to generate matplotlib figures comparing allocated and reserved memory across datasets', 'review parse_args to understand the CLI arguments for directory, memory threshold, and filter partition', 'refactor compare_memory_usage to support a dynamic number of datasets beyond the hardcoded four colors']
```

Usage

```
{'prepare_torch_fsdp2': 'prepare a PyTorch model with FSDP2 fully_shard and mixed precision for benchmarking', 'prepare_accelerate_fsdp2': 'prepare an Accelerate model with FSDP2 plugin for distributed training benchmarking', 'get_named_parameters': 'get a dictionary mapping model parameter names to their data pointers or tensors', 'replace_optimizer_params': 'replace optimizer parameters with empty tensors before applying fully_shard to the model', 'swap_back_optimizer_params': 'swap optimizer parameters back to sharded ones after fully_shard is applied'}
```

## File: huggingface_accelerate/benchmarks/fsdp2/visualize.py

Prompts

```
['run the train function to perform a training loop with model, optimizer, dataloader, and accelerator', 'run the evaluate function to train a model and report loss and peak memory usage', 'run the main FSDP2 benchmark comparing optimizer placement strategies with Accelerate', 'review the train function that iterates over batches calling zero_grad, forward, backward, and step', 'review the evaluate function that initializes components via init_fn, trains, and prints memory stats', 'create a MemoryTracker instance to monitor GPU and CPU memory usage for a PyTorch device', 'start the MemoryTracker to begin collecting allocated, reserved, and virtual memory data in a background thread', 'stop the MemoryTracker and save memory usage data as JSON and optional snapshot pickle files', 'get the peak allocated memory value in megabytes from the MemoryTracker after stopping tracking', 'get the peak reserved memory value in megabytes from the MemoryTracker after stopping tracking', 'prepare a PyTorch model with FSDP2 fully_shard and mixed precision for benchmarking', 'prepare an Accelerate model with FSDP2 plugin for distributed training benchmarking', 'get a dictionary mapping model parameter names to their data pointers or tensors', 'replace optimizer parameters with empty tensors before applying fully_shard to the model', 'swap optimizer parameters back to sharded ones after fully_shard is applied', 'run the script to generate allocated and reserved memory comparison plots from JSON data', 'run filter_data to remove low-memory data points below a threshold in the first partition', 'run compare_memory_usage to generate matplotlib figures comparing allocated and reserved memory across datasets', 'review parse_args to understand the CLI arguments for directory, memory threshold, and filter partition', 'refactor compare_memory_usage to support a dynamic number of datasets beyond the hardcoded four colors']
```

Usage

```
{'run_visualize_memory_comparison': 'run the script to generate allocated and reserved memory comparison plots from JSON data', 'run_filter_data': 'run filter_data to remove low-memory data points below a threshold in the first partition', 'run_compare_memory_usage': 'run compare_memory_usage to generate matplotlib figures comparing allocated and reserved memory across datasets', 'review_parse_args': 'review parse_args to understand the CLI arguments for directory, memory threshold, and filter partition', 'refactor_compare_memory_usage': 'refactor compare_memory_usage to support a dynamic number of datasets beyond the hardcoded four colors'}
```

