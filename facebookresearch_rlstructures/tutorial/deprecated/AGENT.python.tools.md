# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/deprecated_tutorial_agent.py

Prompts

```
['create a UniformAgent that samples random actions from a softmax distribution over n_actions', 'call the UniformAgent with an observation and state to get sampled actions and updated state', 'create a GymEnv wrapping four CartPole-v0 environments with a TimeLimit wrapper and fixed seed', 'create a MonoThreadEpisodeBatcher with factory functions for agent and environment creation', 'execute the batcher to collect episodes and retrieve trajectories with their lengths', 'create a Gym environment with Discrete(2) actions that moves state x by 0.3 per step', 'create a multi-process EpisodeBatcher with 4 threads to collect full episodes in parallel', 'execute the EpisodeBatcher to acquire 32 episodes with agent_info and env_info DictTensors', 'get collected trajectories from the EpisodeBatcher using the blocking get method', 'create a custom Gym environment with discrete action space and random walk dynamics', 'create an Agent subclass that samples actions from a softmax distribution over random scores', 'create a factory function that builds a GymEnv with four TimeLimit-wrapped MyEnv instances', 'create a factory function that instantiates a UniformAgent with a given number of actions', 'run a multi-process Batcher to collect timesteps from environments using spawn multiprocessing']
```

Usage

```
{'create_UniformAgent': 'create a UniformAgent that samples random actions from a softmax distribution over n_actions', 'call_UniformAgent': 'call the UniformAgent with an observation and state to get sampled actions and updated state', 'create_GymEnv': 'create a GymEnv wrapping four CartPole-v0 environments with a TimeLimit wrapper and fixed seed', 'create_MonoThreadEpisodeBatcher': 'create a MonoThreadEpisodeBatcher with factory functions for agent and environment creation', 'execute_batcher_and_get_trajectories': 'execute the batcher to collect episodes and retrieve trajectories with their lengths'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/deprecated_tutorial_multiprocess_episode_batcher.py

Prompts

```
['create a UniformAgent that samples random actions from a softmax distribution over n_actions', 'call the UniformAgent with an observation and state to get sampled actions and updated state', 'create a GymEnv wrapping four CartPole-v0 environments with a TimeLimit wrapper and fixed seed', 'create a MonoThreadEpisodeBatcher with factory functions for agent and environment creation', 'execute the batcher to collect episodes and retrieve trajectories with their lengths', 'create a Gym environment with Discrete(2) actions that moves state x by 0.3 per step', 'create a multi-process EpisodeBatcher with 4 threads to collect full episodes in parallel', 'execute the EpisodeBatcher to acquire 32 episodes with agent_info and env_info DictTensors', 'get collected trajectories from the EpisodeBatcher using the blocking get method', 'create a custom Gym environment with discrete action space and random walk dynamics', 'create an Agent subclass that samples actions from a softmax distribution over random scores', 'create a factory function that builds a GymEnv with four TimeLimit-wrapped MyEnv instances', 'create a factory function that instantiates a UniformAgent with a given number of actions', 'run a multi-process Batcher to collect timesteps from environments using spawn multiprocessing']
```

Usage

```
{'create_MyEnv': 'create a Gym environment with Discrete(2) actions that moves state x by 0.3 per step', 'create_UniformAgent': 'create an Agent that samples actions from a softmax categorical distribution over n_actions', 'create_EpisodeBatcher': 'create a multi-process EpisodeBatcher with 4 threads to collect full episodes in parallel', 'execute_batcher': 'execute the EpisodeBatcher to acquire 32 episodes with agent_info and env_info DictTensors', 'get_trajectories': 'get collected trajectories from the EpisodeBatcher using the blocking get method'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/deprecated_tutorial_multiprocess_trajectory_batcher.py

Prompts

```
['create a UniformAgent that samples random actions from a softmax distribution over n_actions', 'call the UniformAgent with an observation and state to get sampled actions and updated state', 'create a GymEnv wrapping four CartPole-v0 environments with a TimeLimit wrapper and fixed seed', 'create a MonoThreadEpisodeBatcher with factory functions for agent and environment creation', 'execute the batcher to collect episodes and retrieve trajectories with their lengths', 'create a Gym environment with Discrete(2) actions that moves state x by 0.3 per step', 'create a multi-process EpisodeBatcher with 4 threads to collect full episodes in parallel', 'execute the EpisodeBatcher to acquire 32 episodes with agent_info and env_info DictTensors', 'get collected trajectories from the EpisodeBatcher using the blocking get method', 'create a custom Gym environment with discrete action space and random walk dynamics', 'create an Agent subclass that samples actions from a softmax distribution over random scores', 'create a factory function that builds a GymEnv with four TimeLimit-wrapped MyEnv instances', 'create a factory function that instantiates a UniformAgent with a given number of actions', 'run a multi-process Batcher to collect timesteps from environments using spawn multiprocessing']
```

Usage

```
{'create_MyEnv_gym_environment': 'create a custom Gym environment with discrete action space and random walk dynamics', 'create_UniformAgent_class': 'create an Agent subclass that samples actions from a softmax distribution over random scores', 'create_env_factory_function': 'create a factory function that builds a GymEnv with four TimeLimit-wrapped MyEnv instances', 'create_agent_factory_function': 'create a factory function that instantiates a UniformAgent with a given number of actions', 'run_Batcher_multiprocess_trajectory_collection': 'run a multi-process Batcher to collect timesteps from environments using spawn multiprocessing'}
```

