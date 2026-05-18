# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/apis/inference.py

Prompts

```
['init a 3D detector model from a config file and optional checkpoint weights', 'run inference on a point cloud file using a loaded 3D detector model', 'visualize predicted 3D bounding boxes on point cloud data and save to output directory', 'review the init_detector function to understand how config and checkpoint loading works', 'refactor the inference_detector function to support batched point cloud inference', 'run a single GPU test on a 3D detection model with a PyTorch data loader', 'test a model on a single GPU and save visualization results to an output directory', 'run inference on a model using torch.no_grad to collect prediction results from a dataset', 'review the single_gpu_test function that evaluates a model and returns a list of prediction results', 'refactor the single_gpu_test function to support multi-GPU testing or custom result formatting']
```

Usage

```
{'init_detector_from_config': 'init a 3D detector model from a config file and optional checkpoint weights', 'inference_detector_on_pointcloud': 'run inference on a point cloud file using a loaded 3D detector model', 'show_result_meshlab_visualization': 'visualize predicted 3D bounding boxes on point cloud data and save to output directory', 'review_init_detector': 'review the init_detector function to understand how config and checkpoint loading works', 'refactor_inference_detector': 'refactor the inference_detector function to support batched point cloud inference'}
```

## File: facebookresearch_nerf-det/mmdet3d/apis/test.py

Prompts

```
['init a 3D detector model from a config file and optional checkpoint weights', 'run inference on a point cloud file using a loaded 3D detector model', 'visualize predicted 3D bounding boxes on point cloud data and save to output directory', 'review the init_detector function to understand how config and checkpoint loading works', 'refactor the inference_detector function to support batched point cloud inference', 'run a single GPU test on a 3D detection model with a PyTorch data loader', 'test a model on a single GPU and save visualization results to an output directory', 'run inference on a model using torch.no_grad to collect prediction results from a dataset', 'review the single_gpu_test function that evaluates a model and returns a list of prediction results', 'refactor the single_gpu_test function to support multi-GPU testing or custom result formatting']
```

Usage

```
{'run_single_gpu_test': 'run a single GPU test on a 3D detection model with a PyTorch data loader', 'test_model_with_visualization': 'test a model on a single GPU and save visualization results to an output directory', 'run_inference_no_grad': 'run inference on a model using torch.no_grad to collect prediction results from a dataset', 'review_single_gpu_test': 'review the single_gpu_test function that evaluates a model and returns a list of prediction results', 'refactor_single_gpu_test': 'refactor the single_gpu_test function to support multi-GPU testing or custom result formatting'}
```

