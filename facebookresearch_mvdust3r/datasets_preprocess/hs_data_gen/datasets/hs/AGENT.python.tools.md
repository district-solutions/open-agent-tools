# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/datasets/hs/generate_from_metadata.py

Prompts

```
['generate multiview color and depth images from a metadata JSON file using Habitat-Sim', 'run the script with --metadata_filename and --output_dir to render scene images from metadata', 'render a viewpoint at a given position and orientation using MultiviewHabitatSimGenerator', 'save camera intrinsics and extrinsics as a JSON file alongside rendered depth images', 'override specific metadata parameters by passing an overload_params dictionary to the generation function', 'generate tuples of overlapping views with optional depth images and camera parameters for a Habitat-Sim scene', 'create a commandline string to generate multiview images for a given scene with depth and exist_ok flags', 'run the script with --list_commands to list all available scenes and their generation commandlines', 'run the script to generate multiview images for scenes from a saved scenes_data.pth file with div and mod filtering', 'review the generate_multiview_images_for_scene function to understand how it generates RGB and depth images with camera poses', 'create a MultiviewHabitatSimGenerator instance with a scene path, navmesh, and desired view count to generate multiview observations', 'call the generator by index to sample random viewpoints and return multiview observations with camera poses and covisibility ratios', 'compute a 3D point cloud from a depth map given hfov, camera position, and camera rotation', 'compute overlap metrics between two point clouds using a distance threshold and optional symmetric comparison', 'generate a spiral trajectory of images around a random viewpoint with configurable radius and half turns', 'create a function that walks a directory to find all .glb scene files and returns SceneData namedtuples', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets into a list', 'create a function that lists ReplicaCAD scene data with navmesh paths for 6 apartments and an empty stage', 'build a function that scans a Replica dataset directory and returns SceneData for each scene mesh', 'create a function that lists all baked lighting ReplicaCAD scenes with their config file and output paths']
```

Usage

