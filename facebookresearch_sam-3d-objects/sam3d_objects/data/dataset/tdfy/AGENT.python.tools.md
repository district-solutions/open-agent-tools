# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/data/dataset/tdfy/img_and_mask_transforms.py

Prompts

```
['create an RGBAImageProcessor to crop, resize, and normalize images with masks for model input', 'crop an image around a mask bounding box with configurable padding and box size factor', 'normalize a 3D pointmap using Scale-Shift Invariant normalization and return scale and shift values', 'apply random gaussian or resolution blur augmentation to an image and mask pair for data augmentation', 'resize an RGB image, mask, and pointmap to the same target size with proper interpolation', 'preprocess a batch of images by padding to square, resizing to target shape, and optionally normalizing with ResNet statistics', 'pad a non-square image tensor to a square shape by adding constant padding along the shorter dimension', 'pad a non-square image to a centered square shape with optional pointmap padding using NaN fill values', 'normalize image tensor values using standard ResNet mean and standard deviation statistics per channel', 'build a torchvision transform pipeline with random color jitter and Gaussian blur for image data augmentation', 'convert an InstancePose object to a PoseTarget using a specified convention class like ScaleShiftInvariant', 'convert a PoseTarget object back to an InstancePose using the PoseTargetConverter with the correct convention', 'create an InvariantPoseTarget from an InstancePose to decouple scene scale from invariant quantities', 'apply a Transform3d postcomposition to batched scale, rotation, and translation tensors using _broadcast_postcompose', 'normalize and denormalize pose values using LogScaleShiftNormalizer with configurable shift and scale log parameters', 'compose scale, rotation, and translation tensors into a single Transform3d object', 'decompose a Transform3d object into separate scale, rotation, and translation tensors', 'get a quaternion representing rotation about the X axis by a given angle', 'create a named tuple holding scale, rotation, and translation components of a 3D transform', 'review the transforms_3d module for composing and decomposing 3D spatial transformations']
```

Usage

