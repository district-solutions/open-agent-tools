# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/models/necks/fmap_proc_neck.py

Prompts

```
['create a FeatureMapProcessor to select, concatenate, and rescale feature maps in a pose estimation model', 'run the forward pass selecting specific feature map indices from a sequence of tensors', 'run the forward pass concatenating multiple feature maps along the channel dimension', 'run the forward pass rescaling feature maps by a given scale factor using bilinear interpolation', 'run the forward pass applying ReLU activation to input feature maps before processing', 'build a Feature Pyramid Network with lateral and fpn convs for multi-scale feature extraction', 'create an FPN instance with extra conv layers on input for RetinaNet style detection', 'run a forward pass through FPN with multi-scale backbone feature tensor inputs', 'review the FPN class init_weights method that applies Xavier uniform initialization to conv layers', 'refactor the FPN forward method to use scale_factor or size based upsampling interpolation', 'build a python module to create a GlobalAveragePooling neck for MMPose model architectures', 'create a function that applies global average pooling to a single torch tensor input', 'create a function that applies global average pooling to a tuple of torch tensor inputs', 'create a function that applies global average pooling to a list of torch tensor inputs', 'review the GlobalAveragePooling class init_weights method for custom weight initialization logic', 'build a PoseWarperNeck module with configurable in_channels, out_channels, and deform_groups for temporal pose estimation', 'create a forward pass through PoseWarperNeck using input feature lists and frame weights', 'test the PoseWarperNeck init_weights method to verify Conv2d and DeformConv2d parameter initialization', 'review the PoseWarperNeck freeze_layers method that freezes the transition layer parameters', 'refactor the PoseWarperNeck _transform_inputs method to support resize_concat and multiple_select input transformations']
```

Usage

