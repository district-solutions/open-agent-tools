# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projects/AriaSyntheticEnvironment/tutorial/code_snippets/interpreter.py

Prompts

```
['create a 3x3 rotation matrix for a given angle around the z-axis using z_rotation', 'convert a list of language entity commands and params into 3D bounding box definitions using language_to_bboxes', 'compute and print counts of each class in a list of bounding box dicts using _compute_counts', 'review the language_to_bboxes function that parses make_wall, make_door, and make_window commands into box definitions', 'summarize the CLASS_LABELS mapping of wall, door, and window class names to integer labels', 'plot a 3D scene with points, trajectory, and language entity bounding boxes from file paths', 'plot a 3D wireframe bounding box for a language entity with rotation, scale, and center', 'plot a 3D point cloud from numpy array points with optional subsampling for large datasets', 'plot a 3D device trajectory with connected line markers from timestamped position data', 'review the PLOTTING_COLORS dictionary mapping entity classes like wall, door, window to hex color codes', 'read an ASE language file and parse scene commands with entity parameters into a list of tuples', 'read a ground truth trajectory CSV file and return device poses with positions, rotations, and transforms', 'read a gzip-compressed semidense point cloud CSV file and return world coordinates as a numpy array', 'build a 4x4 homogeneous transformation matrix from a rotation matrix and translation vector', 'parse a single ground truth trajectory CSV line into a pose dictionary with position, rotation, and transform']
```

Usage

```
{'create_z_rotation_matrix': 'create a 3x3 rotation matrix for a given angle around the z-axis using z_rotation', 'convert_language_entities_to_bboxes': 'convert a list of language entity commands and params into 3D bounding box definitions using language_to_bboxes', 'compute_scene_class_counts': 'compute and print counts of each class in a list of bounding box dicts using _compute_counts', 'review_language_to_bboxes': 'review the language_to_bboxes function that parses make_wall, make_door, and make_window commands into box definitions', 'summarize_class_labels': 'summarize the CLASS_LABELS mapping of wall, door, and window class names to integer labels'}
```

## File: facebookresearch_projectariatools/projects/AriaSyntheticEnvironment/tutorial/code_snippets/plotters.py

Prompts

```
['create a 3x3 rotation matrix for a given angle around the z-axis using z_rotation', 'convert a list of language entity commands and params into 3D bounding box definitions using language_to_bboxes', 'compute and print counts of each class in a list of bounding box dicts using _compute_counts', 'review the language_to_bboxes function that parses make_wall, make_door, and make_window commands into box definitions', 'summarize the CLASS_LABELS mapping of wall, door, and window class names to integer labels', 'plot a 3D scene with points, trajectory, and language entity bounding boxes from file paths', 'plot a 3D wireframe bounding box for a language entity with rotation, scale, and center', 'plot a 3D point cloud from numpy array points with optional subsampling for large datasets', 'plot a 3D device trajectory with connected line markers from timestamped position data', 'review the PLOTTING_COLORS dictionary mapping entity classes like wall, door, window to hex color codes', 'read an ASE language file and parse scene commands with entity parameters into a list of tuples', 'read a ground truth trajectory CSV file and return device poses with positions, rotations, and transforms', 'read a gzip-compressed semidense point cloud CSV file and return world coordinates as a numpy array', 'build a 4x4 homogeneous transformation matrix from a rotation matrix and translation vector', 'parse a single ground truth trajectory CSV line into a pose dictionary with position, rotation, and transform']
```

Usage

```
{'plot_3d_scene': 'plot a 3D scene with points, trajectory, and language entity bounding boxes from file paths', 'plot_box_wireframe': 'plot a 3D wireframe bounding box for a language entity with rotation, scale, and center', 'plot_point_cloud': 'plot a 3D point cloud from numpy array points with optional subsampling for large datasets', 'plot_trajectory': 'plot a 3D device trajectory with connected line markers from timestamped position data', 'review_PLOTTING_COLORS': 'review the PLOTTING_COLORS dictionary mapping entity classes like wall, door, window to hex color codes'}
```

## File: facebookresearch_projectariatools/projects/AriaSyntheticEnvironment/tutorial/code_snippets/readers.py

Prompts

```
['create a 3x3 rotation matrix for a given angle around the z-axis using z_rotation', 'convert a list of language entity commands and params into 3D bounding box definitions using language_to_bboxes', 'compute and print counts of each class in a list of bounding box dicts using _compute_counts', 'review the language_to_bboxes function that parses make_wall, make_door, and make_window commands into box definitions', 'summarize the CLASS_LABELS mapping of wall, door, and window class names to integer labels', 'plot a 3D scene with points, trajectory, and language entity bounding boxes from file paths', 'plot a 3D wireframe bounding box for a language entity with rotation, scale, and center', 'plot a 3D point cloud from numpy array points with optional subsampling for large datasets', 'plot a 3D device trajectory with connected line markers from timestamped position data', 'review the PLOTTING_COLORS dictionary mapping entity classes like wall, door, window to hex color codes', 'read an ASE language file and parse scene commands with entity parameters into a list of tuples', 'read a ground truth trajectory CSV file and return device poses with positions, rotations, and transforms', 'read a gzip-compressed semidense point cloud CSV file and return world coordinates as a numpy array', 'build a 4x4 homogeneous transformation matrix from a rotation matrix and translation vector', 'parse a single ground truth trajectory CSV line into a pose dictionary with position, rotation, and transform']
```

Usage

```
{'read_language_file': 'read an ASE language file and parse scene commands with entity parameters into a list of tuples', 'read_trajectory_file': 'read a ground truth trajectory CSV file and return device poses with positions, rotations, and transforms', 'read_points_file': 'read a gzip-compressed semidense point cloud CSV file and return world coordinates as a numpy array', 'transform_from_Rt': 'build a 4x4 homogeneous transformation matrix from a rotation matrix and translation vector', 'read_trajectory_line': 'parse a single ground truth trajectory CSV line into a pose dictionary with position, rotation, and transform'}
```

