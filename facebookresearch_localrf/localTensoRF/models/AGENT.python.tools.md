# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/localTensoRF/models/tensoRF.py

Prompts

```
['initialize the SVD volume for density and appearance plane and line coefficients with a given resolution and device', 'compute density features from sampled 3D coordinates using plane and line basis grid sampling', 'compute appearance features from sampled 3D coordinates using plane line basis and a basis matrix', 'upsample the volume grid to a target resolution by interpolating plane and line coefficients', 'shrink the volume grid to a new axis-aligned bounding box by cropping plane and line coefficients', 'create a positional encoding from 3D coordinates and frequency bands using sin and cos', 'compute ray marching weights and transmittance from alpha values along sampled rays', 'build an AlphaGridMask module to sample alpha volumes for bounding box ray filtering', 'build an MLP renderer that maps features and view directions to RGB with positional encoding', 'run the TensorBase forward pass to render RGB and depth maps from camera rays']
```

Usage

```
{'init_svd_volume': 'initialize the SVD volume for density and appearance plane and line coefficients with a given resolution and device', 'compute_densityfeature': 'compute density features from sampled 3D coordinates using plane and line basis grid sampling', 'compute_appfeature': 'compute appearance features from sampled 3D coordinates using plane line basis and a basis matrix', 'upsample_volume_grid': 'upsample the volume grid to a target resolution by interpolating plane and line coefficients', 'shrink': 'shrink the volume grid to a new axis-aligned bounding box by cropping plane and line coefficients'}
```

## File: facebookresearch_localrf/localTensoRF/models/tensorBase.py

Prompts

```
['initialize the SVD volume for density and appearance plane and line coefficients with a given resolution and device', 'compute density features from sampled 3D coordinates using plane and line basis grid sampling', 'compute appearance features from sampled 3D coordinates using plane line basis and a basis matrix', 'upsample the volume grid to a target resolution by interpolating plane and line coefficients', 'shrink the volume grid to a new axis-aligned bounding box by cropping plane and line coefficients', 'create a positional encoding from 3D coordinates and frequency bands using sin and cos', 'compute ray marching weights and transmittance from alpha values along sampled rays', 'build an AlphaGridMask module to sample alpha volumes for bounding box ray filtering', 'build an MLP renderer that maps features and view directions to RGB with positional encoding', 'run the TensorBase forward pass to render RGB and depth maps from camera rays']
```

Usage

```
{'create_positional_encoding': 'create a positional encoding from 3D coordinates and frequency bands using sin and cos', 'compute_alpha2weights': 'compute ray marching weights and transmittance from alpha values along sampled rays', 'build_AlphaGridMask': 'build an AlphaGridMask module to sample alpha volumes for bounding box ray filtering', 'build_MLPRender_Fea': 'build an MLP renderer that maps features and view directions to RGB with positional encoding', 'run_TensorBase_forward': 'run the TensorBase forward pass to render RGB and depth maps from camera rays'}
```

