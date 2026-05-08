# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/train/losses.py

Prompts

```
['build a FactoredGeometryRegr3D loss to compute regression on ray directions, depth, pose quats, and pose translations for multi-view 3D reconstruction', 'create a ConfLoss to apply confidence-weighted regression using model-predicted confidence values with configurable alpha regularization', 'build an ExcludeTopNPercentPixelLoss to ignore the top N percent of per-pixel loss values for robust training on real world data', 'create a DisentangledFactoredGeometryScaleRegr3D loss to isolate each factor contribution by constructing world-frame pointmaps from individual predicted factors', 'compute normal loss and gradient matching loss using compute_normal_loss and compute_gradient_matching_loss functions for monocular depth training', 'run the MapAnything dataloading profiler to measure data loading performance across training epochs', 'build a PyTorch DataLoader for training or testing with configurable batch size and workers', 'simulate one training epoch to profile data loading and device transfer operations', 'write profiling statistics to log files and TensorBoard for visualization and analysis', 'get the view name for a sample from the MapAnything base dataset', 'run the MapAnything training loop with distributed support across multiple epochs and datasets', 'run one epoch of training with gradient accumulation, loss scaling, and learning rate scheduling', 'run one epoch of evaluation on a test dataset and collect average and median metrics', 'save the final trained model checkpoint with args, state dict, and best validation metric']
```

Usage

```
{'build_factored_geometry_loss': 'build a FactoredGeometryRegr3D loss to compute regression on ray directions, depth, pose quats, and pose translations for multi-view 3D reconstruction', 'create_confidence_weighted_loss': 'create a ConfLoss to apply confidence-weighted regression using model-predicted confidence values with configurable alpha regularization', 'build_exclude_top_n_percent_loss': 'build an ExcludeTopNPercentPixelLoss to ignore the top N percent of per-pixel loss values for robust training on real world data', 'create_disentangled_factored_geometry_loss': 'create a DisentangledFactoredGeometryScaleRegr3D loss to isolate each factor contribution by constructing world-frame pointmaps from individual predicted factors', 'compute_normal_and_gradient_matching_loss': 'compute normal loss and gradient matching loss using compute_normal_loss and compute_gradient_matching_loss functions for monocular depth training'}
```

## File: facebookresearch_map-anything/mapanything/train/profile_dataloading.py

Prompts

```
['build a FactoredGeometryRegr3D loss to compute regression on ray directions, depth, pose quats, and pose translations for multi-view 3D reconstruction', 'create a ConfLoss to apply confidence-weighted regression using model-predicted confidence values with configurable alpha regularization', 'build an ExcludeTopNPercentPixelLoss to ignore the top N percent of per-pixel loss values for robust training on real world data', 'create a DisentangledFactoredGeometryScaleRegr3D loss to isolate each factor contribution by constructing world-frame pointmaps from individual predicted factors', 'compute normal loss and gradient matching loss using compute_normal_loss and compute_gradient_matching_loss functions for monocular depth training', 'run the MapAnything dataloading profiler to measure data loading performance across training epochs', 'build a PyTorch DataLoader for training or testing with configurable batch size and workers', 'simulate one training epoch to profile data loading and device transfer operations', 'write profiling statistics to log files and TensorBoard for visualization and analysis', 'get the view name for a sample from the MapAnything base dataset', 'run the MapAnything training loop with distributed support across multiple epochs and datasets', 'run one epoch of training with gradient accumulation, loss scaling, and learning rate scheduling', 'run one epoch of evaluation on a test dataset and collect average and median metrics', 'save the final trained model checkpoint with args, state dict, and best validation metric']
```

Usage

```
{'profile_dataloading': 'run the MapAnything dataloading profiler to measure data loading performance across training epochs', 'build_dataset': 'build a PyTorch DataLoader for training or testing with configurable batch size and workers', 'train_one_epoch': 'simulate one training epoch to profile data loading and device transfer operations', 'write_log_stats': 'write profiling statistics to log files and TensorBoard for visualization and analysis', 'view_name': 'get the view name for a sample from the MapAnything base dataset'}
```

## File: facebookresearch_map-anything/mapanything/train/training.py

Prompts

```
['build a FactoredGeometryRegr3D loss to compute regression on ray directions, depth, pose quats, and pose translations for multi-view 3D reconstruction', 'create a ConfLoss to apply confidence-weighted regression using model-predicted confidence values with configurable alpha regularization', 'build an ExcludeTopNPercentPixelLoss to ignore the top N percent of per-pixel loss values for robust training on real world data', 'create a DisentangledFactoredGeometryScaleRegr3D loss to isolate each factor contribution by constructing world-frame pointmaps from individual predicted factors', 'compute normal loss and gradient matching loss using compute_normal_loss and compute_gradient_matching_loss functions for monocular depth training', 'run the MapAnything dataloading profiler to measure data loading performance across training epochs', 'build a PyTorch DataLoader for training or testing with configurable batch size and workers', 'simulate one training epoch to profile data loading and device transfer operations', 'write profiling statistics to log files and TensorBoard for visualization and analysis', 'get the view name for a sample from the MapAnything base dataset', 'run the MapAnything training loop with distributed support across multiple epochs and datasets', 'run one epoch of training with gradient accumulation, loss scaling, and learning rate scheduling', 'run one epoch of evaluation on a test dataset and collect average and median metrics', 'save the final trained model checkpoint with args, state dict, and best validation metric']
```

Usage

```
{'run_train': 'run the MapAnything training loop with distributed support across multiple epochs and datasets', 'run_train_one_epoch': 'run one epoch of training with gradient accumulation, loss scaling, and learning rate scheduling', 'run_test_one_epoch': 'run one epoch of evaluation on a test dataset and collect average and median metrics', 'build_dataset': 'build a PyTorch DataLoader for training or testing with configurable batch size and workers', 'save_final_model': 'save the final trained model checkpoint with args, state dict, and best validation metric'}
```

