# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/bodymocap/train/eftFitter.py

Prompts

```
['run EFT fitting on all samples in the training dataset and export results as pickle files', 'run SMPLify optimization on all samples in the dataset using weak perspective projection and 2D keypoints', 'run a single EFT training step with 2D and 3D keypoint loss on a batch of images', 'run a single EFT training step that includes 3D hand joint loss for SMPL-X hand fitting', 'compute the 3D keypoint reconstruction loss for Panoptic DB body and hand joints with confidence weighting', 'create a FitsDict instance to track best SMPL pose fits per image in the training set', 'save the FitsDict state to disk as numpy arrays in the checkpoint directory', 'retrieve pose, betas, and validity tensors from the FitsDict for a batch of images', 'update FitsDict entries with new pose and betas parameters after undoing flip and rotation', 'flip SMPL pose parameters by permuting joints and negating axis-angle dimensions for mirrored images', 'run the Trainer train_step method to perform a training iteration with SMPL parameter prediction and backpropagation', 'compute the 2D reprojection loss on predicted keypoints weighted by openpose and ground truth confidence scores', 'run the test method to evaluate the trained model on a dataset and return reconstruction error in millimeters', 'compute the SMPL pose and beta parameter regression loss using rotation matrix and MSE criteria']
```

Usage

```
{'run_eft_fitting': 'run EFT fitting on all samples in the training dataset and export results as pickle files', 'run_smplify_fitting': 'run SMPLify optimization on all samples in the dataset using weak perspective projection and 2D keypoints', 'run_eft_step': 'run a single EFT training step with 2D and 3D keypoint loss on a batch of images', 'run_eft_step_with_hand': 'run a single EFT training step that includes 3D hand joint loss for SMPL-X hand fitting', 'compute_3d_keypoint_loss': 'compute the 3D keypoint reconstruction loss for Panoptic DB body and hand joints with confidence weighting'}
```

## File: facebookresearch_eft/bodymocap/train/fits_dict.py

Prompts

```
['run EFT fitting on all samples in the training dataset and export results as pickle files', 'run SMPLify optimization on all samples in the dataset using weak perspective projection and 2D keypoints', 'run a single EFT training step with 2D and 3D keypoint loss on a batch of images', 'run a single EFT training step that includes 3D hand joint loss for SMPL-X hand fitting', 'compute the 3D keypoint reconstruction loss for Panoptic DB body and hand joints with confidence weighting', 'create a FitsDict instance to track best SMPL pose fits per image in the training set', 'save the FitsDict state to disk as numpy arrays in the checkpoint directory', 'retrieve pose, betas, and validity tensors from the FitsDict for a batch of images', 'update FitsDict entries with new pose and betas parameters after undoing flip and rotation', 'flip SMPL pose parameters by permuting joints and negating axis-angle dimensions for mirrored images', 'run the Trainer train_step method to perform a training iteration with SMPL parameter prediction and backpropagation', 'compute the 2D reprojection loss on predicted keypoints weighted by openpose and ground truth confidence scores', 'run the test method to evaluate the trained model on a dataset and return reconstruction error in millimeters', 'compute the SMPL pose and beta parameter regression loss using rotation matrix and MSE criteria']
```

Usage

```
{'create_FitsDict': 'create a FitsDict instance to track best SMPL pose fits per image in the training set', 'save_FitsDict': 'save the FitsDict state to disk as numpy arrays in the checkpoint directory', 'retrieve_FitsDict_getitem': 'retrieve pose, betas, and validity tensors from the FitsDict for a batch of images', 'update_FitsDict_setitem': 'update FitsDict entries with new pose and betas parameters after undoing flip and rotation', 'flip_pose_SMPL': 'flip SMPL pose parameters by permuting joints and negating axis-angle dimensions for mirrored images'}
```

## File: facebookresearch_eft/bodymocap/train/trainer.py

Prompts

```
['run EFT fitting on all samples in the training dataset and export results as pickle files', 'run SMPLify optimization on all samples in the dataset using weak perspective projection and 2D keypoints', 'run a single EFT training step with 2D and 3D keypoint loss on a batch of images', 'run a single EFT training step that includes 3D hand joint loss for SMPL-X hand fitting', 'compute the 3D keypoint reconstruction loss for Panoptic DB body and hand joints with confidence weighting', 'create a FitsDict instance to track best SMPL pose fits per image in the training set', 'save the FitsDict state to disk as numpy arrays in the checkpoint directory', 'retrieve pose, betas, and validity tensors from the FitsDict for a batch of images', 'update FitsDict entries with new pose and betas parameters after undoing flip and rotation', 'flip SMPL pose parameters by permuting joints and negating axis-angle dimensions for mirrored images', 'run the Trainer train_step method to perform a training iteration with SMPL parameter prediction and backpropagation', 'compute the 2D reprojection loss on predicted keypoints weighted by openpose and ground truth confidence scores', 'run the test method to evaluate the trained model on a dataset and return reconstruction error in millimeters', 'compute the SMPL pose and beta parameter regression loss using rotation matrix and MSE criteria']
```

Usage

```
{'train_human_mesh_recovery': 'run the Trainer train_step method to perform a training iteration with SMPL parameter prediction and backpropagation', 'compute_2d_keypoint_loss': 'compute the 2D reprojection loss on predicted keypoints weighted by openpose and ground truth confidence scores', 'compute_3d_keypoint_loss': 'compute the 3D keypoint loss for examples with valid 3D pose annotations using pelvis-centered coordinates', 'run_evaluation_test': 'run the test method to evaluate the trained model on a dataset and return reconstruction error in millimeters', 'compute_smpl_parameter_loss': 'compute the SMPL pose and beta parameter regression loss using rotation matrix and MSE criteria'}
```

