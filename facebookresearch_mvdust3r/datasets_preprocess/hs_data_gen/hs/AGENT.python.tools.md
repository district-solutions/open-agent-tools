# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/hs/generate_from_metadata.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate JPEG color images for each viewpoint defined in a metadata file', 'generate EXR depth maps and camera parameters for each viewpoint in a metadata file', 'review the generate_multiview_images_from_metadata function that renders views using MultiviewHabitatSimGenerator', 'refactor the scene dataset path replacement logic to support custom dataset label mappings', 'generate tuples of overlapping RGB and depth views for a Habitat-Sim scene using MultiviewHabitatSimGenerator', 'run the CLI to generate multiview images for scenes from a JSON config with configurable resolution and covisibility', 'create a commandline string to invoke generate_multiview_images.py for a given scene with depth and exist_ok flags', 'initialize a Gloo-based distributed process group for multi-GPU multiview image generation across ranks', 'filter scene names by dataset split using is_train, is_val, is_hm3d, and is_mp3d helper functions', 'build a MultiviewHabitatSimGenerator instance with a scene path, navmesh, resolution, views count, and hfov to generate multiview observations', 'create a 3D point cloud from a depth map, hfov, camera position, and camera rotation using compute_pointcloud', 'test compute_pointcloud_overlaps_scikit to compute overlap metrics between two point clouds with a distance threshold', 'review the look_at function that returns a camera pose looking at a center point using OpenCV convention', 'summarize generate_random_spiral_trajectory which returns images along a spiral trajectory from a random starting point', 'create a function that walks a directory tree to find all .glb scene files and their navmeshes', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets', 'create a function that lists ReplicaCAD scene data with config files and navmesh paths', 'build a function that scans a base path to find Replica dataset scenes and navmeshes', 'create a function that lists ReplicaCAD baked lighting scenes with their dataset config']
```

Usage

```
{'run_generate_multiview_images': 'run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate_color_images_from_metadata': 'generate JPEG color images for each viewpoint defined in a metadata file', 'generate_depth_maps_from_metadata': 'generate EXR depth maps and camera parameters for each viewpoint in a metadata file', 'review_generate_multiview_images_from_metadata': 'review the generate_multiview_images_from_metadata function that renders views using MultiviewHabitatSimGenerator', 'refactor_path_replacement_logic': 'refactor the scene dataset path replacement logic to support custom dataset label mappings'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/hs/generate_multiview_images.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate JPEG color images for each viewpoint defined in a metadata file', 'generate EXR depth maps and camera parameters for each viewpoint in a metadata file', 'review the generate_multiview_images_from_metadata function that renders views using MultiviewHabitatSimGenerator', 'refactor the scene dataset path replacement logic to support custom dataset label mappings', 'generate tuples of overlapping RGB and depth views for a Habitat-Sim scene using MultiviewHabitatSimGenerator', 'run the CLI to generate multiview images for scenes from a JSON config with configurable resolution and covisibility', 'create a commandline string to invoke generate_multiview_images.py for a given scene with depth and exist_ok flags', 'initialize a Gloo-based distributed process group for multi-GPU multiview image generation across ranks', 'filter scene names by dataset split using is_train, is_val, is_hm3d, and is_mp3d helper functions', 'build a MultiviewHabitatSimGenerator instance with a scene path, navmesh, resolution, views count, and hfov to generate multiview observations', 'create a 3D point cloud from a depth map, hfov, camera position, and camera rotation using compute_pointcloud', 'test compute_pointcloud_overlaps_scikit to compute overlap metrics between two point clouds with a distance threshold', 'review the look_at function that returns a camera pose looking at a center point using OpenCV convention', 'summarize generate_random_spiral_trajectory which returns images along a spiral trajectory from a random starting point', 'create a function that walks a directory tree to find all .glb scene files and their navmeshes', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets', 'create a function that lists ReplicaCAD scene data with config files and navmesh paths', 'build a function that scans a base path to find Replica dataset scenes and navmeshes', 'create a function that lists ReplicaCAD baked lighting scenes with their dataset config']
```

Usage

```
{'generate_multiview_images_for_scene': 'generate tuples of overlapping RGB and depth views for a Habitat-Sim scene using MultiviewHabitatSimGenerator', 'run_cli_multiview_generation': 'run the CLI to generate multiview images for scenes from a JSON config with configurable resolution and covisibility', 'create_commandline': 'create a commandline string to invoke generate_multiview_images.py for a given scene with depth and exist_ok flags', 'init_distributed': 'initialize a Gloo-based distributed process group for multi-GPU multiview image generation across ranks', 'filter_scenes_by_split': 'filter scene names by dataset split using is_train, is_val, is_hm3d, and is_mp3d helper functions'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/hs/multiview_habitat_sim_generator.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate JPEG color images for each viewpoint defined in a metadata file', 'generate EXR depth maps and camera parameters for each viewpoint in a metadata file', 'review the generate_multiview_images_from_metadata function that renders views using MultiviewHabitatSimGenerator', 'refactor the scene dataset path replacement logic to support custom dataset label mappings', 'generate tuples of overlapping RGB and depth views for a Habitat-Sim scene using MultiviewHabitatSimGenerator', 'run the CLI to generate multiview images for scenes from a JSON config with configurable resolution and covisibility', 'create a commandline string to invoke generate_multiview_images.py for a given scene with depth and exist_ok flags', 'initialize a Gloo-based distributed process group for multi-GPU multiview image generation across ranks', 'filter scene names by dataset split using is_train, is_val, is_hm3d, and is_mp3d helper functions', 'build a MultiviewHabitatSimGenerator instance with a scene path, navmesh, resolution, views count, and hfov to generate multiview observations', 'create a 3D point cloud from a depth map, hfov, camera position, and camera rotation using compute_pointcloud', 'test compute_pointcloud_overlaps_scikit to compute overlap metrics between two point clouds with a distance threshold', 'review the look_at function that returns a camera pose looking at a center point using OpenCV convention', 'summarize generate_random_spiral_trajectory which returns images along a spiral trajectory from a random starting point', 'create a function that walks a directory tree to find all .glb scene files and their navmeshes', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets', 'create a function that lists ReplicaCAD scene data with config files and navmesh paths', 'build a function that scans a base path to find Replica dataset scenes and navmeshes', 'create a function that lists ReplicaCAD baked lighting scenes with their dataset config']
```

Usage

```
{'build_MultiviewHabitatSimGenerator': 'build a MultiviewHabitatSimGenerator instance with a scene path, navmesh, resolution, views count, and hfov to generate multiview observations', 'create_compute_pointcloud': 'create a 3D point cloud from a depth map, hfov, camera position, and camera rotation using compute_pointcloud', 'test_compute_pointcloud_overlaps_scikit': 'test compute_pointcloud_overlaps_scikit to compute overlap metrics between two point clouds with a distance threshold', 'review_look_at': 'review the look_at function that returns a camera pose looking at a center point using OpenCV convention', 'summarize_generate_random_spiral_trajectory': 'summarize generate_random_spiral_trajectory which returns images along a spiral trajectory from a random starting point'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/hs/paths.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate JPEG color images for each viewpoint defined in a metadata file', 'generate EXR depth maps and camera parameters for each viewpoint in a metadata file', 'review the generate_multiview_images_from_metadata function that renders views using MultiviewHabitatSimGenerator', 'refactor the scene dataset path replacement logic to support custom dataset label mappings', 'generate tuples of overlapping RGB and depth views for a Habitat-Sim scene using MultiviewHabitatSimGenerator', 'run the CLI to generate multiview images for scenes from a JSON config with configurable resolution and covisibility', 'create a commandline string to invoke generate_multiview_images.py for a given scene with depth and exist_ok flags', 'initialize a Gloo-based distributed process group for multi-GPU multiview image generation across ranks', 'filter scene names by dataset split using is_train, is_val, is_hm3d, and is_mp3d helper functions', 'build a MultiviewHabitatSimGenerator instance with a scene path, navmesh, resolution, views count, and hfov to generate multiview observations', 'create a 3D point cloud from a depth map, hfov, camera position, and camera rotation using compute_pointcloud', 'test compute_pointcloud_overlaps_scikit to compute overlap metrics between two point clouds with a distance threshold', 'review the look_at function that returns a camera pose looking at a center point using OpenCV convention', 'summarize generate_random_spiral_trajectory which returns images along a spiral trajectory from a random starting point', 'create a function that walks a directory tree to find all .glb scene files and their navmeshes', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets', 'create a function that lists ReplicaCAD scene data with config files and navmesh paths', 'build a function that scans a base path to find Replica dataset scenes and navmeshes', 'create a function that lists ReplicaCAD baked lighting scenes with their dataset config']
```

Usage

```
{'list_scenes': 'create a function that walks a directory tree to find all .glb scene files and their navmeshes', 'list_scenes_available': 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets', 'list_replicacad_scenes': 'create a function that lists ReplicaCAD scene data with config files and navmesh paths', 'list_replica_scenes': 'build a function that scans a base path to find Replica dataset scenes and navmeshes', 'list_replica_cad_baked_lighting_scenes': 'create a function that lists ReplicaCAD baked lighting scenes with their dataset config'}
```

