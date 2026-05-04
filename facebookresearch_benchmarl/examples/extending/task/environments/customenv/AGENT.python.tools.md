# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/examples/extending/task/environments/customenv/common.py

Prompts

```
['create a CustomEnvTask subclass to register new benchmark tasks with auto-loaded YAML configs', 'implement get_env_fun to return a lambda that constructs a TorchRL environment with config params', 'define observation_spec and action_spec methods to return CompositeSpec for env observations and actions', 'configure group_map to map agent group names to individual agent names in the environment', 'add log_info method to extract and return custom metrics from collected TensorDict batches']
```

Usage

```
{'create_custom_env_task': 'create a CustomEnvTask subclass to register new benchmark tasks with auto-loaded YAML configs', 'implement_get_env_fun': 'implement get_env_fun to return a lambda that constructs a TorchRL environment with config params', 'define_observation_action_specs': 'define observation_spec and action_spec methods to return CompositeSpec for env observations and actions', 'configure_group_map': 'configure group_map to map agent group names to individual agent names in the environment', 'add_log_info': 'add log_info method to extract and return custom metrics from collected TensorDict batches'}
```

