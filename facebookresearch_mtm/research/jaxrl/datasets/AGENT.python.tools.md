# Agent Python Tools

- repo: facebookresearch/mtm
- repo_uri: https://github.com/facebookresearch/mtm

## File: facebookresearch_mtm/research/jaxrl/datasets/dataset.py

Prompts

```
['split a flat replay buffer into separate trajectories using done flags to detect episode boundaries', 'merge a list of trajectory tuples back into stacked numpy arrays for observations, actions, rewards, masks, and next observations', 'sample a random batch of transitions from the dataset and return a Batch namedtuple with observations, actions, rewards, masks, and next observations', 'filter the dataset to keep only the top percentile of trajectories by cumulative episode return', 'split the dataset into train and validation Dataset objects by trajectory using a configurable train fraction']
```

Usage

```
{'split_into_trajectories': 'split a flat replay buffer into separate trajectories using done flags to detect episode boundaries', 'merge_trajectories': 'merge a list of trajectory tuples back into stacked numpy arrays for observations, actions, rewards, masks, and next observations', 'Dataset_sample': 'sample a random batch of transitions from the dataset and return a Batch namedtuple with observations, actions, rewards, masks, and next observations', 'Dataset_take_top': 'filter the dataset to keep only the top percentile of trajectories by cumulative episode return', 'Dataset_train_validation_split': 'split the dataset into train and validation Dataset objects by trajectory using a configurable train fraction'}
```

