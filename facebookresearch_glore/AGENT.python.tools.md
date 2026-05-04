# Agent Python Tools

- repo: facebookresearch/glore
- repo_uri: https://github.com/facebookresearch/glore

## File: facebookresearch_glore/train_kinetics.py

Prompts

```
['run the Kinetics video classification training with a RESNET50_3D_GCN_X5 network on GPU', 'run distributed video classification training across multiple GPUs using NCCL backend', 'run fine-tuning of a pretrained video classification model by resuming from a saved epoch', 'review the autofill function that auto-generates task names and log file paths from args', 'review the set_logger function that configures logging with file and stream handlers', 'run train_model to train a PyTorch video classification network with configurable epochs and batch size', 'run train_model with fine_tune=True to fine-tune a pretrained model on a new dataset', 'run train_model with resume_epoch to resume training from a saved checkpoint', 'run train_model with distributed=True to train across multiple GPUs using DDP', 'run train_model with precise_bn=True to compute precise batch norm statistics during training']
```

Usage

```
{'run_video_classification_training': 'run the Kinetics video classification training with a RESNET50_3D_GCN_X5 network on GPU', 'run_distributed_training': 'run distributed video classification training across multiple GPUs using NCCL backend', 'run_fine_tune_model': 'run fine-tuning of a pretrained video classification model by resuming from a saved epoch', 'review_autofill_function': 'review the autofill function that auto-generates task names and log file paths from args', 'review_set_logger_function': 'review the set_logger function that configures logging with file and stream handlers'}
```

## File: facebookresearch_glore/train_model.py

Prompts

```
['run the Kinetics video classification training with a RESNET50_3D_GCN_X5 network on GPU', 'run distributed video classification training across multiple GPUs using NCCL backend', 'run fine-tuning of a pretrained video classification model by resuming from a saved epoch', 'review the autofill function that auto-generates task names and log file paths from args', 'review the set_logger function that configures logging with file and stream handlers', 'run train_model to train a PyTorch video classification network with configurable epochs and batch size', 'run train_model with fine_tune=True to fine-tune a pretrained model on a new dataset', 'run train_model with resume_epoch to resume training from a saved checkpoint', 'run train_model with distributed=True to train across multiple GPUs using DDP', 'run train_model with precise_bn=True to compute precise batch norm statistics during training']
```

Usage

```
{'run_train_model': 'run train_model to train a PyTorch video classification network with configurable epochs and batch size', 'run_train_model_finetune': 'run train_model with fine_tune=True to fine-tune a pretrained model on a new dataset', 'run_train_model_resume': 'run train_model with resume_epoch to resume training from a saved checkpoint', 'run_train_model_distributed': 'run train_model with distributed=True to train across multiple GPUs using DDP', 'run_train_model_precise_bn': 'run train_model with precise_bn=True to compute precise batch norm statistics during training'}
```

