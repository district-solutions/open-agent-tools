# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/vis/plotly_vis.py

Prompts

```
['plot a PyTorch3D scene with meshes, pointclouds, cameras, and ray bundles into named plotly subplots', 'plot each batch element of meshes, pointclouds, or cameras in its own plotly subplot', 'get a 3D wireframe tensor representing a camera symbol at a given scale', 'configure plotly subplot axis appearance with grid, ticks, labels, and background color settings', 'configure mesh3d lighting parameters including ambient, diffuse, specular, fresnel, and roughness values', 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return a PIL image of a TexturesUV texture with circled verts_uvs positions for debugging UV alignment', 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize the circle color and radius when plotting UV centers on a texture image', 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles']
```

Usage

```
{'plot_scene': 'plot a PyTorch3D scene with meshes, pointclouds, cameras, and ray bundles into named plotly subplots', 'plot_batch_individually': 'plot each batch element of meshes, pointclouds, or cameras in its own plotly subplot', 'get_camera_wireframe': 'get a 3D wireframe tensor representing a camera symbol at a given scale', 'AxisArgs': 'configure plotly subplot axis appearance with grid, ticks, labels, and background color settings', 'Lighting': 'configure mesh3d lighting parameters including ambient, diffuse, specular, fresnel, and roughness values'}
```

## File: facebookresearch_pytorch3d/pytorch3d/vis/texture_vis.py

Prompts

```
['plot a PyTorch3D scene with meshes, pointclouds, cameras, and ray bundles into named plotly subplots', 'plot each batch element of meshes, pointclouds, or cameras in its own plotly subplot', 'get a 3D wireframe tensor representing a camera symbol at a given scale', 'configure plotly subplot axis appearance with grid, ticks, labels, and background color settings', 'configure mesh3d lighting parameters including ambient, diffuse, specular, fresnel, and roughness values', 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return a PIL image of a TexturesUV texture with circled verts_uvs positions for debugging UV alignment', 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize the circle color and radius when plotting UV centers on a texture image', 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles']
```

Usage

```
{'plot_texturesuv_with_matplotlib': 'plot a TexturesUV texture image with matplotlib showing circled UV coordinate centers for debugging', 'return_texturesuv_pil_image': 'return a PIL image of a TexturesUV texture with circled verts_uvs positions for debugging UV alignment', 'subsample_uv_centers': 'subsample UV coordinate centers when plotting texture images to limit the number of circles drawn', 'customize_circle_color_and_radius': 'customize the circle color and radius when plotting UV centers on a texture image', 'debug_uv_coordinate_alignment': 'debug UV coordinate alignment by visualizing verts_uvs positions on the texture map with circles'}
```

