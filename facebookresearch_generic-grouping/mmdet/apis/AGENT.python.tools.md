# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/apis/inference.py

Prompts

```
['initialize an object detector from a config file and optional checkpoint weights', 'run object detection inference on an image using a loaded detector model', 'run async object detection inference on an image with a loaded detector model', 'visualize object detection results with bounding boxes on an image using pyplot', 'load an image from a file path or numpy array into a results dictionary', 'run a single GPU inference test on a detection model with optional result visualization', 'run a multi-GPU distributed inference test on a detection model with GPU or CPU result collection', 'test the CPU-based result collection across distributed GPU ranks using temporary pickle files', 'test the GPU-based result collection across distributed ranks using torch distributed all_gather', 'review the single_gpu_test function to understand visualization and mask encoding logic', 'run the train_detector function to train an object detection model with a config and dataset', 'run set_random_seed to set random seeds for numpy torch and cuda for reproducibility', 'review the train_detector function to understand how it builds data loaders and registers training hooks', 'review the set_random_seed function to understand how it configures deterministic CUDNN backend behavior', 'refactor the train_detector function to support custom validation pipelines or additional distributed training options']
```

Usage

```
{'init_detector': 'initialize an object detector from a config file and optional checkpoint weights', 'inference_detector': 'run object detection inference on an image using a loaded detector model', 'async_inference_detector': 'run async object detection inference on an image with a loaded detector model', 'show_result_pyplot': 'visualize object detection results with bounding boxes on an image using pyplot', 'LoadImage': 'load an image from a file path or numpy array into a results dictionary'}
```

## File: facebookresearch_generic-grouping/mmdet/apis/test.py

Prompts

```
['initialize an object detector from a config file and optional checkpoint weights', 'run object detection inference on an image using a loaded detector model', 'run async object detection inference on an image with a loaded detector model', 'visualize object detection results with bounding boxes on an image using pyplot', 'load an image from a file path or numpy array into a results dictionary', 'run a single GPU inference test on a detection model with optional result visualization', 'run a multi-GPU distributed inference test on a detection model with GPU or CPU result collection', 'test the CPU-based result collection across distributed GPU ranks using temporary pickle files', 'test the GPU-based result collection across distributed ranks using torch distributed all_gather', 'review the single_gpu_test function to understand visualization and mask encoding logic', 'run the train_detector function to train an object detection model with a config and dataset', 'run set_random_seed to set random seeds for numpy torch and cuda for reproducibility', 'review the train_detector function to understand how it builds data loaders and registers training hooks', 'review the set_random_seed function to understand how it configures deterministic CUDNN backend behavior', 'refactor the train_detector function to support custom validation pipelines or additional distributed training options']
```

Usage

```
{'run_single_gpu_test': 'run a single GPU inference test on a detection model with optional result visualization', 'run_multi_gpu_test': 'run a multi-GPU distributed inference test on a detection model with GPU or CPU result collection', 'test_collect_results_cpu': 'test the CPU-based result collection across distributed GPU ranks using temporary pickle files', 'test_collect_results_gpu': 'test the GPU-based result collection across distributed ranks using torch distributed all_gather', 'review_single_gpu_test': 'review the single_gpu_test function to understand visualization and mask encoding logic'}
```

## File: facebookresearch_generic-grouping/mmdet/apis/train.py

Prompts

```
['initialize an object detector from a config file and optional checkpoint weights', 'run object detection inference on an image using a loaded detector model', 'run async object detection inference on an image with a loaded detector model', 'visualize object detection results with bounding boxes on an image using pyplot', 'load an image from a file path or numpy array into a results dictionary', 'run a single GPU inference test on a detection model with optional result visualization', 'run a multi-GPU distributed inference test on a detection model with GPU or CPU result collection', 'test the CPU-based result collection across distributed GPU ranks using temporary pickle files', 'test the GPU-based result collection across distributed ranks using torch distributed all_gather', 'review the single_gpu_test function to understand visualization and mask encoding logic', 'run the train_detector function to train an object detection model with a config and dataset', 'run set_random_seed to set random seeds for numpy torch and cuda for reproducibility', 'review the train_detector function to understand how it builds data loaders and registers training hooks', 'review the set_random_seed function to understand how it configures deterministic CUDNN backend behavior', 'refactor the train_detector function to support custom validation pipelines or additional distributed training options']
```

Usage

```
{'run_train_detector': 'run the train_detector function to train an object detection model with a config and dataset', 'run_set_random_seed': 'run set_random_seed to set random seeds for numpy torch and cuda for reproducibility', 'review_train_detector': 'review the train_detector function to understand how it builds data loaders and registers training hooks', 'review_set_random_seed': 'review the set_random_seed function to understand how it configures deterministic CUDNN backend behavior', 'refactor_train_detector': 'refactor the train_detector function to support custom validation pipelines or additional distributed training options'}
```

