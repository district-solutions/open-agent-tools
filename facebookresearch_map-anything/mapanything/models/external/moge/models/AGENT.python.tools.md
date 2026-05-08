# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/models/external/moge/models/modules.py

Prompts

```
['build a ResidualConvBlock with configurable normalization, activation, and skip connection for feature extraction', 'build a DINOv2Encoder to extract multi-scale vision features from RGB images with gradient checkpointing', 'build a Resampler module to upsample or downsample feature maps using pixel shuffle, bilinear, or conv transpose', 'build a ConvStack with residual blocks and resamplers for multi-scale feature processing and fusion', 'build an MLP module with configurable layer dimensions and ReLU activations for projection tasks', 'unproject UV coordinates to 3D view space points using OpenCV intrinsics and extrinsics matrices', 'convert a depth map to 3D points using camera intrinsics and optional extrinsics matrices', 'build an OpenCV intrinsics matrix from focal length and principal point parameters', 'generate normalized UV coordinates for a view plane grid given width, height, and aspect ratio', 'recover focal length and Z-axis shift from a point map using least squares optimization', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run the MoGeModel infer method on an image tensor to predict depth, points, and camera intrinsics', 'build a Head decoder module that upsamples ViT features to pixel-level point and mask predictions', 'enable gradient checkpointing on the MoGeModel backbone blocks to reduce memory during training', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run inference on an image to predict 3D points, depth, normals, and camera intrinsics', 'run a forward pass through the MoGeModel to get raw points, normals, mask, and metric scale', 'enable gradient checkpointing on the MoGeModel encoder, neck, and heads to save memory', 'remap raw model output points using linear, sinh, exp, or sinh_exp transformations']
```

Usage

```
{'build_residual_conv_block': 'build a ResidualConvBlock with configurable normalization, activation, and skip connection for feature extraction', 'build_dinov2_encoder': 'build a DINOv2Encoder to extract multi-scale vision features from RGB images with gradient checkpointing', 'build_resampler': 'build a Resampler module to upsample or downsample feature maps using pixel shuffle, bilinear, or conv transpose', 'build_conv_stack': 'build a ConvStack with residual blocks and resamplers for multi-scale feature processing and fusion', 'build_mlp': 'build an MLP module with configurable layer dimensions and ReLU activations for projection tasks'}
```

## File: facebookresearch_map-anything/mapanything/models/external/moge/models/utils.py

Prompts

```
['build a ResidualConvBlock with configurable normalization, activation, and skip connection for feature extraction', 'build a DINOv2Encoder to extract multi-scale vision features from RGB images with gradient checkpointing', 'build a Resampler module to upsample or downsample feature maps using pixel shuffle, bilinear, or conv transpose', 'build a ConvStack with residual blocks and resamplers for multi-scale feature processing and fusion', 'build an MLP module with configurable layer dimensions and ReLU activations for projection tasks', 'unproject UV coordinates to 3D view space points using OpenCV intrinsics and extrinsics matrices', 'convert a depth map to 3D points using camera intrinsics and optional extrinsics matrices', 'build an OpenCV intrinsics matrix from focal length and principal point parameters', 'generate normalized UV coordinates for a view plane grid given width, height, and aspect ratio', 'recover focal length and Z-axis shift from a point map using least squares optimization', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run the MoGeModel infer method on an image tensor to predict depth, points, and camera intrinsics', 'build a Head decoder module that upsamples ViT features to pixel-level point and mask predictions', 'enable gradient checkpointing on the MoGeModel backbone blocks to reduce memory during training', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run inference on an image to predict 3D points, depth, normals, and camera intrinsics', 'run a forward pass through the MoGeModel to get raw points, normals, mask, and metric scale', 'enable gradient checkpointing on the MoGeModel encoder, neck, and heads to save memory', 'remap raw model output points using linear, sinh, exp, or sinh_exp transformations']
```

Usage

```
{'unproject_cv_uv_to_3d': 'unproject UV coordinates to 3D view space points using OpenCV intrinsics and extrinsics matrices', 'depth_to_points_3d': 'convert a depth map to 3D points using camera intrinsics and optional extrinsics matrices', 'intrinsics_from_focal_center': 'build an OpenCV intrinsics matrix from focal length and principal point parameters', 'normalized_view_plane_uv': 'generate normalized UV coordinates for a view plane grid given width, height, and aspect ratio', 'recover_focal_shift': 'recover focal length and Z-axis shift from a point map using least squares optimization'}
```

