# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/croco/datasets/habitat_sim/generate_from_metadata.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file with scene poses', 'generate color and depth images for a scene by rendering viewpoints from metadata poses', 'render a viewpoint using MultiviewHabitatSimGenerator with a position and quaternion orientation', 'save depth images as EXR files and camera intrinsics as JSON alongside color images', 'override specific metadata parameters when generating multiview images from a metadata file', 'generate tuples of overlapping views for a given 3D scene with optional depth and camera parameters', 'list commandlines to generate multiview images for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with configurable depth and exist_ok options', 'resume interrupted multiview image generation from the last saved metadata.json checkpoint file', 'create a MultiviewHabitatSimGenerator instance to generate multiview observations from a Habitat-Sim scene with configurable resolution and views count', 'compute a 3D point cloud from a depth map using camera intrinsics and pose parameters', 'compute overlapping metrics between two point clouds using a distance threshold and nearest neighbor search', 'generate a spiral trajectory of images from a random starting point in a Habitat-Sim scene for visualization', 'compute camera pose in OpenCV convention from a camera position and quaternion orientation', 'list all .glb scene files recursively in a directory and return SceneData tuples with paths', 'list all available Habitat-Sim scenes across HM3D, Gibson, ScanNet, Replica, and ReplicaCAD datasets', 'list ReplicaCAD apartment scenes with navmesh paths and output directories', 'list ReplicaCAD baked lighting scenes with 105 staging scene configurations', 'list Replica dataset scenes by scanning directories for mesh.ply and navmesh files']
```

Usage

```
{'run_generate_multiview_images': 'run the script to generate multiview images from a metadata JSON file with scene poses', 'generate_multiview_images_from_metadata': 'generate color and depth images for a scene by rendering viewpoints from metadata poses', 'render_viewpoint_with_generator': 'render a viewpoint using MultiviewHabitatSimGenerator with a position and quaternion orientation', 'save_depth_and_camera_params': 'save depth images as EXR files and camera intrinsics as JSON alongside color images', 'overload_metadata_params': 'override specific metadata parameters when generating multiview images from a metadata file'}
```

## File: facebookresearch_fast3r/fast3r/croco/datasets/habitat_sim/generate_multiview_images.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file with scene poses', 'generate color and depth images for a scene by rendering viewpoints from metadata poses', 'render a viewpoint using MultiviewHabitatSimGenerator with a position and quaternion orientation', 'save depth images as EXR files and camera intrinsics as JSON alongside color images', 'override specific metadata parameters when generating multiview images from a metadata file', 'generate tuples of overlapping views for a given 3D scene with optional depth and camera parameters', 'list commandlines to generate multiview images for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with configurable depth and exist_ok options', 'resume interrupted multiview image generation from the last saved metadata.json checkpoint file', 'create a MultiviewHabitatSimGenerator instance to generate multiview observations from a Habitat-Sim scene with configurable resolution and views count', 'compute a 3D point cloud from a depth map using camera intrinsics and pose parameters', 'compute overlapping metrics between two point clouds using a distance threshold and nearest neighbor search', 'generate a spiral trajectory of images from a random starting point in a Habitat-Sim scene for visualization', 'compute camera pose in OpenCV convention from a camera position and quaternion orientation', 'list all .glb scene files recursively in a directory and return SceneData tuples with paths', 'list all available Habitat-Sim scenes across HM3D, Gibson, ScanNet, Replica, and ReplicaCAD datasets', 'list ReplicaCAD apartment scenes with navmesh paths and output directories', 'list ReplicaCAD baked lighting scenes with 105 staging scene configurations', 'list Replica dataset scenes by scanning directories for mesh.ply and navmesh files']
```

Usage

```
{'generate_multiview_images_for_scene': 'generate tuples of overlapping views for a given 3D scene with optional depth and camera parameters', 'run_generate_multiview_images': 'run the script to generate multiview images for a Habitat-Sim scene with color and depth output', 'list_scene_commands': 'list commandlines to generate multiview images for all available scenes using the --list_commands flag', 'create_commandline': 'create a commandline string to generate multiview images for a specific scene with configurable depth and exist_ok options', 'resume_generation': 'resume interrupted multiview image generation from the last saved metadata.json checkpoint file'}
```

