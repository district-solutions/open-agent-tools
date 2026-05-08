# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/compositor.py

Prompts

```
['create an AlphaCompositor to accumulate 3D points using alpha compositing with an optional background color', 'create a NormWeightedCompositor to accumulate 3D points using a normalized weighted sum approach', 'run the AlphaCompositor forward pass with fragments, alphas, and point clouds to render images', 'run the NormWeightedCompositor forward pass with fragments, alphas, and point clouds to render images', 'review the _add_background_color_to_images function to mask pixels without points using a background color', 'rasterize a batch of point clouds onto 2D images returning pixel indices, z-buffer, and squared distances', 'run a naive pure PyTorch implementation of point cloud rasterization for debugging or CPU-only environments', 'build a custom autograd forward pass that calls the CUDA rasterize_points kernel with configurable bin size', 'build a custom autograd backward pass that computes gradients through the rasterize_points CUDA kernel', 'create a function that formats a radius value into a per-point tensor for variable-radius point cloud rasterization', 'rasterize a batch of pointclouds into 2D image space using PointsRasterizer forward pass', 'transform pointcloud vertices from world space into NDC camera coordinates using the transform method', 'create a PointsRasterizationSettings dataclass to configure image size, radius, and points per pixel', 'build a PointFragments named tuple storing point indices, z-buffer, and squared distances per pixel', 'move the PointsRasterizer and its cameras to a specified torch device using the to method', 'create a PointsRenderer initialized with a rasterizer and compositor for rendering a batch of points', 'run the PointsRenderer forward pass on point clouds to produce rendered images with distance-based weights', 'move the PointsRenderer and its rasterizer and compositor to a specified torch device', 'review the PointsRenderer forward method to understand how distance-based alpha weights are computed from raster settings radius', 'refactor the PointsRenderer forward method to customize how fragments and weights are passed to the compositor']
```

Usage

```
{'create_AlphaCompositor': 'create an AlphaCompositor to accumulate 3D points using alpha compositing with an optional background color', 'create_NormWeightedCompositor': 'create a NormWeightedCompositor to accumulate 3D points using a normalized weighted sum approach', 'run_AlphaCompositor_forward': 'run the AlphaCompositor forward pass with fragments, alphas, and point clouds to render images', 'run_NormWeightedCompositor_forward': 'run the NormWeightedCompositor forward pass with fragments, alphas, and point clouds to render images', 'review_add_background_color': 'review the _add_background_color_to_images function to mask pixels without points using a background color'}
```

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/rasterize_points.py

Prompts

```
['create an AlphaCompositor to accumulate 3D points using alpha compositing with an optional background color', 'create a NormWeightedCompositor to accumulate 3D points using a normalized weighted sum approach', 'run the AlphaCompositor forward pass with fragments, alphas, and point clouds to render images', 'run the NormWeightedCompositor forward pass with fragments, alphas, and point clouds to render images', 'review the _add_background_color_to_images function to mask pixels without points using a background color', 'rasterize a batch of point clouds onto 2D images returning pixel indices, z-buffer, and squared distances', 'run a naive pure PyTorch implementation of point cloud rasterization for debugging or CPU-only environments', 'build a custom autograd forward pass that calls the CUDA rasterize_points kernel with configurable bin size', 'build a custom autograd backward pass that computes gradients through the rasterize_points CUDA kernel', 'create a function that formats a radius value into a per-point tensor for variable-radius point cloud rasterization', 'rasterize a batch of pointclouds into 2D image space using PointsRasterizer forward pass', 'transform pointcloud vertices from world space into NDC camera coordinates using the transform method', 'create a PointsRasterizationSettings dataclass to configure image size, radius, and points per pixel', 'build a PointFragments named tuple storing point indices, z-buffer, and squared distances per pixel', 'move the PointsRasterizer and its cameras to a specified torch device using the to method', 'create a PointsRenderer initialized with a rasterizer and compositor for rendering a batch of points', 'run the PointsRenderer forward pass on point clouds to produce rendered images with distance-based weights', 'move the PointsRenderer and its rasterizer and compositor to a specified torch device', 'review the PointsRenderer forward method to understand how distance-based alpha weights are computed from raster settings radius', 'refactor the PointsRenderer forward method to customize how fragments and weights are passed to the compositor']
```

Usage

```
{'rasterize_points': 'rasterize a batch of point clouds onto 2D images returning pixel indices, z-buffer, and squared distances', 'rasterize_points_python': 'run a naive pure PyTorch implementation of point cloud rasterization for debugging or CPU-only environments', 'RasterizePoints_forward': 'build a custom autograd forward pass that calls the CUDA rasterize_points kernel with configurable bin size', 'RasterizePoints_backward': 'build a custom autograd backward pass that computes gradients through the rasterize_points CUDA kernel', 'format_radius': 'create a function that formats a radius value into a per-point tensor for variable-radius point cloud rasterization'}
```

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/rasterizer.py

