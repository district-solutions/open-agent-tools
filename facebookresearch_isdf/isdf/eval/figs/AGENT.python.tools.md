# Agent Python Tools

- repo: facebookresearch/isdf
- repo_uri: https://github.com/facebookresearch/isdf

## File: facebookresearch_isdf/isdf/eval/figs/all_seq.py

Prompts

```
['run the main function to generate all sequence comparison plots for iSDF, Voxblox, and GPU fusion', 'plot iSDF evaluation results from vox_res.json files across multiple sequences with mean and std shading', 'plot Voxblox evaluation results including SDF error, collision cost, and gradient cosine distance metrics', 'plot GPU fusion evaluation results from vox_res.json files across multiple sequences', 'apply exponential moving average smoothing to a list of scalar values with a configurable weight', 'restructure evaluation results from a nested JSON dict into parallel lists of times, rays, bins, surface, and object L1 errors', 'plot SDF error metrics including rays, surface, binned loss, and object loss on a matplotlib axes grid with optional std bands', 'draw keyframe images from replicaCAD or ScanNet datasets onto a matplotlib figure subplot with time labels', 'generate and save per-sequence comparison plots for iSDF, KinectFusion+, and Voxblox SDF evaluation results as PNG files', 'run the per-sequence plotting script to generate SDF error comparison plots for ScanNet and replicaCAD sequences', 'compute SDF slice images from a predicted SDF function and ground truth SDF function for visualization', 'compute point cloud slices from a ground truth mesh for a given number of slices and dataset format', 'create a comparison panel of SDF slices across iSDF, VoxBloX, and GPU Fusion methods', 'create a side-by-side comparison panel of SDF slices across multiple sequences and reconstruction methods', 'compute a visibility mask for ScanNet sequences using depth images and camera trajectory']
```

Usage

```
{'run_main_plot_all_seqs': 'run the main function to generate all sequence comparison plots for iSDF, Voxblox, and GPU fusion', 'plot_isdf_results': 'plot iSDF evaluation results from vox_res.json files across multiple sequences with mean and std shading', 'plot_voxblox_results': 'plot Voxblox evaluation results including SDF error, collision cost, and gradient cosine distance metrics', 'plot_gpu_fusion_results': 'plot GPU fusion evaluation results from vox_res.json files across multiple sequences', 'ema_smooth_scalars': 'apply exponential moving average smoothing to a list of scalar values with a configurable weight'}
```

## File: facebookresearch_isdf/isdf/eval/figs/per_seq.py

Prompts

```
['run the main function to generate all sequence comparison plots for iSDF, Voxblox, and GPU fusion', 'plot iSDF evaluation results from vox_res.json files across multiple sequences with mean and std shading', 'plot Voxblox evaluation results including SDF error, collision cost, and gradient cosine distance metrics', 'plot GPU fusion evaluation results from vox_res.json files across multiple sequences', 'apply exponential moving average smoothing to a list of scalar values with a configurable weight', 'restructure evaluation results from a nested JSON dict into parallel lists of times, rays, bins, surface, and object L1 errors', 'plot SDF error metrics including rays, surface, binned loss, and object loss on a matplotlib axes grid with optional std bands', 'draw keyframe images from replicaCAD or ScanNet datasets onto a matplotlib figure subplot with time labels', 'generate and save per-sequence comparison plots for iSDF, KinectFusion+, and Voxblox SDF evaluation results as PNG files', 'run the per-sequence plotting script to generate SDF error comparison plots for ScanNet and replicaCAD sequences', 'compute SDF slice images from a predicted SDF function and ground truth SDF function for visualization', 'compute point cloud slices from a ground truth mesh for a given number of slices and dataset format', 'create a comparison panel of SDF slices across iSDF, VoxBloX, and GPU Fusion methods', 'create a side-by-side comparison panel of SDF slices across multiple sequences and reconstruction methods', 'compute a visibility mask for ScanNet sequences using depth images and camera trajectory']
```

Usage

```
{'restructure_res': 'restructure evaluation results from a nested JSON dict into parallel lists of times, rays, bins, surface, and object L1 errors', 'do_plot': 'plot SDF error metrics including rays, surface, binned loss, and object loss on a matplotlib axes grid with optional std bands', 'draw_keyframes': 'draw keyframe images from replicaCAD or ScanNet datasets onto a matplotlib figure subplot with time labels', 'save_plots': 'generate and save per-sequence comparison plots for iSDF, KinectFusion+, and Voxblox SDF evaluation results as PNG files', 'run_per_seq': 'run the per-sequence plotting script to generate SDF error comparison plots for ScanNet and replicaCAD sequences'}
```

## File: facebookresearch_isdf/isdf/eval/figs/slices.py

Prompts

```
['run the main function to generate all sequence comparison plots for iSDF, Voxblox, and GPU fusion', 'plot iSDF evaluation results from vox_res.json files across multiple sequences with mean and std shading', 'plot Voxblox evaluation results including SDF error, collision cost, and gradient cosine distance metrics', 'plot GPU fusion evaluation results from vox_res.json files across multiple sequences', 'apply exponential moving average smoothing to a list of scalar values with a configurable weight', 'restructure evaluation results from a nested JSON dict into parallel lists of times, rays, bins, surface, and object L1 errors', 'plot SDF error metrics including rays, surface, binned loss, and object loss on a matplotlib axes grid with optional std bands', 'draw keyframe images from replicaCAD or ScanNet datasets onto a matplotlib figure subplot with time labels', 'generate and save per-sequence comparison plots for iSDF, KinectFusion+, and Voxblox SDF evaluation results as PNG files', 'run the per-sequence plotting script to generate SDF error comparison plots for ScanNet and replicaCAD sequences', 'compute SDF slice images from a predicted SDF function and ground truth SDF function for visualization', 'compute point cloud slices from a ground truth mesh for a given number of slices and dataset format', 'create a comparison panel of SDF slices across iSDF, VoxBloX, and GPU Fusion methods', 'create a side-by-side comparison panel of SDF slices across multiple sequences and reconstruction methods', 'compute a visibility mask for ScanNet sequences using depth images and camera trajectory']
```

Usage

```
{'get_slices': 'compute SDF slice images from a predicted SDF function and ground truth SDF function for visualization', 'slices_pc': 'compute point cloud slices from a ground truth mesh for a given number of slices and dataset format', 'sdf_panel': 'create a comparison panel of SDF slices across iSDF, VoxBloX, and GPU Fusion methods', 'all_seqs_panel': 'create a side-by-side comparison panel of SDF slices across multiple sequences and reconstruction methods', 'mask_scannet_visible': 'compute a visibility mask for ScanNet sequences using depth images and camera trajectory'}
```

