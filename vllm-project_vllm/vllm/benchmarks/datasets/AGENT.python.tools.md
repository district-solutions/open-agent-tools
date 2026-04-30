# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/benchmarks/datasets/create_txt_slices_dataset.py

Prompts

```
['create a JSONL benchmark dataset from a plain-text file by randomly slicing tokenized text into prompts', 'run the CLI to convert a local text file into a JSONL dataset for vLLM CustomDataset benchmarking', 'run the CLI to convert a remote text URL into a JSONL dataset for vLLM CustomDataset benchmarking', 'test the load_text function to read text from a local file or remote URL', 'summarize the main CLI entry point with argparse arguments for text-to-JSONL conversion', 'generate synthetic text prompts for vLLM serving benchmarks with configurable input and output token lengths', 'sample conversation pairs from a ShareGPT JSON file and generate benchmark requests with prompt and output token lengths', 'create benchmark requests with synthetic images and videos for testing multimodal LLM inference performance', 'load and sample from HuggingFace datasets like VisionArena, InstructCoder, or MT-Bench for vLLM benchmarking', 'parse a CLI range ratio argument supporting both a plain float and a JSON dict with independent input and output ratios', 'test get_sampling_params to sample per-request input/output token lengths and vocab offsets', 'test _resolve_range_ratios to convert a single float or dict into input and output range ratios', 'test get_sampling_params with dict range_ratio for independent input and output length control', 'test get_sampling_params to subtract tokenizer special tokens from input length before sampling', 'test get_sampling_params to validate range ratios are in [0, 1) and bounds are valid']
```

Usage

```
{'create_txt_slices_jsonl': 'create a JSONL benchmark dataset from a plain-text file by randomly slicing tokenized text into prompts', 'run_cli_convert_text': 'run the CLI to convert a local text file into a JSONL dataset for vLLM CustomDataset benchmarking', 'run_cli_convert_url': 'run the CLI to convert a remote text URL into a JSONL dataset for vLLM CustomDataset benchmarking', 'test_load_text': 'test the load_text function to read text from a local file or remote URL', 'summarize_main': 'summarize the main CLI entry point with argparse arguments for text-to-JSONL conversion'}
```

## File: vllm-project_vllm/vllm/benchmarks/datasets/datasets.py

Prompts

```
['create a JSONL benchmark dataset from a plain-text file by randomly slicing tokenized text into prompts', 'run the CLI to convert a local text file into a JSONL dataset for vLLM CustomDataset benchmarking', 'run the CLI to convert a remote text URL into a JSONL dataset for vLLM CustomDataset benchmarking', 'test the load_text function to read text from a local file or remote URL', 'summarize the main CLI entry point with argparse arguments for text-to-JSONL conversion', 'generate synthetic text prompts for vLLM serving benchmarks with configurable input and output token lengths', 'sample conversation pairs from a ShareGPT JSON file and generate benchmark requests with prompt and output token lengths', 'create benchmark requests with synthetic images and videos for testing multimodal LLM inference performance', 'load and sample from HuggingFace datasets like VisionArena, InstructCoder, or MT-Bench for vLLM benchmarking', 'parse a CLI range ratio argument supporting both a plain float and a JSON dict with independent input and output ratios', 'test get_sampling_params to sample per-request input/output token lengths and vocab offsets', 'test _resolve_range_ratios to convert a single float or dict into input and output range ratios', 'test get_sampling_params with dict range_ratio for independent input and output length control', 'test get_sampling_params to subtract tokenizer special tokens from input length before sampling', 'test get_sampling_params to validate range ratios are in [0, 1) and bounds are valid']
```

Usage

```
{'generate_random_benchmark_prompts': 'generate synthetic text prompts for vLLM serving benchmarks with configurable input and output token lengths', 'sample_sharegpt_dataset': 'sample conversation pairs from a ShareGPT JSON file and generate benchmark requests with prompt and output token lengths', 'create_multimodal_benchmark_requests': 'create benchmark requests with synthetic images and videos for testing multimodal LLM inference performance', 'load_huggingface_dataset': 'load and sample from HuggingFace datasets like VisionArena, InstructCoder, or MT-Bench for vLLM benchmarking', 'parse_range_ratio_cli': 'parse a CLI range ratio argument supporting both a plain float and a JSON dict with independent input and output ratios'}
```

## File: vllm-project_vllm/vllm/benchmarks/datasets/utils.py

Prompts

```
['create a JSONL benchmark dataset from a plain-text file by randomly slicing tokenized text into prompts', 'run the CLI to convert a local text file into a JSONL dataset for vLLM CustomDataset benchmarking', 'run the CLI to convert a remote text URL into a JSONL dataset for vLLM CustomDataset benchmarking', 'test the load_text function to read text from a local file or remote URL', 'summarize the main CLI entry point with argparse arguments for text-to-JSONL conversion', 'generate synthetic text prompts for vLLM serving benchmarks with configurable input and output token lengths', 'sample conversation pairs from a ShareGPT JSON file and generate benchmark requests with prompt and output token lengths', 'create benchmark requests with synthetic images and videos for testing multimodal LLM inference performance', 'load and sample from HuggingFace datasets like VisionArena, InstructCoder, or MT-Bench for vLLM benchmarking', 'parse a CLI range ratio argument supporting both a plain float and a JSON dict with independent input and output ratios', 'test get_sampling_params to sample per-request input/output token lengths and vocab offsets', 'test _resolve_range_ratios to convert a single float or dict into input and output range ratios', 'test get_sampling_params with dict range_ratio for independent input and output length control', 'test get_sampling_params to subtract tokenizer special tokens from input length before sampling', 'test get_sampling_params to validate range ratios are in [0, 1) and bounds are valid']
```

Usage

```
{'test_get_sampling_params': 'test get_sampling_params to sample per-request input/output token lengths and vocab offsets', 'test_resolve_range_ratios': 'test _resolve_range_ratios to convert a single float or dict into input and output range ratios', 'test_get_sampling_params_dict_ratio': 'test get_sampling_params with dict range_ratio for independent input and output length control', 'test_get_sampling_params_special_tokens': 'test get_sampling_params to subtract tokenizer special tokens from input length before sampling', 'test_get_sampling_params_validation': 'test get_sampling_params to validate range ratios are in [0, 1) and bounds are valid'}
```

