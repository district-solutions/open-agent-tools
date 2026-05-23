# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/representations/gaussian/gaussian_model.py

Prompts

```
['create a Gaussian instance with an AABB bounding box and configurable SH degree on CUDA', "save the Gaussian model's xyz, features, opacity, scale, and rotation to a PLY file", 'load Gaussian attributes from a PLY file and convert them to internal hidden representations', 'get the covariance matrix of the Gaussian using scaling, modifier, and rotation parameters', 'build a symmetric covariance matrix from scaling and rotation tensors using a static method', 'build a 3x3 rotation matrix from normalized quaternion coefficients on CUDA', 'build a combined scaling and rotation matrix from scale vectors and quaternions', 'create an exponential learning rate decay function with optional warmup delay steps', 'convert a PIL image to a normalized PyTorch tensor with specified resolution', 'extract the lower triangular elements of a symmetric 3x3 covariance matrix tensor']
```

Usage

```
{'create_Gaussian_instance': 'create a Gaussian instance with an AABB bounding box and configurable SH degree on CUDA', 'save_gaussian_to_ply': "save the Gaussian model's xyz, features, opacity, scale, and rotation to a PLY file", 'load_gaussian_from_ply': 'load Gaussian attributes from a PLY file and convert them to internal hidden representations', 'get_gaussian_covariance': 'get the covariance matrix of the Gaussian using scaling, modifier, and rotation parameters', 'build_covariance_from_scaling_rotation': 'build a symmetric covariance matrix from scaling and rotation tensors using a static method'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/representations/gaussian/general_utils.py

Prompts

```
['create a Gaussian instance with an AABB bounding box and configurable SH degree on CUDA', "save the Gaussian model's xyz, features, opacity, scale, and rotation to a PLY file", 'load Gaussian attributes from a PLY file and convert them to internal hidden representations', 'get the covariance matrix of the Gaussian using scaling, modifier, and rotation parameters', 'build a symmetric covariance matrix from scaling and rotation tensors using a static method', 'build a 3x3 rotation matrix from normalized quaternion coefficients on CUDA', 'build a combined scaling and rotation matrix from scale vectors and quaternions', 'create an exponential learning rate decay function with optional warmup delay steps', 'convert a PIL image to a normalized PyTorch tensor with specified resolution', 'extract the lower triangular elements of a symmetric 3x3 covariance matrix tensor']
```

Usage

```
{'build_rotation_matrix': 'build a 3x3 rotation matrix from normalized quaternion coefficients on CUDA', 'build_scaling_rotation_matrix': 'build a combined scaling and rotation matrix from scale vectors and quaternions', 'create_lr_schedule': 'create an exponential learning rate decay function with optional warmup delay steps', 'convert_pil_to_torch_tensor': 'convert a PIL image to a normalized PyTorch tensor with specified resolution', 'extract_lower_diagonal': 'extract the lower triangular elements of a symmetric 3x3 covariance matrix tensor'}
```

