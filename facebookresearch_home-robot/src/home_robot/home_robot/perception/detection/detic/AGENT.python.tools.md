# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/detection/detic/detic_mask.py

Prompts

```
['run the Detic model on a BGR image and return predictions with optional visualization', 'get a goal segmentation mask from an image by finding the highest confidence instance at the center', 'setup a Detectron2 CfgNode configuration for the Detic model with custom weights and thresholds', 'get CLIP text embeddings for a list of vocabulary terms using a pretrained text encoder', 'augment a segmentation mask by setting the bottom quarter of its bounding box to True', 'initialize DeticPerception with the default COCO vocabulary and model checkpoint for object detection', 'initialize DeticPerception with a custom comma-separated vocabulary for detecting specific object classes', 'run DeticPerception predict on an Observations object to get semantic and instance segmentation maps', 'call reset_vocab on DeticPerception to swap detection classes to a new custom vocabulary at runtime', 'call setup_cfg to build a Detectron2 config with a custom confidence threshold for Detic inference']
```

Usage

```
{'run_detic_on_image': 'run the Detic model on a BGR image and return predictions with optional visualization', 'get_goal_mask_from_image': 'get a goal segmentation mask from an image by finding the highest confidence instance at the center', 'setup_detic_config': 'setup a Detectron2 CfgNode configuration for the Detic model with custom weights and thresholds', 'get_clip_embeddings': 'get CLIP text embeddings for a list of vocabulary terms using a pretrained text encoder', 'augment_mask_with_box': 'augment a segmentation mask by setting the bottom quarter of its bounding box to True'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/perception/detection/detic/detic_perception.py

Prompts

```
['run the Detic model on a BGR image and return predictions with optional visualization', 'get a goal segmentation mask from an image by finding the highest confidence instance at the center', 'setup a Detectron2 CfgNode configuration for the Detic model with custom weights and thresholds', 'get CLIP text embeddings for a list of vocabulary terms using a pretrained text encoder', 'augment a segmentation mask by setting the bottom quarter of its bounding box to True', 'initialize DeticPerception with the default COCO vocabulary and model checkpoint for object detection', 'initialize DeticPerception with a custom comma-separated vocabulary for detecting specific object classes', 'run DeticPerception predict on an Observations object to get semantic and instance segmentation maps', 'call reset_vocab on DeticPerception to swap detection classes to a new custom vocabulary at runtime', 'call setup_cfg to build a Detectron2 config with a custom confidence threshold for Detic inference']
```

Usage

```
{'init_detic_perception_coco': 'initialize DeticPerception with the default COCO vocabulary and model checkpoint for object detection', 'init_detic_perception_custom': 'initialize DeticPerception with a custom comma-separated vocabulary for detecting specific object classes', 'predict_semantic_segmentation': 'run DeticPerception predict on an Observations object to get semantic and instance segmentation maps', 'reset_vocabulary_custom': 'call reset_vocab on DeticPerception to swap detection classes to a new custom vocabulary at runtime', 'setup_cfg_confidence': 'call setup_cfg to build a Detectron2 config with a custom confidence threshold for Detic inference'}
```

