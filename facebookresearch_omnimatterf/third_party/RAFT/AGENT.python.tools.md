# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RAFT/demo.py

Prompts

```
['run the RAFT optical flow demo on a directory of images using a pretrained model checkpoint', 'load an image file from disk and convert it to a CUDA PyTorch tensor batch', 'visualize an image and its computed optical flow side by side using OpenCV', 'run the RAFT model on a pair of padded images to compute optical flow in test mode', 'pad a pair of images to dimensions compatible with the RAFT model using InputPadder', 'validate a RAFT optical flow model on the FlyingChairs dataset and print the EPE score', 'validate a RAFT optical flow model on the Sintel training split for clean and final types', 'validate a RAFT optical flow model on the KITTI-2015 training split and report EPE and F1', 'create a Sintel leaderboard submission by running optical flow inference on the test split', 'create a KITTI leaderboard submission by running optical flow inference on the KITTI test split', 'run the RAFT optical flow model training loop with configurable datasets and mixed precision', 'create an AdamW optimizer and OneCycleLR scheduler for a PyTorch model using training args', 'compute the weighted sequence loss and EPE metrics over multiple optical flow predictions', 'count the total number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'run_demo_optical_flow': 'run the RAFT optical flow demo on a directory of images using a pretrained model checkpoint', 'load_image_to_tensor': 'load an image file from disk and convert it to a CUDA PyTorch tensor batch', 'visualize_flow': 'visualize an image and its computed optical flow side by side using OpenCV', 'run_raft_model_inference': 'run the RAFT model on a pair of padded images to compute optical flow in test mode', 'pad_images_for_raft': 'pad a pair of images to dimensions compatible with the RAFT model using InputPadder'}
```

## File: facebookresearch_omnimatterf/third_party/RAFT/evaluate.py

Prompts

```
['run the RAFT optical flow demo on a directory of images using a pretrained model checkpoint', 'load an image file from disk and convert it to a CUDA PyTorch tensor batch', 'visualize an image and its computed optical flow side by side using OpenCV', 'run the RAFT model on a pair of padded images to compute optical flow in test mode', 'pad a pair of images to dimensions compatible with the RAFT model using InputPadder', 'validate a RAFT optical flow model on the FlyingChairs dataset and print the EPE score', 'validate a RAFT optical flow model on the Sintel training split for clean and final types', 'validate a RAFT optical flow model on the KITTI-2015 training split and report EPE and F1', 'create a Sintel leaderboard submission by running optical flow inference on the test split', 'create a KITTI leaderboard submission by running optical flow inference on the KITTI test split', 'run the RAFT optical flow model training loop with configurable datasets and mixed precision', 'create an AdamW optimizer and OneCycleLR scheduler for a PyTorch model using training args', 'compute the weighted sequence loss and EPE metrics over multiple optical flow predictions', 'count the total number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'validate_chairs': 'validate a RAFT optical flow model on the FlyingChairs dataset and print the EPE score', 'validate_sintel': 'validate a RAFT optical flow model on the Sintel training split for clean and final types', 'validate_kitti': 'validate a RAFT optical flow model on the KITTI-2015 training split and report EPE and F1', 'create_sintel_submission': 'create a Sintel leaderboard submission by running optical flow inference on the test split', 'create_kitti_submission': 'create a KITTI leaderboard submission by running optical flow inference on the KITTI test split'}
```

## File: facebookresearch_omnimatterf/third_party/RAFT/train.py

Prompts

```
['run the RAFT optical flow demo on a directory of images using a pretrained model checkpoint', 'load an image file from disk and convert it to a CUDA PyTorch tensor batch', 'visualize an image and its computed optical flow side by side using OpenCV', 'run the RAFT model on a pair of padded images to compute optical flow in test mode', 'pad a pair of images to dimensions compatible with the RAFT model using InputPadder', 'validate a RAFT optical flow model on the FlyingChairs dataset and print the EPE score', 'validate a RAFT optical flow model on the Sintel training split for clean and final types', 'validate a RAFT optical flow model on the KITTI-2015 training split and report EPE and F1', 'create a Sintel leaderboard submission by running optical flow inference on the test split', 'create a KITTI leaderboard submission by running optical flow inference on the KITTI test split', 'run the RAFT optical flow model training loop with configurable datasets and mixed precision', 'create an AdamW optimizer and OneCycleLR scheduler for a PyTorch model using training args', 'compute the weighted sequence loss and EPE metrics over multiple optical flow predictions', 'count the total number of trainable parameters in a PyTorch model', 'log training metrics and validation results to TensorBoard using the Logger class']
```

Usage

```
{'run_RAFT_training': 'run the RAFT optical flow model training loop with configurable datasets and mixed precision', 'create_optimizer_with_scheduler': 'create an AdamW optimizer and OneCycleLR scheduler for a PyTorch model using training args', 'compute_sequence_loss': 'compute the weighted sequence loss and EPE metrics over multiple optical flow predictions', 'count_trainable_parameters': 'count the total number of trainable parameters in a PyTorch model', 'log_training_metrics': 'log training metrics and validation results to TensorBoard using the Logger class'}
```

