# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/tools/deployment/mmdet2torchserve.py

Prompts

```
['convert an MMDetection model config and checkpoint to TorchServe MAR archive format', 'run the CLI tool to convert MMDetection models to TorchServe format with config and checkpoint', 'parse command line arguments for converting MMDetection models to TorchServe MAR format', 'review the mmdet2torchserve function that packages MMDetection models into TorchServe archives', 'refactor the mmdet2torchserve function to support additional model export options or handlers', 'initialize an MMdetHandler by loading a config file and checkpoint onto GPU or CPU', 'preprocess a list of base64 encoded images into OpenCV arrays for detection', 'run object detection inference on preprocessed images using the mmdet model', 'postprocess detection results to extract bounding boxes, labels, and scores above a threshold', 'review the MMdetHandler class and its initialize, preprocess, inference, and postprocess methods', 'test a detection model by comparing PyTorch results against TorchServe server predictions', 'run a function that converts TorchServe JSON output into a DetDataSample with bboxes, labels, and scores', 'run argument parsing for image, config, checkpoint, model name, inference address, device, and score threshold', 'test model initialization from config and checkpoint files using mmdet init_detector API', 'test single image inference using mmdet inference_detector and visualize results with VISUALIZERS']
```

Usage

```
{'convert_mmdet_to_torchserve': 'convert an MMDetection model config and checkpoint to TorchServe MAR archive format', 'run_mmdet2torchserve_cli': 'run the CLI tool to convert MMDetection models to TorchServe format with config and checkpoint', 'parse_args_mmdet2torchserve': 'parse command line arguments for converting MMDetection models to TorchServe MAR format', 'review_mmdet2torchserve': 'review the mmdet2torchserve function that packages MMDetection models into TorchServe archives', 'refactor_mmdet2torchserve': 'refactor the mmdet2torchserve function to support additional model export options or handlers'}
```

## File: facebookresearch_sapiens/det/tools/deployment/mmdet_handler.py

Prompts

```
['convert an MMDetection model config and checkpoint to TorchServe MAR archive format', 'run the CLI tool to convert MMDetection models to TorchServe format with config and checkpoint', 'parse command line arguments for converting MMDetection models to TorchServe MAR format', 'review the mmdet2torchserve function that packages MMDetection models into TorchServe archives', 'refactor the mmdet2torchserve function to support additional model export options or handlers', 'initialize an MMdetHandler by loading a config file and checkpoint onto GPU or CPU', 'preprocess a list of base64 encoded images into OpenCV arrays for detection', 'run object detection inference on preprocessed images using the mmdet model', 'postprocess detection results to extract bounding boxes, labels, and scores above a threshold', 'review the MMdetHandler class and its initialize, preprocess, inference, and postprocess methods', 'test a detection model by comparing PyTorch results against TorchServe server predictions', 'run a function that converts TorchServe JSON output into a DetDataSample with bboxes, labels, and scores', 'run argument parsing for image, config, checkpoint, model name, inference address, device, and score threshold', 'test model initialization from config and checkpoint files using mmdet init_detector API', 'test single image inference using mmdet inference_detector and visualize results with VISUALIZERS']
```

Usage

```
{'initialize_mmdet_handler': 'initialize an MMdetHandler by loading a config file and checkpoint onto GPU or CPU', 'preprocess_base64_images': 'preprocess a list of base64 encoded images into OpenCV arrays for detection', 'run_object_detection_inference': 'run object detection inference on preprocessed images using the mmdet model', 'postprocess_detection_results': 'postprocess detection results to extract bounding boxes, labels, and scores above a threshold', 'review_mmdet_handler_class': 'review the MMdetHandler class and its initialize, preprocess, inference, and postprocess methods'}
```

## File: facebookresearch_sapiens/det/tools/deployment/test_torchserver.py

Prompts

```
['convert an MMDetection model config and checkpoint to TorchServe MAR archive format', 'run the CLI tool to convert MMDetection models to TorchServe format with config and checkpoint', 'parse command line arguments for converting MMDetection models to TorchServe MAR format', 'review the mmdet2torchserve function that packages MMDetection models into TorchServe archives', 'refactor the mmdet2torchserve function to support additional model export options or handlers', 'initialize an MMdetHandler by loading a config file and checkpoint onto GPU or CPU', 'preprocess a list of base64 encoded images into OpenCV arrays for detection', 'run object detection inference on preprocessed images using the mmdet model', 'postprocess detection results to extract bounding boxes, labels, and scores above a threshold', 'review the MMdetHandler class and its initialize, preprocess, inference, and postprocess methods', 'test a detection model by comparing PyTorch results against TorchServe server predictions', 'run a function that converts TorchServe JSON output into a DetDataSample with bboxes, labels, and scores', 'run argument parsing for image, config, checkpoint, model name, inference address, device, and score threshold', 'test model initialization from config and checkpoint files using mmdet init_detector API', 'test single image inference using mmdet inference_detector and visualize results with VISUALIZERS']
```

Usage

```
{'test_torchserver_inference': 'test a detection model by comparing PyTorch results against TorchServe server predictions', 'run_align_ts_output': 'run a function that converts TorchServe JSON output into a DetDataSample with bboxes, labels, and scores', 'run_parse_args': 'run argument parsing for image, config, checkpoint, model name, inference address, device, and score threshold', 'test_init_detector': 'test model initialization from config and checkpoint files using mmdet init_detector API', 'test_inference_detector': 'test single image inference using mmdet inference_detector and visualize results with VISUALIZERS'}
```

