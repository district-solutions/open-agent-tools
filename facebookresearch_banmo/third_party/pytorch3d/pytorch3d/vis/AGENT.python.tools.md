# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/vis/plotly_vis.py

Prompts

```
['plot a PyTorch3D scene with Meshes, Pointclouds, Cameras, and RayBundle objects into named Plotly subplots', 'plot each element of a batched Meshes, Pointclouds, or Cameras object into its own Plotly subplot', 'generate a 3D wireframe tensor representing a camera symbol for visualization in Plotly', 'configure ambient, diffuse, specular, fresnel, and roughness lighting parameters for Mesh3D rendering in Plotly', 'configure Plotly 3D scene axis display options like grid, ticks, labels, and background color', 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return a PIL image of a TexturesUV texture with circled UV coordinate centers for debugging', 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize the circle color and radius when plotting UV centers on a texture image', 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles']
```

Usage

```
{'plot_scene': 'plot a PyTorch3D scene with Meshes, Pointclouds, Cameras, and RayBundle objects into named Plotly subplots', 'plot_batch_individually': 'plot each element of a batched Meshes, Pointclouds, or Cameras object into its own Plotly subplot', 'get_camera_wireframe': 'generate a 3D wireframe tensor representing a camera symbol for visualization in Plotly', 'Lighting': 'configure ambient, diffuse, specular, fresnel, and roughness lighting parameters for Mesh3D rendering in Plotly', 'AxisArgs': 'configure Plotly 3D scene axis display options like grid, ticks, labels, and background color'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/vis/texture_vis.py

Prompts

```
['plot a PyTorch3D scene with Meshes, Pointclouds, Cameras, and RayBundle objects into named Plotly subplots', 'plot each element of a batched Meshes, Pointclouds, or Cameras object into its own Plotly subplot', 'generate a 3D wireframe tensor representing a camera symbol for visualization in Plotly', 'configure ambient, diffuse, specular, fresnel, and roughness lighting parameters for Mesh3D rendering in Plotly', 'configure Plotly 3D scene axis display options like grid, ticks, labels, and background color', 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return a PIL image of a TexturesUV texture with circled UV coordinate centers for debugging', 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize the circle color and radius when plotting UV centers on a texture image', 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles']
```

Usage

```
{'plot_texturesuv_matplotlib': 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return_texturesuv_pil_image': 'return a PIL image of a TexturesUV texture with circled UV coordinate centers for debugging', 'subsample_uv_centers': 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize_circle_color_radius': 'customize the circle color and radius when plotting UV centers on a texture image', 'debug_uv_alignment': 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles'}
```

