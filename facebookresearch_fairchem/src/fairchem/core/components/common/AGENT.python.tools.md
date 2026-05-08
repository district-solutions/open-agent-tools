# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/components/common/dataloader_builder.py

Prompts

```
['build a pytorch dataloader from a dataset, batch sampler function, collate function, and num workers', 'create a dataloader using a custom batch sampler function for distributed training across replicas', 'test the get_dataloader function with a mock dataset and batch sampler function', 'review the get_dataloader function and its distributed training rank and replica detection logic', 'refactor the get_dataloader function to support additional dataloader configuration options', 'run a FLOPs profiler on a PyTorch model with input data to measure computational cost', 'run a FLOPs profiler on a PyTorch model and print a detailed per-layer profile', "build a python module to profile a PyTorch model's FLOPs using the flops-profiler library", 'test the get_flops_profile function by profiling a simple PyTorch model with sample input data', 'refactor the get_flops_profile function to support batched input data for FLOPs profiling', 'create a python function that reads a JSON file into a pandas DataFrame with optional index and sorting', 'create a python function that loads a JSON file into a DataFrame and sets a specific column as the index', 'create a python function that loads a JSON file into a sorted pandas DataFrame by its index', 'create a python function that reads a compressed JSON file like json.gz into a pandas DataFrame', 'review the python function load_json_to_df that reads JSON files into pandas DataFrames with index and sort options']
```

Usage

```
{'build_dataloader': 'build a pytorch dataloader from a dataset, batch sampler function, collate function, and num workers', 'create_dataloader_with_sampler': 'create a dataloader using a custom batch sampler function for distributed training across replicas', 'test_get_dataloader': 'test the get_dataloader function with a mock dataset and batch sampler function', 'review_get_dataloader': 'review the get_dataloader function and its distributed training rank and replica detection logic', 'refactor_get_dataloader': 'refactor the get_dataloader function to support additional dataloader configuration options'}
```

## File: facebookresearch_fairchem/src/fairchem/core/components/common/flops_profile.py

Prompts

```
['build a pytorch dataloader from a dataset, batch sampler function, collate function, and num workers', 'create a dataloader using a custom batch sampler function for distributed training across replicas', 'test the get_dataloader function with a mock dataset and batch sampler function', 'review the get_dataloader function and its distributed training rank and replica detection logic', 'refactor the get_dataloader function to support additional dataloader configuration options', 'run a FLOPs profiler on a PyTorch model with input data to measure computational cost', 'run a FLOPs profiler on a PyTorch model and print a detailed per-layer profile', "build a python module to profile a PyTorch model's FLOPs using the flops-profiler library", 'test the get_flops_profile function by profiling a simple PyTorch model with sample input data', 'refactor the get_flops_profile function to support batched input data for FLOPs profiling', 'create a python function that reads a JSON file into a pandas DataFrame with optional index and sorting', 'create a python function that loads a JSON file into a DataFrame and sets a specific column as the index', 'create a python function that loads a JSON file into a sorted pandas DataFrame by its index', 'create a python function that reads a compressed JSON file like json.gz into a pandas DataFrame', 'review the python function load_json_to_df that reads JSON files into pandas DataFrames with index and sort options']
```

Usage

```
{'get_flops_profile': 'run a FLOPs profiler on a PyTorch model with input data to measure computational cost', 'get_flops_profile_verbose': 'run a FLOPs profiler on a PyTorch model and print a detailed per-layer profile', 'build_flops_profiler_module': "build a python module to profile a PyTorch model's FLOPs using the flops-profiler library", 'test_get_flops_profile': 'test the get_flops_profile function by profiling a simple PyTorch model with sample input data', 'refactor_get_flops_profile': 'refactor the get_flops_profile function to support batched input data for FLOPs profiling'}
```

## File: facebookresearch_fairchem/src/fairchem/core/components/common/load_dataframe.py

Prompts

```
['build a pytorch dataloader from a dataset, batch sampler function, collate function, and num workers', 'create a dataloader using a custom batch sampler function for distributed training across replicas', 'test the get_dataloader function with a mock dataset and batch sampler function', 'review the get_dataloader function and its distributed training rank and replica detection logic', 'refactor the get_dataloader function to support additional dataloader configuration options', 'run a FLOPs profiler on a PyTorch model with input data to measure computational cost', 'run a FLOPs profiler on a PyTorch model and print a detailed per-layer profile', "build a python module to profile a PyTorch model's FLOPs using the flops-profiler library", 'test the get_flops_profile function by profiling a simple PyTorch model with sample input data', 'refactor the get_flops_profile function to support batched input data for FLOPs profiling', 'create a python function that reads a JSON file into a pandas DataFrame with optional index and sorting', 'create a python function that loads a JSON file into a DataFrame and sets a specific column as the index', 'create a python function that loads a JSON file into a sorted pandas DataFrame by its index', 'create a python function that reads a compressed JSON file like json.gz into a pandas DataFrame', 'review the python function load_json_to_df that reads JSON files into pandas DataFrames with index and sort options']
```

Usage

```
{'load_json_to_dataframe': 'create a python function that reads a JSON file into a pandas DataFrame with optional index and sorting', 'load_json_to_df_with_index': 'create a python function that loads a JSON file into a DataFrame and sets a specific column as the index', 'load_json_to_df_sorted': 'create a python function that loads a JSON file into a sorted pandas DataFrame by its index', 'load_compressed_json_to_df': 'create a python function that reads a compressed JSON file like json.gz into a pandas DataFrame', 'review_load_json_to_df': 'review the python function load_json_to_df that reads JSON files into pandas DataFrames with index and sort options'}
```

