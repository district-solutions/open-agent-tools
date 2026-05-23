# Agent Python Tools

- repo: facebookresearch/tava
- repo_uri: https://github.com/facebookresearch/tava

## File: facebookresearch_tava/tava/models/deform_posi_enc/naive.py

Prompts

```
['build a PoseConditionDPEncoder instance with a positional encoder module and pose dimension for deformable NeRF', 'test the PoseConditionDPEncoder forward pass with 3D coordinates, covariance, and pose latent tensors', 'review the PoseConditionDPEncoder warp_dim property that returns 3 plus the pose dimension', 'review the PoseConditionDPEncoder out_dim property that returns positional encoder output dimension plus pose dimension', 'summarize the PoseConditionDPEncoder class that concatenates pose representation to positional encoding for deformable radiance fields', 'build a part-wise rigid deform positional encoder that projects points from world space to bone space', 'build a disentangled rigid deform positional encoder with learned part probability networks for NeRF', 'test the PartWiseDPEncoder forward pass with point coordinates, covariance, and bone transforms', 'test the DisentangledDPEncoder forward pass to get probability-weighted positional encodings and warp coordinates', 'review the DisentangledDPEncoder learned probability networks that produce per-part softmax weights', 'build a SNARFDPEncoder module with positional encoder, n_transforms, and optional offset network for deformable skinning', 'run forward_skinning on canonical points with world and canonical bones to get world space points via LBS', 'test the query_weights method to get softmax skinning weights for canonical points against bone transforms', 'refactor the _linear_skinning function to blend points across joint transforms with optional canonical and world offsets', "review the _broyden function that finds roots of g(x)=0 using Broyden's quasi-Newton method with inverse Jacobian updates"]
```

Usage

```
{'build_PoseConditionDPEncoder': 'build a PoseConditionDPEncoder instance with a positional encoder module and pose dimension for deformable NeRF', 'test_PoseConditionDPEncoder_forward': 'test the PoseConditionDPEncoder forward pass with 3D coordinates, covariance, and pose latent tensors', 'review_PoseConditionDPEncoder_warp_dim': 'review the PoseConditionDPEncoder warp_dim property that returns 3 plus the pose dimension', 'review_PoseConditionDPEncoder_out_dim': 'review the PoseConditionDPEncoder out_dim property that returns positional encoder output dimension plus pose dimension', 'summarize_PoseConditionDPEncoder': 'summarize the PoseConditionDPEncoder class that concatenates pose representation to positional encoding for deformable radiance fields'}
```

## File: facebookresearch_tava/tava/models/deform_posi_enc/rigid.py

Prompts

```
['build a PoseConditionDPEncoder instance with a positional encoder module and pose dimension for deformable NeRF', 'test the PoseConditionDPEncoder forward pass with 3D coordinates, covariance, and pose latent tensors', 'review the PoseConditionDPEncoder warp_dim property that returns 3 plus the pose dimension', 'review the PoseConditionDPEncoder out_dim property that returns positional encoder output dimension plus pose dimension', 'summarize the PoseConditionDPEncoder class that concatenates pose representation to positional encoding for deformable radiance fields', 'build a part-wise rigid deform positional encoder that projects points from world space to bone space', 'build a disentangled rigid deform positional encoder with learned part probability networks for NeRF', 'test the PartWiseDPEncoder forward pass with point coordinates, covariance, and bone transforms', 'test the DisentangledDPEncoder forward pass to get probability-weighted positional encodings and warp coordinates', 'review the DisentangledDPEncoder learned probability networks that produce per-part softmax weights', 'build a SNARFDPEncoder module with positional encoder, n_transforms, and optional offset network for deformable skinning', 'run forward_skinning on canonical points with world and canonical bones to get world space points via LBS', 'test the query_weights method to get softmax skinning weights for canonical points against bone transforms', 'refactor the _linear_skinning function to blend points across joint transforms with optional canonical and world offsets', "review the _broyden function that finds roots of g(x)=0 using Broyden's quasi-Newton method with inverse Jacobian updates"]
```

Usage

```
{'build_PartWiseDPEncoder': 'build a part-wise rigid deform positional encoder that projects points from world space to bone space', 'build_DisentangledDPEncoder': 'build a disentangled rigid deform positional encoder with learned part probability networks for NeRF', 'test_PartWiseDPEncoder_forward': 'test the PartWiseDPEncoder forward pass with point coordinates, covariance, and bone transforms', 'test_DisentangledDPEncoder_forward': 'test the DisentangledDPEncoder forward pass to get probability-weighted positional encodings and warp coordinates', 'review_DisentangledDPEncoder_nets': 'review the DisentangledDPEncoder learned probability networks that produce per-part softmax weights'}
```

## File: facebookresearch_tava/tava/models/deform_posi_enc/snarf.py

Prompts

```
['build a PoseConditionDPEncoder instance with a positional encoder module and pose dimension for deformable NeRF', 'test the PoseConditionDPEncoder forward pass with 3D coordinates, covariance, and pose latent tensors', 'review the PoseConditionDPEncoder warp_dim property that returns 3 plus the pose dimension', 'review the PoseConditionDPEncoder out_dim property that returns positional encoder output dimension plus pose dimension', 'summarize the PoseConditionDPEncoder class that concatenates pose representation to positional encoding for deformable radiance fields', 'build a part-wise rigid deform positional encoder that projects points from world space to bone space', 'build a disentangled rigid deform positional encoder with learned part probability networks for NeRF', 'test the PartWiseDPEncoder forward pass with point coordinates, covariance, and bone transforms', 'test the DisentangledDPEncoder forward pass to get probability-weighted positional encodings and warp coordinates', 'review the DisentangledDPEncoder learned probability networks that produce per-part softmax weights', 'build a SNARFDPEncoder module with positional encoder, n_transforms, and optional offset network for deformable skinning', 'run forward_skinning on canonical points with world and canonical bones to get world space points via LBS', 'test the query_weights method to get softmax skinning weights for canonical points against bone transforms', 'refactor the _linear_skinning function to blend points across joint transforms with optional canonical and world offsets', "review the _broyden function that finds roots of g(x)=0 using Broyden's quasi-Newton method with inverse Jacobian updates"]
```

Usage

```
{'build_SNARFDPEncoder': 'build a SNARFDPEncoder module with positional encoder, n_transforms, and optional offset network for deformable skinning', 'run_forward_skinning': 'run forward_skinning on canonical points with world and canonical bones to get world space points via LBS', 'test_query_weights': 'test the query_weights method to get softmax skinning weights for canonical points against bone transforms', 'refactor_linear_skinning': 'refactor the _linear_skinning function to blend points across joint transforms with optional canonical and world offsets', 'review_broyden_root_finding': "review the _broyden function that finds roots of g(x)=0 using Broyden's quasi-Newton method with inverse Jacobian updates"}
```

