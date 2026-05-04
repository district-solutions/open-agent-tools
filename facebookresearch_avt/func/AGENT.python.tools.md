# Agent Python Tools

- repo: facebookresearch/avt
- repo_uri: https://github.com/facebookresearch/avt

## File: facebookresearch_avt/func/train.py

Prompts

```
['run the main training loop with a Hydra config to train a video classification model end to end', 'run a single training epoch with gradient clipping, loss weighting, and periodic checkpoint saving', 'run evaluation on test datasets and store logits and accuracy metrics to HDF5 files', 'run store_checkpoint to save the model, optimizer, and lr scheduler state to a .pth file', 'run init_model to load pretrained weights from a checkpoint file into a model with optional module filtering', 'create a NoLossAccuracy module that returns empty losses and accuracies for no-op training', 'create a BasicLossAccuracy module to compute classification loss and top-k accuracy with optional class balancing', 'review the BasicLossAccuracy forward method to compute cls loss and acc1/acc5 per target type', 'create a Basic train ops class that preprocesses data and computes classification losses and accuracies', 'create a PredFutureFeat class to compute classification and regression losses for future feature prediction']
```

Usage

```
{'run_main_training': 'run the main training loop with a Hydra config to train a video classification model end to end', 'run_train_one_epoch': 'run a single training epoch with gradient clipping, loss weighting, and periodic checkpoint saving', 'run_evaluate': 'run evaluation on test datasets and store logits and accuracy metrics to HDF5 files', 'run_store_checkpoint': 'run store_checkpoint to save the model, optimizer, and lr scheduler state to a .pth file', 'run_init_model': 'run init_model to load pretrained weights from a checkpoint file into a model with optional module filtering'}
```

## File: facebookresearch_avt/func/train_eval_ops.py

Prompts

```
['run the main training loop with a Hydra config to train a video classification model end to end', 'run a single training epoch with gradient clipping, loss weighting, and periodic checkpoint saving', 'run evaluation on test datasets and store logits and accuracy metrics to HDF5 files', 'run store_checkpoint to save the model, optimizer, and lr scheduler state to a .pth file', 'run init_model to load pretrained weights from a checkpoint file into a model with optional module filtering', 'create a NoLossAccuracy module that returns empty losses and accuracies for no-op training', 'create a BasicLossAccuracy module to compute classification loss and top-k accuracy with optional class balancing', 'review the BasicLossAccuracy forward method to compute cls loss and acc1/acc5 per target type', 'create a Basic train ops class that preprocesses data and computes classification losses and accuracies', 'create a PredFutureFeat class to compute classification and regression losses for future feature prediction']
```

Usage

```
{'create_NoLossAccuracy': 'create a NoLossAccuracy module that returns empty losses and accuracies for no-op training', 'create_BasicLossAccuracy': 'create a BasicLossAccuracy module to compute classification loss and top-k accuracy with optional class balancing', 'review_BasicLossAccuracy_forward': 'review the BasicLossAccuracy forward method to compute cls loss and acc1/acc5 per target type', 'create_Basic_train_ops': 'create a Basic train ops class that preprocesses data and computes classification losses and accuracies', 'create_PredFutureFeat_train_ops': 'create a PredFutureFeat class to compute classification and regression losses for future feature prediction'}
```

