# Agent Python Tools

- repo: facebookresearch/body2hands
- repo_uri: https://github.com/facebookresearch/body2hands

## File: facebookresearch_body2hands/utils/load_utils.py

Prompts

```
['convert a numpy array of 6D rotation vectors to axis-angle representation using rot6d_to_aa', 'convert a numpy array of axis-angle vectors to 6D rotation representation using aa_to_rot6d', 'convert a 3x3 rotation matrix to 6D rotation representation using np_mat_to_rot6d', 'convert 6D rotation vectors to 3x3 rotation matrices using np_rot6d_to_mat', 'calculate mean and standard deviation for training data normalization using calc_standard', 'build a regressor_fcn_bn_32 network with specified input and output feature dimensions', 'build a regressor_fcn_bn_discriminator network with specified input feature dimensions', 'run a forward pass through the regressor_fcn_bn_32 model with input tensor and optional image', 'run a forward pass through the regressor_fcn_bn_discriminator model with input tensor', 'process an image tensor through the regressor_fcn_bn_32 image_resnet_postprocess and image_reduce layers']
```

Usage

```
{'convert_rot6d_to_axis_angle': 'convert a numpy array of 6D rotation vectors to axis-angle representation using rot6d_to_aa', 'convert_axis_angle_to_rot6d': 'convert a numpy array of axis-angle vectors to 6D rotation representation using aa_to_rot6d', 'convert_rotation_matrix_to_rot6d': 'convert a 3x3 rotation matrix to 6D rotation representation using np_mat_to_rot6d', 'convert_rot6d_to_rotation_matrix': 'convert 6D rotation vectors to 3x3 rotation matrices using np_rot6d_to_mat', 'calculate_standardization_stats': 'calculate mean and standard deviation for training data normalization using calc_standard'}
```

## File: facebookresearch_body2hands/utils/modelZoo.py

Prompts

```
['convert a numpy array of 6D rotation vectors to axis-angle representation using rot6d_to_aa', 'convert a numpy array of axis-angle vectors to 6D rotation representation using aa_to_rot6d', 'convert a 3x3 rotation matrix to 6D rotation representation using np_mat_to_rot6d', 'convert 6D rotation vectors to 3x3 rotation matrices using np_rot6d_to_mat', 'calculate mean and standard deviation for training data normalization using calc_standard', 'build a regressor_fcn_bn_32 network with specified input and output feature dimensions', 'build a regressor_fcn_bn_discriminator network with specified input feature dimensions', 'run a forward pass through the regressor_fcn_bn_32 model with input tensor and optional image', 'run a forward pass through the regressor_fcn_bn_discriminator model with input tensor', 'process an image tensor through the regressor_fcn_bn_32 image_resnet_postprocess and image_reduce layers']
```

Usage

```
{'build_regressor_fcn_bn_32': 'build a regressor_fcn_bn_32 network with specified input and output feature dimensions', 'build_discriminator': 'build a regressor_fcn_bn_discriminator network with specified input feature dimensions', 'run_regressor_forward': 'run a forward pass through the regressor_fcn_bn_32 model with input tensor and optional image', 'run_discriminator_forward': 'run a forward pass through the regressor_fcn_bn_discriminator model with input tensor', 'process_image_embedding': 'process an image tensor through the regressor_fcn_bn_32 image_resnet_postprocess and image_reduce layers'}
```

