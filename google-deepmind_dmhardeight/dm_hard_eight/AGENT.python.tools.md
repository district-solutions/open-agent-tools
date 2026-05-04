# Agent Python Tools

- repo: google-deepmind/dmhardeight
- repo_uri: https://github.com/google-deepmind/dm_hard_eight

## File: google-deepmind_dmhardeight/dm_hard_eight/_load_environment.py

Prompts

```
['load a DeepMind Hard Eight environment from a local disk path using EnvironmentSettings', 'load a DeepMind Hard Eight environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and num_action_repeats', 'step the Hard Eight environment with an action repeated N times and accumulate rewards', 'connect to a running dm_hard_eight environment over gRPC with the given port and settings', 'test the dm_hard_eight load_from_disk function by loading an environment from a directory path', 'test that the environment action spec contains all nine expected action keys', 'run the LoadFromDiskTest suite using absltest with a specified environment path flag', 'review the EnvironmentSettings class usage for configuring seed and level_name parameters', 'review the dm_hard_eight load_from_disk API for loading environments with custom settings', 'test the dm_hard_eight load_from_docker function to verify environment loading from a Docker image', 'run the LoadFromDockerTest class to validate environment creation with a specified Docker image name', 'review the LoadFromDockerTest class and its make_object_under_test method for environment test setup', 'summarize the LoadFromDockerTest class that tests dm_hard_eight environment loading via Docker']
```

Usage

```
{'load_from_disk': 'load a DeepMind Hard Eight environment from a local disk path using EnvironmentSettings', 'load_from_docker': 'load a DeepMind Hard Eight environment from a Docker container using EnvironmentSettings', 'EnvironmentSettings': 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and num_action_repeats', 'HardEightTasksEnv_step': 'step the Hard Eight environment with an action repeated N times and accumulate rewards', 'connect_to_environment': 'connect to a running dm_hard_eight environment over gRPC with the given port and settings'}
```

## File: google-deepmind_dmhardeight/dm_hard_eight/load_from_disk_test.py

Prompts

```
['load a DeepMind Hard Eight environment from a local disk path using EnvironmentSettings', 'load a DeepMind Hard Eight environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and num_action_repeats', 'step the Hard Eight environment with an action repeated N times and accumulate rewards', 'connect to a running dm_hard_eight environment over gRPC with the given port and settings', 'test the dm_hard_eight load_from_disk function by loading an environment from a directory path', 'test that the environment action spec contains all nine expected action keys', 'run the LoadFromDiskTest suite using absltest with a specified environment path flag', 'review the EnvironmentSettings class usage for configuring seed and level_name parameters', 'review the dm_hard_eight load_from_disk API for loading environments with custom settings', 'test the dm_hard_eight load_from_docker function to verify environment loading from a Docker image', 'run the LoadFromDockerTest class to validate environment creation with a specified Docker image name', 'review the LoadFromDockerTest class and its make_object_under_test method for environment test setup', 'summarize the LoadFromDockerTest class that tests dm_hard_eight environment loading via Docker']
```

Usage

```
{'test_load_from_disk': 'test the dm_hard_eight load_from_disk function by loading an environment from a directory path', 'test_action_spec': 'test that the environment action spec contains all nine expected action keys', 'run_load_from_disk_test': 'run the LoadFromDiskTest suite using absltest with a specified environment path flag', 'review_environment_settings': 'review the EnvironmentSettings class usage for configuring seed and level_name parameters', 'review_load_from_disk_api': 'review the dm_hard_eight load_from_disk API for loading environments with custom settings'}
```

## File: google-deepmind_dmhardeight/dm_hard_eight/load_from_docker_test.py

Prompts

```
['load a DeepMind Hard Eight environment from a local disk path using EnvironmentSettings', 'load a DeepMind Hard Eight environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and num_action_repeats', 'step the Hard Eight environment with an action repeated N times and accumulate rewards', 'connect to a running dm_hard_eight environment over gRPC with the given port and settings', 'test the dm_hard_eight load_from_disk function by loading an environment from a directory path', 'test that the environment action spec contains all nine expected action keys', 'run the LoadFromDiskTest suite using absltest with a specified environment path flag', 'review the EnvironmentSettings class usage for configuring seed and level_name parameters', 'review the dm_hard_eight load_from_disk API for loading environments with custom settings', 'test the dm_hard_eight load_from_docker function to verify environment loading from a Docker image', 'run the LoadFromDockerTest class to validate environment creation with a specified Docker image name', 'review the LoadFromDockerTest class and its make_object_under_test method for environment test setup', 'summarize the LoadFromDockerTest class that tests dm_hard_eight environment loading via Docker']
```

Usage

```
{'test_load_from_docker': 'test the dm_hard_eight load_from_docker function to verify environment loading from a Docker image', 'test_action_spec': 'test the action spec keys of the Hard Eight environment to validate expected action names', 'run_load_from_docker_test': 'run the LoadFromDockerTest class to validate environment creation with a specified Docker image name', 'review_load_from_docker_test': 'review the LoadFromDockerTest class and its make_object_under_test method for environment test setup', 'summarize_load_from_docker_test': 'summarize the LoadFromDockerTest class that tests dm_hard_eight environment loading via Docker'}
```

