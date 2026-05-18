# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/envs/doom/multiplayer/doom_multiagent.py

Prompts

```
['create a VizdoomEnvMultiplayer instance with player_id, num_agents, max_num_players, and num_bots parameters', 'find an available UDP port starting from a given port number with a configurable increment', 'reset the multiplayer Doom environment and add named or random difficulty bots to the game', 'step the multiplayer Doom environment forward by one action and return observation, reward, done, info', 'ensure the multiplayer Doom game is initialized as a host server or client joining an existing game', 'create a MultiAgentEnv instance with num_agents, make_env_func, env_config, and skip_frames parameters', 'run a step on the MultiAgentEnv by calling step with a list of actions for each agent', 'reset all agents in the MultiAgentEnv by calling the reset method to get fresh observations', 'initialize a multiplayer Doom environment using init_multiplayer_env with make_env_func, player_id, and env_config', 'create a MultiAgentEnvWorker process or thread for a specific player_id with make_env_func and env_config']
```

Usage

```
{'create_VizdoomEnvMultiplayer': 'create a VizdoomEnvMultiplayer instance with player_id, num_agents, max_num_players, and num_bots parameters', 'find_available_port': 'find an available UDP port starting from a given port number with a configurable increment', 'reset_VizdoomEnvMultiplayer': 'reset the multiplayer Doom environment and add named or random difficulty bots to the game', 'step_VizdoomEnvMultiplayer': 'step the multiplayer Doom environment forward by one action and return observation, reward, done, info', 'ensure_initialized_VizdoomEnvMultiplayer': 'ensure the multiplayer Doom game is initialized as a host server or client joining an existing game'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/envs/doom/multiplayer/doom_multiagent_wrapper.py

Prompts

```
['create a VizdoomEnvMultiplayer instance with player_id, num_agents, max_num_players, and num_bots parameters', 'find an available UDP port starting from a given port number with a configurable increment', 'reset the multiplayer Doom environment and add named or random difficulty bots to the game', 'step the multiplayer Doom environment forward by one action and return observation, reward, done, info', 'ensure the multiplayer Doom game is initialized as a host server or client joining an existing game', 'create a MultiAgentEnv instance with num_agents, make_env_func, env_config, and skip_frames parameters', 'run a step on the MultiAgentEnv by calling step with a list of actions for each agent', 'reset all agents in the MultiAgentEnv by calling the reset method to get fresh observations', 'initialize a multiplayer Doom environment using init_multiplayer_env with make_env_func, player_id, and env_config', 'create a MultiAgentEnvWorker process or thread for a specific player_id with make_env_func and env_config']
```

Usage

```
{'create_multiagent_env': 'create a MultiAgentEnv instance with num_agents, make_env_func, env_config, and skip_frames parameters', 'run_multiagent_step': 'run a step on the MultiAgentEnv by calling step with a list of actions for each agent', 'reset_multiagent_env': 'reset all agents in the MultiAgentEnv by calling the reset method to get fresh observations', 'init_multiplayer_env': 'initialize a multiplayer Doom environment using init_multiplayer_env with make_env_func, player_id, and env_config', 'create_multiagent_worker': 'create a MultiAgentEnvWorker process or thread for a specific player_id with make_env_func and env_config'}
```

