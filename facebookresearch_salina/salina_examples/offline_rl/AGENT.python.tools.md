# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/offline_rl/d4rl.py

Prompts

```
['create a D4RL gym environment with a specified env name and max episode steps using TimeLimit wrapper', 'create a D4RL Atari gym environment with a specified env name and max episode steps using TimeLimit wrapper', 'build a Workspace from a D4RL environment dataset as sliding window transitions with configurable time size and padding', 'build a Workspace from a D4RL environment dataset as full episodes padded to the maximum episode length', 'iterate through D4RL environment trajectories yielding episode dictionaries with observations, actions, rewards, and terminals']
```

Usage

```
{'make_d4rl_env': 'create a D4RL gym environment with a specified env name and max episode steps using TimeLimit wrapper', 'make_d4rl_atari_env': 'create a D4RL Atari gym environment with a specified env name and max episode steps using TimeLimit wrapper', 'd4rl_transition_buffer': 'build a Workspace from a D4RL environment dataset as sliding window transitions with configurable time size and padding', 'd4rl_episode_buffer': 'build a Workspace from a D4RL environment dataset as full episodes padded to the maximum episode length', 'fixed_sequence_dataset': 'iterate through D4RL environment trajectories yielding episode dictionaries with observations, actions, rewards, and terminals'}
```

