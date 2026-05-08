# Agent Python Tools

- repo: facebookresearch/holodiffusion
- repo_uri: https://github.com/facebookresearch/holo_diffusion

## File: facebookresearch_holodiffusion/holo_diffusion/custom_modules.py

Prompts

```
['build a configurable MLP with input skip connections and customizable hidden activation functions', 'create a feature aggregator module that uses an MLP to aggregate multi-view features with ray direction embeddings', 'test the MLPWithInputSkips forward pass with input tensor and optional skip tensor', 'review the MLPMeanFeatureAggregator forward method that aggregates sampled features using weighted mean reduction', 'refactor the function that computes normalized ray directions from 3D points to source camera centers', 'create a HoloDiffusionModel instance with voxel grid resolution and feature size configuration', 'run the forward pass of HoloDiffusionModel with RGB images and cameras to render predictions', 'sample random voxel features through the denoising diffusion process using net_3d and diffusion', 'create a 3D Unet model with configurable input and output channels for voxel feature processing', 'visualize HoloDiffusionModel predictions using Visdom with rendered images, depths, and masks', 'create a RenderMLP instance with configurable density and radiance MLP networks for 3D scene rendering', 'run the RenderMLP forward pass to compute densities, radiance features, and viewpoint-independent features from input features and view directions', 'get surface normals from 3D points using the RenderMLP density network and automatic differentiation', 'build a HoloVoxelGridImplicitFunction with configurable resolution, volume extent, and render MLP for implicit 3D scene representation', 'run the HoloVoxelGridImplicitFunction forward pass to sample voxel grid features along rays and decode densities and colour features']
```

Usage

```
{'build_MLPWithInputSkips': 'build a configurable MLP with input skip connections and customizable hidden activation functions', 'create_MLPMeanFeatureAggregator': 'create a feature aggregator module that uses an MLP to aggregate multi-view features with ray direction embeddings', 'test_MLPWithInputSkips_forward': 'test the MLPWithInputSkips forward pass with input tensor and optional skip tensor', 'review_MLPMeanFeatureAggregator_forward': 'review the MLPMeanFeatureAggregator forward method that aggregates sampled features using weighted mean reduction', 'refactor_get_point_to_source_camera_ray_dirs': 'refactor the function that computes normalized ray directions from 3D points to source camera centers'}
```

## File: facebookresearch_holodiffusion/holo_diffusion/holo_diffusion_model.py

Prompts

```
['build a configurable MLP with input skip connections and customizable hidden activation functions', 'create a feature aggregator module that uses an MLP to aggregate multi-view features with ray direction embeddings', 'test the MLPWithInputSkips forward pass with input tensor and optional skip tensor', 'review the MLPMeanFeatureAggregator forward method that aggregates sampled features using weighted mean reduction', 'refactor the function that computes normalized ray directions from 3D points to source camera centers', 'create a HoloDiffusionModel instance with voxel grid resolution and feature size configuration', 'run the forward pass of HoloDiffusionModel with RGB images and cameras to render predictions', 'sample random voxel features through the denoising diffusion process using net_3d and diffusion', 'create a 3D Unet model with configurable input and output channels for voxel feature processing', 'visualize HoloDiffusionModel predictions using Visdom with rendered images, depths, and masks', 'create a RenderMLP instance with configurable density and radiance MLP networks for 3D scene rendering', 'run the RenderMLP forward pass to compute densities, radiance features, and viewpoint-independent features from input features and view directions', 'get surface normals from 3D points using the RenderMLP density network and automatic differentiation', 'build a HoloVoxelGridImplicitFunction with configurable resolution, volume extent, and render MLP for implicit 3D scene representation', 'run the HoloVoxelGridImplicitFunction forward pass to sample voxel grid features along rays and decode densities and colour features']
```

Usage

```
{'create_HoloDiffusionModel': 'create a HoloDiffusionModel instance with voxel grid resolution and feature size configuration', 'run_forward_HoloDiffusionModel': 'run the forward pass of HoloDiffusionModel with RGB images and cameras to render predictions', 'sample_random_voxel_features': 'sample random voxel features through the denoising diffusion process using net_3d and diffusion', 'create_net_3d': 'create a 3D Unet model with configurable input and output channels for voxel feature processing', 'visualize_predictions': 'visualize HoloDiffusionModel predictions using Visdom with rendered images, depths, and masks'}
```

## File: facebookresearch_holodiffusion/holo_diffusion/holo_voxel_grid_implicit_function.py

Prompts

```
['build a configurable MLP with input skip connections and customizable hidden activation functions', 'create a feature aggregator module that uses an MLP to aggregate multi-view features with ray direction embeddings', 'test the MLPWithInputSkips forward pass with input tensor and optional skip tensor', 'review the MLPMeanFeatureAggregator forward method that aggregates sampled features using weighted mean reduction', 'refactor the function that computes normalized ray directions from 3D points to source camera centers', 'create a HoloDiffusionModel instance with voxel grid resolution and feature size configuration', 'run the forward pass of HoloDiffusionModel with RGB images and cameras to render predictions', 'sample random voxel features through the denoising diffusion process using net_3d and diffusion', 'create a 3D Unet model with configurable input and output channels for voxel feature processing', 'visualize HoloDiffusionModel predictions using Visdom with rendered images, depths, and masks', 'create a RenderMLP instance with configurable density and radiance MLP networks for 3D scene rendering', 'run the RenderMLP forward pass to compute densities, radiance features, and viewpoint-independent features from input features and view directions', 'get surface normals from 3D points using the RenderMLP density network and automatic differentiation', 'build a HoloVoxelGridImplicitFunction with configurable resolution, volume extent, and render MLP for implicit 3D scene representation', 'run the HoloVoxelGridImplicitFunction forward pass to sample voxel grid features along rays and decode densities and colour features']
```

Usage

```
{'create_RenderMLP': 'create a RenderMLP instance with configurable density and radiance MLP networks for 3D scene rendering', 'run_RenderMLP_forward': 'run the RenderMLP forward pass to compute densities, radiance features, and viewpoint-independent features from input features and view directions', 'get_RenderMLP_normals': 'get surface normals from 3D points using the RenderMLP density network and automatic differentiation', 'build_HoloVoxelGridImplicitFunction': 'build a HoloVoxelGridImplicitFunction with configurable resolution, volume extent, and render MLP for implicit 3D scene representation', 'run_HoloVoxelGridImplicitFunction_forward': 'run the HoloVoxelGridImplicitFunction forward pass to sample voxel grid features along rays and decode densities and colour features'}
```

