# Agent Python Tools

- repo: facebookresearch/tava
- repo_uri: https://github.com/facebookresearch/tava

## File: facebookresearch_tava/tava/models/mipnerf_dyn.py

Prompts

```
['build a dynamic MipNeRF model with deformable positional encoding and pose-dependent shading for neural rendering', 'run the forward pass of DynMipNerfModel with rays, posed bones, and rest bones to render RGB, depth, and warp', 'review the DynMipNerfModel _query_mlp method that queries color, density, and warp from the MLP given bone poses', 'create a function to select rays near bones and calculate per-ray near far planes with a distance threshold', 'test the linear interpolation along rays function that interpolates values between valid sample points using masks', 'build a dynamic NeRF model with deformable positional encoding and bone-aware volumetric rendering', 'create a DynNerfModel with implicit shading conditioned on pose latent vectors', 'run the DynNerfModel forward pass with posed and rest bones to render rays', 'review the _query_mlp method that encodes world coordinates and predicts color and density', 'refactor the _select_rays_near_to_bones function to filter rays by bone proximity threshold']
```

Usage

```
{'build_DynMipNerfModel': 'build a dynamic MipNeRF model with deformable positional encoding and pose-dependent shading for neural rendering', 'run_DynMipNerfModel_forward': 'run the forward pass of DynMipNerfModel with rays, posed bones, and rest bones to render RGB, depth, and warp', 'review_DynMipNerfModel_query_mlp': 'review the DynMipNerfModel _query_mlp method that queries color, density, and warp from the MLP given bone poses', 'create_select_rays_near_bones': 'create a function to select rays near bones and calculate per-ray near far planes with a distance threshold', 'test_interp_along_rays': 'test the linear interpolation along rays function that interpolates values between valid sample points using masks'}
```

## File: facebookresearch_tava/tava/models/nerf_dyn.py

Prompts

```
['build a dynamic MipNeRF model with deformable positional encoding and pose-dependent shading for neural rendering', 'run the forward pass of DynMipNerfModel with rays, posed bones, and rest bones to render RGB, depth, and warp', 'review the DynMipNerfModel _query_mlp method that queries color, density, and warp from the MLP given bone poses', 'create a function to select rays near bones and calculate per-ray near far planes with a distance threshold', 'test the linear interpolation along rays function that interpolates values between valid sample points using masks', 'build a dynamic NeRF model with deformable positional encoding and bone-aware volumetric rendering', 'create a DynNerfModel with implicit shading conditioned on pose latent vectors', 'run the DynNerfModel forward pass with posed and rest bones to render rays', 'review the _query_mlp method that encodes world coordinates and predicts color and density', 'refactor the _select_rays_near_to_bones function to filter rays by bone proximity threshold']
```

Usage

```
{'build_DynNerfModel': 'build a dynamic NeRF model with deformable positional encoding and bone-aware volumetric rendering', 'create_DynNerfModel_with_shading': 'create a DynNerfModel with implicit shading conditioned on pose latent vectors', 'run_DynNerfModel_forward': 'run the DynNerfModel forward pass with posed and rest bones to render rays', 'review_DynNerfModel_query_mlp': 'review the _query_mlp method that encodes world coordinates and predicts color and density', 'refactor_select_rays_near_bones': 'refactor the _select_rays_near_to_bones function to filter rays by bone proximity threshold'}
```

