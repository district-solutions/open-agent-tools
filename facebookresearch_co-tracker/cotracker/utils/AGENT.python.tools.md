# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/cotracker/utils/train_utils.py

Prompts

```
['create an evaluation dataloader for datasets like dynamic_replica, tapvid_davis, tapvid_kinetics, or kubric', 'build a training dataset combining kubric and dynamic_replica datasets with configurable augmentation and sampling', 'run evaluation on multiple dataloaders using an EvaluationPredictor and log metrics to TensorBoard', 'push training metrics to the Logger for periodic aggregation and TensorBoard scalar logging', 'handle USR1 signals on a Slurm cluster to requeue the current job and exit gracefully', 'create a Visualizer instance and call visualize to draw object tracking points and trajectories on video frames', 'read a video file from disk path and return stacked numpy array of frames using imageio', 'draw a colored circle at specified coordinates on a PIL image with configurable radius and alpha', 'draw a colored line between two coordinate points on a PIL image with configurable linewidth', 'save a tensor video as an MP4 file to disk using imageio with configurable FPS']
```

Usage

```
{'get_eval_dataloader': 'create an evaluation dataloader for datasets like dynamic_replica, tapvid_davis, tapvid_kinetics, or kubric', 'get_train_dataset': 'build a training dataset combining kubric and dynamic_replica datasets with configurable augmentation and sampling', 'run_test_eval': 'run evaluation on multiple dataloaders using an EvaluationPredictor and log metrics to TensorBoard', 'Logger_push': 'push training metrics to the Logger for periodic aggregation and TensorBoard scalar logging', 'sig_handler': 'handle USR1 signals on a Slurm cluster to requeue the current job and exit gracefully'}
```

## File: facebookresearch_co-tracker/cotracker/utils/visualizer.py

Prompts

```
['create an evaluation dataloader for datasets like dynamic_replica, tapvid_davis, tapvid_kinetics, or kubric', 'build a training dataset combining kubric and dynamic_replica datasets with configurable augmentation and sampling', 'run evaluation on multiple dataloaders using an EvaluationPredictor and log metrics to TensorBoard', 'push training metrics to the Logger for periodic aggregation and TensorBoard scalar logging', 'handle USR1 signals on a Slurm cluster to requeue the current job and exit gracefully', 'create a Visualizer instance and call visualize to draw object tracking points and trajectories on video frames', 'read a video file from disk path and return stacked numpy array of frames using imageio', 'draw a colored circle at specified coordinates on a PIL image with configurable radius and alpha', 'draw a colored line between two coordinate points on a PIL image with configurable linewidth', 'save a tensor video as an MP4 file to disk using imageio with configurable FPS']
```

Usage

```
{'visualize_tracks_on_video': 'create a Visualizer instance and call visualize to draw object tracking points and trajectories on video frames', 'read_video_from_path': 'read a video file from disk path and return stacked numpy array of frames using imageio', 'draw_circle_on_image': 'draw a colored circle at specified coordinates on a PIL image with configurable radius and alpha', 'draw_line_on_image': 'draw a colored line between two coordinate points on a PIL image with configurable linewidth', 'save_video_from_tensor': 'save a tensor video as an MP4 file to disk using imageio with configurable FPS'}
```

