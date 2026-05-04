# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/eval-action-recg-linear.py

Prompts

```
['run the action recognition linear evaluation script with a config and model config file', 'run the main worker to train and evaluate a model across cross-validation folds', 'run a training or test phase on a dataloader and return top1 and top5 accuracy metrics', 'create a BatchWrapper to process large batches by splitting them into smaller chunks for inference', 'run distributed evaluation across multiple GPUs using torch multiprocessing spawn', 'run the action recognition evaluation script with a config file and model config file', 'run the training loop for action recognition with warmup classifier and main training phases', 'run distributed multi-GPU training for action recognition using torch multiprocessing spawn', 'run dense clip-level evaluation with 25 clips per video for metric stability', 'resume training from the last checkpoint for action recognition model evaluation', 'run the AVID audio-video synchronization model training with a YAML config file', 'run a single train or eval phase over a dataloader with loss computation', 'review the main_worker function that sets up model, dataloaders, optimizer, and checkpoint manager', 'review the run_phase function that handles batch processing, gradient steps, and metric logging']
```

Usage

```
{'run_linear_action_recognition_evaluation': 'run the action recognition linear evaluation script with a config and model config file', 'run_main_worker_training_loop': 'run the main worker to train and evaluate a model across cross-validation folds', 'run_phase_train_test_dense': 'run a training or test phase on a dataloader and return top1 and top5 accuracy metrics', 'create_batch_wrapper_for_model': 'create a BatchWrapper to process large batches by splitting them into smaller chunks for inference', 'run_distributed_evaluation_with_multiprocessing': 'run distributed evaluation across multiple GPUs using torch multiprocessing spawn'}
```

## File: facebookresearch_avid-cma/eval-action-recg.py

Prompts

```
['run the action recognition linear evaluation script with a config and model config file', 'run the main worker to train and evaluate a model across cross-validation folds', 'run a training or test phase on a dataloader and return top1 and top5 accuracy metrics', 'create a BatchWrapper to process large batches by splitting them into smaller chunks for inference', 'run distributed evaluation across multiple GPUs using torch multiprocessing spawn', 'run the action recognition evaluation script with a config file and model config file', 'run the training loop for action recognition with warmup classifier and main training phases', 'run distributed multi-GPU training for action recognition using torch multiprocessing spawn', 'run dense clip-level evaluation with 25 clips per video for metric stability', 'resume training from the last checkpoint for action recognition model evaluation', 'run the AVID audio-video synchronization model training with a YAML config file', 'run a single train or eval phase over a dataloader with loss computation', 'review the main_worker function that sets up model, dataloaders, optimizer, and checkpoint manager', 'review the run_phase function that handles batch processing, gradient steps, and metric logging']
```

Usage

```
{'run_evaluation': 'run the action recognition evaluation script with a config file and model config file', 'run_training': 'run the training loop for action recognition with warmup classifier and main training phases', 'run_distributed_training': 'run distributed multi-GPU training for action recognition using torch multiprocessing spawn', 'run_dense_evaluation': 'run dense clip-level evaluation with 25 clips per video for metric stability', 'run_resume_training': 'resume training from the last checkpoint for action recognition model evaluation'}
```

## File: facebookresearch_avid-cma/main-avid.py

Prompts

```
['run the action recognition linear evaluation script with a config and model config file', 'run the main worker to train and evaluate a model across cross-validation folds', 'run a training or test phase on a dataloader and return top1 and top5 accuracy metrics', 'create a BatchWrapper to process large batches by splitting them into smaller chunks for inference', 'run distributed evaluation across multiple GPUs using torch multiprocessing spawn', 'run the action recognition evaluation script with a config file and model config file', 'run the training loop for action recognition with warmup classifier and main training phases', 'run distributed multi-GPU training for action recognition using torch multiprocessing spawn', 'run dense clip-level evaluation with 25 clips per video for metric stability', 'resume training from the last checkpoint for action recognition model evaluation', 'run the AVID audio-video synchronization model training with a YAML config file', 'run a single train or eval phase over a dataloader with loss computation', 'review the main_worker function that sets up model, dataloaders, optimizer, and checkpoint manager', 'review the run_phase function that handles batch processing, gradient steps, and metric logging']
```

Usage

```
{'run_avid_training': 'run the AVID audio-video synchronization model training with a YAML config file', 'run_distributed_training': 'run multi-GPU distributed training for the AVID model using multiprocessing spawn', 'run_training_phase': 'run a single train or eval phase over a dataloader with loss computation', 'review_main_worker': 'review the main_worker function that sets up model, dataloaders, optimizer, and checkpoint manager', 'review_run_phase': 'review the run_phase function that handles batch processing, gradient steps, and metric logging'}
```

