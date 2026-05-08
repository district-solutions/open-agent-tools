# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/platforms/base.py

Prompts

```
['run a training function using the Platform run_job method to set the active platform context', 'save a PyTorch model to disk using the Platform save_model static method', 'load a PyTorch model from disk using the Platform load_model static method', 'check the available GPU or CPU device string using the Platform device_str property', 'check if multi-GPU parallel training is available using the Platform is_parallel property', 'run a training job function using the local Platform with automatic device and context management', 'get the local root data directory path from the Platform class returning open_lth_data under home', 'get the local dataset root directory path from the Platform class returning open_lth_datasets under home', 'save or load a PyTorch model to or from a local file path using Platform static methods', 'check the available torch device string and whether multi-GPU distributed training is active on the platform', 'get the registered platform class by name from the platforms registry', 'review the registered_platforms dictionary to see which platform implementations are available', 'review the get function that looks up a platform class by its string key', 'refactor the get function to return a default platform when the name is not found', 'summarize the platforms registry module that maps platform names to their class implementations']
```

Usage

```
{'run_job_with_platform': 'run a training function using the Platform run_job method to set the active platform context', 'save_model_with_platform': 'save a PyTorch model to disk using the Platform save_model static method', 'load_model_with_platform': 'load a PyTorch model from disk using the Platform load_model static method', 'check_device_with_platform': 'check the available GPU or CPU device string using the Platform device_str property', 'check_parallel_with_platform': 'check if multi-GPU parallel training is available using the Platform is_parallel property'}
```

## File: facebookresearch_openlth/platforms/local.py

Prompts

```
['run a training function using the Platform run_job method to set the active platform context', 'save a PyTorch model to disk using the Platform save_model static method', 'load a PyTorch model from disk using the Platform load_model static method', 'check the available GPU or CPU device string using the Platform device_str property', 'check if multi-GPU parallel training is available using the Platform is_parallel property', 'run a training job function using the local Platform with automatic device and context management', 'get the local root data directory path from the Platform class returning open_lth_data under home', 'get the local dataset root directory path from the Platform class returning open_lth_datasets under home', 'save or load a PyTorch model to or from a local file path using Platform static methods', 'check the available torch device string and whether multi-GPU distributed training is active on the platform', 'get the registered platform class by name from the platforms registry', 'review the registered_platforms dictionary to see which platform implementations are available', 'review the get function that looks up a platform class by its string key', 'refactor the get function to return a default platform when the name is not found', 'summarize the platforms registry module that maps platform names to their class implementations']
```

Usage

```
{'run_job_local_platform': 'run a training job function using the local Platform with automatic device and context management', 'get_local_root_path': 'get the local root data directory path from the Platform class returning open_lth_data under home', 'get_local_dataset_root': 'get the local dataset root directory path from the Platform class returning open_lth_datasets under home', 'save_load_model_local': 'save or load a PyTorch model to or from a local file path using Platform static methods', 'check_device_and_distributed': 'check the available torch device string and whether multi-GPU distributed training is active on the platform'}
```

## File: facebookresearch_openlth/platforms/registry.py

Prompts

```
['run a training function using the Platform run_job method to set the active platform context', 'save a PyTorch model to disk using the Platform save_model static method', 'load a PyTorch model from disk using the Platform load_model static method', 'check the available GPU or CPU device string using the Platform device_str property', 'check if multi-GPU parallel training is available using the Platform is_parallel property', 'run a training job function using the local Platform with automatic device and context management', 'get the local root data directory path from the Platform class returning open_lth_data under home', 'get the local dataset root directory path from the Platform class returning open_lth_datasets under home', 'save or load a PyTorch model to or from a local file path using Platform static methods', 'check the available torch device string and whether multi-GPU distributed training is active on the platform', 'get the registered platform class by name from the platforms registry', 'review the registered_platforms dictionary to see which platform implementations are available', 'review the get function that looks up a platform class by its string key', 'refactor the get function to return a default platform when the name is not found', 'summarize the platforms registry module that maps platform names to their class implementations']
```

Usage

```
{'get_platform_by_name': 'get the registered platform class by name from the platforms registry', 'review_registered_platforms_dict': 'review the registered_platforms dictionary to see which platform implementations are available', 'review_get_function': 'review the get function that looks up a platform class by its string key', 'refactor_get_function': 'refactor the get function to return a default platform when the name is not found', 'summarize_registry_module': 'summarize the platforms registry module that maps platform names to their class implementations'}
```

