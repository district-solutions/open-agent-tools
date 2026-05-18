# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/flava/coco_zero_shot.py

Prompts

```
['run the FLAVA zero-shot image-text retrieval evaluation on the COCO dataset with recall metrics', 'run the compute_recall function to calculate top-k recall from similarity scores', 'run the transform function to apply image and text preprocessing to COCO captions', 'run the collator function to batch and stack images and text tensors for the dataloader', 'run the setup_args function to parse CLI arguments for data root, annotations, and batch size', 'create a FLAVAPreTrainingLightningModule to pretrain a FLAVA multimodal model with image and text data', 'create a FLAVAClassificationLightningModule to fine-tune FLAVA for image text classification tasks', 'run get_optimizers_for_lightning to configure an AdamW optimizer with cosine warmup schedule', 'review the FLAVAPreTrainingLightningModule training_step method to understand how multimodal losses are aggregated and logged', 'review the FLAVAClassificationLightningModule _step method to understand how classification logits and accuracy are computed', 'build a datamodule kwargs dictionary from dataset config and training arguments for FLAVA training', 'build a FLAVA configuration by merging a YAML config file with CLI arguments using OmegaConf', 'review the build_datamodule_kwargs function to understand how it merges dataset and training config kwargs', 'review the build_config function to understand how it loads and merges YAML and CLI configs', 'refactor the build_config function to support additional config validation beyond max_steps assertion']
```

Usage

```
{'run_coco_zero_shot_eval': 'run the FLAVA zero-shot image-text retrieval evaluation on the COCO dataset with recall metrics', 'run_compute_recall': 'run the compute_recall function to calculate top-k recall from similarity scores', 'run_transform': 'run the transform function to apply image and text preprocessing to COCO captions', 'run_collator': 'run the collator function to batch and stack images and text tensors for the dataloader', 'run_setup_args': 'run the setup_args function to parse CLI arguments for data root, annotations, and batch size'}
```

## File: facebookresearch_multimodal/examples/flava/model.py

Prompts

```
['run the FLAVA zero-shot image-text retrieval evaluation on the COCO dataset with recall metrics', 'run the compute_recall function to calculate top-k recall from similarity scores', 'run the transform function to apply image and text preprocessing to COCO captions', 'run the collator function to batch and stack images and text tensors for the dataloader', 'run the setup_args function to parse CLI arguments for data root, annotations, and batch size', 'create a FLAVAPreTrainingLightningModule to pretrain a FLAVA multimodal model with image and text data', 'create a FLAVAClassificationLightningModule to fine-tune FLAVA for image text classification tasks', 'run get_optimizers_for_lightning to configure an AdamW optimizer with cosine warmup schedule', 'review the FLAVAPreTrainingLightningModule training_step method to understand how multimodal losses are aggregated and logged', 'review the FLAVAClassificationLightningModule _step method to understand how classification logits and accuracy are computed', 'build a datamodule kwargs dictionary from dataset config and training arguments for FLAVA training', 'build a FLAVA configuration by merging a YAML config file with CLI arguments using OmegaConf', 'review the build_datamodule_kwargs function to understand how it merges dataset and training config kwargs', 'review the build_config function to understand how it loads and merges YAML and CLI configs', 'refactor the build_config function to support additional config validation beyond max_steps assertion']
```

Usage

```
{'create_FLAVAPreTrainingLightningModule': 'create a FLAVAPreTrainingLightningModule to pretrain a FLAVA multimodal model with image and text data', 'create_FLAVAClassificationLightningModule': 'create a FLAVAClassificationLightningModule to fine-tune FLAVA for image text classification tasks', 'run_get_optimizers_for_lightning': 'run get_optimizers_for_lightning to configure an AdamW optimizer with cosine warmup schedule', 'review_FLAVAPreTrainingLightningModule_training_step': 'review the FLAVAPreTrainingLightningModule training_step method to understand how multimodal losses are aggregated and logged', 'review_FLAVAClassificationLightningModule_step': 'review the FLAVAClassificationLightningModule _step method to understand how classification logits and accuracy are computed'}
```

## File: facebookresearch_multimodal/examples/flava/utils.py

Prompts

```
['run the FLAVA zero-shot image-text retrieval evaluation on the COCO dataset with recall metrics', 'run the compute_recall function to calculate top-k recall from similarity scores', 'run the transform function to apply image and text preprocessing to COCO captions', 'run the collator function to batch and stack images and text tensors for the dataloader', 'run the setup_args function to parse CLI arguments for data root, annotations, and batch size', 'create a FLAVAPreTrainingLightningModule to pretrain a FLAVA multimodal model with image and text data', 'create a FLAVAClassificationLightningModule to fine-tune FLAVA for image text classification tasks', 'run get_optimizers_for_lightning to configure an AdamW optimizer with cosine warmup schedule', 'review the FLAVAPreTrainingLightningModule training_step method to understand how multimodal losses are aggregated and logged', 'review the FLAVAClassificationLightningModule _step method to understand how classification logits and accuracy are computed', 'build a datamodule kwargs dictionary from dataset config and training arguments for FLAVA training', 'build a FLAVA configuration by merging a YAML config file with CLI arguments using OmegaConf', 'review the build_datamodule_kwargs function to understand how it merges dataset and training config kwargs', 'review the build_config function to understand how it loads and merges YAML and CLI configs', 'refactor the build_config function to support additional config validation beyond max_steps assertion']
```

Usage

```
{'build_datamodule_kwargs': 'build a datamodule kwargs dictionary from dataset config and training arguments for FLAVA training', 'build_config': 'build a FLAVA configuration by merging a YAML config file with CLI arguments using OmegaConf', 'review_build_datamodule_kwargs': 'review the build_datamodule_kwargs function to understand how it merges dataset and training config kwargs', 'review_build_config': 'review the build_config function to understand how it loads and merges YAML and CLI configs', 'refactor_build_config': 'refactor the build_config function to support additional config validation beyond max_steps assertion'}
```

