# Agent Python Tools

- repo: facebookresearch/detr
- repo_uri: https://github.com/facebookresearch/detr.git

## File: facebookresearch_detr/d2/converter.py

Prompts

```
['run the converter script to convert a DETR model checkpoint to Detectron2 format', 'run the converter to download and convert a DETR model from a URL to Detectron2 format', 'run the converter to remap 92 DETR COCO classes to contiguous Detectron2 class indices', 'run the converter to remap DETR backbone layer names to Detectron2 ResNet naming conventions', 'run the converter to save a converted DETR model checkpoint to a specified output path', 'run the DETR training script with a config file and GPU count via command line', 'run the DETR model in eval-only mode to test on a dataset using saved weights', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier for DETR', 'build a detection training data loader using the DetrDatasetMapper for DETR model training', 'build a COCOEvaluator for evaluating DETR model predictions on a given dataset']
```

Usage

```
{'convert_detr_model_to_detectron2': 'run the converter script to convert a DETR model checkpoint to Detectron2 format', 'convert_model_from_url': 'run the converter to download and convert a DETR model from a URL to Detectron2 format', 'remap_coco_classes': 'run the converter to remap 92 DETR COCO classes to contiguous Detectron2 class indices', 'convert_backbone_weights': 'run the converter to remap DETR backbone layer names to Detectron2 ResNet naming conventions', 'save_converted_checkpoint': 'run the converter to save a converted DETR model checkpoint to a specified output path'}
```

## File: facebookresearch_detr/d2/train_net.py

Prompts

```
['run the converter script to convert a DETR model checkpoint to Detectron2 format', 'run the converter to download and convert a DETR model from a URL to Detectron2 format', 'run the converter to remap 92 DETR COCO classes to contiguous Detectron2 class indices', 'run the converter to remap DETR backbone layer names to Detectron2 ResNet naming conventions', 'run the converter to save a converted DETR model checkpoint to a specified output path', 'run the DETR training script with a config file and GPU count via command line', 'run the DETR model in eval-only mode to test on a dataset using saved weights', 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier for DETR', 'build a detection training data loader using the DetrDatasetMapper for DETR model training', 'build a COCOEvaluator for evaluating DETR model predictions on a given dataset']
```

Usage

```
{'run_detr_training': 'run the DETR training script with a config file and GPU count via command line', 'run_detr_evaluation': 'run the DETR model in eval-only mode to test on a dataset using saved weights', 'build_optimizer_detr': 'build an SGD or AdamW optimizer with gradient clipping and backbone learning rate multiplier for DETR', 'build_train_loader_detr': 'build a detection training data loader using the DetrDatasetMapper for DETR model training', 'build_evaluator_detr': 'build a COCOEvaluator for evaluating DETR model predictions on a given dataset'}
```

