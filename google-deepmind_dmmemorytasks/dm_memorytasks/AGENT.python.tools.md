# Agent Python Tools

- repo: google-deepmind/dmmemorytasks
- repo_uri: https://github.com/google-deepmind/dm_memorytasks

## File: google-deepmind_dmmemorytasks/dm_memorytasks/_load_environment.py

Prompts

```
['load a DeepMind Memory Tasks environment from a local disk path using EnvironmentSettings', 'load a DeepMind Memory Tasks environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and episode_length_seconds', 'list all valid DeepMind Memory Tasks level names as a frozenset of strings', 'step the Memory Tasks environment with action repetition and accumulated reward and discount', 'run the absl test suite for dm_memorytasks load_from_disk with a specified path flag', 'test loading each memory task level by name using parameterized absl test cases', 'test dm_memorytasks load_from_disk with EnvironmentSettings seed and level_name parameters', 'review the LoadFromDiskTest class that extends EnvironmentTestMixin and absltest.TestCase', 'review the MemoryTaskTest class that parameterizes tests over all MEMORY_TASK_LEVEL_NAMES', 'test loading a dm_memorytasks environment from Docker using load_from_docker with EnvironmentSettings', 'run the LoadFromDockerTest class to verify spot_diff_extrapolate level loads from Docker', 'run the MemoryTaskTest class to verify all memory task levels load from Docker', 'review the dm_memorytasks load_from_docker API usage with EnvironmentSettings and seed parameters']
```

Usage

```
{'load_from_disk': 'load a DeepMind Memory Tasks environment from a local disk path using EnvironmentSettings', 'load_from_docker': 'load a DeepMind Memory Tasks environment from a Docker container using EnvironmentSettings', 'EnvironmentSettings': 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and episode_length_seconds', 'MEMORY_TASK_LEVEL_NAMES': 'list all valid DeepMind Memory Tasks level names as a frozenset of strings', 'MemoryTasksEnv_step': 'step the Memory Tasks environment with action repetition and accumulated reward and discount'}
```

## File: google-deepmind_dmmemorytasks/dm_memorytasks/load_from_disk_test.py

Prompts

```
['load a DeepMind Memory Tasks environment from a local disk path using EnvironmentSettings', 'load a DeepMind Memory Tasks environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and episode_length_seconds', 'list all valid DeepMind Memory Tasks level names as a frozenset of strings', 'step the Memory Tasks environment with action repetition and accumulated reward and discount', 'run the absl test suite for dm_memorytasks load_from_disk with a specified path flag', 'test loading each memory task level by name using parameterized absl test cases', 'test dm_memorytasks load_from_disk with EnvironmentSettings seed and level_name parameters', 'review the LoadFromDiskTest class that extends EnvironmentTestMixin and absltest.TestCase', 'review the MemoryTaskTest class that parameterizes tests over all MEMORY_TASK_LEVEL_NAMES', 'test loading a dm_memorytasks environment from Docker using load_from_docker with EnvironmentSettings', 'run the LoadFromDockerTest class to verify spot_diff_extrapolate level loads from Docker', 'run the MemoryTaskTest class to verify all memory task levels load from Docker', 'review the dm_memorytasks load_from_docker API usage with EnvironmentSettings and seed parameters']
```

Usage

```
{'run_load_from_disk_test': 'run the absl test suite for dm_memorytasks load_from_disk with a specified path flag', 'test_load_level_parameterized': 'test loading each memory task level by name using parameterized absl test cases', 'test_load_from_disk_with_settings': 'test dm_memorytasks load_from_disk with EnvironmentSettings seed and level_name parameters', 'review_LoadFromDiskTest': 'review the LoadFromDiskTest class that extends EnvironmentTestMixin and absltest.TestCase', 'review_MemoryTaskTest': 'review the MemoryTaskTest class that parameterizes tests over all MEMORY_TASK_LEVEL_NAMES'}
```

## File: google-deepmind_dmmemorytasks/dm_memorytasks/load_from_docker_test.py

Prompts

```
['load a DeepMind Memory Tasks environment from a local disk path using EnvironmentSettings', 'load a DeepMind Memory Tasks environment from a Docker container using EnvironmentSettings', 'create an EnvironmentSettings NamedTuple with seed, level_name, width, height, and episode_length_seconds', 'list all valid DeepMind Memory Tasks level names as a frozenset of strings', 'step the Memory Tasks environment with action repetition and accumulated reward and discount', 'run the absl test suite for dm_memorytasks load_from_disk with a specified path flag', 'test loading each memory task level by name using parameterized absl test cases', 'test dm_memorytasks load_from_disk with EnvironmentSettings seed and level_name parameters', 'review the LoadFromDiskTest class that extends EnvironmentTestMixin and absltest.TestCase', 'review the MemoryTaskTest class that parameterizes tests over all MEMORY_TASK_LEVEL_NAMES', 'test loading a dm_memorytasks environment from Docker using load_from_docker with EnvironmentSettings', 'run the LoadFromDockerTest class to verify spot_diff_extrapolate level loads from Docker', 'run the MemoryTaskTest class to verify all memory task levels load from Docker', 'review the dm_memorytasks load_from_docker API usage with EnvironmentSettings and seed parameters']
```

Usage

```
{'test_load_from_docker': 'test loading a dm_memorytasks environment from Docker using load_from_docker with EnvironmentSettings', 'test_load_level_parameterized': 'test loading all MEMORY_TASK_LEVEL_NAMES levels from Docker using parameterized test cases', 'run_load_from_docker_test': 'run the LoadFromDockerTest class to verify spot_diff_extrapolate level loads from Docker', 'run_memory_task_test': 'run the MemoryTaskTest class to verify all memory task levels load from Docker', 'review_load_from_docker_api': 'review the dm_memorytasks load_from_docker API usage with EnvironmentSettings and seed parameters'}
```