## File: facebookresearch_map-anything/mapanything/models/external/moge/models/v1.py

Prompts

```
['build a ResidualConvBlock with configurable normalization, activation, and skip connection for feature extraction', 'build a DINOv2Encoder to extract multi-scale vision features from RGB images with gradient checkpointing', 'build a Resampler module to upsample or downsample feature maps using pixel shuffle, bilinear, or conv transpose', 'build a ConvStack with residual blocks and resamplers for multi-scale feature processing and fusion', 'build an MLP module with configurable layer dimensions and ReLU activations for projection tasks', 'unproject UV coordinates to 3D view space points using OpenCV intrinsics and extrinsics matrices', 'convert a depth map to 3D points using camera intrinsics and optional extrinsics matrices', 'build an OpenCV intrinsics matrix from focal length and principal point parameters', 'generate normalized UV coordinates for a view plane grid given width, height, and aspect ratio', 'recover focal length and Z-axis shift from a point map using least squares optimization', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run the MoGeModel infer method on an image tensor to predict depth, points, and camera intrinsics', 'build a Head decoder module that upsamples ViT features to pixel-level point and mask predictions', 'enable gradient checkpointing on the MoGeModel backbone blocks to reduce memory during training', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run inference on an image to predict 3D points, depth, normals, and camera intrinsics', 'run a forward pass through the MoGeModel to get raw points, normals, mask, and metric scale', 'enable gradient checkpointing on the MoGeModel encoder, neck, and heads to save memory', 'remap raw model output points using linear, sinh, exp, or sinh_exp transformations']
```

Usage

```
{'load_moge_model_from_pretrained': 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run_moge_inference': 'run the MoGeModel infer method on an image tensor to predict depth, points, and camera intrinsics', 'build_residual_conv_block': 'build a ResidualConvBlock with configurable activation, normalization, and channel dimensions for 2D feature processing', 'build_head_decoder': 'build a Head decoder module that upsamples ViT features to pixel-level point and mask predictions', 'enable_gradient_checkpointing': 'enable gradient checkpointing on the MoGeModel backbone blocks to reduce memory during training'}
```

## File: facebookresearch_map-anything/mapanything/models/external/moge/models/v2.py

Prompts

```
['build a ResidualConvBlock with configurable normalization, activation, and skip connection for feature extraction', 'build a DINOv2Encoder to extract multi-scale vision features from RGB images with gradient checkpointing', 'build a Resampler module to upsample or downsample feature maps using pixel shuffle, bilinear, or conv transpose', 'build a ConvStack with residual blocks and resamplers for multi-scale feature processing and fusion', 'build an MLP module with configurable layer dimensions and ReLU activations for projection tasks', 'unproject UV coordinates to 3D view space points using OpenCV intrinsics and extrinsics matrices', 'convert a depth map to 3D points using camera intrinsics and optional extrinsics matrices', 'build an OpenCV intrinsics matrix from focal length and principal point parameters', 'generate normalized UV coordinates for a view plane grid given width, height, and aspect ratio', 'recover focal length and Z-axis shift from a point map using least squares optimization', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run the MoGeModel infer method on an image tensor to predict depth, points, and camera intrinsics', 'build a Head decoder module that upsamples ViT features to pixel-level point and mask predictions', 'enable gradient checkpointing on the MoGeModel backbone blocks to reduce memory during training', 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run inference on an image to predict 3D points, depth, normals, and camera intrinsics', 'run a forward pass through the MoGeModel to get raw points, normals, mask, and metric scale', 'enable gradient checkpointing on the MoGeModel encoder, neck, and heads to save memory', 'remap raw model output points using linear, sinh, exp, or sinh_exp transformations']
```

Usage

```
{'load_pretrained_MoGeModel': 'load a pretrained MoGeModel from a HuggingFace repo or local checkpoint file', 'run_inference_MoGeModel_infer': 'run inference on an image to predict 3D points, depth, normals, and camera intrinsics', 'run_forward_MoGeModel_forward': 'run a forward pass through the MoGeModel to get raw points, normals, mask, and metric scale', 'configure_MoGeModel_gradient_checkpointing': 'enable gradient checkpointing on the MoGeModel encoder, neck, and heads to save memory', 'remap_points_MoGeModel_remap': 'remap raw model output points using linear, sinh, exp, or sinh_exp transformations'}
```

