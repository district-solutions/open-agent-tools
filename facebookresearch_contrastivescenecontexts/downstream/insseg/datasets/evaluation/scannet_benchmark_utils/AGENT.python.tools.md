# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/util.py

Prompts

```
['read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a scene types text file and return a mapping dictionary from scene names to IDs', 'colorize a semantic label image using a color palette and save it to a file', 'colorize an instance segmentation image with unique colors per instance and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance segmentation masks and labels for ScanNet benchmark evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract 3D mesh instances grouped by semantic class labels from vertex instance IDs']
```

Usage

```
{'read_label_mapping': 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read_scene_types_mapping': 'read a scene types text file and return a mapping dictionary from scene names to IDs', 'visualize_label_image': 'colorize a semantic label image using a color palette and save it to a file', 'visualize_instance_image': 'colorize an instance segmentation image with unique colors per instance and save it to a file', 'represents_int': 'check if a given string can be safely converted to an integer'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/util_3d.py

Prompts

```
['read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a scene types text file and return a mapping dictionary from scene names to IDs', 'colorize a semantic label image using a color palette and save it to a file', 'colorize an instance segmentation image with unique colors per instance and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance segmentation masks and labels for ScanNet benchmark evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract 3D mesh instances grouped by semantic class labels from vertex instance IDs']
```

Usage

```
{'transform_3d_points': 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read_mesh_vertices_from_ply': 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export_instance_masks_for_eval': 'export 3D instance segmentation masks and labels for ScanNet benchmark evaluation', 'parse_instance_prediction_file': 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract_instances_by_class': 'extract 3D mesh instances grouped by semantic class labels from vertex instance IDs'}
```

