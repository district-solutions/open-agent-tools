# Agent Python Tools

- repo: google-deepmind/discorl
- repo_uri: https://github.com/google-deepmind/disco_rl

## File: google-deepmind_discorl/disco_rl/environments/wrappers/batched_env.py

Prompts

```
['create a BatchedSingleStreamEnvironment wrapping multiple single-stream env instances with a given batch size', 'step all environments in the batch forward by passing a batched actions tree to the step method', 'reset all environments in the batch to their initial states using the reset method', 'get the single action spec from the BatchedSingleStreamEnvironment via the single_action_spec method', 'get the single observation spec from the BatchedSingleStreamEnvironment via the single_observation_spec method', 'create a BatchedJittableEnvironment wrapper with an env class, batch size, and config settings', 'run a batched environment step using vmapped actions on a list of EnvState objects', 'get the single action spec as a BoundedArray with min zero and max num_actions minus one', 'get the single observation spec as a dictionary with an observation Array entry', 'create a SingleStreamEnv wrapper around a dm_env environment for single-stream RL training', 'reset a SingleStreamEnv instance and return an initial EnvironmentTimestep with UnusedEnvState', 'step a SingleStreamEnv with an action and handle terminal episode auto-reset logic']
```

Usage

```
{'create_batched_env': 'create a BatchedSingleStreamEnvironment wrapping multiple single-stream env instances with a given batch size', 'step_batched_env': 'step all environments in the batch forward by passing a batched actions tree to the step method', 'reset_batched_env': 'reset all environments in the batch to their initial states using the reset method', 'get_action_spec': 'get the single action spec from the BatchedSingleStreamEnvironment via the single_action_spec method', 'get_observation_spec': 'get the single observation spec from the BatchedSingleStreamEnvironment via the single_observation_spec method'}
```

## File: google-deepmind_discorl/disco_rl/environments/wrappers/batched_jittable_env.py

Prompts

```
['create a BatchedSingleStreamEnvironment wrapping multiple single-stream env instances with a given batch size', 'step all environments in the batch forward by passing a batched actions tree to the step method', 'reset all environments in the batch to their initial states using the reset method', 'get the single action spec from the BatchedSingleStreamEnvironment via the single_action_spec method', 'get the single observation spec from the BatchedSingleStreamEnvironment via the single_observation_spec method', 'create a BatchedJittableEnvironment wrapper with an env class, batch size, and config settings', 'run a batched environment step using vmapped actions on a list of EnvState objects', 'get the single action spec as a BoundedArray with min zero and max num_actions minus one', 'get the single observation spec as a dictionary with an observation Array entry', 'create a SingleStreamEnv wrapper around a dm_env environment for single-stream RL training', 'reset a SingleStreamEnv instance and return an initial EnvironmentTimestep with UnusedEnvState', 'step a SingleStreamEnv with an action and handle terminal episode auto-reset logic']
```

Usage

```
{'create_batched_jittable_env': 'create a BatchedJittableEnvironment wrapper with an env class, batch size, and config settings', 'run_batched_env_step': 'run a batched environment step using vmapped actions on a list of EnvState objects', 'reset_batched_env': 'reset a batch of environments by splitting an RNG key across the batch size', 'get_single_action_spec': 'get the single action spec as a BoundedArray with min zero and max num_actions minus one', 'get_single_observation_spec': 'get the single observation spec as a dictionary with an observation Array entry'}
```

## File: google-deepmind_discorl/disco_rl/environments/wrappers/single_stream_env.py

Prompts

```
['create a BatchedSingleStreamEnvironment wrapping multiple single-stream env instances with a given batch size', 'step all environments in the batch forward by passing a batched actions tree to the step method', 'reset all environments in the batch to their initial states using the reset method', 'get the single action spec from the BatchedSingleStreamEnvironment via the single_action_spec method', 'get the single observation spec from the BatchedSingleStreamEnvironment via the single_observation_spec method', 'create a BatchedJittableEnvironment wrapper with an env class, batch size, and config settings', 'run a batched environment step using vmapped actions on a list of EnvState objects', 'get the single action spec as a BoundedArray with min zero and max num_actions minus one', 'get the single observation spec as a dictionary with an observation Array entry', 'create a SingleStreamEnv wrapper around a dm_env environment for single-stream RL training', 'reset a SingleStreamEnv instance and return an initial EnvironmentTimestep with UnusedEnvState', 'step a SingleStreamEnv with an action and handle terminal episode auto-reset logic']
```

Usage

```
{'create_single_stream_env': 'create a SingleStreamEnv wrapper around a dm_env environment for single-stream RL training', 'reset_single_stream_env': 'reset a SingleStreamEnv instance and return an initial EnvironmentTimestep with UnusedEnvState', 'step_single_stream_env': 'step a SingleStreamEnv with an action and handle terminal episode auto-reset logic', 'get_observation_spec': 'get the observation spec from a SingleStreamEnv wrapper by calling single_observation_spec', 'get_action_spec': 'get the action spec from a SingleStreamEnv wrapper by calling single_action_spec'}
```

