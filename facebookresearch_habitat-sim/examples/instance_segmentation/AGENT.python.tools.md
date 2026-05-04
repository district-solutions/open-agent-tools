# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/examples/instance_segmentation/common.py

Prompts

```
['create a numpy vectorized function that filters instance IDs by labels using an extractor', 'filter out sparse or undersized segmentation masks based on bounding box density and image dimensions', 'run the InstanceVisualizer to produce colored segmentation visuals from a model and dataloader', 'compute the per-pixel mode label across multiple masks while ignoring zero background pixels', 'create an InstanceVisualizer with a model, dataloader, device, and number of classes for segmentation', 'train a Mask R-CNN model for one epoch with gradient clipping and learning rate scheduling', 'evaluate a detection model on a COCO dataset and compute bbox and segmentation IoU metrics', 'save a PyTorch model and optimizer checkpoint with the current epoch to a file path', 'load a PyTorch model and optimizer checkpoint from a file and optionally override hyperparameters', 'determine which IoU types to evaluate based on whether the model is Mask R-CNN or Keypoint R-CNN']
```

Usage

```
{'create_mask_filter': 'create a numpy vectorized function that filters instance IDs by labels using an extractor', 'area_filter': 'filter out sparse or undersized segmentation masks based on bounding box density and image dimensions', 'visualize_instance_segmentation_output': 'run the InstanceVisualizer to produce colored segmentation visuals from a model and dataloader', 'compute_mode_ignore_zeros': 'compute the per-pixel mode label across multiple masks while ignoring zero background pixels', 'init_InstanceVisualizer': 'create an InstanceVisualizer with a model, dataloader, device, and number of classes for segmentation'}
```

## File: facebookresearch_habitat-sim/examples/instance_segmentation/engine.py

Prompts

```
['create a numpy vectorized function that filters instance IDs by labels using an extractor', 'filter out sparse or undersized segmentation masks based on bounding box density and image dimensions', 'run the InstanceVisualizer to produce colored segmentation visuals from a model and dataloader', 'compute the per-pixel mode label across multiple masks while ignoring zero background pixels', 'create an InstanceVisualizer with a model, dataloader, device, and number of classes for segmentation', 'train a Mask R-CNN model for one epoch with gradient clipping and learning rate scheduling', 'evaluate a detection model on a COCO dataset and compute bbox and segmentation IoU metrics', 'save a PyTorch model and optimizer checkpoint with the current epoch to a file path', 'load a PyTorch model and optimizer checkpoint from a file and optionally override hyperparameters', 'determine which IoU types to evaluate based on whether the model is Mask R-CNN or Keypoint R-CNN']
```

Usage

```
{'train_one_epoch': 'train a Mask R-CNN model for one epoch with gradient clipping and learning rate scheduling', 'evaluate_model': 'evaluate a detection model on a COCO dataset and compute bbox and segmentation IoU metrics', 'save_model_state': 'save a PyTorch model and optimizer checkpoint with the current epoch to a file path', 'load_model_state': 'load a PyTorch model and optimizer checkpoint from a file and optionally override hyperparameters', 'get_iou_types': 'determine which IoU types to evaluate based on whether the model is Mask R-CNN or Keypoint R-CNN'}
```

