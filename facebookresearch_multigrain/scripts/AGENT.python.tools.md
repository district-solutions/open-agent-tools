# Agent Python Tools

- repo: facebookresearch/multigrain
- repo_uri: https://github.com/facebookresearch/multigrain

## File: facebookresearch_multigrain/scripts/evaluate.py

Prompts

```
['run the evaluate script to evaluate a multigrain model on imagenet-val with a resnet50 backbone', 'run the evaluate script to compute top1 and top5 accuracy on imagenet validation set', 'run the evaluate script resuming from a specific checkpoint epoch in the experiment directory', 'run the evaluate script in dry mode to preview arguments without saving results', 'run the evaluate script with a custom backbone architecture and pretrained imagenet weights', 'run the GeM p exponent finetuning script for a MultiGrain model on ImageNet', 'run a training step that computes cross-entropy loss and updates the pooling exponent p', 'run a validation step that evaluates cross-entropy loss and top-1/top-5 accuracy', 'run a training or validation loop over a DataLoader with metric tracking and logging', 'resume a MultiGrain model from a saved checkpoint file or folder', 'run the multigrain model training loop with ImageNet data and configurable backbone architecture', 'run the training or validation loop over a DataLoader and aggregate metrics per epoch', 'run the step decay learning rate schedule that multiplies LR by gamma factors at drop epochs', 'run the whitening computation pipeline for a MultiGrain model using a specified backbone and checkpoint', 'compute the whitening matrix by extracting embeddings from images and applying PCA via get_whiten', 'initialize whitening layers in the MultiGrain model before computing embeddings on the dataset', 'integrate the computed mean and PCA matrix into the MultiGrain model and save the checkpoint', 'resume a MultiGrain model from a saved checkpoint to compute whitening on a new image list']
```

Usage

```
{'run_evaluation': 'run the evaluate script to evaluate a multigrain model on imagenet-val with a resnet50 backbone', 'run_classification_eval': 'run the evaluate script to compute top1 and top5 accuracy on imagenet validation set', 'run_eval_with_checkpoint': 'run the evaluate script resuming from a specific checkpoint epoch in the experiment directory', 'run_eval_dry_run': 'run the evaluate script in dry mode to preview arguments without saving results', 'run_eval_custom_backbone': 'run the evaluate script with a custom backbone architecture and pretrained imagenet weights'}
```

## File: facebookresearch_multigrain/scripts/finetune_p.py

Prompts

```
['run the evaluate script to evaluate a multigrain model on imagenet-val with a resnet50 backbone', 'run the evaluate script to compute top1 and top5 accuracy on imagenet validation set', 'run the evaluate script resuming from a specific checkpoint epoch in the experiment directory', 'run the evaluate script in dry mode to preview arguments without saving results', 'run the evaluate script with a custom backbone architecture and pretrained imagenet weights', 'run the GeM p exponent finetuning script for a MultiGrain model on ImageNet', 'run a training step that computes cross-entropy loss and updates the pooling exponent p', 'run a validation step that evaluates cross-entropy loss and top-1/top-5 accuracy', 'run a training or validation loop over a DataLoader with metric tracking and logging', 'resume a MultiGrain model from a saved checkpoint file or folder', 'run the multigrain model training loop with ImageNet data and configurable backbone architecture', 'run the training or validation loop over a DataLoader and aggregate metrics per epoch', 'run the step decay learning rate schedule that multiplies LR by gamma factors at drop epochs', 'run the whitening computation pipeline for a MultiGrain model using a specified backbone and checkpoint', 'compute the whitening matrix by extracting embeddings from images and applying PCA via get_whiten', 'initialize whitening layers in the MultiGrain model before computing embeddings on the dataset', 'integrate the computed mean and PCA matrix into the MultiGrain model and save the checkpoint', 'resume a MultiGrain model from a saved checkpoint to compute whitening on a new image list']
```

Usage

```
{'run_finetune_p': 'run the GeM p exponent finetuning script for a MultiGrain model on ImageNet', 'run_training_step': 'run a training step that computes cross-entropy loss and updates the pooling exponent p', 'run_validation_step': 'run a validation step that evaluates cross-entropy loss and top-1/top-5 accuracy', 'run_loop': 'run a training or validation loop over a DataLoader with metric tracking and logging', 'run_checkpoint_resume': 'resume a MultiGrain model from a saved checkpoint file or folder'}
```

