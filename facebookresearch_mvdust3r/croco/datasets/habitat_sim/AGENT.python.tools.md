# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/croco/datasets/habitat_sim/generate_from_metadata.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate color JPEG images and depth EXR maps from camera poses in a metadata file', 'render viewpoint observations using MultiviewHabitatSimGenerator with specified positions and orientations', 'export camera intrinsics and extrinsics as JSON alongside generated depth images', 'review the generate_multiview_images_from_metadata function for path resolution and image generation logic', 'generate tuples of overlapping views for a given Habitat-Sim scene with optional depth and camera parameters', 'list commandlines to generate data for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with depth and exist_ok options', 'resume interrupted multiview image generation by re-running with the same output_dir and existing metadata.json', 'create a MultiviewHabitatSimGenerator instance to sample multiview RGB-D observations from a Habitat-Sim scene', 'generate a random spiral trajectory of images around a viewpoint using generate_random_spiral_trajectory', 'compute a 3D point cloud from a depth map using compute_pointcloud with camera pose', 'compute overlap metrics between two point clouds using compute_pointcloud_overlaps_scikit with a distance threshold', 'sample a random navigable viewpoint position and orientation using sample_random_viewpoint on the generator', 'create a python module that walks a directory to find all .glb scene files and their navmeshes', 'build a python module that aggregates all available Habitat-Sim scenes from HM3D, Gibson, ScanNet, and Replica datasets', 'create a function that lists ReplicaCAD apartment scenes with their navmesh paths and output directories', 'build a python module that lists all baked lighting ReplicaCAD scenes with their config file paths', 'create a function that scans a Replica dataset directory and returns scene mesh and navmesh paths']
```

Usage

```
{'run_generate_multiview_images': 'run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate_color_and_depth_images': 'generate color JPEG images and depth EXR maps from camera poses in a metadata file', 'render_viewpoint_with_generator': 'render viewpoint observations using MultiviewHabitatSimGenerator with specified positions and orientations', 'export_camera_parameters': 'export camera intrinsics and extrinsics as JSON alongside generated depth images', 'review_generate_from_metadata': 'review the generate_multiview_images_from_metadata function for path resolution and image generation logic'}
```

## File: facebookresearch_mvdust3r/croco/datasets/habitat_sim/generate_multiview_images.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate color JPEG images and depth EXR maps from camera poses in a metadata file', 'render viewpoint observations using MultiviewHabitatSimGenerator with specified positions and orientations', 'export camera intrinsics and extrinsics as JSON alongside generated depth images', 'review the generate_multiview_images_from_metadata function for path resolution and image generation logic', 'generate tuples of overlapping views for a given Habitat-Sim scene with optional depth and camera parameters', 'list commandlines to generate data for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with depth and exist_ok options', 'resume interrupted multiview image generation by re-running with the same output_dir and existing metadata.json', 'create a MultiviewHabitatSimGenerator instance to sample multiview RGB-D observations from a Habitat-Sim scene', 'generate a random spiral trajectory of images around a viewpoint using generate_random_spiral_trajectory', 'compute a 3D point cloud from a depth map using compute_pointcloud with camera pose', 'compute overlap metrics between two point clouds using compute_pointcloud_overlaps_scikit with a distance threshold', 'sample a random navigable viewpoint position and orientation using sample_random_viewpoint on the generator', 'create a python module that walks a directory to find all .glb scene files and their navmeshes', 'build a python module that aggregates all available Habitat-Sim scenes from HM3D, Gibson, ScanNet, and Replica datasets', 'create a function that lists ReplicaCAD apartment scenes with their navmesh paths and output directories', 'build a python module that lists all baked lighting ReplicaCAD scenes with their config file paths', 'create a function that scans a Replica dataset directory and returns scene mesh and navmesh paths']
```

Usage

```
{'generate_multiview_images_for_scene': 'generate tuples of overlapping views for a given Habitat-Sim scene with optional depth and camera parameters', 'run_generate_multiview_images': 'run the script with --scene and --output_dir flags to generate multiview image acquisitions for a 3D scene', 'list_commands_for_scenes': 'list commandlines to generate data for all available scenes using the --list_commands flag', 'create_commandline': 'create a commandline string to generate multiview images for a specific scene with depth and exist_ok options', 'resume_generation_from_metadata': 'resume interrupted multiview image generation by re-running with the same output_dir and existing metadata.json'}
```

