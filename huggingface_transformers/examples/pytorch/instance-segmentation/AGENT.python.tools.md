# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/examples/pytorch/instance-segmentation/run_instance_segmentation.py

Prompts

```
['run the instance segmentation finetuning script with a pretrained Mask2Former model on a custom dataset', 'create an Evaluator instance to compute mean average precision metrics for instance segmentation predictions', 'test the augment_and_transform_batch function to apply albumentations transforms and image processing to segmentation data', 'build a custom collate_fn data collator that stacks pixel values and groups mask and class labels for instance segmentation', 'review the Arguments dataclass that defines CLI parameters for model path, dataset name, image dimensions, and training flags', 'run instance segmentation finetuning with Mask2Former model and Accelerate on a custom dataset', 'build a dataset pipeline that loads HuggingFace data, applies albumentations, and prepares mask labels', 'test the evaluation loop that computes MeanAveragePrecision metrics on instance segmentation predictions', 'create albumentations transforms with horizontal flip and brightness contrast for instance segmentation training', 'summarize the collate_fn that stacks pixel values, mask labels, and class labels into a batch']
```

Usage

```
{'run_instance_segmentation_finetune': 'run the instance segmentation finetuning script with a pretrained Mask2Former model on a custom dataset', 'create_evaluator_compute_mAP': 'create an Evaluator instance to compute mean average precision metrics for instance segmentation predictions', 'test_augment_and_transform_batch': 'test the augment_and_transform_batch function to apply albumentations transforms and image processing to segmentation data', 'build_collate_fn_batch': 'build a custom collate_fn data collator that stacks pixel values and groups mask and class labels for instance segmentation', 'review_arguments_dataclass': 'review the Arguments dataclass that defines CLI parameters for model path, dataset name, image dimensions, and training flags'}
```

## File: huggingface_transformers/examples/pytorch/instance-segmentation/run_instance_segmentation_no_trainer.py

Prompts

```
['run the instance segmentation finetuning script with a pretrained Mask2Former model on a custom dataset', 'create an Evaluator instance to compute mean average precision metrics for instance segmentation predictions', 'test the augment_and_transform_batch function to apply albumentations transforms and image processing to segmentation data', 'build a custom collate_fn data collator that stacks pixel values and groups mask and class labels for instance segmentation', 'review the Arguments dataclass that defines CLI parameters for model path, dataset name, image dimensions, and training flags', 'run instance segmentation finetuning with Mask2Former model and Accelerate on a custom dataset', 'build a dataset pipeline that loads HuggingFace data, applies albumentations, and prepares mask labels', 'test the evaluation loop that computes MeanAveragePrecision metrics on instance segmentation predictions', 'create albumentations transforms with horizontal flip and brightness contrast for instance segmentation training', 'summarize the collate_fn that stacks pixel values, mask labels, and class labels into a batch']
```

Usage

```
{'run_instance_segmentation_finetuning': 'run instance segmentation finetuning with Mask2Former model and Accelerate on a custom dataset', 'build_instance_segmentation_dataset_pipeline': 'build a dataset pipeline that loads HuggingFace data, applies albumentations, and prepares mask labels', 'test_evaluation_loop_mAP': 'test the evaluation loop that computes MeanAveragePrecision metrics on instance segmentation predictions', 'create_data_augmentation_transform': 'create albumentations transforms with horizontal flip and brightness contrast for instance segmentation training', 'summarize_collate_fn_batch': 'summarize the collate_fn that stacks pixel values, mask labels, and class labels into a batch'}
```

