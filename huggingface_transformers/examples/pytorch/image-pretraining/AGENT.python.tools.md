# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/examples/pytorch/image-pretraining/run_mae.py

Prompts

```
['pre-train a ViT model as a masked autoencoder (MAE) on image datasets using HuggingFace Transformers', 'load an image dataset from HuggingFace datasets or local directories for MAE pre-training', 'configure ViTMAE model arguments including mask ratio, norm pix loss, and config overrides', 'apply MAE-style image transforms including random resized crop, horizontal flip, and normalization', 'run MAE pre-training and evaluation using the HuggingFace Trainer API with custom data collator', 'run masked image modeling pretraining with SimMIM on a dataset using the HuggingFace Trainer', 'create a MaskGenerator to produce boolean masks for masked patch pretraining', 'build a collate_fn that batches pixel_values and bool_masked_pos tensors for the Trainer', 'configure DataTrainingArguments for dataset name, splits, masking ratio, and patch size', 'configure ModelArguments for model checkpoint, config overrides, image size, and patch size']
```

Usage

```
{'pretrain_vit_mae_model': 'pre-train a ViT model as a masked autoencoder (MAE) on image datasets using HuggingFace Transformers', 'load_image_dataset': 'load an image dataset from HuggingFace datasets or local directories for MAE pre-training', 'configure_mae_model_args': 'configure ViTMAE model arguments including mask ratio, norm pix loss, and config overrides', 'apply_mae_image_transforms': 'apply MAE-style image transforms including random resized crop, horizontal flip, and normalization', 'run_mae_training_evaluation': 'run MAE pre-training and evaluation using the HuggingFace Trainer API with custom data collator'}
```

## File: huggingface_transformers/examples/pytorch/image-pretraining/run_mim.py

Prompts

```
['pre-train a ViT model as a masked autoencoder (MAE) on image datasets using HuggingFace Transformers', 'load an image dataset from HuggingFace datasets or local directories for MAE pre-training', 'configure ViTMAE model arguments including mask ratio, norm pix loss, and config overrides', 'apply MAE-style image transforms including random resized crop, horizontal flip, and normalization', 'run MAE pre-training and evaluation using the HuggingFace Trainer API with custom data collator', 'run masked image modeling pretraining with SimMIM on a dataset using the HuggingFace Trainer', 'create a MaskGenerator to produce boolean masks for masked patch pretraining', 'build a collate_fn that batches pixel_values and bool_masked_pos tensors for the Trainer', 'configure DataTrainingArguments for dataset name, splits, masking ratio, and patch size', 'configure ModelArguments for model checkpoint, config overrides, image size, and patch size']
```

Usage

```
{'run_mim_pretraining': 'run masked image modeling pretraining with SimMIM on a dataset using the HuggingFace Trainer', 'create_mask_generator': 'create a MaskGenerator to produce boolean masks for masked patch pretraining', 'build_collate_fn': 'build a collate_fn that batches pixel_values and bool_masked_pos tensors for the Trainer', 'configure_data_training_args': 'configure DataTrainingArguments for dataset name, splits, masking ratio, and patch size', 'configure_model_arguments': 'configure ModelArguments for model checkpoint, config overrides, image size, and patch size'}
```

