# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/benchmarks/datasets/mnist.py

Prompts

```
['run setup_cached_mnist to download and cache the MNIST dataset to the system temp directory', 'test setup_cached_mnist to verify it downloads MNIST and retries up to 5 times on failure', 'review setup_cached_mnist to understand its retry logic and corrupted data cleanup behavior', 'summarize setup_cached_mnist which downloads MNIST with mirror fallback and automatic corruption recovery', 'refactor setup_cached_mnist to accept a custom root directory instead of using the system temp directory', 'download and tokenize the wikitext-2 dataset into train, validation, and test tensors', 'create distributed PyTorch dataloaders for train, validation, and test datasets with batching', 'return real wikitext-2 dataloaders with vocabulary size for language model benchmarking', 'generate synthetic language model datasets with random token IDs for benchmarking', 'return synthetic dataloaders for fast language model benchmarking without real data']
```

Usage

```
{'run_setup_cached_mnist': 'run setup_cached_mnist to download and cache the MNIST dataset to the system temp directory', 'test_setup_cached_mnist': 'test setup_cached_mnist to verify it downloads MNIST and retries up to 5 times on failure', 'review_setup_cached_mnist': 'review setup_cached_mnist to understand its retry logic and corrupted data cleanup behavior', 'summarize_setup_cached_mnist': 'summarize setup_cached_mnist which downloads MNIST with mirror fallback and automatic corruption recovery', 'refactor_setup_cached_mnist': 'refactor setup_cached_mnist to accept a custom root directory instead of using the system temp directory'}
```

## File: facebookresearch_fairscale/benchmarks/datasets/wikitext2_data.py

Prompts

```
['run setup_cached_mnist to download and cache the MNIST dataset to the system temp directory', 'test setup_cached_mnist to verify it downloads MNIST and retries up to 5 times on failure', 'review setup_cached_mnist to understand its retry logic and corrupted data cleanup behavior', 'summarize setup_cached_mnist which downloads MNIST with mirror fallback and automatic corruption recovery', 'refactor setup_cached_mnist to accept a custom root directory instead of using the system temp directory', 'download and tokenize the wikitext-2 dataset into train, validation, and test tensors', 'create distributed PyTorch dataloaders for train, validation, and test datasets with batching', 'return real wikitext-2 dataloaders with vocabulary size for language model benchmarking', 'generate synthetic language model datasets with random token IDs for benchmarking', 'return synthetic dataloaders for fast language model benchmarking without real data']
```

Usage

```
{'get_real_datasets': 'download and tokenize the wikitext-2 dataset into train, validation, and test tensors', 'get_dataloaders': 'create distributed PyTorch dataloaders for train, validation, and test datasets with batching', 'get_real_dataloaders': 'return real wikitext-2 dataloaders with vocabulary size for language model benchmarking', 'get_synthetic_datasets': 'generate synthetic language model datasets with random token IDs for benchmarking', 'get_synthetic_dataloaders': 'return synthetic dataloaders for fast language model benchmarking without real data'}
```

