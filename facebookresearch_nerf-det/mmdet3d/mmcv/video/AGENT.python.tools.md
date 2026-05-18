# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/video/io.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'get a specific frame by index from a VideoReader using the get_frame method', 'convert a video to individual frame images saved in an output directory using cvt2frames', 'join frame images from a directory into a single video file using frames2video', 'create a fixed-capacity LRU Cache using OrderedDict to store and retrieve video frames', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize an optical flow array to 0-255 uint8 values for compact jpeg storage', 'recover a float32 optical flow array from quantized dx and dy uint8 components', 'warp an image using an optical flow field with nearest or bilinear interpolation via flow_warp', 'convert a video file to another format using ffmpeg with custom codec options', 'resize a video to a specific width and height or scale ratio with ffmpeg', 'cut a clip from a video by specifying start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg', 'review the video processing module functions for ffmpeg conversion, resizing, cutting, and concatenation']
```

Usage

```
{'create_VideoReader': 'create a VideoReader instance to open a video file and access frames by index or iteration', 'use_VideoReader_get_frame': 'get a specific frame by index from a VideoReader using the get_frame method', 'use_VideoReader_cvt2frames': 'convert a video to individual frame images saved in an output directory using cvt2frames', 'use_frames2video': 'join frame images from a directory into a single video file using frames2video', 'use_Cache': 'create a fixed-capacity LRU Cache using OrderedDict to store and retrieve video frames'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/video/optflow.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'get a specific frame by index from a VideoReader using the get_frame method', 'convert a video to individual frame images saved in an output directory using cvt2frames', 'join frame images from a directory into a single video file using frames2video', 'create a fixed-capacity LRU Cache using OrderedDict to store and retrieve video frames', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize an optical flow array to 0-255 uint8 values for compact jpeg storage', 'recover a float32 optical flow array from quantized dx and dy uint8 components', 'warp an image using an optical flow field with nearest or bilinear interpolation via flow_warp', 'convert a video file to another format using ffmpeg with custom codec options', 'resize a video to a specific width and height or scale ratio with ffmpeg', 'cut a clip from a video by specifying start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg', 'review the video processing module functions for ffmpeg conversion, resizing, cutting, and concatenation']
```

Usage

```
{'read_flow_from_file': 'read an optical flow map from a .flo file or numpy array using flowread', 'write_flow_to_file': 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize_flow': 'quantize an optical flow array to 0-255 uint8 values for compact jpeg storage', 'dequantize_flow': 'recover a float32 optical flow array from quantized dx and dy uint8 components', 'warp_image_with_flow': 'warp an image using an optical flow field with nearest or bilinear interpolation via flow_warp'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/video/processing.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'get a specific frame by index from a VideoReader using the get_frame method', 'convert a video to individual frame images saved in an output directory using cvt2frames', 'join frame images from a directory into a single video file using frames2video', 'create a fixed-capacity LRU Cache using OrderedDict to store and retrieve video frames', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize an optical flow array to 0-255 uint8 values for compact jpeg storage', 'recover a float32 optical flow array from quantized dx and dy uint8 components', 'warp an image using an optical flow field with nearest or bilinear interpolation via flow_warp', 'convert a video file to another format using ffmpeg with custom codec options', 'resize a video to a specific width and height or scale ratio with ffmpeg', 'cut a clip from a video by specifying start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg', 'review the video processing module functions for ffmpeg conversion, resizing, cutting, and concatenation']
```

Usage

```
{'convert_video_ffmpeg': 'convert a video file to another format using ffmpeg with custom codec options', 'resize_video_dimensions': 'resize a video to a specific width and height or scale ratio with ffmpeg', 'cut_video_clip': 'cut a clip from a video by specifying start and end time in seconds', 'concat_video_list': 'concatenate multiple video files into a single output video using ffmpeg', 'review_processing_functions': 'review the video processing module functions for ffmpeg conversion, resizing, cutting, and concatenation'}
```

