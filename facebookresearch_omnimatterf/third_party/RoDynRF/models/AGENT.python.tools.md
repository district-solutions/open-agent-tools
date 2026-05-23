# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RoDynRF/models/sh.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree 0-4', 'evaluate spherical harmonics basis functions at unit directions without linear combination', 'compute color values from SH coefficients by evaluating at camera view directions', 'compute the SH basis tensor for a given degree and set of 3D directions', 'review the hardcoded spherical harmonics normalization constants C0 through C4', 'create a TensorVM instance with aabb, gridSize, and device for static 3D scene representation', 'compute density features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'compute appearance features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'get forward and backward scene flow vectors for 4D spatiotemporal point tracking', 'warp 3D coordinates using time-conditioned MLP to model scene deformation over time', 'create a TensorBase model for 4D tensor representation with configurable grid size and appearance components', 'build an MLP renderer module with positional encoding for view-dependent neural rendering', 'implement an AlphaGridMask to filter spatial regions based on alpha volume thresholds', 'compute frequency-based positional encoding for 3D coordinates using sine and cosine functions', 'render volume using raw2alpha to convert sigma values to alpha weights for ray marching']
```

Usage

```
{'eval_sh_with_coeffs': 'evaluate spherical harmonics at unit directions using SH coefficients and degree 0-4', 'eval_sh_bases_for_directions': 'evaluate spherical harmonics basis functions at unit directions without linear combination', 'compute_sh_color_values': 'compute color values from SH coefficients by evaluating at camera view directions', 'compute_sh_basis_tensor': 'compute the SH basis tensor for a given degree and set of 3D directions', 'review_sh_constants': 'review the hardcoded spherical harmonics normalization constants C0 through C4'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/models/tensoRF.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree 0-4', 'evaluate spherical harmonics basis functions at unit directions without linear combination', 'compute color values from SH coefficients by evaluating at camera view directions', 'compute the SH basis tensor for a given degree and set of 3D directions', 'review the hardcoded spherical harmonics normalization constants C0 through C4', 'create a TensorVM instance with aabb, gridSize, and device for static 3D scene representation', 'compute density features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'compute appearance features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'get forward and backward scene flow vectors for 4D spatiotemporal point tracking', 'warp 3D coordinates using time-conditioned MLP to model scene deformation over time', 'create a TensorBase model for 4D tensor representation with configurable grid size and appearance components', 'build an MLP renderer module with positional encoding for view-dependent neural rendering', 'implement an AlphaGridMask to filter spatial regions based on alpha volume thresholds', 'compute frequency-based positional encoding for 3D coordinates using sine and cosine functions', 'render volume using raw2alpha to convert sigma values to alpha weights for ray marching']
```

Usage

```
{'create_TensorVM_instance': 'create a TensorVM instance with aabb, gridSize, and device for static 3D scene representation', 'compute_densityfeature_TensorVMSplit': 'compute density features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'compute_appfeature_TensorVMSplit': 'compute appearance features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'get_forward_backward_scene_flow_TensorVMSplit_TimeEmbedding': 'get forward and backward scene flow vectors for 4D spatiotemporal point tracking', 'warp_coordinate_TensorVMSplit_TimeEmbedding': 'warp 3D coordinates using time-conditioned MLP to model scene deformation over time'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/models/tensorBase.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree 0-4', 'evaluate spherical harmonics basis functions at unit directions without linear combination', 'compute color values from SH coefficients by evaluating at camera view directions', 'compute the SH basis tensor for a given degree and set of 3D directions', 'review the hardcoded spherical harmonics normalization constants C0 through C4', 'create a TensorVM instance with aabb, gridSize, and device for static 3D scene representation', 'compute density features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'compute appearance features from sampled xyz coordinates and time embeddings using TensorVMSplit', 'get forward and backward scene flow vectors for 4D spatiotemporal point tracking', 'warp 3D coordinates using time-conditioned MLP to model scene deformation over time', 'create a TensorBase model for 4D tensor representation with configurable grid size and appearance components', 'build an MLP renderer module with positional encoding for view-dependent neural rendering', 'implement an AlphaGridMask to filter spatial regions based on alpha volume thresholds', 'compute frequency-based positional encoding for 3D coordinates using sine and cosine functions', 'render volume using raw2alpha to convert sigma values to alpha weights for ray marching']
```

Usage

```
{'create_TensorBase_model': 'create a TensorBase model for 4D tensor representation with configurable grid size and appearance components', 'build_MLP_renderer': 'build an MLP renderer module with positional encoding for view-dependent neural rendering', 'implement_alpha_mask': 'implement an AlphaGridMask to filter spatial regions based on alpha volume thresholds', 'compute_positional_encoding': 'compute frequency-based positional encoding for 3D coordinates using sine and cosine functions', 'render_volume_with_raw2alpha': 'render volume using raw2alpha to convert sigma values to alpha weights for ray marching'}
```

