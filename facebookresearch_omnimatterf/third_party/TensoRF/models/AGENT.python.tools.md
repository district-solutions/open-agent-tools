# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/TensoRF/models/sh.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree up to 4', 'evaluate spherical harmonics basis functions at unit directions without taking linear combination', 'compute color values from spherical harmonic coefficients given 3D unit direction vectors', 'review the eval_sh function that evaluates hardcoded SH polynomials with batch dimension support', 'refactor the spherical harmonic coefficient constants C0 through C4 for different precision', 'initialize a TensorVM model with plane and line coefficients for 3D scene representation', 'compute density features from sampled 3D coordinates using TensorVM plane and line basis sampling', 'compute appearance features from sampled 3D coordinates using TensorVMSplit split plane and line coefficients', 'upsample the TensorCP volume grid to a target resolution using bilinear interpolation on line coefficients', 'shrink the TensorVMSplit volume grid to a new axis-aligned bounding box by slicing plane and line tensors', 'create a TensorBase model with configurable grid size, density components, and shading mode for 3D scene representation', 'sample points along camera rays using sample_ray method with configurable number of samples and bounding box constraints', 'compute density features from sampled 3D coordinates using the compute_densityfeature method for volume rendering', 'render RGB colors using MLPRender_PE module with positional encoding for both position and view direction inputs', 'update the alpha mask grid to filter empty space and optimize ray marching performance during training']
```

Usage

```
{'eval_sh_with_coeffs': 'evaluate spherical harmonics at unit directions using SH coefficients and degree up to 4', 'eval_sh_bases_for_directions': 'evaluate spherical harmonics basis functions at unit directions without taking linear combination', 'compute_sh_color_from_dirs': 'compute color values from spherical harmonic coefficients given 3D unit direction vectors', 'review_eval_sh_implementation': 'review the eval_sh function that evaluates hardcoded SH polynomials with batch dimension support', 'refactor_sh_coefficients': 'refactor the spherical harmonic coefficient constants C0 through C4 for different precision'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/models/tensoRF.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree up to 4', 'evaluate spherical harmonics basis functions at unit directions without taking linear combination', 'compute color values from spherical harmonic coefficients given 3D unit direction vectors', 'review the eval_sh function that evaluates hardcoded SH polynomials with batch dimension support', 'refactor the spherical harmonic coefficient constants C0 through C4 for different precision', 'initialize a TensorVM model with plane and line coefficients for 3D scene representation', 'compute density features from sampled 3D coordinates using TensorVM plane and line basis sampling', 'compute appearance features from sampled 3D coordinates using TensorVMSplit split plane and line coefficients', 'upsample the TensorCP volume grid to a target resolution using bilinear interpolation on line coefficients', 'shrink the TensorVMSplit volume grid to a new axis-aligned bounding box by slicing plane and line tensors', 'create a TensorBase model with configurable grid size, density components, and shading mode for 3D scene representation', 'sample points along camera rays using sample_ray method with configurable number of samples and bounding box constraints', 'compute density features from sampled 3D coordinates using the compute_densityfeature method for volume rendering', 'render RGB colors using MLPRender_PE module with positional encoding for both position and view direction inputs', 'update the alpha mask grid to filter empty space and optimize ray marching performance during training']
```

Usage

```
{'init_TensorVM_svd_volume': 'initialize a TensorVM model with plane and line coefficients for 3D scene representation', 'compute_densityfeature_TensorVM': 'compute density features from sampled 3D coordinates using TensorVM plane and line basis sampling', 'compute_appfeature_TensorVMSplit': 'compute appearance features from sampled 3D coordinates using TensorVMSplit split plane and line coefficients', 'upsample_volume_grid_TensorCP': 'upsample the TensorCP volume grid to a target resolution using bilinear interpolation on line coefficients', 'shrink_TensorVMSplit': 'shrink the TensorVMSplit volume grid to a new axis-aligned bounding box by slicing plane and line tensors'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/models/tensorBase.py

Prompts

```
['evaluate spherical harmonics at unit directions using SH coefficients and degree up to 4', 'evaluate spherical harmonics basis functions at unit directions without taking linear combination', 'compute color values from spherical harmonic coefficients given 3D unit direction vectors', 'review the eval_sh function that evaluates hardcoded SH polynomials with batch dimension support', 'refactor the spherical harmonic coefficient constants C0 through C4 for different precision', 'initialize a TensorVM model with plane and line coefficients for 3D scene representation', 'compute density features from sampled 3D coordinates using TensorVM plane and line basis sampling', 'compute appearance features from sampled 3D coordinates using TensorVMSplit split plane and line coefficients', 'upsample the TensorCP volume grid to a target resolution using bilinear interpolation on line coefficients', 'shrink the TensorVMSplit volume grid to a new axis-aligned bounding box by slicing plane and line tensors', 'create a TensorBase model with configurable grid size, density components, and shading mode for 3D scene representation', 'sample points along camera rays using sample_ray method with configurable number of samples and bounding box constraints', 'compute density features from sampled 3D coordinates using the compute_densityfeature method for volume rendering', 'render RGB colors using MLPRender_PE module with positional encoding for both position and view direction inputs', 'update the alpha mask grid to filter empty space and optimize ray marching performance during training']
```

Usage

```
{'create_TensorBase_model': 'create a TensorBase model with configurable grid size, density components, and shading mode for 3D scene representation', 'sample_ray_points': 'sample points along camera rays using sample_ray method with configurable number of samples and bounding box constraints', 'compute_density_features': 'compute density features from sampled 3D coordinates using the compute_densityfeature method for volume rendering', 'render_with_MLPRender_PE': 'render RGB colors using MLPRender_PE module with positional encoding for both position and view direction inputs', 'update_alpha_mask': 'update the alpha mask grid to filter empty space and optimize ray marching performance during training'}
```

