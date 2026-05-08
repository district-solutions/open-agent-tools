# Agent Python Tools

- repo: facebookresearch/interhand2.6m
- repo_uri: https://github.com/facebookresearch/interhand2.6m

## File: facebookresearch_interhand2.6m/tool/MANO_world_to_camera/convert.py

Prompts

```
['convert MANO mesh vertices from world coordinates to camera coordinates using camera extrinsic rotation and translation', 'convert MANO pose parameters from world to camera coordinates by multiplying camera rotation into the root pose', 'calculate the mean fitting error between MANO mesh joints and ground truth 3D joint coordinates in camera space', 'load InterHand2.6M MANO neural annotation, camera, and 3D joint JSON files for a given split', 'fix the left hand MANO shapedirs bug by negating the first shapedir column when it matches the right hand']
```

Usage

```
{'convert_mano_world_to_camera_mesh': 'convert MANO mesh vertices from world coordinates to camera coordinates using camera extrinsic rotation and translation', 'convert_mano_world_to_camera_params': 'convert MANO pose parameters from world to camera coordinates by multiplying camera rotation into the root pose', 'calculate_fitting_error': 'calculate the mean fitting error between MANO mesh joints and ground truth 3D joint coordinates in camera space', 'load_interhand_annotations': 'load InterHand2.6M MANO neural annotation, camera, and 3D joint JSON files for a given split', 'fix_mano_shapedirs_bug': 'fix the left hand MANO shapedirs bug by negating the first shapedir column when it matches the right hand'}
```

