# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/renderers/gaussian_renderer_4D.py

Prompts

```
['render 4D Gaussian splats by calling GaussianRenderer4D with gs_params, timestamps, intrinsics, and extrinsics to get RGB, mask, and depth', 'rasterize a single 3D Gaussian image using SingleImageRasterization with means, quaternions, scales, opacities, colors, viewmats, and camera intrinsics', 'rasterize a batch of 4D Gaussian frames using SingleBatchRasterization that computes temporal marginalization and updated opacities per timestamp', 'compute the temporal marginal probability of a Gaussian at a given timestamp using compute_marginal_t with target time, mean time, and covariance', 'review the GaussianRenderer4D class which extends GaussianRenderer to support 4D rendering with temporal parameters t, cov_t, and ms3', 'build a TLODRenderer instance with configurable height, width, marginal threshold, and 2DGS rendering mode', 'run the TLODRenderer call method with gaussian splat params, timestamps, intrinsics, and extrinsics to render images', 'run the fourdgs_rasterizer function to rasterize 4D gaussian splats with time-varying means, rotations, and opacities', 'run the threedgs_rasterizer function to rasterize 3D gaussian splats using gsplat rasterization with camera view matrices', 'run the twodgs_rasterizer function to rasterize 2D gaussian splats with channel padding and surface normal computation']
```

Usage

```
{'render_4D_gaussians': 'render 4D Gaussian splats by calling GaussianRenderer4D with gs_params, timestamps, intrinsics, and extrinsics to get RGB, mask, and depth', 'rasterize_single_image': 'rasterize a single 3D Gaussian image using SingleImageRasterization with means, quaternions, scales, opacities, colors, viewmats, and camera intrinsics', 'rasterize_batch_with_marginalization': 'rasterize a batch of 4D Gaussian frames using SingleBatchRasterization that computes temporal marginalization and updated opacities per timestamp', 'compute_temporal_marginal': 'compute the temporal marginal probability of a Gaussian at a given timestamp using compute_marginal_t with target time, mean time, and covariance', 'review_GaussianRenderer4D': 'review the GaussianRenderer4D class which extends GaussianRenderer to support 4D rendering with temporal parameters t, cov_t, and ms3'}
```

## File: facebookresearch_4dgt/tlod/renderers/tlod_renderer.py

Prompts

```
['render 4D Gaussian splats by calling GaussianRenderer4D with gs_params, timestamps, intrinsics, and extrinsics to get RGB, mask, and depth', 'rasterize a single 3D Gaussian image using SingleImageRasterization with means, quaternions, scales, opacities, colors, viewmats, and camera intrinsics', 'rasterize a batch of 4D Gaussian frames using SingleBatchRasterization that computes temporal marginalization and updated opacities per timestamp', 'compute the temporal marginal probability of a Gaussian at a given timestamp using compute_marginal_t with target time, mean time, and covariance', 'review the GaussianRenderer4D class which extends GaussianRenderer to support 4D rendering with temporal parameters t, cov_t, and ms3', 'build a TLODRenderer instance with configurable height, width, marginal threshold, and 2DGS rendering mode', 'run the TLODRenderer call method with gaussian splat params, timestamps, intrinsics, and extrinsics to render images', 'run the fourdgs_rasterizer function to rasterize 4D gaussian splats with time-varying means, rotations, and opacities', 'run the threedgs_rasterizer function to rasterize 3D gaussian splats using gsplat rasterization with camera view matrices', 'run the twodgs_rasterizer function to rasterize 2D gaussian splats with channel padding and surface normal computation']
```

Usage

```
{'build_TLODRenderer': 'build a TLODRenderer instance with configurable height, width, marginal threshold, and 2DGS rendering mode', 'run_TLODRenderer_call': 'run the TLODRenderer call method with gaussian splat params, timestamps, intrinsics, and extrinsics to render images', 'run_fourdgs_rasterizer': 'run the fourdgs_rasterizer function to rasterize 4D gaussian splats with time-varying means, rotations, and opacities', 'run_threedgs_rasterizer': 'run the threedgs_rasterizer function to rasterize 3D gaussian splats using gsplat rasterization with camera view matrices', 'run_twodgs_rasterizer': 'run the twodgs_rasterizer function to rasterize 2D gaussian splats with channel padding and surface normal computation'}
```

