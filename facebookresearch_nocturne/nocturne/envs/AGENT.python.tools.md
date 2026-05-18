# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/nocturne/envs/base_env.py

Prompts

```
['create a BaseEnv instance with a config dict to initialize the Nocturne driving simulation environment', 'run a simulation step by calling step with a dict of vehicle actions and get observations and rewards', 'reset the environment to a new random scenario and return initial observations for all controlled vehicles', 'apply a dictionary of actions to vehicle objects supporting Action, numpy array, list, or discrete index formats', 'render an ego-vehicle cone view image from the render vehicle perspective with configurable view distance and angle', 'create a base Nocturne environment from a config object using the create_env constructor function', 'create a PPO-wrapped Nocturne environment from a config object using the create_ppo_env constructor function', 'review the OnPolicyPPOWrapper step method that converts agent action dicts to lists for multi-agent environments', 'review the OnPolicyPPOWrapper reset method that converts observation dicts to lists and tracks agent IDs', 'refactor the OnPolicyPPOWrapper class to customize observation space handling for multi-agent reinforcement learning']
```

Usage

```
{'create_BaseEnv': 'create a BaseEnv instance with a config dict to initialize the Nocturne driving simulation environment', 'run_step': 'run a simulation step by calling step with a dict of vehicle actions and get observations and rewards', 'run_reset': 'reset the environment to a new random scenario and return initial observations for all controlled vehicles', 'apply_actions': 'apply a dictionary of actions to vehicle objects supporting Action, numpy array, list, or discrete index formats', 'render_ego': 'render an ego-vehicle cone view image from the render vehicle perspective with configurable view distance and angle'}
```

## File: facebookresearch_nocturne/nocturne/envs/wrappers.py

Prompts

```
['create a BaseEnv instance with a config dict to initialize the Nocturne driving simulation environment', 'run a simulation step by calling step with a dict of vehicle actions and get observations and rewards', 'reset the environment to a new random scenario and return initial observations for all controlled vehicles', 'apply a dictionary of actions to vehicle objects supporting Action, numpy array, list, or discrete index formats', 'render an ego-vehicle cone view image from the render vehicle perspective with configurable view distance and angle', 'create a base Nocturne environment from a config object using the create_env constructor function', 'create a PPO-wrapped Nocturne environment from a config object using the create_ppo_env constructor function', 'review the OnPolicyPPOWrapper step method that converts agent action dicts to lists for multi-agent environments', 'review the OnPolicyPPOWrapper reset method that converts observation dicts to lists and tracks agent IDs', 'refactor the OnPolicyPPOWrapper class to customize observation space handling for multi-agent reinforcement learning']
```

Usage

```
{'create_env': 'create a base Nocturne environment from a config object using the create_env constructor function', 'create_ppo_env': 'create a PPO-wrapped Nocturne environment from a config object using the create_ppo_env constructor function', 'review_OnPolicyPPOWrapper_step': 'review the OnPolicyPPOWrapper step method that converts agent action dicts to lists for multi-agent environments', 'review_OnPolicyPPOWrapper_reset': 'review the OnPolicyPPOWrapper reset method that converts observation dicts to lists and tracks agent IDs', 'refactor_OnPolicyPPOWrapper': 'refactor the OnPolicyPPOWrapper class to customize observation space handling for multi-agent reinforcement learning'}
```

