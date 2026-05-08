# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/voxel/feature/conceptfusion.py

Prompts

```
['build a ConceptFusion scene from image depth and pose observations to create a voxelized pointcloud map', 'query a ConceptFusion voxel map with text queries to retrieve 3D instances matching the description', 'generate per-region concept fusion features from SAM masks and CLIP global features for an image', 'cluster 3D point cloud data with DBSCAN and return bounding boxes around each detected cluster', 'save original images and SAM segmentation masks to disk for debugging ConceptFusion processing']
```

Usage

```
{'build_ConceptFusion_scene': 'build a ConceptFusion scene from image depth and pose observations to create a voxelized pointcloud map', 'query_ConceptFusion_instances': 'query a ConceptFusion voxel map with text queries to retrieve 3D instances matching the description', 'generate_ConceptFusion_local_features': 'generate per-region concept fusion features from SAM masks and CLIP global features for an image', 'cluster_get_bounding_boxes': 'cluster 3D point cloud data with DBSCAN and return bounding boxes around each detected cluster', 'save_ConceptFusion_input_data': 'save original images and SAM segmentation masks to disk for debugging ConceptFusion processing'}
```