## File: facebookresearch_multigrain/scripts/train.py

Prompts

```
['run the evaluate script to evaluate a multigrain model on imagenet-val with a resnet50 backbone', 'run the evaluate script to compute top1 and top5 accuracy on imagenet validation set', 'run the evaluate script resuming from a specific checkpoint epoch in the experiment directory', 'run the evaluate script in dry mode to preview arguments without saving results', 'run the evaluate script with a custom backbone architecture and pretrained imagenet weights', 'run the GeM p exponent finetuning script for a MultiGrain model on ImageNet', 'run a training step that computes cross-entropy loss and updates the pooling exponent p', 'run a validation step that evaluates cross-entropy loss and top-1/top-5 accuracy', 'run a training or validation loop over a DataLoader with metric tracking and logging', 'resume a MultiGrain model from a saved checkpoint file or folder', 'run the multigrain model training loop with ImageNet data and configurable backbone architecture', 'run the training or validation loop over a DataLoader and aggregate metrics per epoch', 'run the step decay learning rate schedule that multiplies LR by gamma factors at drop epochs', 'run the whitening computation pipeline for a MultiGrain model using a specified backbone and checkpoint', 'compute the whitening matrix by extracting embeddings from images and applying PCA via get_whiten', 'initialize whitening layers in the MultiGrain model before computing embeddings on the dataset', 'integrate the computed mean and PCA matrix into the MultiGrain model and save the checkpoint', 'resume a MultiGrain model from a saved checkpoint to compute whitening on a new image list']
```

Usage

```
{'run_multigrain_training': 'run the multigrain model training loop with ImageNet data and configurable backbone architecture', 'run_training_step': 'run a single training step with gradient accumulation and multi-criterion loss computation', 'run_validation_step': 'run a single validation step to compute cross-entropy loss and top-1 and top-5 accuracy', 'run_training_loop': 'run the training or validation loop over a DataLoader and aggregate metrics per epoch', 'run_learning_rate_schedule': 'run the step decay learning rate schedule that multiplies LR by gamma factors at drop epochs'}
```

## File: facebookresearch_multigrain/scripts/whiten.py

Prompts

```
['run the evaluate script to evaluate a multigrain model on imagenet-val with a resnet50 backbone', 'run the evaluate script to compute top1 and top5 accuracy on imagenet validation set', 'run the evaluate script resuming from a specific checkpoint epoch in the experiment directory', 'run the evaluate script in dry mode to preview arguments without saving results', 'run the evaluate script with a custom backbone architecture and pretrained imagenet weights', 'run the GeM p exponent finetuning script for a MultiGrain model on ImageNet', 'run a training step that computes cross-entropy loss and updates the pooling exponent p', 'run a validation step that evaluates cross-entropy loss and top-1/top-5 accuracy', 'run a training or validation loop over a DataLoader with metric tracking and logging', 'resume a MultiGrain model from a saved checkpoint file or folder', 'run the multigrain model training loop with ImageNet data and configurable backbone architecture', 'run the training or validation loop over a DataLoader and aggregate metrics per epoch', 'run the step decay learning rate schedule that multiplies LR by gamma factors at drop epochs', 'run the whitening computation pipeline for a MultiGrain model using a specified backbone and checkpoint', 'compute the whitening matrix by extracting embeddings from images and applying PCA via get_whiten', 'initialize whitening layers in the MultiGrain model before computing embeddings on the dataset', 'integrate the computed mean and PCA matrix into the MultiGrain model and save the checkpoint', 'resume a MultiGrain model from a saved checkpoint to compute whitening on a new image list']
```

Usage

```
{'run_whitening_pipeline': 'run the whitening computation pipeline for a MultiGrain model using a specified backbone and checkpoint', 'compute_whitening_matrix': 'compute the whitening matrix by extracting embeddings from images and applying PCA via get_whiten', 'init_model_whitening': 'initialize whitening layers in the MultiGrain model before computing embeddings on the dataset', 'integrate_whitening_into_model': 'integrate the computed mean and PCA matrix into the MultiGrain model and save the checkpoint', 'resume_checkpoint_for_whitening': 'resume a MultiGrain model from a saved checkpoint to compute whitening on a new image list'}
```

