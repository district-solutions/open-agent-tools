# Agent Python Tools

- repo: facebookresearch/pifuhd
- repo_uri: https://github.com/facebookresearch/pifuhd.git

## File: facebookresearch_pifuhd/apps/clean_mesh.py

Prompts

```
['run the meshcleaning function to clean OBJ mesh files in a directory', 'run the CLI with -f flag to clean all OBJ meshes in a folder', 'refactor the meshcleaning function to keep the largest connected component by vertex count', 'review the meshcleaning function to understand how it selects the tallest connected component', 'summarize the meshcleaning function that splits OBJ meshes and keeps the tallest component', 'run the reconWrapper CLI to reconstruct 3D human meshes from images using PIFuHD checkpoints', 'run the recon function to generate 3D OBJ meshes from a dataset of input images', 'run gen_mesh to reconstruct a 3D mesh with normal-based vertex colors from a single image', 'run gen_mesh_imgColor to reconstruct a 3D mesh with image-projected UV colors from a single image', 'review the recon function to understand how PIFuHD checkpoints are loaded and meshes are generated', 'render a 360 degree turntable video from OBJ mesh files using the CLI with -f flag', 'create a 3x3 rotation matrix from Euler angles rx, ry, rz using make_rotate', 'render OBJ meshes with GeoRender geometry mode using the -g flag for normal visualization', 'render OBJ meshes with ColorRender mode using vertex normals as colors for visual output', 'encode rendered rotation frames into an MP4 video using ffmpeg at 30fps with libx264']
```

Usage

```
{'run_meshcleaning': 'run the meshcleaning function to clean OBJ mesh files in a directory', 'run_cli_meshcleaning': 'run the CLI with -f flag to clean all OBJ meshes in a folder', 'refactor_meshcleaning': 'refactor the meshcleaning function to keep the largest connected component by vertex count', 'review_meshcleaning': 'review the meshcleaning function to understand how it selects the tallest connected component', 'summarize_meshcleaning': 'summarize the meshcleaning function that splits OBJ meshes and keeps the tallest component'}
```

## File: facebookresearch_pifuhd/apps/recon.py

Prompts

```
['run the meshcleaning function to clean OBJ mesh files in a directory', 'run the CLI with -f flag to clean all OBJ meshes in a folder', 'refactor the meshcleaning function to keep the largest connected component by vertex count', 'review the meshcleaning function to understand how it selects the tallest connected component', 'summarize the meshcleaning function that splits OBJ meshes and keeps the tallest component', 'run the reconWrapper CLI to reconstruct 3D human meshes from images using PIFuHD checkpoints', 'run the recon function to generate 3D OBJ meshes from a dataset of input images', 'run gen_mesh to reconstruct a 3D mesh with normal-based vertex colors from a single image', 'run gen_mesh_imgColor to reconstruct a 3D mesh with image-projected UV colors from a single image', 'review the recon function to understand how PIFuHD checkpoints are loaded and meshes are generated', 'render a 360 degree turntable video from OBJ mesh files using the CLI with -f flag', 'create a 3x3 rotation matrix from Euler angles rx, ry, rz using make_rotate', 'render OBJ meshes with GeoRender geometry mode using the -g flag for normal visualization', 'render OBJ meshes with ColorRender mode using vertex normals as colors for visual output', 'encode rendered rotation frames into an MP4 video using ffmpeg at 30fps with libx264']
```

Usage

```
{'run_reconWrapper': 'run the reconWrapper CLI to reconstruct 3D human meshes from images using PIFuHD checkpoints', 'run_recon': 'run the recon function to generate 3D OBJ meshes from a dataset of input images', 'run_gen_mesh': 'run gen_mesh to reconstruct a 3D mesh with normal-based vertex colors from a single image', 'run_gen_mesh_imgColor': 'run gen_mesh_imgColor to reconstruct a 3D mesh with image-projected UV colors from a single image', 'review_recon': 'review the recon function to understand how PIFuHD checkpoints are loaded and meshes are generated'}
```

## File: facebookresearch_pifuhd/apps/render_turntable.py

Prompts

```
['run the meshcleaning function to clean OBJ mesh files in a directory', 'run the CLI with -f flag to clean all OBJ meshes in a folder', 'refactor the meshcleaning function to keep the largest connected component by vertex count', 'review the meshcleaning function to understand how it selects the tallest connected component', 'summarize the meshcleaning function that splits OBJ meshes and keeps the tallest component', 'run the reconWrapper CLI to reconstruct 3D human meshes from images using PIFuHD checkpoints', 'run the recon function to generate 3D OBJ meshes from a dataset of input images', 'run gen_mesh to reconstruct a 3D mesh with normal-based vertex colors from a single image', 'run gen_mesh_imgColor to reconstruct a 3D mesh with image-projected UV colors from a single image', 'review the recon function to understand how PIFuHD checkpoints are loaded and meshes are generated', 'render a 360 degree turntable video from OBJ mesh files using the CLI with -f flag', 'create a 3x3 rotation matrix from Euler angles rx, ry, rz using make_rotate', 'render OBJ meshes with GeoRender geometry mode using the -g flag for normal visualization', 'render OBJ meshes with ColorRender mode using vertex normals as colors for visual output', 'encode rendered rotation frames into an MP4 video using ffmpeg at 30fps with libx264']
```

Usage

```
{'render_turntable_video': 'render a 360 degree turntable video from OBJ mesh files using the CLI with -f flag', 'make_rotate_matrix': 'create a 3x3 rotation matrix from Euler angles rx, ry, rz using make_rotate', 'render_with_geo_render': 'render OBJ meshes with GeoRender geometry mode using the -g flag for normal visualization', 'render_with_color_render': 'render OBJ meshes with ColorRender mode using vertex normals as colors for visual output', 'encode_frames_to_mp4': 'encode rendered rotation frames into an MP4 video using ffmpeg at 30fps with libx264'}
```

