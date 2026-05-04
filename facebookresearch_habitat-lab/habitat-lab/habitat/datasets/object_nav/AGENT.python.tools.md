# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/datasets/object_nav/object_nav_dataset.py

Prompts

```
['create an ObjectNavDatasetV1 instance to load object navigation episodes from a JSON dataset file', 'deduplicate goals across episodes by category and store them in a shared goals_by_category dictionary', 'serialize the ObjectNavDatasetV1 dataset to a JSON string with goals temporarily cleared from episodes', 'deserialize a JSON string into ObjectNavDatasetV1 episodes with reconstructed goals and shortest paths', 'deserialize a serialized ObjectGoal dictionary into an ObjectGoal with view points and agent state']
```

Usage

```
{'load_object_nav_dataset': 'create an ObjectNavDatasetV1 instance to load object navigation episodes from a JSON dataset file', 'dedup_goals': 'deduplicate goals across episodes by category and store them in a shared goals_by_category dictionary', 'serialize_dataset_to_json': 'serialize the ObjectNavDatasetV1 dataset to a JSON string with goals temporarily cleared from episodes', 'deserialize_dataset_from_json': 'deserialize a JSON string into ObjectNavDatasetV1 episodes with reconstructed goals and shortest paths', 'deserialize_single_goal': 'deserialize a serialized ObjectGoal dictionary into an ObjectGoal with view points and agent state'}
```

