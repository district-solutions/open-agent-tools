# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/RAFT/demo.py

Prompts

```
['run the RAFT demo to compute optical flow between image pairs in a directory', 'run the load_image function to load an image file as a CUDA PyTorch tensor', 'run the viz function to display an image alongside its optical flow visualization', 'run the demo function to load a RAFT checkpoint and infer flow on sorted image pairs', 'review the demo.py CLI arguments for model path, image path, small model, and mixed precision', 'run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MPI Sintel dataset for clean and final splits', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the MPI Sintel leaderboard test set', 'create optical flow submission files for the KITTI leaderboard test set', 'run the RAFT optical flow model training loop with configurable dataset and hyperparameters', 'create an AdamW optimizer with OneCycleLR scheduler for the RAFT model', 'compute the weighted sequence loss over multiple optical flow predictions with EPE metrics', 'count the number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'run_demo_optical_flow': 'run the RAFT demo to compute optical flow between image pairs in a directory', 'run_load_image': 'run the load_image function to load an image file as a CUDA PyTorch tensor', 'run_viz_flow': 'run the viz function to display an image alongside its optical flow visualization', 'run_demo_model_inference': 'run the demo function to load a RAFT checkpoint and infer flow on sorted image pairs', 'review_demo_cli': 'review the demo.py CLI arguments for model path, image path, small model, and mixed precision'}
```

## File: facebookresearch_localrf/RAFT/evaluate.py

Prompts

```
['run the RAFT demo to compute optical flow between image pairs in a directory', 'run the load_image function to load an image file as a CUDA PyTorch tensor', 'run the viz function to display an image alongside its optical flow visualization', 'run the demo function to load a RAFT checkpoint and infer flow on sorted image pairs', 'review the demo.py CLI arguments for model path, image path, small model, and mixed precision', 'run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MPI Sintel dataset for clean and final splits', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the MPI Sintel leaderboard test set', 'create optical flow submission files for the KITTI leaderboard test set', 'run the RAFT optical flow model training loop with configurable dataset and hyperparameters', 'create an AdamW optimizer with OneCycleLR scheduler for the RAFT model', 'compute the weighted sequence loss over multiple optical flow predictions with EPE metrics', 'count the number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'run_validate_chairs': 'run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run_validate_sintel': 'run the RAFT model validation on the MPI Sintel dataset for clean and final splits', 'run_validate_kitti': 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create_sintel_submission': 'create optical flow submission files for the MPI Sintel leaderboard test set', 'create_kitti_submission': 'create optical flow submission files for the KITTI leaderboard test set'}
```

## File: facebookresearch_localrf/RAFT/train.py

Prompts

```
['run the RAFT demo to compute optical flow between image pairs in a directory', 'run the load_image function to load an image file as a CUDA PyTorch tensor', 'run the viz function to display an image alongside its optical flow visualization', 'run the demo function to load a RAFT checkpoint and infer flow on sorted image pairs', 'review the demo.py CLI arguments for model path, image path, small model, and mixed precision', 'run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MPI Sintel dataset for clean and final splits', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the MPI Sintel leaderboard test set', 'create optical flow submission files for the KITTI leaderboard test set', 'run the RAFT optical flow model training loop with configurable dataset and hyperparameters', 'create an AdamW optimizer with OneCycleLR scheduler for the RAFT model', 'compute the weighted sequence loss over multiple optical flow predictions with EPE metrics', 'count the number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'run_train_raft': 'run the RAFT optical flow model training loop with configurable dataset and hyperparameters', 'create_optimizer': 'create an AdamW optimizer with OneCycleLR scheduler for the RAFT model', 'compute_sequence_loss': 'compute the weighted sequence loss over multiple optical flow predictions with EPE metrics', 'count_model_parameters': 'count the number of trainable parameters in a PyTorch model', 'log_training_metrics': 'log training metrics and validation results to TensorBoard using the Logger class'}
```

