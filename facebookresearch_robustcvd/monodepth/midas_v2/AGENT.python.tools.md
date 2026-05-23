# Agent Python Tools

- repo: facebookresearch/robustcvd
- repo_uri: https://github.com/facebookresearch/robust_cvd

## File: facebookresearch_robustcvd/monodepth/midas_v2/base_model.py

Prompts

```
['load PyTorch model weights from a checkpoint file path into a BaseModel instance', 'create a subclass of BaseModel that inherits the load method for loading model state dicts', 'review the BaseModel load method to understand how it handles optimizer and model keys in checkpoints', 'refactor the BaseModel load method to support additional checkpoint formats beyond optimizer and model keys', 'test the BaseModel load method by loading a checkpoint file and verifying the state dict was applied', 'build a MiDaS encoder using _make_encoder with a ResNeXt-101 WSL pretrained backbone and scratch layers', 'create scratch Conv2d layers from in_shape channels to a uniform out_shape using _make_scratch', 'build an Interpolate nn.Module that upscales a tensor by a given scale_factor and interpolation mode', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU that adds input as a residual', 'build a FeatureFusionBlock that fuses two feature tensors via residual conv units and upsamples by 2x', 'create a MidasNet model for monocular depth estimation with optional pretrained weights path', 'run a forward pass through MidasNet to predict depth from an input image tensor', 'review the MidasNet constructor to understand feature count, non-negative output, and pretrained backbone options', 'test loading pretrained model weights into MidasNet from a saved checkpoint file path', 'summarize the MidasNet architecture with its ResNeXt encoder, four RefineNet stages, and output convolution', 'resize a sample dict with image, disparity, and mask to ensure minimum size while keeping aspect ratio', 'create a Resize transform to resize image samples to a target width and height with optional aspect ratio', 'create a NormalizeImage transform to normalize image samples by subtracting mean and dividing by std', 'create a PrepareForNet transform to transpose and cast image samples for network input', 'use the Resize get_size method to compute the constrained output dimensions for a given input width and height']
```

Usage

```
{'load_model_weights': 'load PyTorch model weights from a checkpoint file path into a BaseModel instance', 'create_base_model_subclass': 'create a subclass of BaseModel that inherits the load method for loading model state dicts', 'review_base_model_load': 'review the BaseModel load method to understand how it handles optimizer and model keys in checkpoints', 'refactor_base_model_load': 'refactor the BaseModel load method to support additional checkpoint formats beyond optimizer and model keys', 'test_base_model_load': 'test the BaseModel load method by loading a checkpoint file and verifying the state dict was applied'}
```

## File: facebookresearch_robustcvd/monodepth/midas_v2/blocks.py

Prompts

```
['load PyTorch model weights from a checkpoint file path into a BaseModel instance', 'create a subclass of BaseModel that inherits the load method for loading model state dicts', 'review the BaseModel load method to understand how it handles optimizer and model keys in checkpoints', 'refactor the BaseModel load method to support additional checkpoint formats beyond optimizer and model keys', 'test the BaseModel load method by loading a checkpoint file and verifying the state dict was applied', 'build a MiDaS encoder using _make_encoder with a ResNeXt-101 WSL pretrained backbone and scratch layers', 'create scratch Conv2d layers from in_shape channels to a uniform out_shape using _make_scratch', 'build an Interpolate nn.Module that upscales a tensor by a given scale_factor and interpolation mode', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU that adds input as a residual', 'build a FeatureFusionBlock that fuses two feature tensors via residual conv units and upsamples by 2x', 'create a MidasNet model for monocular depth estimation with optional pretrained weights path', 'run a forward pass through MidasNet to predict depth from an input image tensor', 'review the MidasNet constructor to understand feature count, non-negative output, and pretrained backbone options', 'test loading pretrained model weights into MidasNet from a saved checkpoint file path', 'summarize the MidasNet architecture with its ResNeXt encoder, four RefineNet stages, and output convolution', 'resize a sample dict with image, disparity, and mask to ensure minimum size while keeping aspect ratio', 'create a Resize transform to resize image samples to a target width and height with optional aspect ratio', 'create a NormalizeImage transform to normalize image samples by subtracting mean and dividing by std', 'create a PrepareForNet transform to transpose and cast image samples for network input', 'use the Resize get_size method to compute the constrained output dimensions for a given input width and height']
```

Usage

```
{'build_encoder_with_resnext101': 'build a MiDaS encoder using _make_encoder with a ResNeXt-101 WSL pretrained backbone and scratch layers', 'create_scratch_conv_layers': 'create scratch Conv2d layers from in_shape channels to a uniform out_shape using _make_scratch', 'build_interpolate_module': 'build an Interpolate nn.Module that upscales a tensor by a given scale_factor and interpolation mode', 'create_residual_conv_unit': 'create a ResidualConvUnit with two 3x3 conv layers and ReLU that adds input as a residual', 'build_feature_fusion_block': 'build a FeatureFusionBlock that fuses two feature tensors via residual conv units and upsamples by 2x'}
```

