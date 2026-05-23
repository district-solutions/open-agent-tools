# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/playing_with_rlstructures.py

Prompts

```
['create a GymEnv wrapper with multiple CartPole-v0 environments and optional timestep limits', 'create a GymEnvInf autoreset wrapper with multiple CartPole-v0 environments that never stop', 'create a custom RL_Agent subclass that tracks timesteps and selects actions from agent_info', 'create a MyAgent instance using the factory function for use with RL_Batcher', 'run an RL_Batcher to sample complete episodes or trajectory slots across multiple processes', 'create a custom gym.Env subclass with discrete action space and dictionary-based observations', 'wrap multiple gym.Env instances into a rlstructures GymEnv vectorized environment', 'reset a vectorized environment and retrieve initial observations with running env indices', 'step a vectorized environment using a DictTensor action and collect observations', 'review the MyEnv class step method that moves state x toward episode termination', 'create a UniformAgent that samples random actions using softmax probabilities over n_actions', 'run an RL_Batcher to collect trajectories by executing a UniformAgent in CartPole-v0 environments', 'review the UniformAgent call method that samples categorical actions and updates timestep state']
```

Usage

```
{'create_env': 'create a GymEnv wrapper with multiple CartPole-v0 environments and optional timestep limits', 'create_autoreset_env': 'create a GymEnvInf autoreset wrapper with multiple CartPole-v0 environments that never stop', 'create_MyAgent': 'create a custom RL_Agent subclass that tracks timesteps and selects actions from agent_info', 'create_agent': 'create a MyAgent instance using the factory function for use with RL_Batcher', 'run_RL_Batcher': 'run an RL_Batcher to sample complete episodes or trajectory slots across multiple processes'}
```

## File: facebookresearch_rlstructures/tutorial/tutorial_environments.py

Prompts

```
['create a GymEnv wrapper with multiple CartPole-v0 environments and optional timestep limits', 'create a GymEnvInf autoreset wrapper with multiple CartPole-v0 environments that never stop', 'create a custom RL_Agent subclass that tracks timesteps and selects actions from agent_info', 'create a MyAgent instance using the factory function for use with RL_Batcher', 'run an RL_Batcher to sample complete episodes or trajectory slots across multiple processes', 'create a custom gym.Env subclass with discrete action space and dictionary-based observations', 'wrap multiple gym.Env instances into a rlstructures GymEnv vectorized environment', 'reset a vectorized environment and retrieve initial observations with running env indices', 'step a vectorized environment using a DictTensor action and collect observations', 'review the MyEnv class step method that moves state x toward episode termination', 'create a UniformAgent that samples random actions using softmax probabilities over n_actions', 'run an RL_Batcher to collect trajectories by executing a UniformAgent in CartPole-v0 environments', 'review the UniformAgent call method that samples categorical actions and updates timestep state']
```

Usage

```
{'create_custom_gym_env': 'create a custom gym.Env subclass with discrete action space and dictionary-based observations', 'wrap_gym_envs_with_gymenv': 'wrap multiple gym.Env instances into a rlstructures GymEnv vectorized environment', 'reset_vecenv_and_observe': 'reset a vectorized environment and retrieve initial observations with running env indices', 'step_vecenv_with_dicttensor': 'step a vectorized environment using a DictTensor action and collect observations', 'review_MyEnv_class': 'review the MyEnv class step method that moves state x toward episode termination'}
```

## File: facebookresearch_rlstructures/tutorial/tutorial_rlagent.py

Prompts

```
['create a GymEnv wrapper with multiple CartPole-v0 environments and optional timestep limits', 'create a GymEnvInf autoreset wrapper with multiple CartPole-v0 environments that never stop', 'create a custom RL_Agent subclass that tracks timesteps and selects actions from agent_info', 'create a MyAgent instance using the factory function for use with RL_Batcher', 'run an RL_Batcher to sample complete episodes or trajectory slots across multiple processes', 'create a custom gym.Env subclass with discrete action space and dictionary-based observations', 'wrap multiple gym.Env instances into a rlstructures GymEnv vectorized environment', 'reset a vectorized environment and retrieve initial observations with running env indices', 'step a vectorized environment using a DictTensor action and collect observations', 'review the MyEnv class step method that moves state x toward episode termination', 'create a UniformAgent that samples random actions using softmax probabilities over n_actions', 'run an RL_Batcher to collect trajectories by executing a UniformAgent in CartPole-v0 environments', 'review the UniformAgent call method that samples categorical actions and updates timestep state']
```

Usage

```
{'create_uniform_agent': 'create a UniformAgent that samples random actions using softmax probabilities over n_actions', 'create_env': 'create a GymEnv wrapping four CartPole-v0 environments with a TimeLimit wrapper', 'create_agent': 'create a factory function that returns a UniformAgent instance with the given number of actions', 'run_rl_batcher': 'run an RL_Batcher to collect trajectories by executing a UniformAgent in CartPole-v0 environments', 'review_uniform_agent_call': 'review the UniformAgent call method that samples categorical actions and updates timestep state'}
```

