# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/augmentation.py

Prompts

```
['build a list of data augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader from a Detectron2 config with dataset, mapper, and sampler', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and segmentation from named datasets', 'filter out images that have only crowd annotations from a Detectron2 dataset dict list', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS video dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format with augmentations', 'create a function that filters out empty instances from an Instances object by box or mask', 'create an Instances object from YouTube-VIS annotations with boxes, classes, ids, and masks', 'create a function that validates image dimensions match the dataset dict and raises SizeMismatchError on mismatch', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model prediction outputs into YTVIS COCO JSON format for evaluation', 'run COCO-style evaluation on YTVIS predictions using the YTVOSeval API to compute segmentation metrics']
```

Usage

```
{'build_augmentation': 'build a list of data augmentation transforms from a detectron2 config for training or testing', 'create_ResizeShortestEdge': 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create_RandomFlip': 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review_ResizeShortestEdge_get_transform': 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review_RandomFlip_get_transform': 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/build.py

Prompts

```
['build a list of data augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader from a Detectron2 config with dataset, mapper, and sampler', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and segmentation from named datasets', 'filter out images that have only crowd annotations from a Detectron2 dataset dict list', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS video dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format with augmentations', 'create a function that filters out empty instances from an Instances object by box or mask', 'create an Instances object from YouTube-VIS annotations with boxes, classes, ids, and masks', 'create a function that validates image dimensions match the dataset dict and raises SizeMismatchError on mismatch', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model prediction outputs into YTVIS COCO JSON format for evaluation', 'run COCO-style evaluation on YTVIS predictions using the YTVOSeval API to compute segmentation metrics']
```

Usage

```
{'build_detection_train_loader': 'build a detection training data loader from a Detectron2 config with dataset, mapper, and sampler', 'build_detection_test_loader': 'build a detection test data loader with batch size 1 for inference evaluation', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for instance detection and segmentation from named datasets', 'filter_images_with_only_crowd_annotations': 'filter out images that have only crowd annotations from a Detectron2 dataset dict list', 'compute_num_images_per_worker': 'compute the number of images per worker from the solver batch size and world size'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/dataset_mapper.py

Prompts

```
['build a list of data augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader from a Detectron2 config with dataset, mapper, and sampler', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and segmentation from named datasets', 'filter out images that have only crowd annotations from a Detectron2 dataset dict list', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS video dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format with augmentations', 'create a function that filters out empty instances from an Instances object by box or mask', 'create an Instances object from YouTube-VIS annotations with boxes, classes, ids, and masks', 'create a function that validates image dimensions match the dataset dict and raises SizeMismatchError on mismatch', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model prediction outputs into YTVIS COCO JSON format for evaluation', 'run COCO-style evaluation on YTVIS predictions using the YTVOSeval API to compute segmentation metrics']
```

Usage

```
{'build_YTVISDatasetMapper': 'build a YTVISDatasetMapper to map YouTube-VIS video dataset dicts into model input format with frame sampling', 'build_CocoClipDatasetMapper': 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format with augmentations', 'create_filter_empty_instances': 'create a function that filters out empty instances from an Instances object by box or mask', 'create_ytvis_annotations_to_instances': 'create an Instances object from YouTube-VIS annotations with boxes, classes, ids, and masks', 'create_check_image_size': 'create a function that validates image dimensions match the dataset dict and raises SizeMismatchError on mismatch'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/data_video/ytvis_eval.py

Prompts

```
['build a list of data augmentation transforms from a detectron2 config for training or testing', 'create a ResizeShortestEdge augmentation that scales the shorter edge with clip-aware frame counting', 'create a RandomFlip augmentation that flips images horizontally or vertically with clip-aware frame counting', 'review the ResizeShortestEdge get_transform method that computes scale and returns a ResizeTransform', 'review the RandomFlip get_transform method that returns HFlipTransform, VFlipTransform, or NoOpTransform', 'build a detection training data loader from a Detectron2 config with dataset, mapper, and sampler', 'build a detection test data loader with batch size 1 for inference evaluation', 'load and prepare dataset dicts for instance detection and segmentation from named datasets', 'filter out images that have only crowd annotations from a Detectron2 dataset dict list', 'compute the number of images per worker from the solver batch size and world size', 'build a YTVISDatasetMapper to map YouTube-VIS video dataset dicts into model input format with frame sampling', 'build a CocoClipDatasetMapper to convert COCO images into multi-frame model input format with augmentations', 'create a function that filters out empty instances from an Instances object by box or mask', 'create an Instances object from YouTube-VIS annotations with boxes, classes, ids, and masks', 'create a function that validates image dimensions match the dataset dict and raises SizeMismatchError on mismatch', 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert video model prediction outputs into YTVIS COCO JSON format for evaluation', 'run COCO-style evaluation on YTVIS predictions using the YTVOSeval API to compute segmentation metrics']
```

Usage

```
{'create_YTVISEvaluator': 'create a YTVISEvaluator instance to evaluate video instance segmentation predictions on a YTVIS dataset', 'run_YTVISEvaluator_evaluate': 'run the YTVISEvaluator evaluate method to compute AP and AR metrics on collected predictions', 'process_YTVISEvaluator_predictions': 'process model inputs and outputs through YTVISEvaluator to accumulate video segmentation predictions', 'convert_instances_to_coco_json_video': 'convert video model prediction outputs into YTVIS COCO JSON format for evaluation', 'run_evaluate_predictions_on_coco': 'run COCO-style evaluation on YTVIS predictions using the YTVOSeval API to compute segmentation metrics'}
```