## File: facebookresearch_robustcvd/monodepth/midas_v2/midas_net.py

Prompts

```
['load PyTorch model weights from a checkpoint file path into a BaseModel instance', 'create a subclass of BaseModel that inherits the load method for loading model state dicts', 'review the BaseModel load method to understand how it handles optimizer and model keys in checkpoints', 'refactor the BaseModel load method to support additional checkpoint formats beyond optimizer and model keys', 'test the BaseModel load method by loading a checkpoint file and verifying the state dict was applied', 'build a MiDaS encoder using _make_encoder with a ResNeXt-101 WSL pretrained backbone and scratch layers', 'create scratch Conv2d layers from in_shape channels to a uniform out_shape using _make_scratch', 'build an Interpolate nn.Module that upscales a tensor by a given scale_factor and interpolation mode', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU that adds input as a residual', 'build a FeatureFusionBlock that fuses two feature tensors via residual conv units and upsamples by 2x', 'create a MidasNet model for monocular depth estimation with optional pretrained weights path', 'run a forward pass through MidasNet to predict depth from an input image tensor', 'review the MidasNet constructor to understand feature count, non-negative output, and pretrained backbone options', 'test loading pretrained model weights into MidasNet from a saved checkpoint file path', 'summarize the MidasNet architecture with its ResNeXt encoder, four RefineNet stages, and output convolution', 'resize a sample dict with image, disparity, and mask to ensure minimum size while keeping aspect ratio', 'create a Resize transform to resize image samples to a target width and height with optional aspect ratio', 'create a NormalizeImage transform to normalize image samples by subtracting mean and dividing by std', 'create a PrepareForNet transform to transpose and cast image samples for network input', 'use the Resize get_size method to compute the constrained output dimensions for a given input width and height']
```

Usage

```
{'create_MidasNet_model': 'create a MidasNet model for monocular depth estimation with optional pretrained weights path', 'run_MidasNet_forward': 'run a forward pass through MidasNet to predict depth from an input image tensor', 'review_MidasNet_init': 'review the MidasNet constructor to understand feature count, non-negative output, and pretrained backbone options', 'test_MidasNet_load': 'test loading pretrained model weights into MidasNet from a saved checkpoint file path', 'summarize_MidasNet_architecture': 'summarize the MidasNet architecture with its ResNeXt encoder, four RefineNet stages, and output convolution'}
```

## File: facebookresearch_robustcvd/monodepth/midas_v2/transforms.py

Prompts

```
['load PyTorch model weights from a checkpoint file path into a BaseModel instance', 'create a subclass of BaseModel that inherits the load method for loading model state dicts', 'review the BaseModel load method to understand how it handles optimizer and model keys in checkpoints', 'refactor the BaseModel load method to support additional checkpoint formats beyond optimizer and model keys', 'test the BaseModel load method by loading a checkpoint file and verifying the state dict was applied', 'build a MiDaS encoder using _make_encoder with a ResNeXt-101 WSL pretrained backbone and scratch layers', 'create scratch Conv2d layers from in_shape channels to a uniform out_shape using _make_scratch', 'build an Interpolate nn.Module that upscales a tensor by a given scale_factor and interpolation mode', 'create a ResidualConvUnit with two 3x3 conv layers and ReLU that adds input as a residual', 'build a FeatureFusionBlock that fuses two feature tensors via residual conv units and upsamples by 2x', 'create a MidasNet model for monocular depth estimation with optional pretrained weights path', 'run a forward pass through MidasNet to predict depth from an input image tensor', 'review the MidasNet constructor to understand feature count, non-negative output, and pretrained backbone options', 'test loading pretrained model weights into MidasNet from a saved checkpoint file path', 'summarize the MidasNet architecture with its ResNeXt encoder, four RefineNet stages, and output convolution', 'resize a sample dict with image, disparity, and mask to ensure minimum size while keeping aspect ratio', 'create a Resize transform to resize image samples to a target width and height with optional aspect ratio', 'create a NormalizeImage transform to normalize image samples by subtracting mean and dividing by std', 'create a PrepareForNet transform to transpose and cast image samples for network input', 'use the Resize get_size method to compute the constrained output dimensions for a given input width and height']
```

Usage

```
{'apply_min_size': 'resize a sample dict with image, disparity, and mask to ensure minimum size while keeping aspect ratio', 'Resize_class': 'create a Resize transform to resize image samples to a target width and height with optional aspect ratio', 'NormalizeImage_class': 'create a NormalizeImage transform to normalize image samples by subtracting mean and dividing by std', 'PrepareForNet_class': 'create a PrepareForNet transform to transpose and cast image samples for network input', 'Resize_get_size': 'use the Resize get_size method to compute the constrained output dimensions for a given input width and height'}
```

