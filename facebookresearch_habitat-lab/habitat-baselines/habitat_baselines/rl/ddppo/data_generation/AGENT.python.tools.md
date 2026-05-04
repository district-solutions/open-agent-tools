# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/data_generation/create_gibson_large_dataset.py

Prompts

```
['generate a Gibson training dataset for PointNav by filtering scenes with quality threshold 2 or higher', 'generate 10000 PointNav episodes for a single Gibson scene using the Habitat simulator', 'filter Gibson scene files by quality threshold and train split from dataset statistics JSON', 'create a gzip compressed JSON file containing PointNav episodes for a single scene', 'create a directory safely ignoring errors if the directory already exists']
```

Usage

```
{'generate_gibson_large_dataset': 'generate a Gibson training dataset for PointNav by filtering scenes with quality threshold 2 or higher', 'generate_pointnav_episodes_per_scene': 'generate 10000 PointNav episodes for a single Gibson scene using the Habitat simulator', 'filter_gibson_scenes_by_quality': 'filter Gibson scene files by quality threshold and train split from dataset statistics JSON', 'create_gibson_dataset_json_gz': 'create a gzip compressed JSON file containing PointNav episodes for a single scene', 'safe_mkdir_directory': 'create a directory safely ignoring errors if the directory already exists'}
```

