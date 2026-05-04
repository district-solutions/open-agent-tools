# Agent Python Tools

- repo: facebookresearch/densepose
- repo_uri: https://github.com/facebookresearch/densepose

## File: facebookresearch_densepose/tools/infer.py

Prompts

```
['run inference on a single image using detectron models and output a visualization PDF', 'get region proposal network box proposals and scores from an input image', 'parse command line arguments for image inference including model pkl and config yaml pairs', 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes', 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run inference on images using a config YAML file and model weights pickle file', 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize a detectron model from a weights file using the config and cache URL utilities', 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize detection results by enabling the vis flag during network inference testing', 'train a Detectron network using a config file and optional command-line override options', 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'train a Detectron network and skip the final model testing step to save time', 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides', 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run the vis function to visualize only the first k images from a detections pickle file', 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run parse_args to print help text and exit when no command line arguments are provided', 'run the vis function to save visualization output images to a custom output directory']
```

Usage

```
{'run_inference_on_image': 'run inference on a single image using detectron models and output a visualization PDF', 'get_rpn_box_proposals': 'get region proposal network box proposals and scores from an input image', 'parse_inference_args': 'parse command line arguments for image inference including model pkl and config yaml pairs', 'check_inference_args': 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run_multi_model_inference': 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes'}
```

## File: facebookresearch_densepose/tools/infer_simple.py

Prompts

```
['run inference on a single image using detectron models and output a visualization PDF', 'get region proposal network box proposals and scores from an input image', 'parse command line arguments for image inference including model pkl and config yaml pairs', 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes', 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run inference on images using a config YAML file and model weights pickle file', 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize a detectron model from a weights file using the config and cache URL utilities', 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize detection results by enabling the vis flag during network inference testing', 'train a Detectron network using a config file and optional command-line override options', 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'train a Detectron network and skip the final model testing step to save time', 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides', 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run the vis function to visualize only the first k images from a detections pickle file', 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run parse_args to print help text and exit when no command line arguments are provided', 'run the vis function to save visualization output images to a custom output directory']
```

Usage

```
{'run_densepose_inference_on_image': 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run_inference_with_config_and_weights': 'run inference on images using a config YAML file and model weights pickle file', 'parse_inference_cli_args': 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize_detection_results_as_pdf': 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize_detectron_model_from_weights': 'initialize a detectron model from a weights file using the config and cache URL utilities'}
```

## File: facebookresearch_densepose/tools/test_net.py

Prompts

```
['run inference on a single image using detectron models and output a visualization PDF', 'get region proposal network box proposals and scores from an input image', 'parse command line arguments for image inference including model pkl and config yaml pairs', 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes', 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run inference on images using a config YAML file and model weights pickle file', 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize a detectron model from a weights file using the config and cache URL utilities', 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize detection results by enabling the vis flag during network inference testing', 'train a Detectron network using a config file and optional command-line override options', 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'train a Detectron network and skip the final model testing step to save time', 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides', 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run the vis function to visualize only the first k images from a detections pickle file', 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run parse_args to print help text and exit when no command line arguments are provided', 'run the vis function to save visualization output images to a custom output directory']
```

Usage

```
{'run_inference_on_datasets': 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test_network_with_config': 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse_args_for_testing': 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run_multi_gpu_inference': 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize_detections': 'visualize detection results by enabling the vis flag during network inference testing'}
```

## File: facebookresearch_densepose/tools/train_net.py

Prompts

```
['run inference on a single image using detectron models and output a visualization PDF', 'get region proposal network box proposals and scores from an input image', 'parse command line arguments for image inference including model pkl and config yaml pairs', 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes', 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run inference on images using a config YAML file and model weights pickle file', 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize a detectron model from a weights file using the config and cache URL utilities', 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize detection results by enabling the vis flag during network inference testing', 'train a Detectron network using a config file and optional command-line override options', 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'train a Detectron network and skip the final model testing step to save time', 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides', 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run the vis function to visualize only the first k images from a detections pickle file', 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run parse_args to print help text and exit when no command line arguments are provided', 'run the vis function to save visualization output images to a custom output directory']
```

Usage

```
{'train_detectron_network': 'train a Detectron network using a config file and optional command-line override options', 'test_trained_model': 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'run_multi_gpu_inference': 'run inference on a trained model using multiple GPUs for faster evaluation', 'skip_test_training': 'train a Detectron network and skip the final model testing step to save time', 'parse_training_args': 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides'}
```

## File: facebookresearch_densepose/tools/visualize_results.py

Prompts

```
['run inference on a single image using detectron models and output a visualization PDF', 'get region proposal network box proposals and scores from an input image', 'parse command line arguments for image inference including model pkl and config yaml pairs', 'validate and cache inference arguments ensuring rpn pkl and cfg files exist', 'run multiple detectron models in sequence on an image to predict boxes, masks, keypoints, and body meshes', 'run end-to-end DensePose inference on a single image or folder of images using detectron', 'run inference on images using a config YAML file and model weights pickle file', 'parse command line arguments for cfg file, weights, output directory, image extension, and image path', 'visualize detected boxes, segmentations, keypoints, and body meshes as PDF output files', 'initialize a detectron model from a weights file using the config and cache URL utilities', 'run inference on one or more datasets using a trained Fast R-CNN network with detectron', 'test a Fast R-CNN network by loading a config file and running inference with specified weights', 'parse command line arguments including config file, GPU settings, and inference range for network testing', 'run inference across multiple GPUs using cfg.NUM_GPUS for parallel DensePose testing', 'visualize detection results by enabling the vis flag during network inference testing', 'train a Detectron network using a config file and optional command-line override options', 'test a trained Detectron model by running inference on the test dataset with expected result checks', 'train a Detectron network and skip the final model testing step to save time', 'parse command-line arguments including config file path, multi-GPU testing flag, and config overrides', 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run the vis function to visualize only the first k images from a detections pickle file', 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run parse_args to print help text and exit when no command line arguments are provided', 'run the vis function to save visualization output images to a custom output directory']
```

Usage

```
{'run_visualize_detections': 'run the script to visualize detection results from a detections.pkl file with configurable threshold', 'run_vis_with_limit': 'run the vis function to visualize only the first k images from a detections pickle file', 'run_vis_with_custom_thresh': 'run the vis function with a custom probability threshold to filter low-confidence detections', 'run_parse_args_help': 'run parse_args to print help text and exit when no command line arguments are provided', 'run_vis_with_output_dir': 'run the vis function to save visualization output images to a custom output directory'}
```

