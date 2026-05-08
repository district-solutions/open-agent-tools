# Agent Python Tools

- repo: facebookresearch/interhand2.6m
- repo_uri: https://github.com/facebookresearch/interhand2.6m

## File: facebookresearch_interhand2.6m/tool/MANO_render/render.py

Prompts

```
['render a MANO hand mesh to RGB and depth images using PyTorch3D PerspectiveCameras and SoftPhongShader', 'save 3D mesh vertices and face indices to an OBJ file for visualization or export', 'generate a 3D hand mesh from MANO pose, shape, and translation parameters using SMPLX', 'blend a rendered hand mesh onto a real image using depth-based masking and compositing', 'transform a 3D mesh from world coordinates to camera coordinates using rotation and translation matrices']
```

Usage

```
{'render_hand_mesh_pytorch3d': 'render a MANO hand mesh to RGB and depth images using PyTorch3D PerspectiveCameras and SoftPhongShader', 'save_obj_vertices_faces': 'save 3D mesh vertices and face indices to an OBJ file for visualization or export', 'generate_mano_mesh_from_params': 'generate a 3D hand mesh from MANO pose, shape, and translation parameters using SMPLX', 'blend_rendered_hand_onto_image': 'blend a rendered hand mesh onto a real image using depth-based masking and compositing', 'apply_camera_extrinsics_to_mesh': 'transform a 3D mesh from world coordinates to camera coordinates using rotation and translation matrices'}
```

