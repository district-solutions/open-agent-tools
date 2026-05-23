# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/apis/det_inferencer.py

Prompts

```
['build a python module to instantiate DetInferencer with a model config and checkpoint weights', 'run object detection inference on images using DetInferencer with text prompts for open detection', 'visualize detection predictions with bounding boxes and masks using DetInferencer visualize method', 'convert DetDataSample predictions to a json-serializable dictionary using the pred2dict method', 'load checkpoint weights and dataset metadata into a detection model using _load_weights_to_model', 'initialize a detector model from a config file and optional checkpoint weights on a given device', 'run object detection inference on one or more images using a loaded detector model', 'run asynchronous object detection inference on one or more images with a detector model', 'run multi-object tracking inference on a single video frame using a loaded MOT model', 'initialize a multi-object tracking model from a config file with optional detector and reid checkpoints']
```

Usage

```
{'build_det_inferencer': 'build a python module to instantiate DetInferencer with a model config and checkpoint weights', 'run_object_detection_inference': 'run object detection inference on images using DetInferencer with text prompts for open detection', 'visualize_detection_predictions': 'visualize detection predictions with bounding boxes and masks using DetInferencer visualize method', 'convert_predictions_to_dict': 'convert DetDataSample predictions to a json-serializable dictionary using the pred2dict method', 'load_weights_to_model': 'load checkpoint weights and dataset metadata into a detection model using _load_weights_to_model'}
```

## File: facebookresearch_sapiens/det/mmdet/apis/inference.py

Prompts

```
['build a python module to instantiate DetInferencer with a model config and checkpoint weights', 'run object detection inference on images using DetInferencer with text prompts for open detection', 'visualize detection predictions with bounding boxes and masks using DetInferencer visualize method', 'convert DetDataSample predictions to a json-serializable dictionary using the pred2dict method', 'load checkpoint weights and dataset metadata into a detection model using _load_weights_to_model', 'initialize a detector model from a config file and optional checkpoint weights on a given device', 'run object detection inference on one or more images using a loaded detector model', 'run asynchronous object detection inference on one or more images with a detector model', 'run multi-object tracking inference on a single video frame using a loaded MOT model', 'initialize a multi-object tracking model from a config file with optional detector and reid checkpoints']
```

Usage

```
{'init_detector': 'initialize a detector model from a config file and optional checkpoint weights on a given device', 'inference_detector': 'run object detection inference on one or more images using a loaded detector model', 'async_inference_detector': 'run asynchronous object detection inference on one or more images with a detector model', 'inference_mot': 'run multi-object tracking inference on a single video frame using a loaded MOT model', 'init_track_model': 'initialize a multi-object tracking model from a config file with optional detector and reid checkpoints'}
```

