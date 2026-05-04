# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/benchmarl/environments/common.py

Prompts

```
['create a subclass of TaskClass implementing get_env_fun, supports_continuous_actions, and supports_discrete_actions abstract methods', 'load a Benchmarl task configuration from a YAML file using Task.get_from_yaml to get a TaskClass instance', 'get a TaskClass object by calling Task.get_task with a custom config dictionary', 'check if a task supports continuous or discrete actions using TaskClass supports_continuous_actions and supports_discrete_actions methods', 'get observation and action specs for an environment by calling TaskClass observation_spec and action_spec methods']
```

Usage

```
{'create_taskclass_subclass': 'create a subclass of TaskClass implementing get_env_fun, supports_continuous_actions, and supports_discrete_actions abstract methods', 'load_task_from_yaml': 'load a Benchmarl task configuration from a YAML file using Task.get_from_yaml to get a TaskClass instance', 'get_task_with_config': 'get a TaskClass object by calling Task.get_task with a custom config dictionary', 'check_task_action_support': 'check if a task supports continuous or discrete actions using TaskClass supports_continuous_actions and supports_discrete_actions methods', 'get_observation_action_specs': 'get observation and action specs for an environment by calling TaskClass observation_spec and action_spec methods'}
```

