# Agent Python Tools

- repo: facebookresearch/detectandtrack
- repo_uri: https://github.com/facebookresearch/detectandtrack

## File: facebookresearch_detectandtrack/tools/test_net.py

Prompts

```
['run a Fast R-CNN network test on an image database using a config file and model weights', 'run test_net on a specific range of indices for parallel subprocess inference on a dataset', 'run multi-GPU testing on a Fast R-CNN network using cfg.NUM_GPUS for inference', 'run RPN-only model testing on a dataset to generate region proposals across multiple datasets', 'run network testing that auto-discovers model weights from the output directory if no weights are specified', 'run DetectandTrack on a single video with --cfg and --video flags to detect objects and track them', 'run the script to extract frames from a video into a temporary folder using _read_video', 'run 3D detection on consecutive video frames using the 3d config model for multi-frame detection', 'run LSTM-based tracking on video detections by enabling TRACKING.LSTM_TEST.LSTM_TRACKING_ON in the config', 'run visualization generation to produce annotated frames with bounding boxes, keypoints, and track IDs', 'train a detection network using a config file and optional command line options', 'create a detection model with automatic checkpoint resume from previous training iterations', 'run the training loop with logging, checkpointing, and NaN loss detection', 'test a trained detection model using saved weights and multi GPU inference', 'optimize model memory by sharing gradient blobs across GPUs using memonger', 'run the visualization tool with --cfg and --thresh to generate detection result images', 'run the vis function to visualize ground truth and predicted detections side by side', 'run _generate_visualizations to produce GT and predicted bounding box images for a single frame', 'run _convert_roidb_to_pred_boxes to append a confidence column to roidb bounding boxes', 'run _convert_roidb_to_pred_keyps to transform ground truth keypoints into visualization format']
```

Usage

```
{'run_test_fast_rcnn_network': 'run a Fast R-CNN network test on an image database using a config file and model weights', 'run_test_net_with_range': 'run test_net on a specific range of indices for parallel subprocess inference on a dataset', 'run_multi_gpu_testing': 'run multi-GPU testing on a Fast R-CNN network using cfg.NUM_GPUS for inference', 'run_rpn_only_testing': 'run RPN-only model testing on a dataset to generate region proposals across multiple datasets', 'run_test_with_auto_weights': 'run network testing that auto-discovers model weights from the output directory if no weights are specified'}
```

## File: facebookresearch_detectandtrack/tools/test_on_single_video.py

Prompts

```
['run a Fast R-CNN network test on an image database using a config file and model weights', 'run test_net on a specific range of indices for parallel subprocess inference on a dataset', 'run multi-GPU testing on a Fast R-CNN network using cfg.NUM_GPUS for inference', 'run RPN-only model testing on a dataset to generate region proposals across multiple datasets', 'run network testing that auto-discovers model weights from the output directory if no weights are specified', 'run DetectandTrack on a single video with --cfg and --video flags to detect objects and track them', 'run the script to extract frames from a video into a temporary folder using _read_video', 'run 3D detection on consecutive video frames using the 3d config model for multi-frame detection', 'run LSTM-based tracking on video detections by enabling TRACKING.LSTM_TEST.LSTM_TRACKING_ON in the config', 'run visualization generation to produce annotated frames with bounding boxes, keypoints, and track IDs', 'train a detection network using a config file and optional command line options', 'create a detection model with automatic checkpoint resume from previous training iterations', 'run the training loop with logging, checkpointing, and NaN loss detection', 'test a trained detection model using saved weights and multi GPU inference', 'optimize model memory by sharing gradient blobs across GPUs using memonger', 'run the visualization tool with --cfg and --thresh to generate detection result images', 'run the vis function to visualize ground truth and predicted detections side by side', 'run _generate_visualizations to produce GT and predicted bounding box images for a single frame', 'run _convert_roidb_to_pred_boxes to append a confidence column to roidb bounding boxes', 'run _convert_roidb_to_pred_keyps to transform ground truth keypoints into visualization format']
```

Usage

```
{'run_detectandtrack_on_video': 'run DetectandTrack on a single video with --cfg and --video flags to detect objects and track them', 'run_video_frame_extraction': 'run the script to extract frames from a video into a temporary folder using _read_video', 'run_3d_detection': 'run 3D detection on consecutive video frames using the 3d config model for multi-frame detection', 'run_lstm_tracking': 'run LSTM-based tracking on video detections by enabling TRACKING.LSTM_TEST.LSTM_TRACKING_ON in the config', 'run_visualization_generation': 'run visualization generation to produce annotated frames with bounding boxes, keypoints, and track IDs'}
```