```
{'generate_multiview_images_from_metadata': 'generate multiview color and depth images from a metadata JSON file using Habitat-Sim', 'run_generate_from_metadata_cli': 'run the script with --metadata_filename and --output_dir to render scene images from metadata', 'render_viewpoint_with_generator': 'render a viewpoint at a given position and orientation using MultiviewHabitatSimGenerator', 'save_camera_params_json': 'save camera intrinsics and extrinsics as a JSON file alongside rendered depth images', 'overload_metadata_params': 'override specific metadata parameters by passing an overload_params dictionary to the generation function'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/datasets/hs/generate_multiview_images.py

Prompts

```
['generate multiview color and depth images from a metadata JSON file using Habitat-Sim', 'run the script with --metadata_filename and --output_dir to render scene images from metadata', 'render a viewpoint at a given position and orientation using MultiviewHabitatSimGenerator', 'save camera intrinsics and extrinsics as a JSON file alongside rendered depth images', 'override specific metadata parameters by passing an overload_params dictionary to the generation function', 'generate tuples of overlapping views with optional depth images and camera parameters for a Habitat-Sim scene', 'create a commandline string to generate multiview images for a given scene with depth and exist_ok flags', 'run the script with --list_commands to list all available scenes and their generation commandlines', 'run the script to generate multiview images for scenes from a saved scenes_data.pth file with div and mod filtering', 'review the generate_multiview_images_for_scene function to understand how it generates RGB and depth images with camera poses', 'create a MultiviewHabitatSimGenerator instance with a scene path, navmesh, and desired view count to generate multiview observations', 'call the generator by index to sample random viewpoints and return multiview observations with camera poses and covisibility ratios', 'compute a 3D point cloud from a depth map given hfov, camera position, and camera rotation', 'compute overlap metrics between two point clouds using a distance threshold and optional symmetric comparison', 'generate a spiral trajectory of images around a random viewpoint with configurable radius and half turns', 'create a function that walks a directory to find all .glb scene files and returns SceneData namedtuples', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets into a list', 'create a function that lists ReplicaCAD scene data with navmesh paths for 6 apartments and an empty stage', 'build a function that scans a Replica dataset directory and returns SceneData for each scene mesh', 'create a function that lists all baked lighting ReplicaCAD scenes with their config file and output paths']
```

Usage

```
{'generate_multiview_images_for_scene': 'generate tuples of overlapping views with optional depth images and camera parameters for a Habitat-Sim scene', 'create_commandline': 'create a commandline string to generate multiview images for a given scene with depth and exist_ok flags', 'run_list_commands': 'run the script with --list_commands to list all available scenes and their generation commandlines', 'run_scene_generation': 'run the script to generate multiview images for scenes from a saved scenes_data.pth file with div and mod filtering', 'review_generate_multiview_images_for_scene': 'review the generate_multiview_images_for_scene function to understand how it generates RGB and depth images with camera poses'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/datasets/hs/multiview_habitat_sim_generator.py

Prompts

```
['generate multiview color and depth images from a metadata JSON file using Habitat-Sim', 'run the script with --metadata_filename and --output_dir to render scene images from metadata', 'render a viewpoint at a given position and orientation using MultiviewHabitatSimGenerator', 'save camera intrinsics and extrinsics as a JSON file alongside rendered depth images', 'override specific metadata parameters by passing an overload_params dictionary to the generation function', 'generate tuples of overlapping views with optional depth images and camera parameters for a Habitat-Sim scene', 'create a commandline string to generate multiview images for a given scene with depth and exist_ok flags', 'run the script with --list_commands to list all available scenes and their generation commandlines', 'run the script to generate multiview images for scenes from a saved scenes_data.pth file with div and mod filtering', 'review the generate_multiview_images_for_scene function to understand how it generates RGB and depth images with camera poses', 'create a MultiviewHabitatSimGenerator instance with a scene path, navmesh, and desired view count to generate multiview observations', 'call the generator by index to sample random viewpoints and return multiview observations with camera poses and covisibility ratios', 'compute a 3D point cloud from a depth map given hfov, camera position, and camera rotation', 'compute overlap metrics between two point clouds using a distance threshold and optional symmetric comparison', 'generate a spiral trajectory of images around a random viewpoint with configurable radius and half turns', 'create a function that walks a directory to find all .glb scene files and returns SceneData namedtuples', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets into a list', 'create a function that lists ReplicaCAD scene data with navmesh paths for 6 apartments and an empty stage', 'build a function that scans a Replica dataset directory and returns SceneData for each scene mesh', 'create a function that lists all baked lighting ReplicaCAD scenes with their config file and output paths']
```

Usage

```
{'create_multiview_generator': 'create a MultiviewHabitatSimGenerator instance with a scene path, navmesh, and desired view count to generate multiview observations', 'generate_multiview_observations': 'call the generator by index to sample random viewpoints and return multiview observations with camera poses and covisibility ratios', 'compute_pointcloud_from_depth': 'compute a 3D point cloud from a depth map given hfov, camera position, and camera rotation', 'compute_pointcloud_overlap': 'compute overlap metrics between two point clouds using a distance threshold and optional symmetric comparison', 'generate_spiral_trajectory': 'generate a spiral trajectory of images around a random viewpoint with configurable radius and half turns'}
```

## File: facebookresearch_mvdust3r/datasets_preprocess/hs_data_gen/datasets/hs/paths.py

Prompts

```
['generate multiview color and depth images from a metadata JSON file using Habitat-Sim', 'run the script with --metadata_filename and --output_dir to render scene images from metadata', 'render a viewpoint at a given position and orientation using MultiviewHabitatSimGenerator', 'save camera intrinsics and extrinsics as a JSON file alongside rendered depth images', 'override specific metadata parameters by passing an overload_params dictionary to the generation function', 'generate tuples of overlapping views with optional depth images and camera parameters for a Habitat-Sim scene', 'create a commandline string to generate multiview images for a given scene with depth and exist_ok flags', 'run the script with --list_commands to list all available scenes and their generation commandlines', 'run the script to generate multiview images for scenes from a saved scenes_data.pth file with div and mod filtering', 'review the generate_multiview_images_for_scene function to understand how it generates RGB and depth images with camera poses', 'create a MultiviewHabitatSimGenerator instance with a scene path, navmesh, and desired view count to generate multiview observations', 'call the generator by index to sample random viewpoints and return multiview observations with camera poses and covisibility ratios', 'compute a 3D point cloud from a depth map given hfov, camera position, and camera rotation', 'compute overlap metrics between two point clouds using a distance threshold and optional symmetric comparison', 'generate a spiral trajectory of images around a random viewpoint with configurable radius and half turns', 'create a function that walks a directory to find all .glb scene files and returns SceneData namedtuples', 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets into a list', 'create a function that lists ReplicaCAD scene data with navmesh paths for 6 apartments and an empty stage', 'build a function that scans a Replica dataset directory and returns SceneData for each scene mesh', 'create a function that lists all baked lighting ReplicaCAD scenes with their config file and output paths']
```

Usage

```
{'list_scenes': 'create a function that walks a directory to find all .glb scene files and returns SceneData namedtuples', 'list_scenes_available': 'build a module that aggregates all available Habitat-Sim scenes from HM3D and Gibson datasets into a list', 'list_replicacad_scenes': 'create a function that lists ReplicaCAD scene data with navmesh paths for 6 apartments and an empty stage', 'list_replica_scenes': 'build a function that scans a Replica dataset directory and returns SceneData for each scene mesh', 'list_replica_cad_baked_lighting_scenes': 'create a function that lists all baked lighting ReplicaCAD scenes with their config file and output paths'}
```