```
{'create_feature_map_processor': 'create a FeatureMapProcessor to select, concatenate, and rescale feature maps in a pose estimation model', 'run_forward_with_select_index': 'run the forward pass selecting specific feature map indices from a sequence of tensors', 'run_forward_with_concat': 'run the forward pass concatenating multiple feature maps along the channel dimension', 'run_forward_with_rescale': 'run the forward pass rescaling feature maps by a given scale factor using bilinear interpolation', 'run_forward_with_relu': 'run the forward pass applying ReLU activation to input feature maps before processing'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/necks/fpn.py

Prompts

```
['create a FeatureMapProcessor to select, concatenate, and rescale feature maps in a pose estimation model', 'run the forward pass selecting specific feature map indices from a sequence of tensors', 'run the forward pass concatenating multiple feature maps along the channel dimension', 'run the forward pass rescaling feature maps by a given scale factor using bilinear interpolation', 'run the forward pass applying ReLU activation to input feature maps before processing', 'build a Feature Pyramid Network with lateral and fpn convs for multi-scale feature extraction', 'create an FPN instance with extra conv layers on input for RetinaNet style detection', 'run a forward pass through FPN with multi-scale backbone feature tensor inputs', 'review the FPN class init_weights method that applies Xavier uniform initialization to conv layers', 'refactor the FPN forward method to use scale_factor or size based upsampling interpolation', 'build a python module to create a GlobalAveragePooling neck for MMPose model architectures', 'create a function that applies global average pooling to a single torch tensor input', 'create a function that applies global average pooling to a tuple of torch tensor inputs', 'create a function that applies global average pooling to a list of torch tensor inputs', 'review the GlobalAveragePooling class init_weights method for custom weight initialization logic', 'build a PoseWarperNeck module with configurable in_channels, out_channels, and deform_groups for temporal pose estimation', 'create a forward pass through PoseWarperNeck using input feature lists and frame weights', 'test the PoseWarperNeck init_weights method to verify Conv2d and DeformConv2d parameter initialization', 'review the PoseWarperNeck freeze_layers method that freezes the transition layer parameters', 'refactor the PoseWarperNeck _transform_inputs method to support resize_concat and multiple_select input transformations']
```

Usage

```
{'build_FPN_feature_pyramid': 'build a Feature Pyramid Network with lateral and fpn convs for multi-scale feature extraction', 'create_FPN_with_extra_convs': 'create an FPN instance with extra conv layers on input for RetinaNet style detection', 'run_FPN_forward_pass': 'run a forward pass through FPN with multi-scale backbone feature tensor inputs', 'review_FPN_init_weights': 'review the FPN class init_weights method that applies Xavier uniform initialization to conv layers', 'refactor_FPN_upsample_config': 'refactor the FPN forward method to use scale_factor or size based upsampling interpolation'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/necks/gap_neck.py

Prompts

```
['create a FeatureMapProcessor to select, concatenate, and rescale feature maps in a pose estimation model', 'run the forward pass selecting specific feature map indices from a sequence of tensors', 'run the forward pass concatenating multiple feature maps along the channel dimension', 'run the forward pass rescaling feature maps by a given scale factor using bilinear interpolation', 'run the forward pass applying ReLU activation to input feature maps before processing', 'build a Feature Pyramid Network with lateral and fpn convs for multi-scale feature extraction', 'create an FPN instance with extra conv layers on input for RetinaNet style detection', 'run a forward pass through FPN with multi-scale backbone feature tensor inputs', 'review the FPN class init_weights method that applies Xavier uniform initialization to conv layers', 'refactor the FPN forward method to use scale_factor or size based upsampling interpolation', 'build a python module to create a GlobalAveragePooling neck for MMPose model architectures', 'create a function that applies global average pooling to a single torch tensor input', 'create a function that applies global average pooling to a tuple of torch tensor inputs', 'create a function that applies global average pooling to a list of torch tensor inputs', 'review the GlobalAveragePooling class init_weights method for custom weight initialization logic', 'build a PoseWarperNeck module with configurable in_channels, out_channels, and deform_groups for temporal pose estimation', 'create a forward pass through PoseWarperNeck using input feature lists and frame weights', 'test the PoseWarperNeck init_weights method to verify Conv2d and DeformConv2d parameter initialization', 'review the PoseWarperNeck freeze_layers method that freezes the transition layer parameters', 'refactor the PoseWarperNeck _transform_inputs method to support resize_concat and multiple_select input transformations']
```

Usage

```
{'build_GAP_neck': 'build a python module to create a GlobalAveragePooling neck for MMPose model architectures', 'create_GAP_forward_tensor': 'create a function that applies global average pooling to a single torch tensor input', 'create_GAP_forward_tuple': 'create a function that applies global average pooling to a tuple of torch tensor inputs', 'create_GAP_forward_list': 'create a function that applies global average pooling to a list of torch tensor inputs', 'review_GAP_init_weights': 'review the GlobalAveragePooling class init_weights method for custom weight initialization logic'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/necks/posewarper_neck.py

Prompts

```
['create a FeatureMapProcessor to select, concatenate, and rescale feature maps in a pose estimation model', 'run the forward pass selecting specific feature map indices from a sequence of tensors', 'run the forward pass concatenating multiple feature maps along the channel dimension', 'run the forward pass rescaling feature maps by a given scale factor using bilinear interpolation', 'run the forward pass applying ReLU activation to input feature maps before processing', 'build a Feature Pyramid Network with lateral and fpn convs for multi-scale feature extraction', 'create an FPN instance with extra conv layers on input for RetinaNet style detection', 'run a forward pass through FPN with multi-scale backbone feature tensor inputs', 'review the FPN class init_weights method that applies Xavier uniform initialization to conv layers', 'refactor the FPN forward method to use scale_factor or size based upsampling interpolation', 'build a python module to create a GlobalAveragePooling neck for MMPose model architectures', 'create a function that applies global average pooling to a single torch tensor input', 'create a function that applies global average pooling to a tuple of torch tensor inputs', 'create a function that applies global average pooling to a list of torch tensor inputs', 'review the GlobalAveragePooling class init_weights method for custom weight initialization logic', 'build a PoseWarperNeck module with configurable in_channels, out_channels, and deform_groups for temporal pose estimation', 'create a forward pass through PoseWarperNeck using input feature lists and frame weights', 'test the PoseWarperNeck init_weights method to verify Conv2d and DeformConv2d parameter initialization', 'review the PoseWarperNeck freeze_layers method that freezes the transition layer parameters', 'refactor the PoseWarperNeck _transform_inputs method to support resize_concat and multiple_select input transformations']
```

Usage

```
{'build_PoseWarperNeck': 'build a PoseWarperNeck module with configurable in_channels, out_channels, and deform_groups for temporal pose estimation', 'create_PoseWarperNeck_forward': 'create a forward pass through PoseWarperNeck using input feature lists and frame weights', 'test_PoseWarperNeck_init_weights': 'test the PoseWarperNeck init_weights method to verify Conv2d and DeformConv2d parameter initialization', 'review_PoseWarperNeck_freeze_layers': 'review the PoseWarperNeck freeze_layers method that freezes the transition layer parameters', 'refactor_PoseWarperNeck_transform_inputs': 'refactor the PoseWarperNeck _transform_inputs method to support resize_concat and multiple_select input transformations'}
```

