# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/utils/utils.py

Prompts

```
['load a wavefront OBJ file and return vertices, texture vertices, and face indices', 'load a KRT file containing camera intrinsic and extrinsic parameters', 'create a Logger that duplicates all stdout output to a file', 'downsample an image array by a given factor using Gaussian filtering', 'generate texture maps containing vertex indices and barycentric coordinates from mesh data', 'create a video from image frames using ffmpeg by writing frames to a temp folder then encoding with libx264', 'build a color wheel and compute colored optical flow visualization from u and v flow tensor components', 'create a Writer instance to batch write tensor images asynchronously and finalize into an MP4 video file', 'refactor the writeimage function to render RGB, single channel, or flow field tensors into a PNG image file', 'summarize the resizecat function that resizes mismatched height tensors then concatenates them along a specified dimension']
```

Usage

```
{'load_obj_file': 'load a wavefront OBJ file and return vertices, texture vertices, and face indices', 'load_krt_camera_params': 'load a KRT file containing camera intrinsic and extrinsic parameters', 'create_logger_stdout_dup': 'create a Logger that duplicates all stdout output to a file', 'downsample_image': 'downsample an image array by a given factor using Gaussian filtering', 'generate_tritex_maps': 'generate texture maps containing vertex indices and barycentric coordinates from mesh data'}
```

## File: facebookresearch_mvp/utils/videowriter.py

Prompts

```
['load a wavefront OBJ file and return vertices, texture vertices, and face indices', 'load a KRT file containing camera intrinsic and extrinsic parameters', 'create a Logger that duplicates all stdout output to a file', 'downsample an image array by a given factor using Gaussian filtering', 'generate texture maps containing vertex indices and barycentric coordinates from mesh data', 'create a video from image frames using ffmpeg by writing frames to a temp folder then encoding with libx264', 'build a color wheel and compute colored optical flow visualization from u and v flow tensor components', 'create a Writer instance to batch write tensor images asynchronously and finalize into an MP4 video file', 'refactor the writeimage function to render RGB, single channel, or flow field tensors into a PNG image file', 'summarize the resizecat function that resizes mismatched height tensors then concatenates them along a specified dimension']
```

Usage

```
{'create_video_from_images': 'create a video from image frames using ffmpeg by writing frames to a temp folder then encoding with libx264', 'build_optical_flow_color_visualization': 'build a color wheel and compute colored optical flow visualization from u and v flow tensor components', 'create_writer_class_for_batch_image_output': 'create a Writer instance to batch write tensor images asynchronously and finalize into an MP4 video file', 'refactor_writeimage_for_single_frame_rendering': 'refactor the writeimage function to render RGB, single channel, or flow field tensors into a PNG image file', 'summarize_resizecat_tensor_concatenation': 'summarize the resizecat function that resizes mismatched height tensors then concatenates them along a specified dimension'}
```

