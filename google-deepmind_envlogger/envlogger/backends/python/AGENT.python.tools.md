# Agent Python Tools

- repo: google-deepmind/envlogger
- repo_uri: https://github.com/google-deepmind/envlogger

## File: google-deepmind_envlogger/envlogger/backends/python/episode_info_test.py

Prompts

```
['test that an empty EpisodeInfo has default start 0, num_steps 0, and None metadata', 'test EpisodeInfo initialization with random start, num_steps, and storage_pb2 metadata values', 'create an empty EpisodeInfo object with default start, num_steps, and metadata values', 'create an EpisodeInfo with custom start, num_steps, and a storage_pb2 Data metadata object', 'run the absltest suite for EpisodeInfo including empty and random kwargs test cases', 'initialize a RiegeliDatasetWriter, add encoded proto steps, then close the writer', 'initialize a RiegeliDatasetReader and iterate over num_steps to read each step', 'clone a RiegeliDatasetReader to create an independent copy for parallel reading', 'pickle a RiegeliDatasetWriter to serialize and restore its state and configuration', 'use a RiegeliDatasetReader to iterate over num_episodes and read episode metadata']
```

Usage

```
{'test_empty_episode_info': 'test that an empty EpisodeInfo has default start 0, num_steps 0, and None metadata', 'test_episode_info_init_with_kwargs': 'test EpisodeInfo initialization with random start, num_steps, and storage_pb2 metadata values', 'create_episode_info_empty': 'create an empty EpisodeInfo object with default start, num_steps, and metadata values', 'create_episode_info_with_metadata': 'create an EpisodeInfo with custom start, num_steps, and a storage_pb2 Data metadata object', 'run_episode_info_tests': 'run the absltest suite for EpisodeInfo including empty and random kwargs test cases'}
```

## File: google-deepmind_envlogger/envlogger/backends/python/riegeli_dataset_test.py

Prompts

```
['test that an empty EpisodeInfo has default start 0, num_steps 0, and None metadata', 'test EpisodeInfo initialization with random start, num_steps, and storage_pb2 metadata values', 'create an empty EpisodeInfo object with default start, num_steps, and metadata values', 'create an EpisodeInfo with custom start, num_steps, and a storage_pb2 Data metadata object', 'run the absltest suite for EpisodeInfo including empty and random kwargs test cases', 'initialize a RiegeliDatasetWriter, add encoded proto steps, then close the writer', 'initialize a RiegeliDatasetReader and iterate over num_steps to read each step', 'clone a RiegeliDatasetReader to create an independent copy for parallel reading', 'pickle a RiegeliDatasetWriter to serialize and restore its state and configuration', 'use a RiegeliDatasetReader to iterate over num_episodes and read episode metadata']
```

Usage

```
{'write_proto_steps_to_riegeli_dataset': 'initialize a RiegeliDatasetWriter, add encoded proto steps, then close the writer', 'read_steps_from_riegeli_dataset': 'initialize a RiegeliDatasetReader and iterate over num_steps to read each step', 'clone_riegeli_reader': 'clone a RiegeliDatasetReader to create an independent copy for parallel reading', 'pickle_riegeli_writer': 'pickle a RiegeliDatasetWriter to serialize and restore its state and configuration', 'read_episodes_from_riegeli_dataset': 'use a RiegeliDatasetReader to iterate over num_episodes and read episode metadata'}
```

