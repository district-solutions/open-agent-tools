# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/config.py

Prompts

```
['add DETIC config options to a detectron2 CfgNode for open-vocabulary detection', 'set USE_ZEROSHOT_CLS and ZEROSHOT_WEIGHT_PATH to enable open-vocabulary classification', 'set USE_FED_LOSS and FED_LOSS_NUM_CAT to enable federated loss training', 'set DETR hyperparameters like NUM_CLASSES, NHEADS, and NUM_OBJECT_QUERIES', 'set DATASET_RATIO and USE_DIFF_BS_SIZE for multi-dataset training', 'build a custom optimizer from a detectron2 config node and PyTorch model with configurable SGD or AdamW', 'build an optimizer with full model gradient clipping enabled via the config solver settings', 'match parameter names against a list of keyword strings to apply custom learning rate multipliers', 'review the build_custom_optimizer function to understand how backbone and custom multiplier learning rates are applied', 'refactor the match_name_keywords function to use any() for more concise keyword matching logic', 'run the VisualizationDemo class on a BGR image to get predictions and visualized output', 'run the VisualizationDemo class on a video stream to yield visualized frame predictions', 'create an AsyncPredictor with multiple GPU workers for asynchronous model inference on images', 'get CLIP text embeddings for a list of vocabulary class names using a pretrained text encoder', 'review the AsyncPredictor._PredictWorker multiprocessing class that runs a DefaultPredictor loop on a task queue']
```

Usage

```
{'add_detic_config_to_cfg': 'add DETIC config options to a detectron2 CfgNode for open-vocabulary detection', 'configure_zeroshot_classifier': 'set USE_ZEROSHOT_CLS and ZEROSHOT_WEIGHT_PATH to enable open-vocabulary classification', 'configure_federated_loss': 'set USE_FED_LOSS and FED_LOSS_NUM_CAT to enable federated loss training', 'configure_detr_model': 'set DETR hyperparameters like NUM_CLASSES, NHEADS, and NUM_OBJECT_QUERIES', 'configure_multi_dataset_dataloader': 'set DATASET_RATIO and USE_DIFF_BS_SIZE for multi-dataset training'}
```

## File: facebookresearch_detic/detic/custom_solver.py

Prompts

```
['add DETIC config options to a detectron2 CfgNode for open-vocabulary detection', 'set USE_ZEROSHOT_CLS and ZEROSHOT_WEIGHT_PATH to enable open-vocabulary classification', 'set USE_FED_LOSS and FED_LOSS_NUM_CAT to enable federated loss training', 'set DETR hyperparameters like NUM_CLASSES, NHEADS, and NUM_OBJECT_QUERIES', 'set DATASET_RATIO and USE_DIFF_BS_SIZE for multi-dataset training', 'build a custom optimizer from a detectron2 config node and PyTorch model with configurable SGD or AdamW', 'build an optimizer with full model gradient clipping enabled via the config solver settings', 'match parameter names against a list of keyword strings to apply custom learning rate multipliers', 'review the build_custom_optimizer function to understand how backbone and custom multiplier learning rates are applied', 'refactor the match_name_keywords function to use any() for more concise keyword matching logic', 'run the VisualizationDemo class on a BGR image to get predictions and visualized output', 'run the VisualizationDemo class on a video stream to yield visualized frame predictions', 'create an AsyncPredictor with multiple GPU workers for asynchronous model inference on images', 'get CLIP text embeddings for a list of vocabulary class names using a pretrained text encoder', 'review the AsyncPredictor._PredictWorker multiprocessing class that runs a DefaultPredictor loop on a task queue']
```

Usage

```
{'build_custom_optimizer': 'build a custom optimizer from a detectron2 config node and PyTorch model with configurable SGD or AdamW', 'build_optimizer_with_gradient_clipping': 'build an optimizer with full model gradient clipping enabled via the config solver settings', 'match_name_keywords': 'match parameter names against a list of keyword strings to apply custom learning rate multipliers', 'review_build_custom_optimizer': 'review the build_custom_optimizer function to understand how backbone and custom multiplier learning rates are applied', 'refactor_match_name_keywords': 'refactor the match_name_keywords function to use any() for more concise keyword matching logic'}
```

## File: facebookresearch_detic/detic/predictor.py

Prompts

```
['add DETIC config options to a detectron2 CfgNode for open-vocabulary detection', 'set USE_ZEROSHOT_CLS and ZEROSHOT_WEIGHT_PATH to enable open-vocabulary classification', 'set USE_FED_LOSS and FED_LOSS_NUM_CAT to enable federated loss training', 'set DETR hyperparameters like NUM_CLASSES, NHEADS, and NUM_OBJECT_QUERIES', 'set DATASET_RATIO and USE_DIFF_BS_SIZE for multi-dataset training', 'build a custom optimizer from a detectron2 config node and PyTorch model with configurable SGD or AdamW', 'build an optimizer with full model gradient clipping enabled via the config solver settings', 'match parameter names against a list of keyword strings to apply custom learning rate multipliers', 'review the build_custom_optimizer function to understand how backbone and custom multiplier learning rates are applied', 'refactor the match_name_keywords function to use any() for more concise keyword matching logic', 'run the VisualizationDemo class on a BGR image to get predictions and visualized output', 'run the VisualizationDemo class on a video stream to yield visualized frame predictions', 'create an AsyncPredictor with multiple GPU workers for asynchronous model inference on images', 'get CLIP text embeddings for a list of vocabulary class names using a pretrained text encoder', 'review the AsyncPredictor._PredictWorker multiprocessing class that runs a DefaultPredictor loop on a task queue']
```

Usage

```
{'run_VisualizationDemo_on_image': 'run the VisualizationDemo class on a BGR image to get predictions and visualized output', 'run_VisualizationDemo_on_video': 'run the VisualizationDemo class on a video stream to yield visualized frame predictions', 'create_AsyncPredictor': 'create an AsyncPredictor with multiple GPU workers for asynchronous model inference on images', 'get_clip_embeddings': 'get CLIP text embeddings for a list of vocabulary class names using a pretrained text encoder', 'review_AsyncPredictor_PredictWorker': 'review the AsyncPredictor._PredictWorker multiprocessing class that runs a DefaultPredictor loop on a task queue'}
```

