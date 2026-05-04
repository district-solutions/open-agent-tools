# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/datasets/pointnav/pointnav_dataset.py

Prompts

```
['create a PointNavDatasetV1 instance from a DictConfig to load navigation episodes from a dataset file', 'parse a JSON string into NavigationEpisode objects with goals and shortest paths using from_json', 'get a list of scene IDs available in the dataset directory using get_scenes_to_load', 'check if the dataset data path and scenes directory exist using check_config_paths_exist', 'discover scene names from a content directory by scanning matching file extensions using _get_scenes_from_folder', 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity filtering', 'check if a start and target position pair forms a compatible navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'compute the aggressive sampling rate for filtering straight-line episodes based on geodesic to Euclidean distance ratio', 'review the ISLAND_RADIUS_LIMIT constant used to filter isolated navigable points that are not part of a floor']
```

Usage

```
{'load_PointNavDatasetV1': 'create a PointNavDatasetV1 instance from a DictConfig to load navigation episodes from a dataset file', 'parse_from_json': 'parse a JSON string into NavigationEpisode objects with goals and shortest paths using from_json', 'get_scenes_to_load': 'get a list of scene IDs available in the dataset directory using get_scenes_to_load', 'check_config_paths_exist': 'check if the dataset data path and scenes directory exist using check_config_paths_exist', 'discover_scenes_from_folder': 'discover scene names from a content directory by scanning matching file extensions using _get_scenes_from_folder'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/datasets/pointnav/pointnav_generator.py

Prompts

```
['create a PointNavDatasetV1 instance from a DictConfig to load navigation episodes from a dataset file', 'parse a JSON string into NavigationEpisode objects with goals and shortest paths using from_json', 'get a list of scene IDs available in the dataset directory using get_scenes_to_load', 'check if the dataset data path and scenes directory exist using check_config_paths_exist', 'discover scene names from a content directory by scanning matching file extensions using _get_scenes_from_folder', 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity filtering', 'check if a start and target position pair forms a compatible navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'compute the aggressive sampling rate for filtering straight-line episodes based on geodesic to Euclidean distance ratio', 'review the ISLAND_RADIUS_LIMIT constant used to filter isolated navigable points that are not part of a floor']
```

Usage

```
{'generate_pointnav_episodes': 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity filtering', 'check_compatible_episode': 'check if a start and target position pair forms a compatible navigation episode within distance bounds', 'create_navigation_episode': 'create a NavigationEpisode object with start position, rotation, target position, and optional shortest paths', 'compute_ratio_sample_rate': 'compute the aggressive sampling rate for filtering straight-line episodes based on geodesic to Euclidean distance ratio', 'review_island_radius_limit': 'review the ISLAND_RADIUS_LIMIT constant used to filter isolated navigable points that are not part of a floor'}
```

