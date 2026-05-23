# Agent Python Tools

- repo: facebookresearch/robustcvd
- repo_uri: https://github.com/facebookresearch/robust_cvd

## File: facebookresearch_robustcvd/raft/evaluate.py

Prompts

```
['run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MpiSintel training split for clean and final types', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the Sintel leaderboard test split in .flo format', 'create optical flow submission files for the KITTI test split in the KITTI format', 'run optical flow estimation on stereo image pairs using the RAFT model with a given checkpoint', 'load a list of right image files and their corresponding left pairs as padded tensors on CUDA', 'visualize horizontal optical flow as an RGB image and save it to a PNG file', 'load a single image file from disk and convert it to a PyTorch tensor with channel-first format', 'extract horizontal flow values as disparity maps and save them as NumPy arrays', 'train a RAFT optical flow model on a specified dataset with configurable learning rate and iterations', 'compute the sequence loss over flow predictions with weighted temporal averaging and EPE metrics', 'create an AdamW optimizer and OneCycleLR scheduler for a RAFT model with configurable learning rate', 'log training metrics and loss values to TensorBoard at regular intervals during model training', 'count the number of trainable parameters in a PyTorch model for reporting and debugging']
```

Usage

```
{'run_validate_chairs': 'run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run_validate_sintel': 'run the RAFT model validation on the MpiSintel training split for clean and final types', 'run_validate_kitti': 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create_sintel_submission': 'create optical flow submission files for the Sintel leaderboard test split in .flo format', 'create_kitti_submission': 'create optical flow submission files for the KITTI test split in the KITTI format'}
```

## File: facebookresearch_robustcvd/raft/main.py

Prompts

```
['run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MpiSintel training split for clean and final types', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the Sintel leaderboard test split in .flo format', 'create optical flow submission files for the KITTI test split in the KITTI format', 'run optical flow estimation on stereo image pairs using the RAFT model with a given checkpoint', 'load a list of right image files and their corresponding left pairs as padded tensors on CUDA', 'visualize horizontal optical flow as an RGB image and save it to a PNG file', 'load a single image file from disk and convert it to a PyTorch tensor with channel-first format', 'extract horizontal flow values as disparity maps and save them as NumPy arrays', 'train a RAFT optical flow model on a specified dataset with configurable learning rate and iterations', 'compute the sequence loss over flow predictions with weighted temporal averaging and EPE metrics', 'create an AdamW optimizer and OneCycleLR scheduler for a RAFT model with configurable learning rate', 'log training metrics and loss values to TensorBoard at regular intervals during model training', 'count the number of trainable parameters in a PyTorch model for reporting and debugging']
```

Usage

```
{'run_stereo_flow_estimation': 'run optical flow estimation on stereo image pairs using the RAFT model with a given checkpoint', 'load_image_list': 'load a list of right image files and their corresponding left pairs as padded tensors on CUDA', 'viz_flow_map': 'visualize horizontal optical flow as an RGB image and save it to a PNG file', 'load_image': 'load a single image file from disk and convert it to a PyTorch tensor with channel-first format', 'extract_disparity': 'extract horizontal flow values as disparity maps and save them as NumPy arrays'}
```

## File: facebookresearch_robustcvd/raft/train.py

Prompts

```
['run the RAFT model validation on the FlyingChairs dataset and print EPE metrics', 'run the RAFT model validation on the MpiSintel training split for clean and final types', 'run the RAFT model validation on the KITTI-2015 training split and print EPE and F1 scores', 'create optical flow submission files for the Sintel leaderboard test split in .flo format', 'create optical flow submission files for the KITTI test split in the KITTI format', 'run optical flow estimation on stereo image pairs using the RAFT model with a given checkpoint', 'load a list of right image files and their corresponding left pairs as padded tensors on CUDA', 'visualize horizontal optical flow as an RGB image and save it to a PNG file', 'load a single image file from disk and convert it to a PyTorch tensor with channel-first format', 'extract horizontal flow values as disparity maps and save them as NumPy arrays', 'train a RAFT optical flow model on a specified dataset with configurable learning rate and iterations', 'compute the sequence loss over flow predictions with weighted temporal averaging and EPE metrics', 'create an AdamW optimizer and OneCycleLR scheduler for a RAFT model with configurable learning rate', 'log training metrics and loss values to TensorBoard at regular intervals during model training', 'count the number of trainable parameters in a PyTorch model for reporting and debugging']
```

Usage

```
{'train_RAFT_model': 'train a RAFT optical flow model on a specified dataset with configurable learning rate and iterations', 'compute_sequence_loss': 'compute the sequence loss over flow predictions with weighted temporal averaging and EPE metrics', 'create_optimizer_and_scheduler': 'create an AdamW optimizer and OneCycleLR scheduler for a RAFT model with configurable learning rate', 'log_training_metrics': 'log training metrics and loss values to TensorBoard at regular intervals during model training', 'count_model_parameters': 'count the number of trainable parameters in a PyTorch model for reporting and debugging'}
```

