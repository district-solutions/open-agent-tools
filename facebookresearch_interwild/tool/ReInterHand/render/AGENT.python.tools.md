# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/tool/ReInterHand/render/reih_render_mano_3rd.py

Prompts

```
['run the script to render MANO hand meshes from pose parameters and save composited images', 'run the load_ply function to read a PLY file and return vertex coordinates as a numpy array', 'run the render_mesh function to rasterize a hand mesh with camera parameters and return RGB, depth, and mask', 'review the render_mesh function that uses PyTorch3D PerspectiveCameras, MeshRasterizer, and SoftPhongShader to render meshes', 'refactor the render_mesh function to support configurable material colors beyond hardcoded red for right and green for left hands', 'render MANO hand model meshes onto ego camera images using PyTorch3D with fisheye distortion', 'load vertex positions from a PLY mesh file and return them as a numpy array', 'apply fisheye lens distortion to 3D point coordinates using polynomial distortion coefficients', 'render a 3D mesh with camera parameters using PyTorch3D and return RGB, depth, and mask', 'review the distort_fisheye function that applies polynomial fisheye distortion to 3D points']
```

Usage

```
{'run_render_mano_hands': 'run the script to render MANO hand meshes from pose parameters and save composited images', 'run_load_ply': 'run the load_ply function to read a PLY file and return vertex coordinates as a numpy array', 'run_render_mesh': 'run the render_mesh function to rasterize a hand mesh with camera parameters and return RGB, depth, and mask', 'review_render_mesh': 'review the render_mesh function that uses PyTorch3D PerspectiveCameras, MeshRasterizer, and SoftPhongShader to render meshes', 'refactor_render_mesh': 'refactor the render_mesh function to support configurable material colors beyond hardcoded red for right and green for left hands'}
```

## File: facebookresearch_interwild/tool/ReInterHand/render/reih_render_mano_ego.py

Prompts

```
['run the script to render MANO hand meshes from pose parameters and save composited images', 'run the load_ply function to read a PLY file and return vertex coordinates as a numpy array', 'run the render_mesh function to rasterize a hand mesh with camera parameters and return RGB, depth, and mask', 'review the render_mesh function that uses PyTorch3D PerspectiveCameras, MeshRasterizer, and SoftPhongShader to render meshes', 'refactor the render_mesh function to support configurable material colors beyond hardcoded red for right and green for left hands', 'render MANO hand model meshes onto ego camera images using PyTorch3D with fisheye distortion', 'load vertex positions from a PLY mesh file and return them as a numpy array', 'apply fisheye lens distortion to 3D point coordinates using polynomial distortion coefficients', 'render a 3D mesh with camera parameters using PyTorch3D and return RGB, depth, and mask', 'review the distort_fisheye function that applies polynomial fisheye distortion to 3D points']
```

Usage

```
{'render_MANO_hand_meshes': 'render MANO hand model meshes onto ego camera images using PyTorch3D with fisheye distortion', 'load_ply': 'load vertex positions from a PLY mesh file and return them as a numpy array', 'distort_fisheye': 'apply fisheye lens distortion to 3D point coordinates using polynomial distortion coefficients', 'render_mesh': 'render a 3D mesh with camera parameters using PyTorch3D and return RGB, depth, and mask', 'review_distort_fisheye': 'review the distort_fisheye function that applies polynomial fisheye distortion to 3D points'}
```

