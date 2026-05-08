# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/util.py

Prompts

```
['read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a scene types text file and return a mapping dictionary from scene names to integers', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer value', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'create an Instance object from mesh vertex instances to extract label_id and vert_count', 'parse a ScanNet instance prediction file and return a dictionary of mask file paths with label and confidence']
```

Usage

```
{'read_label_mapping': 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read_scene_types_mapping': 'read a scene types text file and return a mapping dictionary from scene names to integers', 'visualize_label_image': 'create a colorized visualization image from a label array and save it to a file', 'visualize_instance_image': 'create a colorized visualization image from an instance segmentation array and save it to a file', 'represents_int': 'check if a given string can be safely converted to an integer value'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/util_3d.py

Prompts

```
['read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a scene types text file and return a mapping dictionary from scene names to integers', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer value', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'create an Instance object from mesh vertex instances to extract label_id and vert_count', 'parse a ScanNet instance prediction file and return a dictionary of mask file paths with label and confidence']
```

Usage

```
{'transform_3d_points': 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read_mesh_vertices_from_ply': 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export_instance_ids_for_eval': 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'create_instance_object': 'create an Instance object from mesh vertex instances to extract label_id and vert_count', 'parse_instance_prediction_file': 'parse a ScanNet instance prediction file and return a dictionary of mask file paths with label and confidence'}
```

