# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projectaria_tools/projects/ase/interpreter.py

Prompts

```
['convert a list of language entity commands and params into 3D bounding box definitions for walls, doors, and windows', 'compute a 3x3 rotation matrix for a given angle around the z-axis in radians', 'count and print the number of each class of bounding boxes in a scene', 'create a bounding box definition for a wall entity using corner coordinates, height, and thickness', 'create a bounding box definition for a door or window entity attached to an existing wall', 'read an ASE language file and parse entities with their parameters into a list of tuples', 'read a ground truth trajectory CSV file and return device poses and timestamps', 'read a semidense point cloud file and return world positions as a numpy array', 'parse a single ground truth trajectory CSV line into a pose with timestamp and SE3 transform', 'summarize the ASE readers module functions for loading language files, trajectories, and point clouds']
```

Usage

```
{'convert_language_entities_to_bounding_boxes': 'convert a list of language entity commands and params into 3D bounding box definitions for walls, doors, and windows', 'compute_z_rotation_matrix': 'compute a 3x3 rotation matrix for a given angle around the z-axis in radians', 'count_scene_classes': 'count and print the number of each class of bounding boxes in a scene', 'create_wall_bounding_box': 'create a bounding box definition for a wall entity using corner coordinates, height, and thickness', 'create_door_or_window_bounding_box': 'create a bounding box definition for a door or window entity attached to an existing wall'}
```

## File: facebookresearch_projectariatools/projectaria_tools/projects/ase/readers.py

Prompts

```
['convert a list of language entity commands and params into 3D bounding box definitions for walls, doors, and windows', 'compute a 3x3 rotation matrix for a given angle around the z-axis in radians', 'count and print the number of each class of bounding boxes in a scene', 'create a bounding box definition for a wall entity using corner coordinates, height, and thickness', 'create a bounding box definition for a door or window entity attached to an existing wall', 'read an ASE language file and parse entities with their parameters into a list of tuples', 'read a ground truth trajectory CSV file and return device poses and timestamps', 'read a semidense point cloud file and return world positions as a numpy array', 'parse a single ground truth trajectory CSV line into a pose with timestamp and SE3 transform', 'summarize the ASE readers module functions for loading language files, trajectories, and point clouds']
```

Usage

```
{'read_language_file': 'read an ASE language file and parse entities with their parameters into a list of tuples', 'read_trajectory_file': 'read a ground truth trajectory CSV file and return device poses and timestamps', 'read_points_file': 'read a semidense point cloud file and return world positions as a numpy array', 'parse_trajectory_line': 'parse a single ground truth trajectory CSV line into a pose with timestamp and SE3 transform', 'summarize_readers_module': 'summarize the ASE readers module functions for loading language files, trajectories, and point clouds'}
```

