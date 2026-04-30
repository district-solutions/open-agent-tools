# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/benchmarks/big_model_inference/big_model_inference.py

Prompts

```
['run a benchmark that loads a large model and times text generation across multiple prompts', 'run the big model inference benchmark with disk offloading enabled for memory constrained setups', 'run a generation benchmark on a causal language model like gpt-j-6b or opt-30b', 'run a generation benchmark on a seq2seq model like T0pp using device map auto', 'review the parse_args function that resolves default model configs from the DEFAULT_MODELS dictionary', 'create a function that starts measuring CPU and GPU memory and elapsed time for benchmarking', 'create a function that ends measurement and returns delta CPU GPU memory and time in MiB', 'create a function that prints benchmark results including time GPU peak memory and CPU RAM', 'build a PeakCPUMemory class that tracks peak CPU RSS memory using a background daemon thread', 'review the PeakCPUMemory class start and stop methods for threaded peak CPU memory monitoring']
```

Usage

```
{'run_big_model_inference_benchmark': 'run a benchmark that loads a large model and times text generation across multiple prompts', 'run_model_loading_with_disk_offload': 'run the big model inference benchmark with disk offloading enabled for memory constrained setups', 'run_causal_model_generation_benchmark': 'run a generation benchmark on a causal language model like gpt-j-6b or opt-30b', 'run_seq2seq_model_generation_benchmark': 'run a generation benchmark on a seq2seq model like T0pp using device map auto', 'review_parse_args_default_models': 'review the parse_args function that resolves default model configs from the DEFAULT_MODELS dictionary'}
```

## File: huggingface_accelerate/benchmarks/big_model_inference/measures_util.py

Prompts

```
['run a benchmark that loads a large model and times text generation across multiple prompts', 'run the big model inference benchmark with disk offloading enabled for memory constrained setups', 'run a generation benchmark on a causal language model like gpt-j-6b or opt-30b', 'run a generation benchmark on a seq2seq model like T0pp using device map auto', 'review the parse_args function that resolves default model configs from the DEFAULT_MODELS dictionary', 'create a function that starts measuring CPU and GPU memory and elapsed time for benchmarking', 'create a function that ends measurement and returns delta CPU GPU memory and time in MiB', 'create a function that prints benchmark results including time GPU peak memory and CPU RAM', 'build a PeakCPUMemory class that tracks peak CPU RSS memory using a background daemon thread', 'review the PeakCPUMemory class start and stop methods for threaded peak CPU memory monitoring']
```

Usage

```
{'start_measure': 'create a function that starts measuring CPU and GPU memory and elapsed time for benchmarking', 'end_measure': 'create a function that ends measurement and returns delta CPU GPU memory and time in MiB', 'log_measures': 'create a function that prints benchmark results including time GPU peak memory and CPU RAM', 'build_PeakCPUMemory': 'build a PeakCPUMemory class that tracks peak CPU RSS memory using a background daemon thread', 'review_PeakCPUMemory': 'review the PeakCPUMemory class start and stop methods for threaded peak CPU memory monitoring'}
```

