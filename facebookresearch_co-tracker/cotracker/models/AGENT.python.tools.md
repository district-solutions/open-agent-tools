# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/cotracker/models/bootstap_predictor.py

Prompts

```
['create a TAPIRPredictor instance with bootstap mode enabled to load the bootstapir checkpoint model', 'run the TAPIRPredictor forward pass on video RGB frames with query points to get tracks and visibility', 'postprocess occlusion and expected distance tensors to compute a binary visibility mask for tracked points', 'review the TAPIRPredictor class init to understand how it loads standard or bootstap TAPIR checkpoints', 'refactor the TAPIRPredictor forward method to support variable interpolation shapes instead of hardcoded 256x256', 'build a CoTracker3 offline model with default window length of 16 frames', 'build a CoTracker3 online model for real-time point tracking with configurable window length', 'build a CoTracker2 model with stride 4 and a custom window length', 'build a CoTracker model and load pretrained weights from a checkpoint file', 'review the build_cotracker factory function that constructs CoTracker2 or CoTracker3 models', 'create an EvaluationPredictor instance wrapping a CoTrackerThreeOffline model with configurable grid and SIFT sampling options', 'run the EvaluationPredictor forward pass on a video tensor and query points to get trajectory and visibility predictions', 'process a single query point through the model using the _process_one_point method with local grid augmentation', 'configure the EvaluationPredictor with grid_size and local_grid_size parameters for grid-based point sampling during tracking', 'configure the EvaluationPredictor with sift_size and num_uniformly_sampled_pts parameters for SIFT and uniform point sampling']
```

Usage

```
{'create_TAPIRPredictor': 'create a TAPIRPredictor instance with bootstap mode enabled to load the bootstapir checkpoint model', 'run_forward_tracking': 'run the TAPIRPredictor forward pass on video RGB frames with query points to get tracks and visibility', 'postprocess_occlusions': 'postprocess occlusion and expected distance tensors to compute a binary visibility mask for tracked points', 'review_TAPIRPredictor_init': 'review the TAPIRPredictor class init to understand how it loads standard or bootstap TAPIR checkpoints', 'refactor_forward_interpolation': 'refactor the TAPIRPredictor forward method to support variable interpolation shapes instead of hardcoded 256x256'}
```

## File: facebookresearch_co-tracker/cotracker/models/build_cotracker.py

Prompts

```
['create a TAPIRPredictor instance with bootstap mode enabled to load the bootstapir checkpoint model', 'run the TAPIRPredictor forward pass on video RGB frames with query points to get tracks and visibility', 'postprocess occlusion and expected distance tensors to compute a binary visibility mask for tracked points', 'review the TAPIRPredictor class init to understand how it loads standard or bootstap TAPIR checkpoints', 'refactor the TAPIRPredictor forward method to support variable interpolation shapes instead of hardcoded 256x256', 'build a CoTracker3 offline model with default window length of 16 frames', 'build a CoTracker3 online model for real-time point tracking with configurable window length', 'build a CoTracker2 model with stride 4 and a custom window length', 'build a CoTracker model and load pretrained weights from a checkpoint file', 'review the build_cotracker factory function that constructs CoTracker2 or CoTracker3 models', 'create an EvaluationPredictor instance wrapping a CoTrackerThreeOffline model with configurable grid and SIFT sampling options', 'run the EvaluationPredictor forward pass on a video tensor and query points to get trajectory and visibility predictions', 'process a single query point through the model using the _process_one_point method with local grid augmentation', 'configure the EvaluationPredictor with grid_size and local_grid_size parameters for grid-based point sampling during tracking', 'configure the EvaluationPredictor with sift_size and num_uniformly_sampled_pts parameters for SIFT and uniform point sampling']
```

Usage

```
{'build_cotracker3_offline': 'build a CoTracker3 offline model with default window length of 16 frames', 'build_cotracker3_online': 'build a CoTracker3 online model for real-time point tracking with configurable window length', 'build_cotracker2': 'build a CoTracker2 model with stride 4 and a custom window length', 'load_checkpoint': 'build a CoTracker model and load pretrained weights from a checkpoint file', 'review_build_cotracker': 'review the build_cotracker factory function that constructs CoTracker2 or CoTracker3 models'}
```

## File: facebookresearch_co-tracker/cotracker/models/evaluation_predictor.py

Prompts

```
['create a TAPIRPredictor instance with bootstap mode enabled to load the bootstapir checkpoint model', 'run the TAPIRPredictor forward pass on video RGB frames with query points to get tracks and visibility', 'postprocess occlusion and expected distance tensors to compute a binary visibility mask for tracked points', 'review the TAPIRPredictor class init to understand how it loads standard or bootstap TAPIR checkpoints', 'refactor the TAPIRPredictor forward method to support variable interpolation shapes instead of hardcoded 256x256', 'build a CoTracker3 offline model with default window length of 16 frames', 'build a CoTracker3 online model for real-time point tracking with configurable window length', 'build a CoTracker2 model with stride 4 and a custom window length', 'build a CoTracker model and load pretrained weights from a checkpoint file', 'review the build_cotracker factory function that constructs CoTracker2 or CoTracker3 models', 'create an EvaluationPredictor instance wrapping a CoTrackerThreeOffline model with configurable grid and SIFT sampling options', 'run the EvaluationPredictor forward pass on a video tensor and query points to get trajectory and visibility predictions', 'process a single query point through the model using the _process_one_point method with local grid augmentation', 'configure the EvaluationPredictor with grid_size and local_grid_size parameters for grid-based point sampling during tracking', 'configure the EvaluationPredictor with sift_size and num_uniformly_sampled_pts parameters for SIFT and uniform point sampling']
```

Usage

```
{'create_evaluation_predictor': 'create an EvaluationPredictor instance wrapping a CoTrackerThreeOffline model with configurable grid and SIFT sampling options', 'run_evaluation_predictor_forward': 'run the EvaluationPredictor forward pass on a video tensor and query points to get trajectory and visibility predictions', 'process_single_point_tracking': 'process a single query point through the model using the _process_one_point method with local grid augmentation', 'configure_grid_sampling': 'configure the EvaluationPredictor with grid_size and local_grid_size parameters for grid-based point sampling during tracking', 'configure_sift_sampling': 'configure the EvaluationPredictor with sift_size and num_uniformly_sampled_pts parameters for SIFT and uniform point sampling'}
```

