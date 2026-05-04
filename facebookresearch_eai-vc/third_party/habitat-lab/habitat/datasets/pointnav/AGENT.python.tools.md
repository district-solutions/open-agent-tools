# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/datasets/pointnav/pointnav_dataset.py

Prompts

```
['create a PointNavDatasetV1 instance from a Habitat config to load navigation episodes from gzipped JSON files', 'call PointNavDatasetV1.check_config_paths_exist to verify the dataset data path and scenes directory exist', 'call PointNavDatasetV1.get_scenes_to_load to return a list of scene IDs available in the dataset', 'call PointNavDatasetV1.from_json to parse a JSON string into NavigationEpisode objects with goals and shortest paths', 'call PointNavDatasetV1._get_scenes_from_folder to list scene names from a content directory by file extension', 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity ratio', 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target goal, and optional shortest paths', 'calculate the aggressive rejection sampling rate for episodes with low geodesic to Euclidean distance ratio', 'review the generate_pointnav_episode generator function for navigation complexity filtering and rejection sampling logic']
```

Usage

```
{'load_PointNavDatasetV1': 'create a PointNavDatasetV1 instance from a Habitat config to load navigation episodes from gzipped JSON files', 'check_config_paths_exist': 'call PointNavDatasetV1.check_config_paths_exist to verify the dataset data path and scenes directory exist', 'get_scenes_to_load': 'call PointNavDatasetV1.get_scenes_to_load to return a list of scene IDs available in the dataset', 'from_json': 'call PointNavDatasetV1.from_json to parse a JSON string into NavigationEpisode objects with goals and shortest paths', 'get_scenes_from_folder': 'call PointNavDatasetV1._get_scenes_from_folder to list scene names from a content directory by file extension'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/datasets/pointnav/pointnav_generator.py

Prompts

```
['create a PointNavDatasetV1 instance from a Habitat config to load navigation episodes from gzipped JSON files', 'call PointNavDatasetV1.check_config_paths_exist to verify the dataset data path and scenes directory exist', 'call PointNavDatasetV1.get_scenes_to_load to return a list of scene IDs available in the dataset', 'call PointNavDatasetV1.from_json to parse a JSON string into NavigationEpisode objects with goals and shortest paths', 'call PointNavDatasetV1._get_scenes_from_folder to list scene names from a content directory by file extension', 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity ratio', 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create a NavigationEpisode object with start position, rotation, target goal, and optional shortest paths', 'calculate the aggressive rejection sampling rate for episodes with low geodesic to Euclidean distance ratio', 'review the generate_pointnav_episode generator function for navigation complexity filtering and rejection sampling logic']
```

Usage

```
{'generate_pointnav_episodes': 'generate PointNav navigation episodes for a HabitatSim simulator with configurable distance limits and complexity ratio', 'check_compatible_episode': 'check if a start and target position pair forms a valid navigation episode within distance bounds', 'create_navigation_episode': 'create a NavigationEpisode object with start position, rotation, target goal, and optional shortest paths', 'calculate_ratio_sample_rate': 'calculate the aggressive rejection sampling rate for episodes with low geodesic to Euclidean distance ratio', 'review_generate_pointnav_episode': 'review the generate_pointnav_episode generator function for navigation complexity filtering and rejection sampling logic'}
```

