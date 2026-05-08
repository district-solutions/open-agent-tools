# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/evals/image_classification_frozen/eval.py

Prompts

```
['run the main eval loop to fine-tune an AttentiveClassifier on a frozen pretrained JEPA vision encoder', 'run one training or validation epoch with the frozen encoder and classifier returning top-1 accuracy', 'initialize a pretrained vision transformer encoder from a checkpoint file with optional video frame support', 'create a train or validation dataloader with auto-augment transforms for image classification datasets', 'initialize an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for the classifier']
```

Usage

```
{'run_image_classification_frozen': 'run the main eval loop to fine-tune an AttentiveClassifier on a frozen pretrained JEPA vision encoder', 'run_one_epoch_train_val': 'run one training or validation epoch with the frozen encoder and classifier returning top-1 accuracy', 'init_model_vision_transformer': 'initialize a pretrained vision transformer encoder from a checkpoint file with optional video frame support', 'make_dataloader_dataset': 'create a train or validation dataloader with auto-augment transforms for image classification datasets', 'init_opt_adamw_schedulers': 'initialize an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for the classifier'}
```

