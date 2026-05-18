# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/dust3r/heads/dpt_head.py

Prompts

```
['create a DPT head for a given network by calling create_dpt_head with net and has_conf parameters', 'initialize a DPTOutputAdapter_fix instance by calling init with dim_tokens_enc to remove duplicated weights', 'run forward pass on encoder tokens through DPTOutputAdapter_fix with image_size to get spatial output', 'run forward pass on input tokens through PixelwiseTaskWithDPT with img_info to get 3D points and confidence', 'review the PixelwiseTaskWithDPT class to understand how it wraps DPTOutputAdapter_fix for pixelwise 3D regression tasks', 'build a LinearPts3d head that outputs 16x16 3D points with optional confidence from decoder tokens', 'build a GSHead that predicts RGB, opacity, scale, and rotation for 3D Gaussian Splatting from decoder tokens', 'build a PyTorch MLP with configurable input, hidden, output dimensions and depth using ReLU activations', 'create a DownSampling convolutional block with Conv2d, BatchNorm2d, and SELU activation for feature reduction', 'test the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'extract 3D points and confidence scores from prediction head output using postprocess with depth and confidence modes', 'extract 3D points from prediction head output using linear, square, or exponential depth regression modes', 'extract confidence values from prediction head output using exponential or sigmoid confidence regression modes', 'run postprocess on feature maps with linear, square, or exp depth modes to get 3D point predictions', 'run postprocess on feature maps with exp or sigmoid confidence modes to get confidence predictions']
```

Usage

```
{'create_dpt_head': 'create a DPT head for a given network by calling create_dpt_head with net and has_conf parameters', 'init_DPTOutputAdapter_fix': 'initialize a DPTOutputAdapter_fix instance by calling init with dim_tokens_enc to remove duplicated weights', 'forward_DPTOutputAdapter_fix': 'run forward pass on encoder tokens through DPTOutputAdapter_fix with image_size to get spatial output', 'forward_PixelwiseTaskWithDPT': 'run forward pass on input tokens through PixelwiseTaskWithDPT with img_info to get 3D points and confidence', 'review_PixelwiseTaskWithDPT': 'review the PixelwiseTaskWithDPT class to understand how it wraps DPTOutputAdapter_fix for pixelwise 3D regression tasks'}
```

## File: facebookresearch_mvdust3r/dust3r/heads/linear_head.py

Prompts

```
['create a DPT head for a given network by calling create_dpt_head with net and has_conf parameters', 'initialize a DPTOutputAdapter_fix instance by calling init with dim_tokens_enc to remove duplicated weights', 'run forward pass on encoder tokens through DPTOutputAdapter_fix with image_size to get spatial output', 'run forward pass on input tokens through PixelwiseTaskWithDPT with img_info to get 3D points and confidence', 'review the PixelwiseTaskWithDPT class to understand how it wraps DPTOutputAdapter_fix for pixelwise 3D regression tasks', 'build a LinearPts3d head that outputs 16x16 3D points with optional confidence from decoder tokens', 'build a GSHead that predicts RGB, opacity, scale, and rotation for 3D Gaussian Splatting from decoder tokens', 'build a PyTorch MLP with configurable input, hidden, output dimensions and depth using ReLU activations', 'create a DownSampling convolutional block with Conv2d, BatchNorm2d, and SELU activation for feature reduction', 'test the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'extract 3D points and confidence scores from prediction head output using postprocess with depth and confidence modes', 'extract 3D points from prediction head output using linear, square, or exponential depth regression modes', 'extract confidence values from prediction head output using exponential or sigmoid confidence regression modes', 'run postprocess on feature maps with linear, square, or exp depth modes to get 3D point predictions', 'run postprocess on feature maps with exp or sigmoid confidence modes to get confidence predictions']
```

Usage

```
{'build_linear_head_for_3d_points': 'build a LinearPts3d head that outputs 16x16 3D points with optional confidence from decoder tokens', 'build_gaussian_splatting_head': 'build a GSHead that predicts RGB, opacity, scale, and rotation for 3D Gaussian Splatting from decoder tokens', 'build_pytorch_mlp': 'build a PyTorch MLP with configurable input, hidden, output dimensions and depth using ReLU activations', 'create_downsampling_block': 'create a DownSampling convolutional block with Conv2d, BatchNorm2d, and SELU activation for feature reduction', 'test_trunc_normal_initialization': 'test the trunc_normal_ function that initializes tensors with a truncated normal distribution'}
```

## File: facebookresearch_mvdust3r/dust3r/heads/postprocess.py

Prompts

```
['create a DPT head for a given network by calling create_dpt_head with net and has_conf parameters', 'initialize a DPTOutputAdapter_fix instance by calling init with dim_tokens_enc to remove duplicated weights', 'run forward pass on encoder tokens through DPTOutputAdapter_fix with image_size to get spatial output', 'run forward pass on input tokens through PixelwiseTaskWithDPT with img_info to get 3D points and confidence', 'review the PixelwiseTaskWithDPT class to understand how it wraps DPTOutputAdapter_fix for pixelwise 3D regression tasks', 'build a LinearPts3d head that outputs 16x16 3D points with optional confidence from decoder tokens', 'build a GSHead that predicts RGB, opacity, scale, and rotation for 3D Gaussian Splatting from decoder tokens', 'build a PyTorch MLP with configurable input, hidden, output dimensions and depth using ReLU activations', 'create a DownSampling convolutional block with Conv2d, BatchNorm2d, and SELU activation for feature reduction', 'test the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'extract 3D points and confidence scores from prediction head output using postprocess with depth and confidence modes', 'extract 3D points from prediction head output using linear, square, or exponential depth regression modes', 'extract confidence values from prediction head output using exponential or sigmoid confidence regression modes', 'run postprocess on feature maps with linear, square, or exp depth modes to get 3D point predictions', 'run postprocess on feature maps with exp or sigmoid confidence modes to get confidence predictions']
```

Usage

```
{'postprocess_extract_3d_points_and_confidence': 'extract 3D points and confidence scores from prediction head output using postprocess with depth and confidence modes', 'reg_dense_depth_extract_3d_points': 'extract 3D points from prediction head output using linear, square, or exponential depth regression modes', 'reg_dense_conf_extract_confidence': 'extract confidence values from prediction head output using exponential or sigmoid confidence regression modes', 'postprocess_with_depth_modes': 'run postprocess on feature maps with linear, square, or exp depth modes to get 3D point predictions', 'postprocess_with_confidence_modes': 'run postprocess on feature maps with exp or sigmoid confidence modes to get confidence predictions'}
```

