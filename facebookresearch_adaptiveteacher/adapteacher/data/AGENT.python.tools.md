# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/data/build.py

Prompts

```
['divide dataset dicts into labeled and unlabeled sets using a supervision percentage and pre-generated random seed file', 'build a semi-supervised training data loader from labeled datasets using a detectron2 config and optional mapper', 'build a test data loader for evaluation on a named dataset using a detectron2 config', 'build a semi-supervised training data loader with separate labeled and unlabeled datasets supporting cross-dataset or supervision modes', 'build a batch data loader that groups labeled and unlabeled datasets by aspect ratio for two-crop semi-supervised training', 'build a strong augmentation pipeline with ColorJitter, GaussianBlur, and RandomErasing for training', 'create a Compose transform pipeline with SimCLR-style augmentations for self-supervised training', 'test the build_strong_augmentation function with is_train True and False to verify pipeline', 'refactor build_strong_augmentation to accept configurable probabilities and scales for each transform', 'review the build_strong_augmentation function and its torchvision transform composition logic']
```

Usage

```
{'divide_label_unlabel': 'divide dataset dicts into labeled and unlabeled sets using a supervision percentage and pre-generated random seed file', 'build_detection_semisup_train_loader': 'build a semi-supervised training data loader from labeled datasets using a detectron2 config and optional mapper', 'build_detection_test_loader': 'build a test data loader for evaluation on a named dataset using a detectron2 config', 'build_detection_semisup_train_loader_two_crops': 'build a semi-supervised training data loader with separate labeled and unlabeled datasets supporting cross-dataset or supervision modes', 'build_semisup_batch_data_loader_two_crop': 'build a batch data loader that groups labeled and unlabeled datasets by aspect ratio for two-crop semi-supervised training'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/data/detection_utils.py

Prompts

```
['divide dataset dicts into labeled and unlabeled sets using a supervision percentage and pre-generated random seed file', 'build a semi-supervised training data loader from labeled datasets using a detectron2 config and optional mapper', 'build a test data loader for evaluation on a named dataset using a detectron2 config', 'build a semi-supervised training data loader with separate labeled and unlabeled datasets supporting cross-dataset or supervision modes', 'build a batch data loader that groups labeled and unlabeled datasets by aspect ratio for two-crop semi-supervised training', 'build a strong augmentation pipeline with ColorJitter, GaussianBlur, and RandomErasing for training', 'create a Compose transform pipeline with SimCLR-style augmentations for self-supervised training', 'test the build_strong_augmentation function with is_train True and False to verify pipeline', 'refactor build_strong_augmentation to accept configurable probabilities and scales for each transform', 'review the build_strong_augmentation function and its torchvision transform composition logic']
```

Usage

```
{'build_strong_augmentation': 'build a strong augmentation pipeline with ColorJitter, GaussianBlur, and RandomErasing for training', 'create_augmentation_pipeline': 'create a Compose transform pipeline with SimCLR-style augmentations for self-supervised training', 'test_build_strong_augmentation': 'test the build_strong_augmentation function with is_train True and False to verify pipeline', 'refactor_augmentation_params': 'refactor build_strong_augmentation to accept configurable probabilities and scales for each transform', 'review_augmentation_transforms': 'review the build_strong_augmentation function and its torchvision transform composition logic'}
```

