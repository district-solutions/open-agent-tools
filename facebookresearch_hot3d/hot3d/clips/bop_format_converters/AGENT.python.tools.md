# Agent Python Tools

- repo: facebookresearch/hot3d
- repo_uri: https://github.com/facebookresearch/hot3d

## File: facebookresearch_hot3d/hot3d/clips/bop_format_converters/hot3d_clips_to_bop_scenewise.py

Prompts

```
['run the script to convert Hot3D-Clips dataset to BOP scenewise format using --hot3d-dataset-path and --split args', 'run the conversion script with --split train_quest3 to process Meta Quest 3 camera streams as gray1 and gray2', 'run the conversion script with --split train_aria to process Aria camera streams as rgb, gray1, and gray2', 'run the process_clip function to convert a single tar clip file into BOP scenewise format with camera, gt, and gt_info JSON', 'run the custom_rle_to_mask function to convert a custom RLE list into a 2D binary numpy array mask', 'run the script to convert GLB mesh files from Hot3D format to BOP PLY format', 'run the CLI tool with --input-gltf-dir and --output-bop-dir to convert all GLB models to PLY', 'use load_mesh to load a GLB file as a single concatenated trimesh Trimesh object', 'review the load_mesh function that loads a GLB scene and concatenates primitives into one mesh', 'refactor the main function to customize the meter to millimeter vertex scaling factor', 'convert all GLB files in a directory to BOP format PLY meshes and PNG textures', 'run the Hot3D to BOP format converter script with input GLTF and output BOP directories', 'save a GLB mesh as a PLY file with UV coordinates and extract its texture as PNG', 'extract the texture image from a GLB file and save it as a PNG image', 'convert Hot3D dataset object models from GLTF format to standard BOP PLY format']
```

Usage

```
{'convert_hot3d_clips_to_bop_scenewise': 'run the script to convert Hot3D-Clips dataset to BOP scenewise format using --hot3d-dataset-path and --split args', 'convert_quest3_split': 'run the conversion script with --split train_quest3 to process Meta Quest 3 camera streams as gray1 and gray2', 'convert_aria_split': 'run the conversion script with --split train_aria to process Aria camera streams as rgb, gray1, and gray2', 'process_clip_to_bop': 'run the process_clip function to convert a single tar clip file into BOP scenewise format with camera, gt, and gt_info JSON', 'convert_rle_to_mask': 'run the custom_rle_to_mask function to convert a custom RLE list into a 2D binary numpy array mask'}
```

## File: facebookresearch_hot3d/hot3d/clips/bop_format_converters/hot3d_models_eval_to_bop.py

Prompts

```
['run the script to convert Hot3D-Clips dataset to BOP scenewise format using --hot3d-dataset-path and --split args', 'run the conversion script with --split train_quest3 to process Meta Quest 3 camera streams as gray1 and gray2', 'run the conversion script with --split train_aria to process Aria camera streams as rgb, gray1, and gray2', 'run the process_clip function to convert a single tar clip file into BOP scenewise format with camera, gt, and gt_info JSON', 'run the custom_rle_to_mask function to convert a custom RLE list into a 2D binary numpy array mask', 'run the script to convert GLB mesh files from Hot3D format to BOP PLY format', 'run the CLI tool with --input-gltf-dir and --output-bop-dir to convert all GLB models to PLY', 'use load_mesh to load a GLB file as a single concatenated trimesh Trimesh object', 'review the load_mesh function that loads a GLB scene and concatenates primitives into one mesh', 'refactor the main function to customize the meter to millimeter vertex scaling factor', 'convert all GLB files in a directory to BOP format PLY meshes and PNG textures', 'run the Hot3D to BOP format converter script with input GLTF and output BOP directories', 'save a GLB mesh as a PLY file with UV coordinates and extract its texture as PNG', 'extract the texture image from a GLB file and save it as a PNG image', 'convert Hot3D dataset object models from GLTF format to standard BOP PLY format']
```

Usage

```
{'convert_glb_to_ply': 'run the script to convert GLB mesh files from Hot3D format to BOP PLY format', 'run_hot3d_to_bop_conversion': 'run the CLI tool with --input-gltf-dir and --output-bop-dir to convert all GLB models to PLY', 'load_mesh_from_glb': 'use load_mesh to load a GLB file as a single concatenated trimesh Trimesh object', 'review_load_mesh': 'review the load_mesh function that loads a GLB scene and concatenates primitives into one mesh', 'refactor_main_scaling': 'refactor the main function to customize the meter to millimeter vertex scaling factor'}
```

## File: facebookresearch_hot3d/hot3d/clips/bop_format_converters/hot3d_models_to_bop.py

Prompts

```
['run the script to convert Hot3D-Clips dataset to BOP scenewise format using --hot3d-dataset-path and --split args', 'run the conversion script with --split train_quest3 to process Meta Quest 3 camera streams as gray1 and gray2', 'run the conversion script with --split train_aria to process Aria camera streams as rgb, gray1, and gray2', 'run the process_clip function to convert a single tar clip file into BOP scenewise format with camera, gt, and gt_info JSON', 'run the custom_rle_to_mask function to convert a custom RLE list into a 2D binary numpy array mask', 'run the script to convert GLB mesh files from Hot3D format to BOP PLY format', 'run the CLI tool with --input-gltf-dir and --output-bop-dir to convert all GLB models to PLY', 'use load_mesh to load a GLB file as a single concatenated trimesh Trimesh object', 'review the load_mesh function that loads a GLB scene and concatenates primitives into one mesh', 'refactor the main function to customize the meter to millimeter vertex scaling factor', 'convert all GLB files in a directory to BOP format PLY meshes and PNG textures', 'run the Hot3D to BOP format converter script with input GLTF and output BOP directories', 'save a GLB mesh as a PLY file with UV coordinates and extract its texture as PNG', 'extract the texture image from a GLB file and save it as a PNG image', 'convert Hot3D dataset object models from GLTF format to standard BOP PLY format']
```

Usage

```
{'convert_glb_to_ply_and_png': 'convert all GLB files in a directory to BOP format PLY meshes and PNG textures', 'run_hot3d_to_bop_converter': 'run the Hot3D to BOP format converter script with input GLTF and output BOP directories', 'save_mesh_as_ply_with_uv_and_texture': 'save a GLB mesh as a PLY file with UV coordinates and extract its texture as PNG', 'extract_texture_from_glb': 'extract the texture image from a GLB file and save it as a PNG image', 'convert_hot3d_models_to_bop_format': 'convert Hot3D dataset object models from GLTF format to standard BOP PLY format'}
```