## File: facebookresearch_mvdust3r/croco/datasets/habitat_sim/multiview_habitat_sim_generator.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate color JPEG images and depth EXR maps from camera poses in a metadata file', 'render viewpoint observations using MultiviewHabitatSimGenerator with specified positions and orientations', 'export camera intrinsics and extrinsics as JSON alongside generated depth images', 'review the generate_multiview_images_from_metadata function for path resolution and image generation logic', 'generate tuples of overlapping views for a given Habitat-Sim scene with optional depth and camera parameters', 'list commandlines to generate data for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with depth and exist_ok options', 'resume interrupted multiview image generation by re-running with the same output_dir and existing metadata.json', 'create a MultiviewHabitatSimGenerator instance to sample multiview RGB-D observations from a Habitat-Sim scene', 'generate a random spiral trajectory of images around a viewpoint using generate_random_spiral_trajectory', 'compute a 3D point cloud from a depth map using compute_pointcloud with camera pose', 'compute overlap metrics between two point clouds using compute_pointcloud_overlaps_scikit with a distance threshold', 'sample a random navigable viewpoint position and orientation using sample_random_viewpoint on the generator', 'create a python module that walks a directory to find all .glb scene files and their navmeshes', 'build a python module that aggregates all available Habitat-Sim scenes from HM3D, Gibson, ScanNet, and Replica datasets', 'create a function that lists ReplicaCAD apartment scenes with their navmesh paths and output directories', 'build a python module that lists all baked lighting ReplicaCAD scenes with their config file paths', 'create a function that scans a Replica dataset directory and returns scene mesh and navmesh paths']
```

Usage

```
{'create_multiview_generator': 'create a MultiviewHabitatSimGenerator instance to sample multiview RGB-D observations from a Habitat-Sim scene', 'generate_spiral_trajectory': 'generate a random spiral trajectory of images around a viewpoint using generate_random_spiral_trajectory', 'compute_pointcloud_from_depth': 'compute a 3D point cloud from a depth map using compute_pointcloud with camera pose', 'compute_pointcloud_overlaps': 'compute overlap metrics between two point clouds using compute_pointcloud_overlaps_scikit with a distance threshold', 'sample_random_viewpoint': 'sample a random navigable viewpoint position and orientation using sample_random_viewpoint on the generator'}
```

## File: facebookresearch_mvdust3r/croco/datasets/habitat_sim/paths.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file using Habitat-Sim', 'generate color JPEG images and depth EXR maps from camera poses in a metadata file', 'render viewpoint observations using MultiviewHabitatSimGenerator with specified positions and orientations', 'export camera intrinsics and extrinsics as JSON alongside generated depth images', 'review the generate_multiview_images_from_metadata function for path resolution and image generation logic', 'generate tuples of overlapping views for a given Habitat-Sim scene with optional depth and camera parameters', 'list commandlines to generate data for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with depth and exist_ok options', 'resume interrupted multiview image generation by re-running with the same output_dir and existing metadata.json', 'create a MultiviewHabitatSimGenerator instance to sample multiview RGB-D observations from a Habitat-Sim scene', 'generate a random spiral trajectory of images around a viewpoint using generate_random_spiral_trajectory', 'compute a 3D point cloud from a depth map using compute_pointcloud with camera pose', 'compute overlap metrics between two point clouds using compute_pointcloud_overlaps_scikit with a distance threshold', 'sample a random navigable viewpoint position and orientation using sample_random_viewpoint on the generator', 'create a python module that walks a directory to find all .glb scene files and their navmeshes', 'build a python module that aggregates all available Habitat-Sim scenes from HM3D, Gibson, ScanNet, and Replica datasets', 'create a function that lists ReplicaCAD apartment scenes with their navmesh paths and output directories', 'build a python module that lists all baked lighting ReplicaCAD scenes with their config file paths', 'create a function that scans a Replica dataset directory and returns scene mesh and navmesh paths']
```

Usage

```
{'list_scenes': 'create a python module that walks a directory to find all .glb scene files and their navmeshes', 'list_scenes_available': 'build a python module that aggregates all available Habitat-Sim scenes from HM3D, Gibson, ScanNet, and Replica datasets', 'list_replicacad_scenes': 'create a function that lists ReplicaCAD apartment scenes with their navmesh paths and output directories', 'list_replica_cad_baked_lighting_scenes': 'build a python module that lists all baked lighting ReplicaCAD scenes with their config file paths', 'list_replica_scenes': 'create a function that scans a Replica dataset directory and returns scene mesh and navmesh paths'}
```

