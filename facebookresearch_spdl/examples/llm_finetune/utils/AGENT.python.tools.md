# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/examples/llm_finetune/utils/dataloader.py

Prompts

```
['build a reusable PyTorch DataLoader for distributed LLM fine-tuning with automatic device transfer and epoch management', 'create a map-style dataset that tokenizes Alpaca-style instruction samples on the fly using a HuggingFace tokenizer', 'create a DataLoader wrapper that automatically transfers batches to a CUDA device and manages DistributedSampler epochs', 'review the InstructDataset getitem method that tokenizes individual samples into input IDs and attention masks', 'test the DeviceDataLoader iterator that yields device-transferred batches with automatic epoch incrementing', 'build a reusable SPDL data loader with nested pipeline architecture for LLM fine-tuning that separates CPU data loading from GPU transfer', 'create a picklable callable that looks up a training sample by index from a list of sample dictionaries', 'create a thread-local tokenizer that deepcopies from a source tokenizer for safe concurrent tokenization across threads', 'create a picklable callable that tokenizes a sample using a thread-local tokenizer with configurable max sequence length', 'review the nested pipeline architecture that isolates CPU-bound data loading in a subprocess from the main training process', 'load and concatenate data from one or more JSONL files into a list of dictionaries', 'format an Alpaca-style sample with instruction, input, and output into a single prompt string', 'format and tokenize a single Alpaca-style sample using a HuggingFace tokenizer with max sequence length', 'stack a list of tokenized samples into a batched dictionary of PyTorch tensors', 'resolve a model path string returning the local filesystem path as-is in OSS mode']
```

Usage

```
{'build_pytorch_dataloader': 'build a reusable PyTorch DataLoader for distributed LLM fine-tuning with automatic device transfer and epoch management', 'create_InstructDataset': 'create a map-style dataset that tokenizes Alpaca-style instruction samples on the fly using a HuggingFace tokenizer', 'create_DeviceDataLoader': 'create a DataLoader wrapper that automatically transfers batches to a CUDA device and manages DistributedSampler epochs', 'review_InstructDataset_getitem': 'review the InstructDataset getitem method that tokenizes individual samples into input IDs and attention masks', 'test_DeviceDataLoader_iter': 'test the DeviceDataLoader iterator that yields device-transferred batches with automatic epoch incrementing'}
```

## File: facebookresearch_spdl/examples/llm_finetune/utils/pipeline.py

Prompts

```
['build a reusable PyTorch DataLoader for distributed LLM fine-tuning with automatic device transfer and epoch management', 'create a map-style dataset that tokenizes Alpaca-style instruction samples on the fly using a HuggingFace tokenizer', 'create a DataLoader wrapper that automatically transfers batches to a CUDA device and manages DistributedSampler epochs', 'review the InstructDataset getitem method that tokenizes individual samples into input IDs and attention masks', 'test the DeviceDataLoader iterator that yields device-transferred batches with automatic epoch incrementing', 'build a reusable SPDL data loader with nested pipeline architecture for LLM fine-tuning that separates CPU data loading from GPU transfer', 'create a picklable callable that looks up a training sample by index from a list of sample dictionaries', 'create a thread-local tokenizer that deepcopies from a source tokenizer for safe concurrent tokenization across threads', 'create a picklable callable that tokenizes a sample using a thread-local tokenizer with configurable max sequence length', 'review the nested pipeline architecture that isolates CPU-bound data loading in a subprocess from the main training process', 'load and concatenate data from one or more JSONL files into a list of dictionaries', 'format an Alpaca-style sample with instruction, input, and output into a single prompt string', 'format and tokenize a single Alpaca-style sample using a HuggingFace tokenizer with max sequence length', 'stack a list of tokenized samples into a batched dictionary of PyTorch tensors', 'resolve a model path string returning the local filesystem path as-is in OSS mode']
```

Usage

```
{'build_spdl_dataloader': 'build a reusable SPDL data loader with nested pipeline architecture for LLM fine-tuning that separates CPU data loading from GPU transfer', 'create_Lookup_callable': 'create a picklable callable that looks up a training sample by index from a list of sample dictionaries', 'create_ThreadLocalTokenizer': 'create a thread-local tokenizer that deepcopies from a source tokenizer for safe concurrent tokenization across threads', 'create_Tokenize_callable': 'create a picklable callable that tokenizes a sample using a thread-local tokenizer with configurable max sequence length', 'review_pipeline_architecture': 'review the nested pipeline architecture that isolates CPU-bound data loading in a subprocess from the main training process'}
```

## File: facebookresearch_spdl/examples/llm_finetune/utils/utils.py

Prompts

```
['build a reusable PyTorch DataLoader for distributed LLM fine-tuning with automatic device transfer and epoch management', 'create a map-style dataset that tokenizes Alpaca-style instruction samples on the fly using a HuggingFace tokenizer', 'create a DataLoader wrapper that automatically transfers batches to a CUDA device and manages DistributedSampler epochs', 'review the InstructDataset getitem method that tokenizes individual samples into input IDs and attention masks', 'test the DeviceDataLoader iterator that yields device-transferred batches with automatic epoch incrementing', 'build a reusable SPDL data loader with nested pipeline architecture for LLM fine-tuning that separates CPU data loading from GPU transfer', 'create a picklable callable that looks up a training sample by index from a list of sample dictionaries', 'create a thread-local tokenizer that deepcopies from a source tokenizer for safe concurrent tokenization across threads', 'create a picklable callable that tokenizes a sample using a thread-local tokenizer with configurable max sequence length', 'review the nested pipeline architecture that isolates CPU-bound data loading in a subprocess from the main training process', 'load and concatenate data from one or more JSONL files into a list of dictionaries', 'format an Alpaca-style sample with instruction, input, and output into a single prompt string', 'format and tokenize a single Alpaca-style sample using a HuggingFace tokenizer with max sequence length', 'stack a list of tokenized samples into a batched dictionary of PyTorch tensors', 'resolve a model path string returning the local filesystem path as-is in OSS mode']
```

Usage

```
{'load_data_jsonl': 'load and concatenate data from one or more JSONL files into a list of dictionaries', 'format_prompt_alpaca': 'format an Alpaca-style sample with instruction, input, and output into a single prompt string', 'tokenize_sample': 'format and tokenize a single Alpaca-style sample using a HuggingFace tokenizer with max sequence length', 'collate_batch': 'stack a list of tokenized samples into a batched dictionary of PyTorch tensors', 'resolve_model_path': 'resolve a model path string returning the local filesystem path as-is in OSS mode'}
```

