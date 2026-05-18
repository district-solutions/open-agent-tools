# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/apps/multi_distill/factory.py

Prompts

```
['create a CLIP model from a config name with optional pretrained weights and precision settings', 'create a CLIP model along with train and validation image preprocessing transforms', 'get a tokenizer function either the default CLIP tokenizer or a HuggingFace AutoTokenizer', 'list all available model architecture names registered from JSON config files', 'add a new model config directory or file path to the model registry', 'run multi-distillation CLIP training with a config name via the CLI entry point', 'resume multi-distillation training from a checkpoint using the CLI with a config and checkpoint path', 'set reproducible random seeds for torch, numpy, and random modules using random_seed with a seed and rank', 'load a saved checkpoint to resume training with load_checkpoint for a model, optimizer, and scaler', 'run train_one_epoch_ex to train a CLIP model with optional knowledge distillation from a teacher model', 'build a ClipLoss instance with local_loss, gather_with_grad, rank, and world_size arguments', 'run evaluate_ex to perform zero-shot and validation evaluation on a trained CLIP model', 'compute image-to-text and text-to-image retrieval metrics including mean rank, median rank, and recall at k', 'run backward to perform gradient computation with optional gradient scaling and norm clipping']
```

Usage

```
{'create_model': 'create a CLIP model from a config name with optional pretrained weights and precision settings', 'create_model_and_transforms': 'create a CLIP model along with train and validation image preprocessing transforms', 'get_tokenizer': 'get a tokenizer function either the default CLIP tokenizer or a HuggingFace AutoTokenizer', 'list_models': 'list all available model architecture names registered from JSON config files', 'add_model_config': 'add a new model config directory or file path to the model registry'}
```

## File: facebookresearch_metaclip/apps/multi_distill/main.py

Prompts

```
['create a CLIP model from a config name with optional pretrained weights and precision settings', 'create a CLIP model along with train and validation image preprocessing transforms', 'get a tokenizer function either the default CLIP tokenizer or a HuggingFace AutoTokenizer', 'list all available model architecture names registered from JSON config files', 'add a new model config directory or file path to the model registry', 'run multi-distillation CLIP training with a config name via the CLI entry point', 'resume multi-distillation training from a checkpoint using the CLI with a config and checkpoint path', 'set reproducible random seeds for torch, numpy, and random modules using random_seed with a seed and rank', 'load a saved checkpoint to resume training with load_checkpoint for a model, optimizer, and scaler', 'run train_one_epoch_ex to train a CLIP model with optional knowledge distillation from a teacher model', 'build a ClipLoss instance with local_loss, gather_with_grad, rank, and world_size arguments', 'run evaluate_ex to perform zero-shot and validation evaluation on a trained CLIP model', 'compute image-to-text and text-to-image retrieval metrics including mean rank, median rank, and recall at k', 'run backward to perform gradient computation with optional gradient scaling and norm clipping']
```

Usage

```
{'run_multi_distill_training': 'run multi-distillation CLIP training with a config name via the CLI entry point', 'run_resume_training': 'resume multi-distillation training from a checkpoint using the CLI with a config and checkpoint path', 'create_model_and_transforms': 'create a CLIP model and its train/val transforms using create_model_and_transforms with a model name and pretrained path', 'set_random_seed': 'set reproducible random seeds for torch, numpy, and random modules using random_seed with a seed and rank', 'load_checkpoint': 'load a saved checkpoint to resume training with load_checkpoint for a model, optimizer, and scaler'}
```

## File: facebookresearch_metaclip/apps/multi_distill/train.py

Prompts

```
['create a CLIP model from a config name with optional pretrained weights and precision settings', 'create a CLIP model along with train and validation image preprocessing transforms', 'get a tokenizer function either the default CLIP tokenizer or a HuggingFace AutoTokenizer', 'list all available model architecture names registered from JSON config files', 'add a new model config directory or file path to the model registry', 'run multi-distillation CLIP training with a config name via the CLI entry point', 'resume multi-distillation training from a checkpoint using the CLI with a config and checkpoint path', 'set reproducible random seeds for torch, numpy, and random modules using random_seed with a seed and rank', 'load a saved checkpoint to resume training with load_checkpoint for a model, optimizer, and scaler', 'run train_one_epoch_ex to train a CLIP model with optional knowledge distillation from a teacher model', 'build a ClipLoss instance with local_loss, gather_with_grad, rank, and world_size arguments', 'run evaluate_ex to perform zero-shot and validation evaluation on a trained CLIP model', 'compute image-to-text and text-to-image retrieval metrics including mean rank, median rank, and recall at k', 'run backward to perform gradient computation with optional gradient scaling and norm clipping']
```

Usage

```
{'train_CLIP_model': 'run train_one_epoch_ex to train a CLIP model with optional knowledge distillation from a teacher model', 'build_CLIP_loss': 'build a ClipLoss instance with local_loss, gather_with_grad, rank, and world_size arguments', 'evaluate_CLIP_model': 'run evaluate_ex to perform zero-shot and validation evaluation on a trained CLIP model', 'compute_CLIP_metrics': 'compute image-to-text and text-to-image retrieval metrics including mean rank, median rank, and recall at k', 'backward_pass_CLIP': 'run backward to perform gradient computation with optional gradient scaling and norm clipping'}
```

