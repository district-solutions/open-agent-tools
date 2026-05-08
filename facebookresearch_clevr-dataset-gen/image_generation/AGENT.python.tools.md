# Agent Python Tools

- repo: facebookresearch/clevr-dataset-gen
- repo_uri: https://github.com/facebookresearch/clevr-dataset-gen

## File: facebookresearch_clevr-dataset-gen/image_generation/render_images.py

Prompts

```
['render random CLEVR scenes with objects of random size, position, color, and shape using Blender', 'add random non-intersecting objects to a Blender scene with randomized size, color, shape, and orientation', 'compute spatial relationships between all pairs of objects in a CLEVR scene structure', 'check whether all objects in a Blender scene have a minimum number of visible pixels', 'render a Blender scene with flat shading and unique materials per object to verify visibility', 'extract command-line arguments after the double dash separator from sys.argv for Blender scripts', 'parse command-line arguments using an argparse parser by extracting args after the double dash', 'delete a specified Blender object from the scene by selecting it and running the delete operator', 'get 2D pixel-space coordinates and depth for a 3D world position from a camera perspective', 'load a Blender object from a .blend file and place it in the scene with scale and rotation']
```

Usage

```
{'render_clevr_scenes': 'render random CLEVR scenes with objects of random size, position, color, and shape using Blender', 'add_random_objects': 'add random non-intersecting objects to a Blender scene with randomized size, color, shape, and orientation', 'compute_all_relationships': 'compute spatial relationships between all pairs of objects in a CLEVR scene structure', 'check_visibility': 'check whether all objects in a Blender scene have a minimum number of visible pixels', 'render_shadeless': 'render a Blender scene with flat shading and unique materials per object to verify visibility'}
```

## File: facebookresearch_clevr-dataset-gen/image_generation/utils.py

Prompts

```
['render random CLEVR scenes with objects of random size, position, color, and shape using Blender', 'add random non-intersecting objects to a Blender scene with randomized size, color, shape, and orientation', 'compute spatial relationships between all pairs of objects in a CLEVR scene structure', 'check whether all objects in a Blender scene have a minimum number of visible pixels', 'render a Blender scene with flat shading and unique materials per object to verify visibility', 'extract command-line arguments after the double dash separator from sys.argv for Blender scripts', 'parse command-line arguments using an argparse parser by extracting args after the double dash', 'delete a specified Blender object from the scene by selecting it and running the delete operator', 'get 2D pixel-space coordinates and depth for a 3D world position from a camera perspective', 'load a Blender object from a .blend file and place it in the scene with scale and rotation']
```

Usage

```
{'extract_args': 'extract command-line arguments after the double dash separator from sys.argv for Blender scripts', 'parse_args': 'parse command-line arguments using an argparse parser by extracting args after the double dash', 'delete_object': 'delete a specified Blender object from the scene by selecting it and running the delete operator', 'get_camera_coords': 'get 2D pixel-space coordinates and depth for a 3D world position from a camera perspective', 'add_object': 'load a Blender object from a .blend file and place it in the scene with scale and rotation'}
```

