# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoVLPv2/trainer/trainer_charades.py

Prompts

```
['build a distributed multi-GPU trainer for Charades EgoVLPv2 video-language pretraining with dual task support', 'run a single training epoch with mixed precision, gradient scaling, and TensorBoard logging for Charades data', 'run validation on Charades data by computing video-text similarity matrices and mAP metrics across GPUs', 'review the AllGather_multi autograd function that performs distributed all-gather with gradient sharding across GPUs', 'refactor the learning rate scheduler to apply milestone-based decay to optimizer param groups', 'build a distributed multi-GPU trainer for EgoCLIP vision-language models with negative sampling and MLM support', 'run validation with ensemble VTC and VTM predictions gathered across all GPUs', 'create a custom autograd function that performs allgather on tensors across distributed GPUs', 'review the verbose function that logs epoch metrics and accuracy stats to a stats file', 'build a distributed multi-GPU trainer for EgoVLPv2 video-language retrieval on the EPIC-Kitchens dataset', 'create a custom PyTorch autograd function that performs all-gather across GPUs with gradient scattering', 'review the verbose function that logs nDCG and mAP metrics for video-to-text and text-to-video retrieval']
```

Usage

```
{'build_trainer_charades': 'build a distributed multi-GPU trainer for Charades EgoVLPv2 video-language pretraining with dual task support', 'run_train_epoch': 'run a single training epoch with mixed precision, gradient scaling, and TensorBoard logging for Charades data', 'run_validation_epoch': 'run validation on Charades data by computing video-text similarity matrices and mAP metrics across GPUs', 'review_allgather_multi': 'review the AllGather_multi autograd function that performs distributed all-gather with gradient sharding across GPUs', 'refactor_adjust_learning_rate': 'refactor the learning rate scheduler to apply milestone-based decay to optimizer param groups'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/trainer/trainer_egoclip.py

Prompts

```
['build a distributed multi-GPU trainer for Charades EgoVLPv2 video-language pretraining with dual task support', 'run a single training epoch with mixed precision, gradient scaling, and TensorBoard logging for Charades data', 'run validation on Charades data by computing video-text similarity matrices and mAP metrics across GPUs', 'review the AllGather_multi autograd function that performs distributed all-gather with gradient sharding across GPUs', 'refactor the learning rate scheduler to apply milestone-based decay to optimizer param groups', 'build a distributed multi-GPU trainer for EgoCLIP vision-language models with negative sampling and MLM support', 'run validation with ensemble VTC and VTM predictions gathered across all GPUs', 'create a custom autograd function that performs allgather on tensors across distributed GPUs', 'review the verbose function that logs epoch metrics and accuracy stats to a stats file', 'build a distributed multi-GPU trainer for EgoVLPv2 video-language retrieval on the EPIC-Kitchens dataset', 'create a custom PyTorch autograd function that performs all-gather across GPUs with gradient scattering', 'review the verbose function that logs nDCG and mAP metrics for video-to-text and text-to-video retrieval']
```

Usage

```
{'build_Multi_Trainer_dist': 'build a distributed multi-GPU trainer for EgoCLIP vision-language models with negative sampling and MLM support', 'run_train_epoch': 'run a single training epoch with mixed precision, gradient scaling, and multi-dataloader support', 'run_valid_epoch': 'run validation with ensemble VTC and VTM predictions gathered across all GPUs', 'create_AllGather_multi': 'create a custom autograd function that performs allgather on tensors across distributed GPUs', 'review_verbose_metrics': 'review the verbose function that logs epoch metrics and accuracy stats to a stats file'}
```

## File: facebookresearch_egovlpv2/EgoVLPv2/trainer/trainer_epic.py

Prompts

```
['build a distributed multi-GPU trainer for Charades EgoVLPv2 video-language pretraining with dual task support', 'run a single training epoch with mixed precision, gradient scaling, and TensorBoard logging for Charades data', 'run validation on Charades data by computing video-text similarity matrices and mAP metrics across GPUs', 'review the AllGather_multi autograd function that performs distributed all-gather with gradient sharding across GPUs', 'refactor the learning rate scheduler to apply milestone-based decay to optimizer param groups', 'build a distributed multi-GPU trainer for EgoCLIP vision-language models with negative sampling and MLM support', 'run validation with ensemble VTC and VTM predictions gathered across all GPUs', 'create a custom autograd function that performs allgather on tensors across distributed GPUs', 'review the verbose function that logs epoch metrics and accuracy stats to a stats file', 'build a distributed multi-GPU trainer for EgoVLPv2 video-language retrieval on the EPIC-Kitchens dataset', 'create a custom PyTorch autograd function that performs all-gather across GPUs with gradient scattering', 'review the verbose function that logs nDCG and mAP metrics for video-to-text and text-to-video retrieval']
```

Usage

```
{'build_trainer_for_epic_kitchens': 'build a distributed multi-GPU trainer for EgoVLPv2 video-language retrieval on the EPIC-Kitchens dataset', 'create_allgather_autograd_function': 'create a custom PyTorch autograd function that performs all-gather across GPUs with gradient scattering', 'run_train_epoch': 'run a single training epoch with mixed precision, tokenization, and gradient scaling for video-text dual tasks', 'run_validation_epoch': 'run validation to compute video-text similarity matrices and evaluate nDCG and mAP retrieval metrics', 'review_verbose_metrics_logging': 'review the verbose function that logs nDCG and mAP metrics for video-to-text and text-to-video retrieval'}
```

