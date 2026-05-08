# Agent Python Tools

- repo: facebookresearch/posediffusion
- repo_uri: https://github.com/facebookresearch/posediffusion

## File: facebookresearch_posediffusion/pose_diffusion/demo.py

Prompts

```
['run the pose diffusion demo to predict camera poses from a folder of images', 'extract keypoint matches between images in a folder for geometry-guided sampling', 'load and preprocess images from a folder into tensors for the model', 'perform geometry-guided sampling using extracted keypoint matches to condition pose prediction', 'compute the absolute rotation error between predicted and ground truth camera rotations', 'run the test_fn to evaluate a pose diffusion model on Co3D dataset categories with Hydra config', 'run _test_one_category to test the model on a single object category and collect rotation and translation errors', 'run prefix_with_module to add a module. prefix to all keys in a PyTorch checkpoint state dict', 'review the test_fn function that orchestrates model evaluation across multiple categories with AUC and accuracy metrics', 'review _test_one_category which loads sequences, extracts matches, runs inference, and computes camera alignment errors', 'run the pose diffusion model training loop with Hydra config and HuggingFace Accelerator for multi-GPU support', 'run evaluation on the pose diffusion model to compute rotation and translation accuracy metrics', 'create a DynamicBatchSampler DataLoader that groups sequences by length for efficient batch processing', 'compute relative rotation and translation angle accuracy metrics including Racc, Tacc, and AUC scores', 'resume pose diffusion model training from a saved checkpoint with state dict loading']
```

Usage

```
{'run_demo': 'run the pose diffusion demo to predict camera poses from a folder of images', 'extract_match': 'extract keypoint matches between images in a folder for geometry-guided sampling', 'load_and_preprocess_images': 'load and preprocess images from a folder into tensors for the model', 'geometry_guided_sampling': 'perform geometry-guided sampling using extracted keypoint matches to condition pose prediction', 'compute_ARE': 'compute the absolute rotation error between predicted and ground truth camera rotations'}
```

## File: facebookresearch_posediffusion/pose_diffusion/test.py

Prompts

```
['run the pose diffusion demo to predict camera poses from a folder of images', 'extract keypoint matches between images in a folder for geometry-guided sampling', 'load and preprocess images from a folder into tensors for the model', 'perform geometry-guided sampling using extracted keypoint matches to condition pose prediction', 'compute the absolute rotation error between predicted and ground truth camera rotations', 'run the test_fn to evaluate a pose diffusion model on Co3D dataset categories with Hydra config', 'run _test_one_category to test the model on a single object category and collect rotation and translation errors', 'run prefix_with_module to add a module. prefix to all keys in a PyTorch checkpoint state dict', 'review the test_fn function that orchestrates model evaluation across multiple categories with AUC and accuracy metrics', 'review _test_one_category which loads sequences, extracts matches, runs inference, and computes camera alignment errors', 'run the pose diffusion model training loop with Hydra config and HuggingFace Accelerator for multi-GPU support', 'run evaluation on the pose diffusion model to compute rotation and translation accuracy metrics', 'create a DynamicBatchSampler DataLoader that groups sequences by length for efficient batch processing', 'compute relative rotation and translation angle accuracy metrics including Racc, Tacc, and AUC scores', 'resume pose diffusion model training from a saved checkpoint with state dict loading']
```

Usage

```
{'run_test_fn': 'run the test_fn to evaluate a pose diffusion model on Co3D dataset categories with Hydra config', 'run_test_one_category': 'run _test_one_category to test the model on a single object category and collect rotation and translation errors', 'run_prefix_with_module': 'run prefix_with_module to add a module. prefix to all keys in a PyTorch checkpoint state dict', 'review_test_fn': 'review the test_fn function that orchestrates model evaluation across multiple categories with AUC and accuracy metrics', 'review_test_one_category': 'review _test_one_category which loads sequences, extracts matches, runs inference, and computes camera alignment errors'}
```

## File: facebookresearch_posediffusion/pose_diffusion/train.py

Prompts

```
['run the pose diffusion demo to predict camera poses from a folder of images', 'extract keypoint matches between images in a folder for geometry-guided sampling', 'load and preprocess images from a folder into tensors for the model', 'perform geometry-guided sampling using extracted keypoint matches to condition pose prediction', 'compute the absolute rotation error between predicted and ground truth camera rotations', 'run the test_fn to evaluate a pose diffusion model on Co3D dataset categories with Hydra config', 'run _test_one_category to test the model on a single object category and collect rotation and translation errors', 'run prefix_with_module to add a module. prefix to all keys in a PyTorch checkpoint state dict', 'review the test_fn function that orchestrates model evaluation across multiple categories with AUC and accuracy metrics', 'review _test_one_category which loads sequences, extracts matches, runs inference, and computes camera alignment errors', 'run the pose diffusion model training loop with Hydra config and HuggingFace Accelerator for multi-GPU support', 'run evaluation on the pose diffusion model to compute rotation and translation accuracy metrics', 'create a DynamicBatchSampler DataLoader that groups sequences by length for efficient batch processing', 'compute relative rotation and translation angle accuracy metrics including Racc, Tacc, and AUC scores', 'resume pose diffusion model training from a saved checkpoint with state dict loading']
```

Usage

```
{'train_pose_diffusion_model': 'run the pose diffusion model training loop with Hydra config and HuggingFace Accelerator for multi-GPU support', 'evaluate_camera_predictions': 'run evaluation on the pose diffusion model to compute rotation and translation accuracy metrics', 'create_dynamic_batch_sampler': 'create a DynamicBatchSampler DataLoader that groups sequences by length for efficient batch processing', 'compute_camera_accuracy_metrics': 'compute relative rotation and translation angle accuracy metrics including Racc, Tacc, and AUC scores', 'resume_training_from_checkpoint': 'resume pose diffusion model training from a saved checkpoint with state dict loading'}
```