## File: facebookresearch_detectandtrack/tools/train_net.py

Prompts

```
['run a Fast R-CNN network test on an image database using a config file and model weights', 'run test_net on a specific range of indices for parallel subprocess inference on a dataset', 'run multi-GPU testing on a Fast R-CNN network using cfg.NUM_GPUS for inference', 'run RPN-only model testing on a dataset to generate region proposals across multiple datasets', 'run network testing that auto-discovers model weights from the output directory if no weights are specified', 'run DetectandTrack on a single video with --cfg and --video flags to detect objects and track them', 'run the script to extract frames from a video into a temporary folder using _read_video', 'run 3D detection on consecutive video frames using the 3d config model for multi-frame detection', 'run LSTM-based tracking on video detections by enabling TRACKING.LSTM_TEST.LSTM_TRACKING_ON in the config', 'run visualization generation to produce annotated frames with bounding boxes, keypoints, and track IDs', 'train a detection network using a config file and optional command line options', 'create a detection model with automatic checkpoint resume from previous training iterations', 'run the training loop with logging, checkpointing, and NaN loss detection', 'test a trained detection model using saved weights and multi GPU inference', 'optimize model memory by sharing gradient blobs across GPUs using memonger', 'run the visualization tool with --cfg and --thresh to generate detection result images', 'run the vis function to visualize ground truth and predicted detections side by side', 'run _generate_visualizations to produce GT and predicted bounding box images for a single frame', 'run _convert_roidb_to_pred_boxes to append a confidence column to roidb bounding boxes', 'run _convert_roidb_to_pred_keyps to transform ground truth keypoints into visualization format']
```

Usage

```
{'train_detection_network': 'train a detection network using a config file and optional command line options', 'create_model_with_resume': 'create a detection model with automatic checkpoint resume from previous training iterations', 'run_training_loop': 'run the training loop with logging, checkpointing, and NaN loss detection', 'test_trained_model': 'test a trained detection model using saved weights and multi GPU inference', 'optimize_model_memory': 'optimize model memory by sharing gradient blobs across GPUs using memonger'}
```

## File: facebookresearch_detectandtrack/tools/visualize_results_v2.py

Prompts

```
['run a Fast R-CNN network test on an image database using a config file and model weights', 'run test_net on a specific range of indices for parallel subprocess inference on a dataset', 'run multi-GPU testing on a Fast R-CNN network using cfg.NUM_GPUS for inference', 'run RPN-only model testing on a dataset to generate region proposals across multiple datasets', 'run network testing that auto-discovers model weights from the output directory if no weights are specified', 'run DetectandTrack on a single video with --cfg and --video flags to detect objects and track them', 'run the script to extract frames from a video into a temporary folder using _read_video', 'run 3D detection on consecutive video frames using the 3d config model for multi-frame detection', 'run LSTM-based tracking on video detections by enabling TRACKING.LSTM_TEST.LSTM_TRACKING_ON in the config', 'run visualization generation to produce annotated frames with bounding boxes, keypoints, and track IDs', 'train a detection network using a config file and optional command line options', 'create a detection model with automatic checkpoint resume from previous training iterations', 'run the training loop with logging, checkpointing, and NaN loss detection', 'test a trained detection model using saved weights and multi GPU inference', 'optimize model memory by sharing gradient blobs across GPUs using memonger', 'run the visualization tool with --cfg and --thresh to generate detection result images', 'run the vis function to visualize ground truth and predicted detections side by side', 'run _generate_visualizations to produce GT and predicted bounding box images for a single frame', 'run _convert_roidb_to_pred_boxes to append a confidence column to roidb bounding boxes', 'run _convert_roidb_to_pred_keyps to transform ground truth keypoints into visualization format']
```

Usage

```
{'run_visualize_results': 'run the visualization tool with --cfg and --thresh to generate detection result images', 'run_vis_function': 'run the vis function to visualize ground truth and predicted detections side by side', 'run_generate_visualizations': 'run _generate_visualizations to produce GT and predicted bounding box images for a single frame', 'run_convert_roidb_to_pred_boxes': 'run _convert_roidb_to_pred_boxes to append a confidence column to roidb bounding boxes', 'run_convert_roidb_to_pred_keyps': 'run _convert_roidb_to_pred_keyps to transform ground truth keypoints into visualization format'}
```

