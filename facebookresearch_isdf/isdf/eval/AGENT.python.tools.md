# Agent Python Tools

- repo: facebookresearch/isdf
- repo_uri: https://github.com/facebookresearch/isdf

## File: facebookresearch_isdf/isdf/eval/eval_pts.py

Prompts

```
['run fixed_pts_eval to compute SDF and gradient metrics on fixed evaluation points for a given timestep', 'run sub_eval to compute L1 SDF error, binned losses, and chomp cost differences between predicted and ground truth SDF values', 'run eval_grad to compute numerical gradients of an SDF interpolation at given points using finite differences', 'run get_cache_dataset to create a SceneCache dataset from a sequence directory with depth and RGB transforms', 'run get_dirs_C to compute camera ray direction tensors for replicaCAD or ScanNet dataset formats', 'compute accuracy and completion metrics between two trimesh meshes by sampling their surfaces', 'calculate the completion ratio between ground truth and reconstructed point clouds using a distance threshold', 'compute the CHOMP collision cost from signed distance field samples along a trajectory', 'compute the aligned absolute trajectory error RMSE between two sets of poses', 'bin signed distance field prediction losses into distance-based bins for analysis', 'load a trained SDFMap model from a checkpoint file using a ground truth mesh and device', 'load and return the JSON results file from an experiment directory', 'load a ground truth signed distance field grid and create an interpolator from directory files', 'get a signed distance field interpolator from GpuFusion experiment output at a given evaluation time', 'get a signed distance field interpolator from VoxBloX experiment output using a ground truth mesh']
```

Usage

```
{'run_fixed_pts_eval': 'run fixed_pts_eval to compute SDF and gradient metrics on fixed evaluation points for a given timestep', 'run_sub_eval': 'run sub_eval to compute L1 SDF error, binned losses, and chomp cost differences between predicted and ground truth SDF values', 'run_eval_grad': 'run eval_grad to compute numerical gradients of an SDF interpolation at given points using finite differences', 'run_get_cache_dataset': 'run get_cache_dataset to create a SceneCache dataset from a sequence directory with depth and RGB transforms', 'run_get_dirs_C': 'run get_dirs_C to compute camera ray direction tensors for replicaCAD or ScanNet dataset formats'}
```

## File: facebookresearch_isdf/isdf/eval/metrics.py

Prompts

```
['run fixed_pts_eval to compute SDF and gradient metrics on fixed evaluation points for a given timestep', 'run sub_eval to compute L1 SDF error, binned losses, and chomp cost differences between predicted and ground truth SDF values', 'run eval_grad to compute numerical gradients of an SDF interpolation at given points using finite differences', 'run get_cache_dataset to create a SceneCache dataset from a sequence directory with depth and RGB transforms', 'run get_dirs_C to compute camera ray direction tensors for replicaCAD or ScanNet dataset formats', 'compute accuracy and completion metrics between two trimesh meshes by sampling their surfaces', 'calculate the completion ratio between ground truth and reconstructed point clouds using a distance threshold', 'compute the CHOMP collision cost from signed distance field samples along a trajectory', 'compute the aligned absolute trajectory error RMSE between two sets of poses', 'bin signed distance field prediction losses into distance-based bins for analysis', 'load a trained SDFMap model from a checkpoint file using a ground truth mesh and device', 'load and return the JSON results file from an experiment directory', 'load a ground truth signed distance field grid and create an interpolator from directory files', 'get a signed distance field interpolator from GpuFusion experiment output at a given evaluation time', 'get a signed distance field interpolator from VoxBloX experiment output using a ground truth mesh']
```

Usage

```
{'compute_accuracy_completion': 'compute accuracy and completion metrics between two trimesh meshes by sampling their surfaces', 'calculate_completion_ratio': 'calculate the completion ratio between ground truth and reconstructed point clouds using a distance threshold', 'compute_chomp_collision_cost': 'compute the CHOMP collision cost from signed distance field samples along a trajectory', 'compute_aligned_ate': 'compute the aligned absolute trajectory error RMSE between two sets of poses', 'bin_sdf_losses': 'bin signed distance field prediction losses into distance-based bins for analysis'}
```

## File: facebookresearch_isdf/isdf/eval/plot_utils.py

Prompts

```
['run fixed_pts_eval to compute SDF and gradient metrics on fixed evaluation points for a given timestep', 'run sub_eval to compute L1 SDF error, binned losses, and chomp cost differences between predicted and ground truth SDF values', 'run eval_grad to compute numerical gradients of an SDF interpolation at given points using finite differences', 'run get_cache_dataset to create a SceneCache dataset from a sequence directory with depth and RGB transforms', 'run get_dirs_C to compute camera ray direction tensors for replicaCAD or ScanNet dataset formats', 'compute accuracy and completion metrics between two trimesh meshes by sampling their surfaces', 'calculate the completion ratio between ground truth and reconstructed point clouds using a distance threshold', 'compute the CHOMP collision cost from signed distance field samples along a trajectory', 'compute the aligned absolute trajectory error RMSE between two sets of poses', 'bin signed distance field prediction losses into distance-based bins for analysis', 'load a trained SDFMap model from a checkpoint file using a ground truth mesh and device', 'load and return the JSON results file from an experiment directory', 'load a ground truth signed distance field grid and create an interpolator from directory files', 'get a signed distance field interpolator from GpuFusion experiment output at a given evaluation time', 'get a signed distance field interpolator from VoxBloX experiment output using a ground truth mesh']
```

Usage

```
{'load_model': 'load a trained SDFMap model from a checkpoint file using a ground truth mesh and device', 'load_res': 'load and return the JSON results file from an experiment directory', 'load_gt_sdf': 'load a ground truth signed distance field grid and create an interpolator from directory files', 'get_gpuf_sdf_interp': 'get a signed distance field interpolator from GpuFusion experiment output at a given evaluation time', 'get_voxblox_sdf_interp': 'get a signed distance field interpolator from VoxBloX experiment output using a ground truth mesh'}
```

