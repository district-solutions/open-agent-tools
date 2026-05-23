# Agent Python Tools

- repo: facebookresearch/robust-dynrf
- repo_uri: https://github.com/facebookresearch/robust-dynrf

## File: facebookresearch_robust-dynrf/models/tensoRF.py

Prompts

```
['create a TensorVMSplit model with bounding box, grid size, and time size parameters for static 3D scene representation', 'create a TensorVMSplit_TimeEmbedding model with MLP layers for dynamic 3D scene representation with temporal awareness', 'compute density features from sampled 3D coordinates using plane and line coefficient basis decomposition', 'compute appearance features from sampled 3D coordinates using basis matrix projection on decomposed coefficients', 'warp 3D coordinates using time-conditioned MLP to predict spatial displacement for dynamic scene deformation', 'build a TensorBase volume rendering model with configurable grid size, shading mode, and appearance components', 'create an AlphaGridMask module to sample alpha values from a 4D volume at given 3D coordinates and time indices', 'create an MLPRender_Fea MLP renderer that maps features and view directions to RGB colors with positional encoding', 'create an MLPRender_Fea_TimeEmbedding renderer that processes features separately from view directions before combining for RGB output', 'use raw2alpha to convert sigma densities and sample distances into alpha values, ray marching weights, and background weights']
```

Usage

```
{'init_tensorvm_split': 'create a TensorVMSplit model with bounding box, grid size, and time size parameters for static 3D scene representation', 'init_tensorvm_time_embedding': 'create a TensorVMSplit_TimeEmbedding model with MLP layers for dynamic 3D scene representation with temporal awareness', 'compute_density_feature': 'compute density features from sampled 3D coordinates using plane and line coefficient basis decomposition', 'compute_app_feature': 'compute appearance features from sampled 3D coordinates using basis matrix projection on decomposed coefficients', 'warp_coordinate': 'warp 3D coordinates using time-conditioned MLP to predict spatial displacement for dynamic scene deformation'}
```

## File: facebookresearch_robust-dynrf/models/tensorBase.py

Prompts

```
['create a TensorVMSplit model with bounding box, grid size, and time size parameters for static 3D scene representation', 'create a TensorVMSplit_TimeEmbedding model with MLP layers for dynamic 3D scene representation with temporal awareness', 'compute density features from sampled 3D coordinates using plane and line coefficient basis decomposition', 'compute appearance features from sampled 3D coordinates using basis matrix projection on decomposed coefficients', 'warp 3D coordinates using time-conditioned MLP to predict spatial displacement for dynamic scene deformation', 'build a TensorBase volume rendering model with configurable grid size, shading mode, and appearance components', 'create an AlphaGridMask module to sample alpha values from a 4D volume at given 3D coordinates and time indices', 'create an MLPRender_Fea MLP renderer that maps features and view directions to RGB colors with positional encoding', 'create an MLPRender_Fea_TimeEmbedding renderer that processes features separately from view directions before combining for RGB output', 'use raw2alpha to convert sigma densities and sample distances into alpha values, ray marching weights, and background weights']
```

Usage

```
{'build_TensorBase': 'build a TensorBase volume rendering model with configurable grid size, shading mode, and appearance components', 'create_AlphaGridMask': 'create an AlphaGridMask module to sample alpha values from a 4D volume at given 3D coordinates and time indices', 'create_MLPRender_Fea': 'create an MLPRender_Fea MLP renderer that maps features and view directions to RGB colors with positional encoding', 'create_MLPRender_Fea_TimeEmbedding': 'create an MLPRender_Fea_TimeEmbedding renderer that processes features separately from view directions before combining for RGB output', 'use_raw2alpha': 'use raw2alpha to convert sigma densities and sample distances into alpha values, ray marching weights, and background weights'}
```