Prompts

```
['create an AlphaCompositor to accumulate 3D points using alpha compositing with an optional background color', 'create a NormWeightedCompositor to accumulate 3D points using a normalized weighted sum approach', 'run the AlphaCompositor forward pass with fragments, alphas, and point clouds to render images', 'run the NormWeightedCompositor forward pass with fragments, alphas, and point clouds to render images', 'review the _add_background_color_to_images function to mask pixels without points using a background color', 'rasterize a batch of point clouds onto 2D images returning pixel indices, z-buffer, and squared distances', 'run a naive pure PyTorch implementation of point cloud rasterization for debugging or CPU-only environments', 'build a custom autograd forward pass that calls the CUDA rasterize_points kernel with configurable bin size', 'build a custom autograd backward pass that computes gradients through the rasterize_points CUDA kernel', 'create a function that formats a radius value into a per-point tensor for variable-radius point cloud rasterization', 'rasterize a batch of pointclouds into 2D image space using PointsRasterizer forward pass', 'transform pointcloud vertices from world space into NDC camera coordinates using the transform method', 'create a PointsRasterizationSettings dataclass to configure image size, radius, and points per pixel', 'build a PointFragments named tuple storing point indices, z-buffer, and squared distances per pixel', 'move the PointsRasterizer and its cameras to a specified torch device using the to method', 'create a PointsRenderer initialized with a rasterizer and compositor for rendering a batch of points', 'run the PointsRenderer forward pass on point clouds to produce rendered images with distance-based weights', 'move the PointsRenderer and its rasterizer and compositor to a specified torch device', 'review the PointsRenderer forward method to understand how distance-based alpha weights are computed from raster settings radius', 'refactor the PointsRenderer forward method to customize how fragments and weights are passed to the compositor']
```

Usage

```
{'rasterize_pointclouds': 'rasterize a batch of pointclouds into 2D image space using PointsRasterizer forward pass', 'transform_points_to_ndc': 'transform pointcloud vertices from world space into NDC camera coordinates using the transform method', 'create_rasterization_settings': 'create a PointsRasterizationSettings dataclass to configure image size, radius, and points per pixel', 'build_pointfragments': 'build a PointFragments named tuple storing point indices, z-buffer, and squared distances per pixel', 'move_rasterizer_to_device': 'move the PointsRasterizer and its cameras to a specified torch device using the to method'}
```

## File: facebookresearch_pytorch3d/pytorch3d/renderer/points/renderer.py

Prompts

```
['create an AlphaCompositor to accumulate 3D points using alpha compositing with an optional background color', 'create a NormWeightedCompositor to accumulate 3D points using a normalized weighted sum approach', 'run the AlphaCompositor forward pass with fragments, alphas, and point clouds to render images', 'run the NormWeightedCompositor forward pass with fragments, alphas, and point clouds to render images', 'review the _add_background_color_to_images function to mask pixels without points using a background color', 'rasterize a batch of point clouds onto 2D images returning pixel indices, z-buffer, and squared distances', 'run a naive pure PyTorch implementation of point cloud rasterization for debugging or CPU-only environments', 'build a custom autograd forward pass that calls the CUDA rasterize_points kernel with configurable bin size', 'build a custom autograd backward pass that computes gradients through the rasterize_points CUDA kernel', 'create a function that formats a radius value into a per-point tensor for variable-radius point cloud rasterization', 'rasterize a batch of pointclouds into 2D image space using PointsRasterizer forward pass', 'transform pointcloud vertices from world space into NDC camera coordinates using the transform method', 'create a PointsRasterizationSettings dataclass to configure image size, radius, and points per pixel', 'build a PointFragments named tuple storing point indices, z-buffer, and squared distances per pixel', 'move the PointsRasterizer and its cameras to a specified torch device using the to method', 'create a PointsRenderer initialized with a rasterizer and compositor for rendering a batch of points', 'run the PointsRenderer forward pass on point clouds to produce rendered images with distance-based weights', 'move the PointsRenderer and its rasterizer and compositor to a specified torch device', 'review the PointsRenderer forward method to understand how distance-based alpha weights are computed from raster settings radius', 'refactor the PointsRenderer forward method to customize how fragments and weights are passed to the compositor']
```

Usage

```
{'create_PointsRenderer': 'create a PointsRenderer initialized with a rasterizer and compositor for rendering a batch of points', 'run_PointsRenderer_forward': 'run the PointsRenderer forward pass on point clouds to produce rendered images with distance-based weights', 'move_PointsRenderer_to_device': 'move the PointsRenderer and its rasterizer and compositor to a specified torch device', 'review_PointsRenderer_weights': 'review the PointsRenderer forward method to understand how distance-based alpha weights are computed from raster settings radius', 'refactor_PointsRenderer_compositor_call': 'refactor the PointsRenderer forward method to customize how fragments and weights are passed to the compositor'}
```