## File: facebookresearch_fast3r/fast3r/croco/datasets/habitat_sim/multiview_habitat_sim_generator.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file with scene poses', 'generate color and depth images for a scene by rendering viewpoints from metadata poses', 'render a viewpoint using MultiviewHabitatSimGenerator with a position and quaternion orientation', 'save depth images as EXR files and camera intrinsics as JSON alongside color images', 'override specific metadata parameters when generating multiview images from a metadata file', 'generate tuples of overlapping views for a given 3D scene with optional depth and camera parameters', 'list commandlines to generate multiview images for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with configurable depth and exist_ok options', 'resume interrupted multiview image generation from the last saved metadata.json checkpoint file', 'create a MultiviewHabitatSimGenerator instance to generate multiview observations from a Habitat-Sim scene with configurable resolution and views count', 'compute a 3D point cloud from a depth map using camera intrinsics and pose parameters', 'compute overlapping metrics between two point clouds using a distance threshold and nearest neighbor search', 'generate a spiral trajectory of images from a random starting point in a Habitat-Sim scene for visualization', 'compute camera pose in OpenCV convention from a camera position and quaternion orientation', 'list all .glb scene files recursively in a directory and return SceneData tuples with paths', 'list all available Habitat-Sim scenes across HM3D, Gibson, ScanNet, Replica, and ReplicaCAD datasets', 'list ReplicaCAD apartment scenes with navmesh paths and output directories', 'list ReplicaCAD baked lighting scenes with 105 staging scene configurations', 'list Replica dataset scenes by scanning directories for mesh.ply and navmesh files']
```

Usage

```
{'generate_multiview_habitat_sim': 'create a MultiviewHabitatSimGenerator instance to generate multiview observations from a Habitat-Sim scene with configurable resolution and views count', 'compute_pointcloud_from_depth': 'compute a 3D point cloud from a depth map using camera intrinsics and pose parameters', 'compute_pointcloud_overlaps': 'compute overlapping metrics between two point clouds using a distance threshold and nearest neighbor search', 'generate_spiral_trajectory': 'generate a spiral trajectory of images from a random starting point in a Habitat-Sim scene for visualization', 'compute_camera_pose_opencv': 'compute camera pose in OpenCV convention from a camera position and quaternion orientation'}
```

## File: facebookresearch_fast3r/fast3r/croco/datasets/habitat_sim/paths.py

Prompts

```
['run the script to generate multiview images from a metadata JSON file with scene poses', 'generate color and depth images for a scene by rendering viewpoints from metadata poses', 'render a viewpoint using MultiviewHabitatSimGenerator with a position and quaternion orientation', 'save depth images as EXR files and camera intrinsics as JSON alongside color images', 'override specific metadata parameters when generating multiview images from a metadata file', 'generate tuples of overlapping views for a given 3D scene with optional depth and camera parameters', 'list commandlines to generate multiview images for all available scenes using the --list_commands flag', 'create a commandline string to generate multiview images for a specific scene with configurable depth and exist_ok options', 'resume interrupted multiview image generation from the last saved metadata.json checkpoint file', 'create a MultiviewHabitatSimGenerator instance to generate multiview observations from a Habitat-Sim scene with configurable resolution and views count', 'compute a 3D point cloud from a depth map using camera intrinsics and pose parameters', 'compute overlapping metrics between two point clouds using a distance threshold and nearest neighbor search', 'generate a spiral trajectory of images from a random starting point in a Habitat-Sim scene for visualization', 'compute camera pose in OpenCV convention from a camera position and quaternion orientation', 'list all .glb scene files recursively in a directory and return SceneData tuples with paths', 'list all available Habitat-Sim scenes across HM3D, Gibson, ScanNet, Replica, and ReplicaCAD datasets', 'list ReplicaCAD apartment scenes with navmesh paths and output directories', 'list ReplicaCAD baked lighting scenes with 105 staging scene configurations', 'list Replica dataset scenes by scanning directories for mesh.ply and navmesh files']
```

Usage

```
{'list_scenes': 'list all .glb scene files recursively in a directory and return SceneData tuples with paths', 'list_scenes_available': 'list all available Habitat-Sim scenes across HM3D, Gibson, ScanNet, Replica, and ReplicaCAD datasets', 'list_replicacad_scenes': 'list ReplicaCAD apartment scenes with navmesh paths and output directories', 'list_replica_cad_baked_lighting_scenes': 'list ReplicaCAD baked lighting scenes with 105 staging scene configurations', 'list_replica_scenes': 'list Replica dataset scenes by scanning directories for mesh.ply and navmesh files'}
```

