# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/agents/locobot/end_to_end_semantic_scout/segmentation/detectron2_segmentation.py

Prompts

```
['run Detectron2Segmentation to get segmentation prediction masks and visualizations from a batch of BGR images', 'create an ImageSegmentation instance with a confidence threshold and GPU id for Mask R-CNN inference', 'build a BatchPredictor from a Detectron2 config to run batch inference on numpy image arrays', 'review VisualizationDemo run_on_images method to return instance segmentation predictions and visualizations for a batch', 'refactor setup_cfg to load a Detectron2 config file and set score thresholds for RetinaNet, ROI heads, and Panoptic FPN', 'initialize MMDetectionSegmentation with a prediction threshold, device, and visualization flag', 'run get_prediction on BGR images to get segmentation masks and visualization outputs', 'review the MMDetectionSegmentation class and its get_prediction method for segmentation inference', 'refactor get_prediction to support dynamic confidence score thresholds per image batch', 'summarize the MMDetectionSegmentation class that wraps mmdet inference for semantic segmentation']
```

Usage

```
{'run_Detectron2Segmentation_get_prediction': 'run Detectron2Segmentation to get segmentation prediction masks and visualizations from a batch of BGR images', 'create_ImageSegmentation': 'create an ImageSegmentation instance with a confidence threshold and GPU id for Mask R-CNN inference', 'build_BatchPredictor': 'build a BatchPredictor from a Detectron2 config to run batch inference on numpy image arrays', 'review_VisualizationDemo_run_on_images': 'review VisualizationDemo run_on_images method to return instance segmentation predictions and visualizations for a batch', 'refactor_setup_cfg': 'refactor setup_cfg to load a Detectron2 config file and set score thresholds for RetinaNet, ROI heads, and Panoptic FPN'}
```

## File: facebookresearch_fairo/agents/locobot/end_to_end_semantic_scout/segmentation/mmdetection_segmentation.py

Prompts

```
['run Detectron2Segmentation to get segmentation prediction masks and visualizations from a batch of BGR images', 'create an ImageSegmentation instance with a confidence threshold and GPU id for Mask R-CNN inference', 'build a BatchPredictor from a Detectron2 config to run batch inference on numpy image arrays', 'review VisualizationDemo run_on_images method to return instance segmentation predictions and visualizations for a batch', 'refactor setup_cfg to load a Detectron2 config file and set score thresholds for RetinaNet, ROI heads, and Panoptic FPN', 'initialize MMDetectionSegmentation with a prediction threshold, device, and visualization flag', 'run get_prediction on BGR images to get segmentation masks and visualization outputs', 'review the MMDetectionSegmentation class and its get_prediction method for segmentation inference', 'refactor get_prediction to support dynamic confidence score thresholds per image batch', 'summarize the MMDetectionSegmentation class that wraps mmdet inference for semantic segmentation']
```

Usage

```
{'init_MMDetectionSegmentation': 'initialize MMDetectionSegmentation with a prediction threshold, device, and visualization flag', 'run_get_prediction': 'run get_prediction on BGR images to get segmentation masks and visualization outputs', 'review_MMDetectionSegmentation_class': 'review the MMDetectionSegmentation class and its get_prediction method for segmentation inference', 'refactor_get_prediction_threshold': 'refactor get_prediction to support dynamic confidence score thresholds per image batch', 'summarize_MMDetectionSegmentation': 'summarize the MMDetectionSegmentation class that wraps mmdet inference for semantic segmentation'}
```

