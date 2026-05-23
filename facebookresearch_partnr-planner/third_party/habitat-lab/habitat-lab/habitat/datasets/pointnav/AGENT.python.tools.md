# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/datasets/pointnav/pointnav_dataset.py

Prompts

```
['instantiate a PointNavDatasetV1 with a DictConfig to load navigation episodes from a dataset file', 'check whether the data_path and scenes_dir in a PointNav-v1 config both exist on disk', 'get a list of scene IDs that have separate episode files for a PointNav-v1 config', 'parse a JSON string into NavigationEpisode objects and populate a PointNavDatasetV1 instance', 'list scene names from a content_scenes_path folder by matching the expected file extension', 'generate PointGoal navigation episodes for a HabitatSim simulator with configurable distance limits and retry logic', 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'review the is_compatible_episode function to understand geodesic distance and Euclidean ratio filtering logic', 'summarize the generate_pointnav_episode generator function and its rejection sampling strategy for navigation complexity']
```

Usage

```
{'load_PointNavDatasetV1': 'instantiate a PointNavDatasetV1 with a DictConfig to load navigation episodes from a dataset file', 'check_PointNavDatasetV1_config_paths': 'check whether the data_path and scenes_dir in a PointNav-v1 config both exist on disk', 'get_PointNavDatasetV1_scenes_to_load': 'get a list of scene IDs that have separate episode files for a PointNav-v1 config', 'parse_PointNavDatasetV1_from_json': 'parse a JSON string into NavigationEpisode objects and populate a PointNavDatasetV1 instance', 'list_PointNavDatasetV1_scenes_from_folder': 'list scene names from a content_scenes_path folder by matching the expected file extension'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/datasets/pointnav/pointnav_generator.py

Prompts

```
['instantiate a PointNavDatasetV1 with a DictConfig to load navigation episodes from a dataset file', 'check whether the data_path and scenes_dir in a PointNav-v1 config both exist on disk', 'get a list of scene IDs that have separate episode files for a PointNav-v1 config', 'parse a JSON string into NavigationEpisode objects and populate a PointNavDatasetV1 instance', 'list scene names from a content_scenes_path folder by matching the expected file extension', 'generate PointGoal navigation episodes for a HabitatSim simulator with configurable distance limits and retry logic', 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'review the is_compatible_episode function to understand geodesic distance and Euclidean ratio filtering logic', 'summarize the generate_pointnav_episode generator function and its rejection sampling strategy for navigation complexity']
```

Usage

```
{'generate_pointnav_episodes': 'generate PointGoal navigation episodes for a HabitatSim simulator with configurable distance limits and retry logic', 'check_compatible_episode': 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create_navigation_episode': 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'review_is_compatible_episode': 'review the is_compatible_episode function to understand geodesic distance and Euclidean ratio filtering logic', 'summarize_generate_pointnav_episode': 'summarize the generate_pointnav_episode generator function and its rejection sampling strategy for navigation complexity'}
```