```
{'create_rgba_image_processor': 'create an RGBAImageProcessor to crop, resize, and normalize images with masks for model input', 'crop_around_mask_with_padding': 'crop an image around a mask bounding box with configurable padding and box size factor', 'normalize_pointmap_ssi': 'normalize a 3D pointmap using Scale-Shift Invariant normalization and return scale and shift values', 'apply_blur_augmentation': 'apply random gaussian or resolution blur augmentation to an image and mask pair for data augmentation', 'resize_all_to_same_size': 'resize an RGB image, mask, and pointmap to the same target size with proper interpolation'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/data/dataset/tdfy/img_processing.py

Prompts

```
['create an RGBAImageProcessor to crop, resize, and normalize images with masks for model input', 'crop an image around a mask bounding box with configurable padding and box size factor', 'normalize a 3D pointmap using Scale-Shift Invariant normalization and return scale and shift values', 'apply random gaussian or resolution blur augmentation to an image and mask pair for data augmentation', 'resize an RGB image, mask, and pointmap to the same target size with proper interpolation', 'preprocess a batch of images by padding to square, resizing to target shape, and optionally normalizing with ResNet statistics', 'pad a non-square image tensor to a square shape by adding constant padding along the shorter dimension', 'pad a non-square image to a centered square shape with optional pointmap padding using NaN fill values', 'normalize image tensor values using standard ResNet mean and standard deviation statistics per channel', 'build a torchvision transform pipeline with random color jitter and Gaussian blur for image data augmentation', 'convert an InstancePose object to a PoseTarget using a specified convention class like ScaleShiftInvariant', 'convert a PoseTarget object back to an InstancePose using the PoseTargetConverter with the correct convention', 'create an InvariantPoseTarget from an InstancePose to decouple scene scale from invariant quantities', 'apply a Transform3d postcomposition to batched scale, rotation, and translation tensors using _broadcast_postcompose', 'normalize and denormalize pose values using LogScaleShiftNormalizer with configurable shift and scale log parameters', 'compose scale, rotation, and translation tensors into a single Transform3d object', 'decompose a Transform3d object into separate scale, rotation, and translation tensors', 'get a quaternion representing rotation about the X axis by a given angle', 'create a named tuple holding scale, rotation, and translation components of a 3D transform', 'review the transforms_3d module for composing and decomposing 3D spatial transformations']
```

Usage

```
{'preprocess_img': 'preprocess a batch of images by padding to square, resizing to target shape, and optionally normalizing with ResNet statistics', 'pad_to_square': 'pad a non-square image tensor to a square shape by adding constant padding along the shorter dimension', 'pad_to_square_centered': 'pad a non-square image to a centered square shape with optional pointmap padding using NaN fill values', 'resnet_img_normalization': 'normalize image tensor values using standard ResNet mean and standard deviation statistics per channel', 'get_img_color_augmentation': 'build a torchvision transform pipeline with random color jitter and Gaussian blur for image data augmentation'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/data/dataset/tdfy/pose_target.py

Prompts

```
['create an RGBAImageProcessor to crop, resize, and normalize images with masks for model input', 'crop an image around a mask bounding box with configurable padding and box size factor', 'normalize a 3D pointmap using Scale-Shift Invariant normalization and return scale and shift values', 'apply random gaussian or resolution blur augmentation to an image and mask pair for data augmentation', 'resize an RGB image, mask, and pointmap to the same target size with proper interpolation', 'preprocess a batch of images by padding to square, resizing to target shape, and optionally normalizing with ResNet statistics', 'pad a non-square image tensor to a square shape by adding constant padding along the shorter dimension', 'pad a non-square image to a centered square shape with optional pointmap padding using NaN fill values', 'normalize image tensor values using standard ResNet mean and standard deviation statistics per channel', 'build a torchvision transform pipeline with random color jitter and Gaussian blur for image data augmentation', 'convert an InstancePose object to a PoseTarget using a specified convention class like ScaleShiftInvariant', 'convert a PoseTarget object back to an InstancePose using the PoseTargetConverter with the correct convention', 'create an InvariantPoseTarget from an InstancePose to decouple scene scale from invariant quantities', 'apply a Transform3d postcomposition to batched scale, rotation, and translation tensors using _broadcast_postcompose', 'normalize and denormalize pose values using LogScaleShiftNormalizer with configurable shift and scale log parameters', 'compose scale, rotation, and translation tensors into a single Transform3d object', 'decompose a Transform3d object into separate scale, rotation, and translation tensors', 'get a quaternion representing rotation about the X axis by a given angle', 'create a named tuple holding scale, rotation, and translation components of a 3D transform', 'review the transforms_3d module for composing and decomposing 3D spatial transformations']
```

Usage

```
{'convert_instance_pose_to_pose_target': 'convert an InstancePose object to a PoseTarget using a specified convention class like ScaleShiftInvariant', 'convert_pose_target_to_instance_pose': 'convert a PoseTarget object back to an InstancePose using the PoseTargetConverter with the correct convention', 'create_invariant_pose_target': 'create an InvariantPoseTarget from an InstancePose to decouple scene scale from invariant quantities', 'apply_broadcast_postcompose_transform': 'apply a Transform3d postcomposition to batched scale, rotation, and translation tensors using _broadcast_postcompose', 'normalize_pose_with_log_scale_shift': 'normalize and denormalize pose values using LogScaleShiftNormalizer with configurable shift and scale log parameters'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/data/dataset/tdfy/transforms_3d.py

Prompts

```
['create an RGBAImageProcessor to crop, resize, and normalize images with masks for model input', 'crop an image around a mask bounding box with configurable padding and box size factor', 'normalize a 3D pointmap using Scale-Shift Invariant normalization and return scale and shift values', 'apply random gaussian or resolution blur augmentation to an image and mask pair for data augmentation', 'resize an RGB image, mask, and pointmap to the same target size with proper interpolation', 'preprocess a batch of images by padding to square, resizing to target shape, and optionally normalizing with ResNet statistics', 'pad a non-square image tensor to a square shape by adding constant padding along the shorter dimension', 'pad a non-square image to a centered square shape with optional pointmap padding using NaN fill values', 'normalize image tensor values using standard ResNet mean and standard deviation statistics per channel', 'build a torchvision transform pipeline with random color jitter and Gaussian blur for image data augmentation', 'convert an InstancePose object to a PoseTarget using a specified convention class like ScaleShiftInvariant', 'convert a PoseTarget object back to an InstancePose using the PoseTargetConverter with the correct convention', 'create an InvariantPoseTarget from an InstancePose to decouple scene scale from invariant quantities', 'apply a Transform3d postcomposition to batched scale, rotation, and translation tensors using _broadcast_postcompose', 'normalize and denormalize pose values using LogScaleShiftNormalizer with configurable shift and scale log parameters', 'compose scale, rotation, and translation tensors into a single Transform3d object', 'decompose a Transform3d object into separate scale, rotation, and translation tensors', 'get a quaternion representing rotation about the X axis by a given angle', 'create a named tuple holding scale, rotation, and translation components of a 3D transform', 'review the transforms_3d module for composing and decomposing 3D spatial transformations']
```

Usage

```
{'compose_transform': 'compose scale, rotation, and translation tensors into a single Transform3d object', 'decompose_transform': 'decompose a Transform3d object into separate scale, rotation, and translation tensors', 'get_rotation_about_x_axis': 'get a quaternion representing rotation about the X axis by a given angle', 'DecomposedTransform': 'create a named tuple holding scale, rotation, and translation components of a 3D transform', 'review_transforms_3d': 'review the transforms_3d module for composing and decomposing 3D spatial transformations'}
```

