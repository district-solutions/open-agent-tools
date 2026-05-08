# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/predict.py

Prompts

```
['run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former predictor with COCO panoptic segmentation model weights and all segmentation modes enabled', 'build a cog Predictor class that loads a Mask2Former Swin-Large model for image segmentation inference', 'review the Predictor predict method that concatenates panoptic, instance, and semantic segmentation results into a single output image', 'refactor the Predictor to reuse a single Visualizer instance instead of creating three separate ones for each segmentation type', 'run the MaskFormer training script with a config file and GPU count via command line', 'run evaluation only on a MaskFormer model using a config file and pre-trained weights', 'build an optimizer for the MaskFormer model with configurable SGD or AdamW and gradient clipping', 'build an evaluator for datasets like COCO, ADE20K, Cityscapes, or Mapillary Vistas for segmentation tasks', 'build a training data loader with dataset mappers for semantic, panoptic, or instance segmentation', 'run the MaskFormer video training script with a config file and GPU count via command line', 'run the MaskFormer video model evaluation only mode using a config file and pre-trained weights', 'test the MaskFormer video model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_Predictor_predict': 'run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create_Predictor_setup': 'create a Mask2Former predictor with COCO panoptic segmentation model weights and all segmentation modes enabled', 'build_Predictor_class': 'build a cog Predictor class that loads a Mask2Former Swin-Large model for image segmentation inference', 'review_Predictor_predict': 'review the Predictor predict method that concatenates panoptic, instance, and semantic segmentation results into a single output image', 'refactor_Predictor_visualizer': 'refactor the Predictor to reuse a single Visualizer instance instead of creating three separate ones for each segmentation type'}
```

## File: facebookresearch_mask2former/train_net.py

Prompts

```
['run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former predictor with COCO panoptic segmentation model weights and all segmentation modes enabled', 'build a cog Predictor class that loads a Mask2Former Swin-Large model for image segmentation inference', 'review the Predictor predict method that concatenates panoptic, instance, and semantic segmentation results into a single output image', 'refactor the Predictor to reuse a single Visualizer instance instead of creating three separate ones for each segmentation type', 'run the MaskFormer training script with a config file and GPU count via command line', 'run evaluation only on a MaskFormer model using a config file and pre-trained weights', 'build an optimizer for the MaskFormer model with configurable SGD or AdamW and gradient clipping', 'build an evaluator for datasets like COCO, ADE20K, Cityscapes, or Mapillary Vistas for segmentation tasks', 'build a training data loader with dataset mappers for semantic, panoptic, or instance segmentation', 'run the MaskFormer video training script with a config file and GPU count via command line', 'run the MaskFormer video model evaluation only mode using a config file and pre-trained weights', 'test the MaskFormer video model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_mask2former_training': 'run the MaskFormer training script with a config file and GPU count via command line', 'run_mask2former_evaluation': 'run evaluation only on a MaskFormer model using a config file and pre-trained weights', 'build_trainer_optimizer': 'build an optimizer for the MaskFormer model with configurable SGD or AdamW and gradient clipping', 'build_trainer_evaluator': 'build an evaluator for datasets like COCO, ADE20K, Cityscapes, or Mapillary Vistas for segmentation tasks', 'build_trainer_train_loader': 'build a training data loader with dataset mappers for semantic, panoptic, or instance segmentation'}
```

## File: facebookresearch_mask2former/train_net_video.py

Prompts

```
['run the Predictor class to perform panoptic, instance, and semantic segmentation on an input image', 'create a Mask2Former predictor with COCO panoptic segmentation model weights and all segmentation modes enabled', 'build a cog Predictor class that loads a Mask2Former Swin-Large model for image segmentation inference', 'review the Predictor predict method that concatenates panoptic, instance, and semantic segmentation results into a single output image', 'refactor the Predictor to reuse a single Visualizer instance instead of creating three separate ones for each segmentation type', 'run the MaskFormer training script with a config file and GPU count via command line', 'run evaluation only on a MaskFormer model using a config file and pre-trained weights', 'build an optimizer for the MaskFormer model with configurable SGD or AdamW and gradient clipping', 'build an evaluator for datasets like COCO, ADE20K, Cityscapes, or Mapillary Vistas for segmentation tasks', 'build a training data loader with dataset mappers for semantic, panoptic, or instance segmentation', 'run the MaskFormer video training script with a config file and GPU count via command line', 'run the MaskFormer video model evaluation only mode using a config file and pre-trained weights', 'test the MaskFormer video model on a dataset and print evaluation results in CSV format']
```

Usage

```
{'run_trainer_train': 'run the MaskFormer video training script with a config file and GPU count via command line', 'run_trainer_eval': 'run the MaskFormer video model evaluation only mode using a config file and pre-trained weights', 'build_trainer_optimizer': 'build an AdamW or SGD optimizer with gradient clipping and per-layer learning rate for the model', 'build_trainer_train_loader': 'build a YTVIS training data loader with dataset mapper and detection dataset dicts', 'test_trainer_model': 'test the MaskFormer video model on a dataset and print evaluation results in CSV format'}
```

