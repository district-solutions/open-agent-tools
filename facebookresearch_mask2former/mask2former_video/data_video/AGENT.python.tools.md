# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former_video/data_video/augmentation.py

Prompts

```
['build a list of image augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader with dataset, mapper, sampler, and batch size from config', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and semantic segmentation from dataset names', 'filter out images with only crowd annotations from a list of dataset dicts', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format', 'filter empty instances from an Instances object by box size or mask emptiness', 'convert YouTube-VIS annotation dicts into a detectron2 Instances object with boxes, classes, ids, and masks', 'review the YTVISDatasetMapper call method for frame sampling, augmentation, and instance annotation transformation logic', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model outputs with scores, labels, and masks into YTVIS COCO JSON format', 'run COCO evaluation on YTVIS predictions using YTVOSeval to compute segmentation AP metrics']
```

Usage

```
{'build_augmentation': 'build a list of image augmentation transforms from a detectron2 config for training or testing', 'create_ResizeShortestEdge': 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create_RandomFlip': 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review_ResizeShortestEdge_get_transform': 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review_RandomFlip_get_transform': 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform'}
```

## File: facebookresearch_mask2former/mask2former_video/data_video/build.py

Prompts

```
['build a list of image augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader with dataset, mapper, sampler, and batch size from config', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and semantic segmentation from dataset names', 'filter out images with only crowd annotations from a list of dataset dicts', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format', 'filter empty instances from an Instances object by box size or mask emptiness', 'convert YouTube-VIS annotation dicts into a detectron2 Instances object with boxes, classes, ids, and masks', 'review the YTVISDatasetMapper call method for frame sampling, augmentation, and instance annotation transformation logic', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model outputs with scores, labels, and masks into YTVIS COCO JSON format', 'run COCO evaluation on YTVIS predictions using YTVOSeval to compute segmentation AP metrics']
```

Usage

```
{'build_detection_train_loader': 'build a detection training data loader with dataset, mapper, sampler, and batch size from config', 'build_detection_test_loader': 'build a detection test data loader with batch size 1 for inference evaluation', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for instance detection and semantic segmentation from dataset names', 'filter_images_with_only_crowd_annotations': 'filter out images with only crowd annotations from a list of dataset dicts', 'compute_num_images_per_worker': 'compute the number of images per worker from the solver batch size and world size'}
```

## File: facebookresearch_mask2former/mask2former_video/data_video/dataset_mapper.py

Prompts

```
['build a list of image augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader with dataset, mapper, sampler, and batch size from config', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and semantic segmentation from dataset names', 'filter out images with only crowd annotations from a list of dataset dicts', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format', 'filter empty instances from an Instances object by box size or mask emptiness', 'convert YouTube-VIS annotation dicts into a detectron2 Instances object with boxes, classes, ids, and masks', 'review the YTVISDatasetMapper call method for frame sampling, augmentation, and instance annotation transformation logic', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model outputs with scores, labels, and masks into YTVIS COCO JSON format', 'run COCO evaluation on YTVIS predictions using YTVOSeval to compute segmentation AP metrics']
```

Usage

```
{'build_YTVISDatasetMapper': 'build a YTVISDatasetMapper to map YouTube-VIS dataset dicts into model input format with frame sampling', 'build_CocoClipDatasetMapper': 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format', 'filter_empty_instances': 'filter empty instances from an Instances object by box size or mask emptiness', 'convert_ytvis_annotations_to_instances': 'convert YouTube-VIS annotation dicts into a detectron2 Instances object with boxes, classes, ids, and masks', 'review_YTVISDatasetMapper_call': 'review the YTVISDatasetMapper call method for frame sampling, augmentation, and instance annotation transformation logic'}
```

## File: facebookresearch_mask2former/mask2former_video/data_video/ytvis_eval.py

Prompts

```
['build a list of image augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader with dataset, mapper, sampler, and batch size from config', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and semantic segmentation from dataset names', 'filter out images with only crowd annotations from a list of dataset dicts', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format', 'filter empty instances from an Instances object by box size or mask emptiness', 'convert YouTube-VIS annotation dicts into a detectron2 Instances object with boxes, classes, ids, and masks', 'review the YTVISDatasetMapper call method for frame sampling, augmentation, and instance annotation transformation logic', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model outputs with scores, labels, and masks into YTVIS COCO JSON format', 'run COCO evaluation on YTVIS predictions using YTVOSeval to compute segmentation AP metrics']
```

Usage

```
{'create_YTVISEvaluator': 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run_YTVISEvaluator_evaluate': 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process_YTVISEvaluator_predictions': 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert_instances_to_coco_json_video': 'convert video model outputs with scores, labels, and masks into YTVIS COCO JSON format', 'run_evaluate_predictions_on_coco': 'run COCO evaluation on YTVIS predictions using YTVOSeval to compute segmentation AP metrics'}
```

