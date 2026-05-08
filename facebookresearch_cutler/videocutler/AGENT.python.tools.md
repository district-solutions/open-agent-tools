# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/eval_ytvis.py

Prompts

```
['run the YT-VIS evaluation script to evaluate segmentation results against ground truth annotations', 'run the YT-VIS evaluation with custom dataset path, dataset name, and result path arguments', 'summarize the cocoEval stats into a comma-separated string of percentage values', 'create an argparse parser with dataset-path, dataset-name, and result-path arguments for YT-VIS evaluation', 'evaluate YT-VIS segmentation results by loading ground truth and inference results then running evaluation', 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former DefaultPredictor configured for COCO panoptic segmentation with semantic and instance modes enabled', 'build a Detectron2 Visualizer to draw panoptic, instance, and semantic segmentation results on an image', 'refactor the Predictor predict method to output individual segmentation results instead of concatenated images', 'review the Predictor class setup and predict methods for Mask2Former-based image segmentation inference', 'run the MaskFormer training script with a config file and optional dataset overrides', 'run evaluation only mode on a trained MaskFormer model with test-time augmentation', 'build an evaluator for COCO, Cityscapes, ADE20K, or Mapillary Vistas datasets', 'build a training data loader with semantic, panoptic, or instance segmentation dataset mappers', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier', 'run the MaskFormer video segmentation training script with a config file and dataset arguments', 'run evaluation only mode on a trained video segmentation model using detection checkpointer weights', 'test a video segmentation model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_ytvis_evaluation': 'run the YT-VIS evaluation script to evaluate segmentation results against ground truth annotations', 'run_ytvis_evaluation_with_custom_paths': 'run the YT-VIS evaluation with custom dataset path, dataset name, and result path arguments', 'summarize_cocoeval_stats': 'summarize the cocoEval stats into a comma-separated string of percentage values', 'create_ytvis_parser': 'create an argparse parser with dataset-path, dataset-name, and result-path arguments for YT-VIS evaluation', 'evaluate_ytvis_segmentation_results': 'evaluate YT-VIS segmentation results by loading ground truth and inference results then running evaluation'}
```

## File: facebookresearch_cutler/videocutler/predict.py

Prompts

```
['run the YT-VIS evaluation script to evaluate segmentation results against ground truth annotations', 'run the YT-VIS evaluation with custom dataset path, dataset name, and result path arguments', 'summarize the cocoEval stats into a comma-separated string of percentage values', 'create an argparse parser with dataset-path, dataset-name, and result-path arguments for YT-VIS evaluation', 'evaluate YT-VIS segmentation results by loading ground truth and inference results then running evaluation', 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former DefaultPredictor configured for COCO panoptic segmentation with semantic and instance modes enabled', 'build a Detectron2 Visualizer to draw panoptic, instance, and semantic segmentation results on an image', 'refactor the Predictor predict method to output individual segmentation results instead of concatenated images', 'review the Predictor class setup and predict methods for Mask2Former-based image segmentation inference', 'run the MaskFormer training script with a config file and optional dataset overrides', 'run evaluation only mode on a trained MaskFormer model with test-time augmentation', 'build an evaluator for COCO, Cityscapes, ADE20K, or Mapillary Vistas datasets', 'build a training data loader with semantic, panoptic, or instance segmentation dataset mappers', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier', 'run the MaskFormer video segmentation training script with a config file and dataset arguments', 'run evaluation only mode on a trained video segmentation model using detection checkpointer weights', 'test a video segmentation model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_Predictor_predict': 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create_Predictor_setup': 'create a Mask2Former DefaultPredictor configured for COCO panoptic segmentation with semantic and instance modes enabled', 'build_visualizer_segmentation': 'build a Detectron2 Visualizer to draw panoptic, instance, and semantic segmentation results on an image', 'refactor_Predictor_predict': 'refactor the Predictor predict method to output individual segmentation results instead of concatenated images', 'review_Predictor_class': 'review the Predictor class setup and predict methods for Mask2Former-based image segmentation inference'}
```

## File: facebookresearch_cutler/videocutler/train_net.py

Prompts

```
['run the YT-VIS evaluation script to evaluate segmentation results against ground truth annotations', 'run the YT-VIS evaluation with custom dataset path, dataset name, and result path arguments', 'summarize the cocoEval stats into a comma-separated string of percentage values', 'create an argparse parser with dataset-path, dataset-name, and result-path arguments for YT-VIS evaluation', 'evaluate YT-VIS segmentation results by loading ground truth and inference results then running evaluation', 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former DefaultPredictor configured for COCO panoptic segmentation with semantic and instance modes enabled', 'build a Detectron2 Visualizer to draw panoptic, instance, and semantic segmentation results on an image', 'refactor the Predictor predict method to output individual segmentation results instead of concatenated images', 'review the Predictor class setup and predict methods for Mask2Former-based image segmentation inference', 'run the MaskFormer training script with a config file and optional dataset overrides', 'run evaluation only mode on a trained MaskFormer model with test-time augmentation', 'build an evaluator for COCO, Cityscapes, ADE20K, or Mapillary Vistas datasets', 'build a training data loader with semantic, panoptic, or instance segmentation dataset mappers', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier', 'run the MaskFormer video segmentation training script with a config file and dataset arguments', 'run evaluation only mode on a trained video segmentation model using detection checkpointer weights', 'test a video segmentation model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_training': 'run the MaskFormer training script with a config file and optional dataset overrides', 'run_evaluation': 'run evaluation only mode on a trained MaskFormer model with test-time augmentation', 'build_evaluator': 'build an evaluator for COCO, Cityscapes, ADE20K, or Mapillary Vistas datasets', 'build_train_loader': 'build a training data loader with semantic, panoptic, or instance segmentation dataset mappers', 'build_optimizer': 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier'}
```

## File: facebookresearch_cutler/videocutler/train_net_video.py

Prompts

```
['run the YT-VIS evaluation script to evaluate segmentation results against ground truth annotations', 'run the YT-VIS evaluation with custom dataset path, dataset name, and result path arguments', 'summarize the cocoEval stats into a comma-separated string of percentage values', 'create an argparse parser with dataset-path, dataset-name, and result-path arguments for YT-VIS evaluation', 'evaluate YT-VIS segmentation results by loading ground truth and inference results then running evaluation', 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former DefaultPredictor configured for COCO panoptic segmentation with semantic and instance modes enabled', 'build a Detectron2 Visualizer to draw panoptic, instance, and semantic segmentation results on an image', 'refactor the Predictor predict method to output individual segmentation results instead of concatenated images', 'review the Predictor class setup and predict methods for Mask2Former-based image segmentation inference', 'run the MaskFormer training script with a config file and optional dataset overrides', 'run evaluation only mode on a trained MaskFormer model with test-time augmentation', 'build an evaluator for COCO, Cityscapes, ADE20K, or Mapillary Vistas datasets', 'build a training data loader with semantic, panoptic, or instance segmentation dataset mappers', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier', 'run the MaskFormer video segmentation training script with a config file and dataset arguments', 'run evaluation only mode on a trained video segmentation model using detection checkpointer weights', 'test a video segmentation model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_video_segmentation_training': 'run the MaskFormer video segmentation training script with a config file and dataset arguments', 'run_evaluation_only': 'run evaluation only mode on a trained video segmentation model using detection checkpointer weights', 'build_optimizer': 'build an AdamW or SGD optimizer with gradient clipping and per-module learning rate multipliers', 'build_train_loader': 'build a YTVIS training data loader with dataset mapper and detection dataset dicts', 'test_model': 'test a video segmentation model on a dataset and print evaluation results in CSV format'}
```

