# Agent Python Tools

- repo: google-deepmind/dmfastmapping
- repo_uri: https://github.com/google-deepmind/dm_fast_mapping

## File: google-deepmind_dmfastmapping/dm_fast_mapping/_load_environment.py

Prompts

```
['load a DeepMind Fast Mapping environment from a local disk path using EnvironmentSettings', 'load a DeepMapping environment from a Docker container using EnvironmentSettings and an optional image name', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, episode_length_seconds, and num_action_repeats', 'validate EnvironmentSettings to ensure episode_length_seconds, num_action_repeats, width, and height are positive values', 'list all valid Fast Mapping task level names from the FAST_MAPPING_TASK_LEVEL_NAMES frozenset', 'test the LoadFromDiskTest class to verify dm_fast_mapping loads from disk with a given path and settings', 'test the FastMappingTaskTest class to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from disk', 'run the LoadFromDiskTest make_object_under_test method to create a dm_fast_mapping environment with seed 123', 'review the dm_fast_mapping load_from_disk function usage with EnvironmentSettings seed and level_name parameters', 'summarize the FastMappingTaskTest parameterized test that iterates over all FAST_MAPPING_TASK_LEVEL_NAMES', 'run the LoadFromDockerTest to verify dm_fast_mapping.load_from_docker creates a valid environment from a Docker image', 'run the parameterized FastMappingTaskTest to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from Docker', 'test dm_fast_mapping.load_from_docker with EnvironmentSettings seed and level_name to return a non-None environment', 'test EnvironmentSettings with a seed and level_name to configure a Fast Mapping task environment', 'review the FAST_MAPPING_TASK_LEVEL_NAMES constant to see all available Fast Mapping task levels for parameterized testing']
```

Usage

```
{'load_from_disk': 'load a DeepMind Fast Mapping environment from a local disk path using EnvironmentSettings', 'load_from_docker': 'load a DeepMapping environment from a Docker container using EnvironmentSettings and an optional image name', 'create_EnvironmentSettings': 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, episode_length_seconds, and num_action_repeats', 'validate_environment_settings': 'validate EnvironmentSettings to ensure episode_length_seconds, num_action_repeats, width, and height are positive values', 'list_FAST_MAPPING_TASK_LEVEL_NAMES': 'list all valid Fast Mapping task level names from the FAST_MAPPING_TASK_LEVEL_NAMES frozenset'}
```

## File: google-deepmind_dmfastmapping/dm_fast_mapping/load_from_disk_test.py

Prompts

```
['load a DeepMind Fast Mapping environment from a local disk path using EnvironmentSettings', 'load a DeepMapping environment from a Docker container using EnvironmentSettings and an optional image name', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, episode_length_seconds, and num_action_repeats', 'validate EnvironmentSettings to ensure episode_length_seconds, num_action_repeats, width, and height are positive values', 'list all valid Fast Mapping task level names from the FAST_MAPPING_TASK_LEVEL_NAMES frozenset', 'test the LoadFromDiskTest class to verify dm_fast_mapping loads from disk with a given path and settings', 'test the FastMappingTaskTest class to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from disk', 'run the LoadFromDiskTest make_object_under_test method to create a dm_fast_mapping environment with seed 123', 'review the dm_fast_mapping load_from_disk function usage with EnvironmentSettings seed and level_name parameters', 'summarize the FastMappingTaskTest parameterized test that iterates over all FAST_MAPPING_TASK_LEVEL_NAMES', 'run the LoadFromDockerTest to verify dm_fast_mapping.load_from_docker creates a valid environment from a Docker image', 'run the parameterized FastMappingTaskTest to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from Docker', 'test dm_fast_mapping.load_from_docker with EnvironmentSettings seed and level_name to return a non-None environment', 'test EnvironmentSettings with a seed and level_name to configure a Fast Mapping task environment', 'review the FAST_MAPPING_TASK_LEVEL_NAMES constant to see all available Fast Mapping task levels for parameterized testing']
```

Usage

```
{'test_load_from_disk': 'test the LoadFromDiskTest class to verify dm_fast_mapping loads from disk with a given path and settings', 'test_fast_mapping_levels': 'test the FastMappingTaskTest class to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from disk', 'run_load_from_disk_test': 'run the LoadFromDiskTest make_object_under_test method to create a dm_fast_mapping environment with seed 123', 'review_load_from_disk_api': 'review the dm_fast_mapping load_from_disk function usage with EnvironmentSettings seed and level_name parameters', 'summarize_fast_mapping_test': 'summarize the FastMappingTaskTest parameterized test that iterates over all FAST_MAPPING_TASK_LEVEL_NAMES'}
```

## File: google-deepmind_dmfastmapping/dm_fast_mapping/load_from_docker_test.py

Prompts

```
['load a DeepMind Fast Mapping environment from a local disk path using EnvironmentSettings', 'load a DeepMapping environment from a Docker container using EnvironmentSettings and an optional image name', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, episode_length_seconds, and num_action_repeats', 'validate EnvironmentSettings to ensure episode_length_seconds, num_action_repeats, width, and height are positive values', 'list all valid Fast Mapping task level names from the FAST_MAPPING_TASK_LEVEL_NAMES frozenset', 'test the LoadFromDiskTest class to verify dm_fast_mapping loads from disk with a given path and settings', 'test the FastMappingTaskTest class to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from disk', 'run the LoadFromDiskTest make_object_under_test method to create a dm_fast_mapping environment with seed 123', 'review the dm_fast_mapping load_from_disk function usage with EnvironmentSettings seed and level_name parameters', 'summarize the FastMappingTaskTest parameterized test that iterates over all FAST_MAPPING_TASK_LEVEL_NAMES', 'run the LoadFromDockerTest to verify dm_fast_mapping.load_from_docker creates a valid environment from a Docker image', 'run the parameterized FastMappingTaskTest to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from Docker', 'test dm_fast_mapping.load_from_docker with EnvironmentSettings seed and level_name to return a non-None environment', 'test EnvironmentSettings with a seed and level_name to configure a Fast Mapping task environment', 'review the FAST_MAPPING_TASK_LEVEL_NAMES constant to see all available Fast Mapping task levels for parameterized testing']
```

Usage

```
{'run_load_from_docker_test': 'run the LoadFromDockerTest to verify dm_fast_mapping.load_from_docker creates a valid environment from a Docker image', 'run_fast_mapping_task_test': 'run the parameterized FastMappingTaskTest to verify all FAST_MAPPING_TASK_LEVEL_NAMES load successfully from Docker', 'test_load_from_docker': 'test dm_fast_mapping.load_from_docker with EnvironmentSettings seed and level_name to return a non-None environment', 'test_environment_settings': 'test EnvironmentSettings with a seed and level_name to configure a Fast Mapping task environment', 'review_fast_mapping_task_level_names': 'review the FAST_MAPPING_TASK_LEVEL_NAMES constant to see all available Fast Mapping task levels for parameterized testing'}
```

