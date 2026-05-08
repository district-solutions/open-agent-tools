# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/engine/bbox_aug.py

Prompts

```
['run bounding box detection with test-time augmentation including flips and multiple scales on images', 'run bounding box detection on original images with resize, tensor conversion, and normalization transforms', 'run bounding box detection on horizontally flipped images and transpose detections back to original orientation', 'run bounding box detection at a specified scale with optional horizontal flip for multi-scale inference', 'review the im_detect_bbox_aug function that merges detections from multiple transforms and applies NMS', 'run inference on a detection model using a data loader and save predictions to an output folder', 'run model predictions on a dataset with optional bounding box augmentation and timing', 'accumulate and merge predictions from multiple GPUs into a single sorted list', 'review the inference function that handles multi-GPU evaluation, timing, and result aggregation for object detection', 'refactor compute_on_dataset to support custom output processing or additional augmentation strategies', 'run the do_train function to train a Mask R-CNN model with mixed precision and validation', 'run reduce_loss_dict to average loss values across all GPU processes in distributed training', 'review the do_train function for its training loop, checkpointing, and periodic validation logic', 'refactor the do_train function to support a custom validation data loader or logging callback', 'summarize the reduce_loss_dict function which reduces and averages loss tensors across distributed processes']
```

Usage

```
{'run_bbox_augmented_detection': 'run bounding box detection with test-time augmentation including flips and multiple scales on images', 'run_bbox_detection': 'run bounding box detection on original images with resize, tensor conversion, and normalization transforms', 'run_bbox_hflip_detection': 'run bounding box detection on horizontally flipped images and transpose detections back to original orientation', 'run_bbox_scale_detection': 'run bounding box detection at a specified scale with optional horizontal flip for multi-scale inference', 'review_bbox_aug_functions': 'review the im_detect_bbox_aug function that merges detections from multiple transforms and applies NMS'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/engine/inference.py

Prompts

```
['run bounding box detection with test-time augmentation including flips and multiple scales on images', 'run bounding box detection on original images with resize, tensor conversion, and normalization transforms', 'run bounding box detection on horizontally flipped images and transpose detections back to original orientation', 'run bounding box detection at a specified scale with optional horizontal flip for multi-scale inference', 'review the im_detect_bbox_aug function that merges detections from multiple transforms and applies NMS', 'run inference on a detection model using a data loader and save predictions to an output folder', 'run model predictions on a dataset with optional bounding box augmentation and timing', 'accumulate and merge predictions from multiple GPUs into a single sorted list', 'review the inference function that handles multi-GPU evaluation, timing, and result aggregation for object detection', 'refactor compute_on_dataset to support custom output processing or additional augmentation strategies', 'run the do_train function to train a Mask R-CNN model with mixed precision and validation', 'run reduce_loss_dict to average loss values across all GPU processes in distributed training', 'review the do_train function for its training loop, checkpointing, and periodic validation logic', 'refactor the do_train function to support a custom validation data loader or logging callback', 'summarize the reduce_loss_dict function which reduces and averages loss tensors across distributed processes']
```

Usage

```
{'run_inference_on_dataset': 'run inference on a detection model using a data loader and save predictions to an output folder', 'run_compute_on_dataset': 'run model predictions on a dataset with optional bounding box augmentation and timing', 'run_accumulate_predictions': 'accumulate and merge predictions from multiple GPUs into a single sorted list', 'review_inference_function': 'review the inference function that handles multi-GPU evaluation, timing, and result aggregation for object detection', 'refactor_compute_on_dataset': 'refactor compute_on_dataset to support custom output processing or additional augmentation strategies'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/engine/trainer.py

Prompts

```
['run bounding box detection with test-time augmentation including flips and multiple scales on images', 'run bounding box detection on original images with resize, tensor conversion, and normalization transforms', 'run bounding box detection on horizontally flipped images and transpose detections back to original orientation', 'run bounding box detection at a specified scale with optional horizontal flip for multi-scale inference', 'review the im_detect_bbox_aug function that merges detections from multiple transforms and applies NMS', 'run inference on a detection model using a data loader and save predictions to an output folder', 'run model predictions on a dataset with optional bounding box augmentation and timing', 'accumulate and merge predictions from multiple GPUs into a single sorted list', 'review the inference function that handles multi-GPU evaluation, timing, and result aggregation for object detection', 'refactor compute_on_dataset to support custom output processing or additional augmentation strategies', 'run the do_train function to train a Mask R-CNN model with mixed precision and validation', 'run reduce_loss_dict to average loss values across all GPU processes in distributed training', 'review the do_train function for its training loop, checkpointing, and periodic validation logic', 'refactor the do_train function to support a custom validation data loader or logging callback', 'summarize the reduce_loss_dict function which reduces and averages loss tensors across distributed processes']
```

Usage

```
{'run_do_train': 'run the do_train function to train a Mask R-CNN model with mixed precision and validation', 'run_reduce_loss_dict': 'run reduce_loss_dict to average loss values across all GPU processes in distributed training', 'review_do_train': 'review the do_train function for its training loop, checkpointing, and periodic validation logic', 'refactor_do_train': 'refactor the do_train function to support a custom validation data loader or logging callback', 'summarize_reduce_loss_dict': 'summarize the reduce_loss_dict function which reduces and averages loss tensors across distributed processes'}
```

