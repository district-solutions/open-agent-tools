# Agent Python Tools

- repo: facebookresearch/habitat-matterport3d-dataset
- repo_uri: https://github.com/facebookresearch/habitat-matterport3d-dataset

## File: facebookresearch_habitat-matterport3d-dataset/scale_comparison/compute_scene_metrics.py

Prompts

```
['run the CLI to compute navigable area, navigation complexity, scene clutter, and floor area metrics for 3D scene files', 'run the script with --dataset-root to compute all valid metrics across a dataset of GLB scene files using multiprocessing', 'run the script with --metrics to compute a single metric like navigable_area for all scenes in the dataset root', 'run the script with --save-path to compute scene metrics and export results as a CSV file', 'run the script with --filter-scenes to compute metrics only on a filtered subset of scenes from the dataset', 'compute the total navigable area in square meters for a habitat simulator scene using the pathfinder', 'compute the navigation complexity ratio of geodesic to euclidean distances between random navigable point pairs', 'compute the scene clutter ratio by measuring mesh area within a threshold distance of navigable regions', 'compute the total floor area as the 2D convex hull of navigable locations across all floors', 'compute the geodesic distance between two 3D points using the habitat simulator pathfinder shortest path']
```

Usage

```
{'run_compute_scene_metrics': 'run the CLI to compute navigable area, navigation complexity, scene clutter, and floor area metrics for 3D scene files', 'run_compute_metrics_for_dataset': 'run the script with --dataset-root to compute all valid metrics across a dataset of GLB scene files using multiprocessing', 'run_compute_single_metric': 'run the script with --metrics to compute a single metric like navigable_area for all scenes in the dataset root', 'run_save_metrics_to_csv': 'run the script with --save-path to compute scene metrics and export results as a CSV file', 'run_compute_metrics_with_filter': 'run the script with --filter-scenes to compute metrics only on a filtered subset of scenes from the dataset'}
```

## File: facebookresearch_habitat-matterport3d-dataset/scale_comparison/metrics.py

Prompts

```
['run the CLI to compute navigable area, navigation complexity, scene clutter, and floor area metrics for 3D scene files', 'run the script with --dataset-root to compute all valid metrics across a dataset of GLB scene files using multiprocessing', 'run the script with --metrics to compute a single metric like navigable_area for all scenes in the dataset root', 'run the script with --save-path to compute scene metrics and export results as a CSV file', 'run the script with --filter-scenes to compute metrics only on a filtered subset of scenes from the dataset', 'compute the total navigable area in square meters for a habitat simulator scene using the pathfinder', 'compute the navigation complexity ratio of geodesic to euclidean distances between random navigable point pairs', 'compute the scene clutter ratio by measuring mesh area within a threshold distance of navigable regions', 'compute the total floor area as the 2D convex hull of navigable locations across all floors', 'compute the geodesic distance between two 3D points using the habitat simulator pathfinder shortest path']
```

Usage

```
{'compute_navigable_area': 'compute the total navigable area in square meters for a habitat simulator scene using the pathfinder', 'compute_navigation_complexity': 'compute the navigation complexity ratio of geodesic to euclidean distances between random navigable point pairs', 'compute_scene_clutter': 'compute the scene clutter ratio by measuring mesh area within a threshold distance of navigable regions', 'compute_floor_area': 'compute the total floor area as the 2D convex hull of navigable locations across all floors', 'get_geodesic_distance': 'compute the geodesic distance between two 3D points using the habitat simulator pathfinder shortest path'}
```

