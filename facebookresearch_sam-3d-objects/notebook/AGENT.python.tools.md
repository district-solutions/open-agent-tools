# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/notebook/inference.py

Prompts

```
['run 3D object inference on an image with optional mask using the Inference class', 'render a 360-degree orbit video from a 3D Gaussian Splatting scene sample', 'merge multiple 3D Gaussian Splatting outputs into a single unified scene', 'normalize a 3D Gaussian Splatting scene by centering and scaling coordinates', 'load multiple segmentation masks from a folder by index with configurable extension', 'run the 3DB mesh alignment pipeline and save the aligned mesh to a PLY file in the output directory', 'run the 3DB mesh alignment pipeline and return aligned vertices, scale factor, and translation values', 'launch an interactive Gradio 3D viewer to visualize aligned human and 3Dfy object meshes side by side', 'load a 3DB mesh file and convert its vertices from OpenGL to PyTorch3D coordinate space', 'generate a MoGe point cloud from an image tensor using the pretrained MoGe ViT-L model']
```

Usage

```
{'run_Inference': 'run 3D object inference on an image with optional mask using the Inference class', 'render_video': 'render a 360-degree orbit video from a 3D Gaussian Splatting scene sample', 'make_scene': 'merge multiple 3D Gaussian Splatting outputs into a single unified scene', 'normalized_gaussian': 'normalize a 3D Gaussian Splatting scene by centering and scaling coordinates', 'load_masks': 'load multiple segmentation masks from a folder by index with configurable extension'}
```

## File: facebookresearch_sam-3d-objects/notebook/mesh_alignment.py

Prompts

```
['run 3D object inference on an image with optional mask using the Inference class', 'render a 360-degree orbit video from a 3D Gaussian Splatting scene sample', 'merge multiple 3D Gaussian Splatting outputs into a single unified scene', 'normalize a 3D Gaussian Splatting scene by centering and scaling coordinates', 'load multiple segmentation masks from a folder by index with configurable extension', 'run the 3DB mesh alignment pipeline and save the aligned mesh to a PLY file in the output directory', 'run the 3DB mesh alignment pipeline and return aligned vertices, scale factor, and translation values', 'launch an interactive Gradio 3D viewer to visualize aligned human and 3Dfy object meshes side by side', 'load a 3DB mesh file and convert its vertices from OpenGL to PyTorch3D coordinate space', 'generate a MoGe point cloud from an image tensor using the pretrained MoGe ViT-L model']
```

Usage

```
{'process_and_save_alignment': 'run the 3DB mesh alignment pipeline and save the aligned mesh to a PLY file in the output directory', 'process_3db_alignment': 'run the 3DB mesh alignment pipeline and return aligned vertices, scale factor, and translation values', 'visualize_meshes_interactive': 'launch an interactive Gradio 3D viewer to visualize aligned human and 3Dfy object meshes side by side', 'load_3db_mesh': 'load a 3DB mesh file and convert its vertices from OpenGL to PyTorch3D coordinate space', 'get_moge_pointcloud': 'generate a MoGe point cloud from an image tensor using the pretrained MoGe ViT-L model'}
```

