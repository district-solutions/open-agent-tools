# Agent Python Tools

- repo: huggingface/autotrain-advanced
- repo_uri: https://github.com/huggingface/autotrain-advanced.git

## File: huggingface_autotrain-advanced/src/autotrain/trainers/image_classification/__main__.py

Prompts

```
['run image classification training by passing a training config JSON file path via the --training_config CLI argument', 'train an image classification model using HuggingFace Transformers Trainer with a provided config dict or ImageClassificationParams object', 'parse command line arguments to extract the path to a training_config JSON file for image classification', 'push a trained image classification model and image processor to a private HuggingFace Hub repository after training completes', 'generate a model card README for the trained image classification model using the config and trainer metrics', 'compute binary classification metrics like f1, precision, recall, auc, and accuracy from raw predictions and labels', 'compute multi-class classification metrics with macro, micro, and weighted averaging for f1, precision, and recall', 'process training and validation image data with albumentations transforms including random crop, rotation, and normalization', 'review the BINARY_CLASSIFICATION_EVAL_METRICS and MULTI_CLASS_CLASSIFICATION_EVAL_METRICS tuples to understand which eval keys are tracked']
```

Usage

```
{'run_image_classification_training': 'run image classification training by passing a training config JSON file path via the --training_config CLI argument', 'train_image_model': 'train an image classification model using HuggingFace Transformers Trainer with a provided config dict or ImageClassificationParams object', 'parse_training_args': 'parse command line arguments to extract the path to a training_config JSON file for image classification', 'push_model_to_hub': 'push a trained image classification model and image processor to a private HuggingFace Hub repository after training completes', 'create_model_card': 'generate a model card README for the trained image classification model using the config and trainer metrics'}
```

## File: huggingface_autotrain-advanced/src/autotrain/trainers/image_classification/utils.py

Prompts

```
['run image classification training by passing a training config JSON file path via the --training_config CLI argument', 'train an image classification model using HuggingFace Transformers Trainer with a provided config dict or ImageClassificationParams object', 'parse command line arguments to extract the path to a training_config JSON file for image classification', 'push a trained image classification model and image processor to a private HuggingFace Hub repository after training completes', 'generate a model card README for the trained image classification model using the config and trainer metrics', 'compute binary classification metrics like f1, precision, recall, auc, and accuracy from raw predictions and labels', 'compute multi-class classification metrics with macro, micro, and weighted averaging for f1, precision, and recall', 'process training and validation image data with albumentations transforms including random crop, rotation, and normalization', 'review the BINARY_CLASSIFICATION_EVAL_METRICS and MULTI_CLASS_CLASSIFICATION_EVAL_METRICS tuples to understand which eval keys are tracked']
```

Usage

```
{'compute_binary_classification_metrics': 'compute binary classification metrics like f1, precision, recall, auc, and accuracy from raw predictions and labels', 'compute_multi_class_classification_metrics': 'compute multi-class classification metrics with macro, micro, and weighted averaging for f1, precision, and recall', 'process_image_classification_data': 'process training and validation image data with albumentations transforms including random crop, rotation, and normalization', 'create_model_card': 'create a model card with validation metrics, dataset tags, and base model info for an image classification model', 'review_EVAL_METRICS_tuples': 'review the BINARY_CLASSIFICATION_EVAL_METRICS and MULTI_CLASS_CLASSIFICATION_EVAL_METRICS tuples to understand which eval keys are tracked'}
```

