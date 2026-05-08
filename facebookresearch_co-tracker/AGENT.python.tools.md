# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/hubconf.py

Prompts

```
['build a CoTracker3 offline predictor with pretrained weights for offline point tracking', 'build a CoTracker3 online predictor with pretrained weights for online point tracking', 'build a CoTracker2 offline predictor with window length 8 for point tracking', 'build a CoTracker2 online predictor with window length 8 for point tracking', 'build a CoTracker2v1 offline predictor with window length 16 for point tracking', 'run the CoTracker three model training loop on Kubric dataset with configurable batch size and learning rate', 'create an AdamW optimizer with OneCycleLR scheduler for the CoTracker model parameters', 'run a forward pass on a video batch to compute trajectory, visibility, and confidence predictions with loss', 'build a CoTrackerThreeOffline or CoTrackerThreeOnline model with configurable stride, correlation radius, and sliding window length', 'run evaluation on datasets like TAP-Vid DAVIS, RobotAP, and Kinetics using the Evaluator class', 'run the CoTracker model training loop on real video data using DDP strategy and teacher models', 'run a forward pass on a video batch using teacher model predictions as ground truth labels', 'run the optimizer setup to create an AdamW optimizer with OneCycleLR scheduler for the model', 'run the LightningLite-based training orchestrator that handles distributed training, checkpointing, and evaluation', 'run the CLI argument parser to configure model name, checkpoint paths, batch size, learning rate, and training steps']
```

Usage

```
{'build_cotracker3_offline_predictor': 'build a CoTracker3 offline predictor with pretrained weights for offline point tracking', 'build_cotracker3_online_predictor': 'build a CoTracker3 online predictor with pretrained weights for online point tracking', 'build_cotracker2_predictor': 'build a CoTracker2 offline predictor with window length 8 for point tracking', 'build_cotracker2_online_predictor': 'build a CoTracker2 online predictor with window length 8 for point tracking', 'build_cotracker2v1_predictor': 'build a CoTracker2v1 offline predictor with window length 16 for point tracking'}
```

## File: facebookresearch_co-tracker/train_on_kubric.py

Prompts

```
['build a CoTracker3 offline predictor with pretrained weights for offline point tracking', 'build a CoTracker3 online predictor with pretrained weights for online point tracking', 'build a CoTracker2 offline predictor with window length 8 for point tracking', 'build a CoTracker2 online predictor with window length 8 for point tracking', 'build a CoTracker2v1 offline predictor with window length 16 for point tracking', 'run the CoTracker three model training loop on Kubric dataset with configurable batch size and learning rate', 'create an AdamW optimizer with OneCycleLR scheduler for the CoTracker model parameters', 'run a forward pass on a video batch to compute trajectory, visibility, and confidence predictions with loss', 'build a CoTrackerThreeOffline or CoTrackerThreeOnline model with configurable stride, correlation radius, and sliding window length', 'run evaluation on datasets like TAP-Vid DAVIS, RobotAP, and Kinetics using the Evaluator class', 'run the CoTracker model training loop on real video data using DDP strategy and teacher models', 'run a forward pass on a video batch using teacher model predictions as ground truth labels', 'run the optimizer setup to create an AdamW optimizer with OneCycleLR scheduler for the model', 'run the LightningLite-based training orchestrator that handles distributed training, checkpointing, and evaluation', 'run the CLI argument parser to configure model name, checkpoint paths, batch size, learning rate, and training steps']
```

Usage

```
{'run_cotracker_training': 'run the CoTracker three model training loop on Kubric dataset with configurable batch size and learning rate', 'fetch_optimizer': 'create an AdamW optimizer with OneCycleLR scheduler for the CoTracker model parameters', 'forward_batch': 'run a forward pass on a video batch to compute trajectory, visibility, and confidence predictions with loss', 'configure_cotracker_model': 'build a CoTrackerThreeOffline or CoTrackerThreeOnline model with configurable stride, correlation radius, and sliding window length', 'evaluate_cotracker_model': 'run evaluation on datasets like TAP-Vid DAVIS, RobotAP, and Kinetics using the Evaluator class'}
```

## File: facebookresearch_co-tracker/train_on_real_data.py

Prompts

```
['build a CoTracker3 offline predictor with pretrained weights for offline point tracking', 'build a CoTracker3 online predictor with pretrained weights for online point tracking', 'build a CoTracker2 offline predictor with window length 8 for point tracking', 'build a CoTracker2 online predictor with window length 8 for point tracking', 'build a CoTracker2v1 offline predictor with window length 16 for point tracking', 'run the CoTracker three model training loop on Kubric dataset with configurable batch size and learning rate', 'create an AdamW optimizer with OneCycleLR scheduler for the CoTracker model parameters', 'run a forward pass on a video batch to compute trajectory, visibility, and confidence predictions with loss', 'build a CoTrackerThreeOffline or CoTrackerThreeOnline model with configurable stride, correlation radius, and sliding window length', 'run evaluation on datasets like TAP-Vid DAVIS, RobotAP, and Kinetics using the Evaluator class', 'run the CoTracker model training loop on real video data using DDP strategy and teacher models', 'run a forward pass on a video batch using teacher model predictions as ground truth labels', 'run the optimizer setup to create an AdamW optimizer with OneCycleLR scheduler for the model', 'run the LightningLite-based training orchestrator that handles distributed training, checkpointing, and evaluation', 'run the CLI argument parser to configure model name, checkpoint paths, batch size, learning rate, and training steps']
```

Usage

```
{'run_train_cotracker': 'run the CoTracker model training loop on real video data using DDP strategy and teacher models', 'run_forward_batch': 'run a forward pass on a video batch using teacher model predictions as ground truth labels', 'run_fetch_optimizer': 'run the optimizer setup to create an AdamW optimizer with OneCycleLR scheduler for the model', 'run_Lite_class': 'run the LightningLite-based training orchestrator that handles distributed training, checkpointing, and evaluation', 'run_argparse_cli': 'run the CLI argument parser to configure model name, checkpoint paths, batch size, learning rate, and training steps'}
```

