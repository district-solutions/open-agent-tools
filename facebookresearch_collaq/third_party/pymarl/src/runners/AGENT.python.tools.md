# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/pymarl/src/runners/episode_runner.py

Prompts

```
['run a single MARL episode in train or test mode using the EpisodeRunner', 'setup the EpisodeRunner with scheme, groups, preprocess, and mac for batch creation', 'reset the EpisodeRunner environment and create a new EpisodeBatch for the next episode', 'get environment info like state shape, action shape, and n_agents from the EpisodeRunner', 'log episode return mean, return std, and aggregated stats using the EpisodeRunner _log method', 'run a batch of parallel MARL environment episodes using ParallelRunner with test_mode flag', 'setup a ParallelRunner with scheme, groups, preprocess, and mac for episode batch creation', 'reset all parallel environment subprocesses and collect initial observations, states, and available actions', 'close all parallel environment subprocesses by sending close commands through parent connections', 'create a CloudpickleWrapper to serialize callable objects for multiprocessing using cloudpickle instead of pickle']
```

Usage

```
{'run_episode': 'run a single MARL episode in train or test mode using the EpisodeRunner', 'setup_episode_runner': 'setup the EpisodeRunner with scheme, groups, preprocess, and mac for batch creation', 'reset_episode_runner': 'reset the EpisodeRunner environment and create a new EpisodeBatch for the next episode', 'get_env_info': 'get environment info like state shape, action shape, and n_agents from the EpisodeRunner', 'log_episode_stats': 'log episode return mean, return std, and aggregated stats using the EpisodeRunner _log method'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/runners/parallel_runner.py

Prompts

```
['run a single MARL episode in train or test mode using the EpisodeRunner', 'setup the EpisodeRunner with scheme, groups, preprocess, and mac for batch creation', 'reset the EpisodeRunner environment and create a new EpisodeBatch for the next episode', 'get environment info like state shape, action shape, and n_agents from the EpisodeRunner', 'log episode return mean, return std, and aggregated stats using the EpisodeRunner _log method', 'run a batch of parallel MARL environment episodes using ParallelRunner with test_mode flag', 'setup a ParallelRunner with scheme, groups, preprocess, and mac for episode batch creation', 'reset all parallel environment subprocesses and collect initial observations, states, and available actions', 'close all parallel environment subprocesses by sending close commands through parent connections', 'create a CloudpickleWrapper to serialize callable objects for multiprocessing using cloudpickle instead of pickle']
```

Usage

```
{'run_parallel_episodes': 'run a batch of parallel MARL environment episodes using ParallelRunner with test_mode flag', 'setup_parallel_runner': 'setup a ParallelRunner with scheme, groups, preprocess, and mac for episode batch creation', 'reset_parallel_envs': 'reset all parallel environment subprocesses and collect initial observations, states, and available actions', 'close_parallel_envs': 'close all parallel environment subprocesses by sending close commands through parent connections', 'create_cloudpickle_wrapper': 'create a CloudpickleWrapper to serialize callable objects for multiprocessing using cloudpickle instead of pickle'}
```

