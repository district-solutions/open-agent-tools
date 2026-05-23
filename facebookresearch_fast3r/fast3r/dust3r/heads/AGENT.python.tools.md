# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/dust3r/heads/dpt_head.py

Prompts

```
['create a DPT head for a given network with optional confidence output using create_dpt_head', 'build a PixelwiseTaskWithDPT module that returns 3D points and confidence for all pixels', 'review the DPTOutputAdapter_fix forward method that fuses encoder tokens through refinement stages', 'refactor the DPTOutputAdapter_fix init method to remove duplicated activation postprocess weights', 'test the PixelwiseTaskWithDPT forward pass with encoder tokens and image info', 'create a LinearPts3d head that outputs 3D points from decoder tokens using a linear projection layer', 'build a LinearPts3d head with confidence scores enabled by setting has_conf to True', 'run the forward pass of LinearPts3d to extract 3D points from decoder output tokens and image shape', 'review the LinearPts3d constructor to understand how patch_size, depth_mode, and conf_mode are configured from the network', 'refactor the LinearPts3d forward method to customize the pixel shuffle and postprocess pipeline for 3D point extraction', 'extract 3D points and confidence from a prediction head output tensor using postprocess', 'reg_dense_depth extracts 3D points from raw xyz coordinates using linear depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using square depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using exponential depth mode', 'reg_dense_conf extracts confidence values from a tensor using sigmoid mode with min and max bounds']
```

Usage

```
{'create_dpt_head': 'create a DPT head for a given network with optional confidence output using create_dpt_head', 'build_pixelwise_task_with_dpt': 'build a PixelwiseTaskWithDPT module that returns 3D points and confidence for all pixels', 'review_DPTOutputAdapter_fix_forward': 'review the DPTOutputAdapter_fix forward method that fuses encoder tokens through refinement stages', 'refactor_DPTOutputAdapter_fix_init': 'refactor the DPTOutputAdapter_fix init method to remove duplicated activation postprocess weights', 'test_PixelwiseTaskWithDPT_forward': 'test the PixelwiseTaskWithDPT forward pass with encoder tokens and image info'}
```

## File: facebookresearch_fast3r/fast3r/dust3r/heads/linear_head.py

Prompts

```
['create a DPT head for a given network with optional confidence output using create_dpt_head', 'build a PixelwiseTaskWithDPT module that returns 3D points and confidence for all pixels', 'review the DPTOutputAdapter_fix forward method that fuses encoder tokens through refinement stages', 'refactor the DPTOutputAdapter_fix init method to remove duplicated activation postprocess weights', 'test the PixelwiseTaskWithDPT forward pass with encoder tokens and image info', 'create a LinearPts3d head that outputs 3D points from decoder tokens using a linear projection layer', 'build a LinearPts3d head with confidence scores enabled by setting has_conf to True', 'run the forward pass of LinearPts3d to extract 3D points from decoder output tokens and image shape', 'review the LinearPts3d constructor to understand how patch_size, depth_mode, and conf_mode are configured from the network', 'refactor the LinearPts3d forward method to customize the pixel shuffle and postprocess pipeline for 3D point extraction', 'extract 3D points and confidence from a prediction head output tensor using postprocess', 'reg_dense_depth extracts 3D points from raw xyz coordinates using linear depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using square depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using exponential depth mode', 'reg_dense_conf extracts confidence values from a tensor using sigmoid mode with min and max bounds']
```

Usage

```
{'create_LinearPts3d': 'create a LinearPts3d head that outputs 3D points from decoder tokens using a linear projection layer', 'build_LinearPts3d_with_confidence': 'build a LinearPts3d head with confidence scores enabled by setting has_conf to True', 'run_LinearPts3d_forward': 'run the forward pass of LinearPts3d to extract 3D points from decoder output tokens and image shape', 'review_LinearPts3d_init': 'review the LinearPts3d constructor to understand how patch_size, depth_mode, and conf_mode are configured from the network', 'refactor_LinearPts3d_forward': 'refactor the LinearPts3d forward method to customize the pixel shuffle and postprocess pipeline for 3D point extraction'}
```

## File: facebookresearch_fast3r/fast3r/dust3r/heads/postprocess.py

Prompts

```
['create a DPT head for a given network with optional confidence output using create_dpt_head', 'build a PixelwiseTaskWithDPT module that returns 3D points and confidence for all pixels', 'review the DPTOutputAdapter_fix forward method that fuses encoder tokens through refinement stages', 'refactor the DPTOutputAdapter_fix init method to remove duplicated activation postprocess weights', 'test the PixelwiseTaskWithDPT forward pass with encoder tokens and image info', 'create a LinearPts3d head that outputs 3D points from decoder tokens using a linear projection layer', 'build a LinearPts3d head with confidence scores enabled by setting has_conf to True', 'run the forward pass of LinearPts3d to extract 3D points from decoder output tokens and image shape', 'review the LinearPts3d constructor to understand how patch_size, depth_mode, and conf_mode are configured from the network', 'refactor the LinearPts3d forward method to customize the pixel shuffle and postprocess pipeline for 3D point extraction', 'extract 3D points and confidence from a prediction head output tensor using postprocess', 'reg_dense_depth extracts 3D points from raw xyz coordinates using linear depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using square depth mode', 'reg_dense_depth extracts 3D points from raw xyz coordinates using exponential depth mode', 'reg_dense_conf extracts confidence values from a tensor using sigmoid mode with min and max bounds']
```

Usage

```
{'extract_3d_points_and_confidence': 'extract 3D points and confidence from a prediction head output tensor using postprocess', 'reg_dense_depth_linear': 'reg_dense_depth extracts 3D points from raw xyz coordinates using linear depth mode', 'reg_dense_depth_square': 'reg_dense_depth extracts 3D points from raw xyz coordinates using square depth mode', 'reg_dense_depth_exp': 'reg_dense_depth extracts 3D points from raw xyz coordinates using exponential depth mode', 'reg_dense_conf_sigmoid': 'reg_dense_conf extracts confidence values from a tensor using sigmoid mode with min and max bounds'}
```

