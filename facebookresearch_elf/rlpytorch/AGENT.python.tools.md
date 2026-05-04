# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rlpytorch/args_provider.py

Prompts

```
['create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print all loaded argument values grouped by their provider class name using Args.print_info', 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'clone an RL model with args, step, and state_dict to a new GPU', 'save an RL model state dict, step, and args to a file with retries', 'load an RL model from a file with optional keys to omit', 'load state dict and step from an existing RL model instance', 'set an RL model to volatile inference mode to skip saving history', 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update model weights by calling optimizer step and incrementing the model step counter', 'average the parameters between two models and update the target model in the interface', 'deep copy a model from one key to another key within the same ModelInterface', 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'create a function that dynamically loads a Python module by path using load_module', 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'create a ModelLoader that calls post-load callback functions on the model via the onload argument']
```

Usage

```
{'create_ArgsProvider': 'create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load_args_with_ArgsProvider_Load': 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace_Args_keys': 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'recursive_map_on_nested_structures': 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print_args_info': 'print all loaded argument values grouped by their provider class name using Args.print_info'}
```

## File: facebookresearch_elf/rlpytorch/args_utils.py

Prompts

```
['create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print all loaded argument values grouped by their provider class name using Args.print_info', 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'clone an RL model with args, step, and state_dict to a new GPU', 'save an RL model state dict, step, and args to a file with retries', 'load an RL model from a file with optional keys to omit', 'load state dict and step from an existing RL model instance', 'set an RL model to volatile inference mode to skip saving history', 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update model weights by calling optimizer step and incrementing the model step counter', 'average the parameters between two models and update the target model in the interface', 'deep copy a model from one key to another key within the same ModelInterface', 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'create a function that dynamically loads a Python module by path using load_module', 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'create a ModelLoader that calls post-load callback functions on the model via the onload argument']
```

Usage

```
{'create_ArgsProvider': 'create an ArgsProvider to define command line arguments with defaults and callbacks for an RL training module', 'load_args_with_ArgsProvider_Load': 'load command line arguments using ArgsProvider.Load with a parser and list of provider instances', 'use_recursive_map': 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'replace_Args_keys': 'replace attribute keys on an Args object by passing a list of old and new key tuples', 'print_args_info': 'print all parsed argument groups and their values using the Args.print_info method'}
```

## File: facebookresearch_elf/rlpytorch/model_base.py

Prompts

```
['create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print all loaded argument values grouped by their provider class name using Args.print_info', 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'clone an RL model with args, step, and state_dict to a new GPU', 'save an RL model state dict, step, and args to a file with retries', 'load an RL model from a file with optional keys to omit', 'load state dict and step from an existing RL model instance', 'set an RL model to volatile inference mode to skip saving history', 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update model weights by calling optimizer step and incrementing the model step counter', 'average the parameters between two models and update the target model in the interface', 'deep copy a model from one key to another key within the same ModelInterface', 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'create a function that dynamically loads a Python module by path using load_module', 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'create a ModelLoader that calls post-load callback functions on the model via the onload argument']
```

Usage

```
{'clone_rl_model': 'clone an RL model with args, step, and state_dict to a new GPU', 'save_rl_model': 'save an RL model state dict, step, and args to a file with retries', 'load_rl_model': 'load an RL model from a file with optional keys to omit', 'load_from_model': 'load state dict and step from an existing RL model instance', 'set_volatile_mode': 'set an RL model to volatile inference mode to skip saving history'}
```

## File: facebookresearch_elf/rlpytorch/model_interface.py

Prompts

```
['create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print all loaded argument values grouped by their provider class name using Args.print_info', 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'clone an RL model with args, step, and state_dict to a new GPU', 'save an RL model state dict, step, and args to a file with retries', 'load an RL model from a file with optional keys to omit', 'load state dict and step from an existing RL model instance', 'set an RL model to volatile inference mode to skip saving history', 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update model weights by calling optimizer step and incrementing the model step counter', 'average the parameters between two models and update the target model in the interface', 'deep copy a model from one key to another key within the same ModelInterface', 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'create a function that dynamically loads a Python module by path using load_module', 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'create a ModelLoader that calls post-load callback functions on the model via the onload argument']
```

Usage

```
{'add_model_to_interface': 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone_model_interface': 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update_model_weights': 'update model weights by calling optimizer step and incrementing the model step counter', 'average_model_parameters': 'average the parameters between two models and update the target model in the interface', 'copy_model_between_keys': 'deep copy a model from one key to another key within the same ModelInterface'}
```

## File: facebookresearch_elf/rlpytorch/model_loader.py

Prompts

```
['create an ArgsProvider instance with define_args tuples specifying CLI argument names and default values', 'load command line arguments by calling ArgsProvider.Load with an ArgumentParser and list of provider instances', 'replace attribute keys on an Args object by calling replace with a list of old to new key tuples', 'apply a function recursively over nested dicts and lists using the recursive_map utility function', 'print all loaded argument values grouped by their provider class name using Args.print_info', 'use recursive_map to apply a function recursively across nested dicts and lists of configuration values', 'clone an RL model with args, step, and state_dict to a new GPU', 'save an RL model state dict, step, and args to a file with retries', 'load an RL model from a file with optional keys to omit', 'load state dict and step from an existing RL model instance', 'set an RL model to volatile inference mode to skip saving history', 'add a PyTorch model to a ModelInterface with an Adam optimizer and optional CUDA placement', 'clone a ModelInterface including all models and optimizers to a specified GPU device', 'update model weights by calling optimizer step and incrementing the model step counter', 'average the parameters between two models and update the target model in the interface', 'deep copy a model from one key to another key within the same ModelInterface', 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'create a function that dynamically loads a Python module by path using load_module', 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'create a ModelLoader that calls post-load callback functions on the model via the onload argument']
```

Usage

```
{'load_model_with_ModelLoader': 'create a ModelLoader instance with a model class and call load_model to load a saved model from disk', 'load_module_dynamic': 'create a function that dynamically loads a Python module by path using load_module', 'load_env_with_load_env': 'build an RL environment by calling load_env with game, model_file, and model config dicts', 'load_model_with_omit_keys': 'create a ModelLoader that loads a saved model while omitting specific keys via the omit_keys argument', 'load_model_with_onload_callbacks': 'create a ModelLoader that calls post-load callback functions on the model via the onload argument'}
```

