# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/examples/pytorch/semantic-segmentation/run_semantic_segmentation.py

Prompts

```
['run semantic segmentation finetuning on a HuggingFace dataset using AutoModelForSemanticSegmentation and Trainer API', 'create a label transformation that sets background to 255 and reduces all other class labels by 1', 'build DataTrainingArguments dataclass for dataset name, split ratio, and label reduction configuration', 'build ModelArguments dataclass for pretrained model path, config, cache dir, and revision settings', 'test compute_metrics function that calculates mean IoU and per-category accuracy and IoU from model logits and labels', 'test loading a huggingface dataset and splitting train into train and validation subsets', 'build albumentations train and validation transforms for semantic segmentation image preprocessing', 'review the accelerator preparation of model, optimizer, dataloaders, and lr scheduler for distributed training']
```

Usage

```
{'run_semantic_segmentation_finetune': 'run semantic segmentation finetuning on a HuggingFace dataset using AutoModelForSemanticSegmentation and Trainer API', 'create_reduce_labels_transform': 'create a label transformation that sets background to 255 and reduces all other class labels by 1', 'build_data_training_arguments': 'build DataTrainingArguments dataclass for dataset name, split ratio, and label reduction configuration', 'build_model_arguments': 'build ModelArguments dataclass for pretrained model path, config, cache dir, and revision settings', 'test_compute_metrics': 'test compute_metrics function that calculates mean IoU and per-category accuracy and IoU from model logits and labels'}
```

## File: huggingface_transformers/examples/pytorch/semantic-segmentation/run_semantic_segmentation_no_trainer.py

Prompts

```
['run semantic segmentation finetuning on a HuggingFace dataset using AutoModelForSemanticSegmentation and Trainer API', 'create a label transformation that sets background to 255 and reduces all other class labels by 1', 'build DataTrainingArguments dataclass for dataset name, split ratio, and label reduction configuration', 'build ModelArguments dataclass for pretrained model path, config, cache dir, and revision settings', 'test compute_metrics function that calculates mean IoU and per-category accuracy and IoU from model logits and labels', 'test loading a huggingface dataset and splitting train into train and validation subsets', 'build albumentations train and validation transforms for semantic segmentation image preprocessing', 'review the accelerator preparation of model, optimizer, dataloaders, and lr scheduler for distributed training']
```

Usage

```
{'run_semantic_segmentation_finetune': 'run the script to finetune a transformers model on a semantic segmentation dataset using no trainer', 'create_reduce_labels_transform': 'create a reduce_labels_transform function that maps background label 0 to 255 and shifts other labels down by 1', 'test_load_dataset_split': 'test loading a huggingface dataset and splitting train into train and validation subsets', 'build_train_transforms': 'build albumentations train and validation transforms for semantic segmentation image preprocessing', 'review_prepare_accelerator': 'review the accelerator preparation of model, optimizer, dataloaders, and lr scheduler for distributed training'}
```

