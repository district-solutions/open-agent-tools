# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/sav_dataset/utils/sav_benchmark.py

Prompts

```
['run the benchmark function to evaluate video object segmentation predictions against ground truth masks across datasets', "create a VideoEvaluator instance to evaluate a single video's predicted masks against ground truth masks", 'run the Evaluator class to feed frame-by-frame mask and ground truth pairs for IoU and boundary F-score computation', 'convert a segmentation mask to a binary boundary map using the _seg2bmap function for boundary analysis', 'compute the Intersection over Union score between two masks using the get_iou function with intersection and pixel sum', 'decode a video file and return RGB frames as a list of numpy arrays', 'show segmentation annotation masks with colored overlays and optional borders on the current matplotlib axis', 'create a SAVDataset instance to load and visualize the SAV dataset annotations with configurable sample rate', 'read video frames from an MP4 file and downsample them to align with annotations', 'visualize manual and auto annotations on a specific frame of a video using the SAVDataset class']
```

Usage

```
{'run_benchmark_evaluation': 'run the benchmark function to evaluate video object segmentation predictions against ground truth masks across datasets', 'create_video_evaluator': "create a VideoEvaluator instance to evaluate a single video's predicted masks against ground truth masks", 'run_evaluator_feed_frame': 'run the Evaluator class to feed frame-by-frame mask and ground truth pairs for IoU and boundary F-score computation', 'convert_segmentation_to_boundary_map': 'convert a segmentation mask to a binary boundary map using the _seg2bmap function for boundary analysis', 'compute_iou_score': 'compute the Intersection over Union score between two masks using the get_iou function with intersection and pixel sum'}
```

## File: facebookresearch_sam2/sav_dataset/utils/sav_utils.py

Prompts

```
['run the benchmark function to evaluate video object segmentation predictions against ground truth masks across datasets', "create a VideoEvaluator instance to evaluate a single video's predicted masks against ground truth masks", 'run the Evaluator class to feed frame-by-frame mask and ground truth pairs for IoU and boundary F-score computation', 'convert a segmentation mask to a binary boundary map using the _seg2bmap function for boundary analysis', 'compute the Intersection over Union score between two masks using the get_iou function with intersection and pixel sum', 'decode a video file and return RGB frames as a list of numpy arrays', 'show segmentation annotation masks with colored overlays and optional borders on the current matplotlib axis', 'create a SAVDataset instance to load and visualize the SAV dataset annotations with configurable sample rate', 'read video frames from an MP4 file and downsample them to align with annotations', 'visualize manual and auto annotations on a specific frame of a video using the SAVDataset class']
```

Usage

```
{'decode_video_frames': 'decode a video file and return RGB frames as a list of numpy arrays', 'show_annotation_masks': 'show segmentation annotation masks with colored overlays and optional borders on the current matplotlib axis', 'create_SAVDataset': 'create a SAVDataset instance to load and visualize the SAV dataset annotations with configurable sample rate', 'read_video_frames': 'read video frames from an MP4 file and downsample them to align with annotations', 'visualize_video_annotations': 'visualize manual and auto annotations on a specific frame of a video using the SAVDataset class'}
```

