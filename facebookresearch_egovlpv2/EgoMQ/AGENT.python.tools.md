# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoMQ/Infer.py

Prompts

```
['run the VSGN model inference pipeline on video temporal action detection data using a trained checkpoint', 'run batch inference with proposal selection on video clips using the VSGN model and parallel processing', 'run per-video inference to generate action proposals with NMS filtering and save results to CSV', 'run non-maximum suppression on temporal action detection proposals using IoU threshold filtering', 'run the EgoMQ inference script via argparse CLI to process video datasets with the VSGN model', 'run the VSGN model training loop with configurable epochs, learning rate, and checkpoint saving', 'run a single training epoch for the VSGN model with loss computation and backpropagation', 'run a single validation epoch for the VSGN model without gradient computation', 'run the main training script that parses options and starts VSGN model training', 'review the Train_VSGN function that orchestrates model training with DataParallel and checkpoint management']
```

Usage

```
{'run_Infer_SegTAD': 'run the VSGN model inference pipeline on video temporal action detection data using a trained checkpoint', 'run_infer_batch_selectprop': 'run batch inference with proposal selection on video clips using the VSGN model and parallel processing', 'run_infer_v_asis': 'run per-video inference to generate action proposals with NMS filtering and save results to CSV', 'run_nms': 'run non-maximum suppression on temporal action detection proposals using IoU threshold filtering', 'run_main': 'run the EgoMQ inference script via argparse CLI to process video datasets with the VSGN model'}
```

## File: facebookresearch_egovlpv2/EgoMQ/Train.py

Prompts

```
['run the VSGN model inference pipeline on video temporal action detection data using a trained checkpoint', 'run batch inference with proposal selection on video clips using the VSGN model and parallel processing', 'run per-video inference to generate action proposals with NMS filtering and save results to CSV', 'run non-maximum suppression on temporal action detection proposals using IoU threshold filtering', 'run the EgoMQ inference script via argparse CLI to process video datasets with the VSGN model', 'run the VSGN model training loop with configurable epochs, learning rate, and checkpoint saving', 'run a single training epoch for the VSGN model with loss computation and backpropagation', 'run a single validation epoch for the VSGN model without gradient computation', 'run the main training script that parses options and starts VSGN model training', 'review the Train_VSGN function that orchestrates model training with DataParallel and checkpoint management']
```

Usage

```
{'run_Train_VSGN': 'run the VSGN model training loop with configurable epochs, learning rate, and checkpoint saving', 'run_train_VSGN_epoch': 'run a single training epoch for the VSGN model with loss computation and backpropagation', 'run_test_VSGN_epoch': 'run a single validation epoch for the VSGN model without gradient computation', 'run_main_training': 'run the main training script that parses options and starts VSGN model training', 'review_Train_VSGN': 'review the Train_VSGN function that orchestrates model training with DataParallel and checkpoint management'}
```

