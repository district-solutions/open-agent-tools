# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/data/HIC/HIC.py

Prompts

```
['create a HIC PyTorch dataset instance with a transform and test data split for 3D hand mesh data', 'load HIC dataset annotations from a COCO JSON file into a datalist with image and MANO mesh paths', 'compute a 2D bounding box by projecting 3D mesh vertices into image space using camera intrinsics', 'evaluate predicted hand meshes against ground truth using MPVPE, MRRPE, RRVE, and bounding box IoU metrics', 'print aggregated evaluation results including bbox IoU, MRRPE, MPVPE for single and interacting hand sequences']
```

Usage

```
{'create_HIC_dataset': 'create a HIC PyTorch dataset instance with a transform and test data split for 3D hand mesh data', 'load_data_HIC': 'load HIC dataset annotations from a COCO JSON file into a datalist with image and MANO mesh paths', 'get_bbox_from_mesh_HIC': 'compute a 2D bounding box by projecting 3D mesh vertices into image space using camera intrinsics', 'evaluate_HIC': 'evaluate predicted hand meshes against ground truth using MPVPE, MRRPE, RRVE, and bounding box IoU metrics', 'print_eval_result_HIC': 'print aggregated evaluation results including bbox IoU, MRRPE, MPVPE for single and interacting hand sequences'}
```

