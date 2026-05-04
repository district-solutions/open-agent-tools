# Agent Python Tools

- repo: facebookresearch/embody-3d
- repo_uri: https://github.com/facebookresearch/embody-3d

## File: facebookresearch_embody-3d/src/load_obj.py

Prompts

```
['load a wavefront OBJ file from a path string and return vertices, texture coordinates, and face indices', 'load a wavefront OBJ file from a file-like object and return parsed mesh data as numpy arrays', 'parse vertex positions from a Wavefront OBJ file and return them as a float32 numpy array', 'parse texture coordinates from a Wavefront OBJ file and return them as a float32 numpy array', 'handle OBJ files with mixed face types like triangles and quads by returning ragged numpy arrays', 'run the CLI to load SMPL-X data and render 3D mesh videos from a dataset', 'run the CLI with --load_multiperson to render SMPL-X meshes for multiple people in a sequence', 'run the CLI with --anno audio to render videos with audio tracks merged via ffmpeg', 'compute SMPL-X mesh vertices from a batch of body, rotation, translation, and shape features', 'load a BaseDataset, compute SMPL-X vertices, render frames, and save as MP4 video files', 'build a PyrenderRenderer instance with a topology OBJ file path and custom rendering dimensions', 'create a checkerboard floor geometry with configurable tile size, colors, and up-axis orientation', 'render a batch of 3D mesh vertex tensors into RGBA images using the forward method', 'compute a camera view transformation matrix from center, up direction, and camera position', 'create a pyrender mesh from a vertex tensor with a specified color and magnification factor']
```

Usage

```
{'load_obj_file': 'load a wavefront OBJ file from a path string and return vertices, texture coordinates, and face indices', 'load_obj_filelike': 'load a wavefront OBJ file from a file-like object and return parsed mesh data as numpy arrays', 'parse_obj_vertices': 'parse vertex positions from a Wavefront OBJ file and return them as a float32 numpy array', 'parse_obj_texture_coords': 'parse texture coordinates from a Wavefront OBJ file and return them as a float32 numpy array', 'handle_mixed_faces': 'handle OBJ files with mixed face types like triangles and quads by returning ragged numpy arrays'}
```

## File: facebookresearch_embody-3d/src/run.py

Prompts

```
['load a wavefront OBJ file from a path string and return vertices, texture coordinates, and face indices', 'load a wavefront OBJ file from a file-like object and return parsed mesh data as numpy arrays', 'parse vertex positions from a Wavefront OBJ file and return them as a float32 numpy array', 'parse texture coordinates from a Wavefront OBJ file and return them as a float32 numpy array', 'handle OBJ files with mixed face types like triangles and quads by returning ragged numpy arrays', 'run the CLI to load SMPL-X data and render 3D mesh videos from a dataset', 'run the CLI with --load_multiperson to render SMPL-X meshes for multiple people in a sequence', 'run the CLI with --anno audio to render videos with audio tracks merged via ffmpeg', 'compute SMPL-X mesh vertices from a batch of body, rotation, translation, and shape features', 'load a BaseDataset, compute SMPL-X vertices, render frames, and save as MP4 video files', 'build a PyrenderRenderer instance with a topology OBJ file path and custom rendering dimensions', 'create a checkerboard floor geometry with configurable tile size, colors, and up-axis orientation', 'render a batch of 3D mesh vertex tensors into RGBA images using the forward method', 'compute a camera view transformation matrix from center, up direction, and camera position', 'create a pyrender mesh from a vertex tensor with a specified color and magnification factor']
```

Usage

```
{'run_smplx_mesh_rendering': 'run the CLI to load SMPL-X data and render 3D mesh videos from a dataset', 'run_multiperson_mesh_rendering': 'run the CLI with --load_multiperson to render SMPL-X meshes for multiple people in a sequence', 'run_audio_video_rendering': 'run the CLI with --anno audio to render videos with audio tracks merged via ffmpeg', 'compute_lbs_from_batch': 'compute SMPL-X mesh vertices from a batch of body, rotation, translation, and shape features', 'load_and_visualize_data': 'load a BaseDataset, compute SMPL-X vertices, render frames, and save as MP4 video files'}
```

## File: facebookresearch_embody-3d/src/visualize.py

Prompts

```
['load a wavefront OBJ file from a path string and return vertices, texture coordinates, and face indices', 'load a wavefront OBJ file from a file-like object and return parsed mesh data as numpy arrays', 'parse vertex positions from a Wavefront OBJ file and return them as a float32 numpy array', 'parse texture coordinates from a Wavefront OBJ file and return them as a float32 numpy array', 'handle OBJ files with mixed face types like triangles and quads by returning ragged numpy arrays', 'run the CLI to load SMPL-X data and render 3D mesh videos from a dataset', 'run the CLI with --load_multiperson to render SMPL-X meshes for multiple people in a sequence', 'run the CLI with --anno audio to render videos with audio tracks merged via ffmpeg', 'compute SMPL-X mesh vertices from a batch of body, rotation, translation, and shape features', 'load a BaseDataset, compute SMPL-X vertices, render frames, and save as MP4 video files', 'build a PyrenderRenderer instance with a topology OBJ file path and custom rendering dimensions', 'create a checkerboard floor geometry with configurable tile size, colors, and up-axis orientation', 'render a batch of 3D mesh vertex tensors into RGBA images using the forward method', 'compute a camera view transformation matrix from center, up direction, and camera position', 'create a pyrender mesh from a vertex tensor with a specified color and magnification factor']
```

Usage

```
{'build_PyrenderRenderer': 'build a PyrenderRenderer instance with a topology OBJ file path and custom rendering dimensions', 'create_checkerboard_geometry': 'create a checkerboard floor geometry with configurable tile size, colors, and up-axis orientation', 'render_meshes_forward': 'render a batch of 3D mesh vertex tensors into RGBA images using the forward method', 'setup_camera_viewmatrix': 'compute a camera view transformation matrix from center, up direction, and camera position', 'create_mesh_from_vertices': 'create a pyrender mesh from a vertex tensor with a specified color and magnification factor'}
```

