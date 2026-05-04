# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/level_replay/level_sampler.py

Prompts

```
['create a LevelSampler instance with seeds, observation space, action space, and a sampling strategy', 'sample a level seed using the LevelSampler sample method with random or sequential strategy', 'update a seed score with the update_seed_score method given actor index, seed, score, and step count', 'update seed scores from rollout data using update_with_rollouts and a strategy like policy_entropy or gae', 'compute normalized sampling weights for all seeds using the sample_weights method with score and staleness transforms', 'create a LevelStore instance with an optional max_size and data_info dictionary for numpy level data', 'insert one or more levels into the LevelStore and receive their assigned seed indices', 'remove one or more levels from the LevelStore by their seed indices', 'retrieve a stored level by its seed, optionally deserialized as a numpy array', 'reconcile the LevelStore seeds by ejecting any seeds not present in the provided list']
```

Usage

```
{'create_LevelSampler': 'create a LevelSampler instance with seeds, observation space, action space, and a sampling strategy', 'sample_level': 'sample a level seed using the LevelSampler sample method with random or sequential strategy', 'update_seed_score': 'update a seed score with the update_seed_score method given actor index, seed, score, and step count', 'update_with_rollouts': 'update seed scores from rollout data using update_with_rollouts and a strategy like policy_entropy or gae', 'sample_weights': 'compute normalized sampling weights for all seeds using the sample_weights method with score and staleness transforms'}
```

## File: facebookresearch_dcd/level_replay/level_store.py

Prompts

```
['create a LevelSampler instance with seeds, observation space, action space, and a sampling strategy', 'sample a level seed using the LevelSampler sample method with random or sequential strategy', 'update a seed score with the update_seed_score method given actor index, seed, score, and step count', 'update seed scores from rollout data using update_with_rollouts and a strategy like policy_entropy or gae', 'compute normalized sampling weights for all seeds using the sample_weights method with score and staleness transforms', 'create a LevelStore instance with an optional max_size and data_info dictionary for numpy level data', 'insert one or more levels into the LevelStore and receive their assigned seed indices', 'remove one or more levels from the LevelStore by their seed indices', 'retrieve a stored level by its seed, optionally deserialized as a numpy array', 'reconcile the LevelStore seeds by ejecting any seeds not present in the provided list']
```

Usage

```
{'create_LevelStore': 'create a LevelStore instance with an optional max_size and data_info dictionary for numpy level data', 'insert_levels': 'insert one or more levels into the LevelStore and receive their assigned seed indices', 'remove_levels': 'remove one or more levels from the LevelStore by their seed indices', 'get_level_by_seed': 'retrieve a stored level by its seed, optionally deserialized as a numpy array', 'reconcile_seeds': 'reconcile the LevelStore seeds by ejecting any seeds not present in the provided list'}
```

