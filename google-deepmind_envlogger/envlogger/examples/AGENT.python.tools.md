# Agent Python Tools

- repo: google-deepmind/envlogger
- repo_uri: https://github.com/google-deepmind/envlogger

## File: google-deepmind_envlogger/envlogger/examples/random_agent_catch.py

Prompts

```
['run a random agent in the Catch environment and log trajectories to a directory', 'create a Catch environment instance using catch_env.Catch() for reinforcement learning tasks', 'wrap an environment with EnvLogger to record episode trajectories with metadata and a step function', 'define a custom step function that returns a timestamp dictionary for each environment step', 'run a configurable number of episodes using absl flags for episode count and trajectory directory', 'run a random agent in the Catch environment and log trajectories to a TFDS dataset', 'create an EnvLogger wrapping a gym environment with a TFDSBackendWriter to record episode data', 'configure a TFDS RLDS DatasetConfig with observation, action, reward, and discount info for trajectory logging', 'define a step function that returns custom metadata like timestamps for each environment step', 'run multiple episodes of a random agent while EnvLogger records all timesteps to disk']
```

Usage

```
{'run_random_agent': 'run a random agent in the Catch environment and log trajectories to a directory', 'create_catch_env': 'create a Catch environment instance using catch_env.Catch() for reinforcement learning tasks', 'wrap_env_with_logger': 'wrap an environment with EnvLogger to record episode trajectories with metadata and a step function', 'define_step_fn': 'define a custom step function that returns a timestamp dictionary for each environment step', 'run_episodes_with_flags': 'run a configurable number of episodes using absl flags for episode count and trajectory directory'}
```

## File: google-deepmind_envlogger/envlogger/examples/tfds_random_agent_catch.py

Prompts

```
['run a random agent in the Catch environment and log trajectories to a directory', 'create a Catch environment instance using catch_env.Catch() for reinforcement learning tasks', 'wrap an environment with EnvLogger to record episode trajectories with metadata and a step function', 'define a custom step function that returns a timestamp dictionary for each environment step', 'run a configurable number of episodes using absl flags for episode count and trajectory directory', 'run a random agent in the Catch environment and log trajectories to a TFDS dataset', 'create an EnvLogger wrapping a gym environment with a TFDSBackendWriter to record episode data', 'configure a TFDS RLDS DatasetConfig with observation, action, reward, and discount info for trajectory logging', 'define a step function that returns custom metadata like timestamps for each environment step', 'run multiple episodes of a random agent while EnvLogger records all timesteps to disk']
```

Usage

```
{'run_random_agent_catch': 'run a random agent in the Catch environment and log trajectories to a TFDS dataset', 'create_envlogger_with_tfds_backend': 'create an EnvLogger wrapping a gym environment with a TFDSBackendWriter to record episode data', 'configure_tfds_dataset_config': 'configure a TFDS RLDS DatasetConfig with observation, action, reward, and discount info for trajectory logging', 'define_step_fn_metadata': 'define a step function that returns custom metadata like timestamps for each environment step', 'run_episodes_with_envlogger': 'run multiple episodes of a random agent while EnvLogger records all timesteps to disk'}
```

