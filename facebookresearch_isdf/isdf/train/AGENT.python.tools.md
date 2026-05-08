# Agent Python Tools

- repo: facebookresearch/isdf
- repo_uri: https://github.com/facebookresearch/isdf

## File: facebookresearch_isdf/isdf/train/train.py

Prompts

```
['run the iSDF training loop with a config file via the CLI entry point', 'run the iSDF training loop in headless mode with no visualisations enabled', 'run the iSDF training loop with incremental SLAM enabled for keyframe selection', 'run the iSDF training loop and save checkpoints, slices, and meshes to disk', 'run the iSDF training loop with SDF and mesh evaluation against ground truth', 'run the iSDF training loop with an Open3D GUI visualization window using a JSON config file', 'run the iSDF incremental SLAM training with keyframe selection and real-time visualization', 'run the iSDF training in non-incremental mode by passing the --no_incremental flag', 'review the optim_iter callback function that handles keyframe addition and optimization steps', 'refactor the optim_iter function to use a different keyframe selection or resizing strategy']
```

Usage

```
{'run_isdf_training': 'run the iSDF training loop with a config file via the CLI entry point', 'run_isdf_headless': 'run the iSDF training loop in headless mode with no visualisations enabled', 'run_isdf_incremental': 'run the iSDF training loop with incremental SLAM enabled for keyframe selection', 'run_isdf_with_saving': 'run the iSDF training loop and save checkpoints, slices, and meshes to disk', 'run_isdf_with_evaluation': 'run the iSDF training loop with SDF and mesh evaluation against ground truth'}
```

## File: facebookresearch_isdf/isdf/train/train_vis.py

Prompts

```
['run the iSDF training loop with a config file via the CLI entry point', 'run the iSDF training loop in headless mode with no visualisations enabled', 'run the iSDF training loop with incremental SLAM enabled for keyframe selection', 'run the iSDF training loop and save checkpoints, slices, and meshes to disk', 'run the iSDF training loop with SDF and mesh evaluation against ground truth', 'run the iSDF training loop with an Open3D GUI visualization window using a JSON config file', 'run the iSDF incremental SLAM training with keyframe selection and real-time visualization', 'run the iSDF training in non-incremental mode by passing the --no_incremental flag', 'review the optim_iter callback function that handles keyframe addition and optimization steps', 'refactor the optim_iter function to use a different keyframe selection or resizing strategy']
```

Usage

```
{'run_isdf_training_visualization': 'run the iSDF training loop with an Open3D GUI visualization window using a JSON config file', 'run_isdf_incremental_slam': 'run the iSDF incremental SLAM training with keyframe selection and real-time visualization', 'run_isdf_non_incremental': 'run the iSDF training in non-incremental mode by passing the --no_incremental flag', 'review_optim_iter_callback': 'review the optim_iter callback function that handles keyframe addition and optimization steps', 'refactor_optim_iter_callback': 'refactor the optim_iter function to use a different keyframe selection or resizing strategy'}
```

