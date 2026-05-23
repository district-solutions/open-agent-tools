# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/video/io.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'read frames sequentially from a video using VideoReader read method with built-in caching support', 'convert a video to individual frame images saved in a directory using cvt2frames method', 'join frame images from a directory into a video file using frames2video function with configurable fps and fourcc', 'create a fixed-capacity LRU cache using the Cache class to store and retrieve video frames efficiently', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize optical flow values to 0-255 range for compact jpeg storage using quantize_flow', 'warp an image using optical flow with nearest or bilinear interpolation via flow_warp', 'parse KITTI sparse optical flow from raw bytes and return flow array with validity mask', 'convert a video file to another format using ffmpeg with custom codec and bitrate options', 'resize a video to a specific width and height using ffmpeg scale filter', 'resize a video by a scaling ratio while optionally keeping the original aspect ratio', 'cut a clip from a video between a start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg concat demuxer']
```

Usage

```
{'create_VideoReader': 'create a VideoReader instance to open a video file and access frames by index or iteration', 'read_frames_with_VideoReader': 'read frames sequentially from a video using VideoReader read method with built-in caching support', 'extract_frames_to_directory': 'convert a video to individual frame images saved in a directory using cvt2frames method', 'build_video_from_frames': 'join frame images from a directory into a video file using frames2video function with configurable fps and fourcc', 'create_Cache': 'create a fixed-capacity LRU cache using the Cache class to store and retrieve video frames efficiently'}
```

## File: facebookresearch_sapiens/cv/mmcv/video/optflow.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'read frames sequentially from a video using VideoReader read method with built-in caching support', 'convert a video to individual frame images saved in a directory using cvt2frames method', 'join frame images from a directory into a video file using frames2video function with configurable fps and fourcc', 'create a fixed-capacity LRU cache using the Cache class to store and retrieve video frames efficiently', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize optical flow values to 0-255 range for compact jpeg storage using quantize_flow', 'warp an image using optical flow with nearest or bilinear interpolation via flow_warp', 'parse KITTI sparse optical flow from raw bytes and return flow array with validity mask', 'convert a video file to another format using ffmpeg with custom codec and bitrate options', 'resize a video to a specific width and height using ffmpeg scale filter', 'resize a video by a scaling ratio while optionally keeping the original aspect ratio', 'cut a clip from a video between a start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg concat demuxer']
```

Usage

```
{'read_optical_flow_flo': 'read an optical flow map from a .flo file or numpy array using flowread', 'write_optical_flow_to_file': 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize_flow_for_storage': 'quantize optical flow values to 0-255 range for compact jpeg storage using quantize_flow', 'warp_image_with_flow': 'warp an image using optical flow with nearest or bilinear interpolation via flow_warp', 'parse_sparse_flow_from_bytes': 'parse KITTI sparse optical flow from raw bytes and return flow array with validity mask'}
```

## File: facebookresearch_sapiens/cv/mmcv/video/processing.py

Prompts

```
['create a VideoReader instance to open a video file and access frames by index or iteration', 'read frames sequentially from a video using VideoReader read method with built-in caching support', 'convert a video to individual frame images saved in a directory using cvt2frames method', 'join frame images from a directory into a video file using frames2video function with configurable fps and fourcc', 'create a fixed-capacity LRU cache using the Cache class to store and retrieve video frames efficiently', 'read an optical flow map from a .flo file or numpy array using flowread', 'write an optical flow numpy array to a .flo file or quantized jpeg using flowwrite', 'quantize optical flow values to 0-255 range for compact jpeg storage using quantize_flow', 'warp an image using optical flow with nearest or bilinear interpolation via flow_warp', 'parse KITTI sparse optical flow from raw bytes and return flow array with validity mask', 'convert a video file to another format using ffmpeg with custom codec and bitrate options', 'resize a video to a specific width and height using ffmpeg scale filter', 'resize a video by a scaling ratio while optionally keeping the original aspect ratio', 'cut a clip from a video between a start and end time in seconds', 'concatenate multiple video files into a single output video using ffmpeg concat demuxer']
```

Usage

```
{'convert_video_ffmpeg': 'convert a video file to another format using ffmpeg with custom codec and bitrate options', 'resize_video_by_size': 'resize a video to a specific width and height using ffmpeg scale filter', 'resize_video_by_ratio': 'resize a video by a scaling ratio while optionally keeping the original aspect ratio', 'cut_video_clip': 'cut a clip from a video between a start and end time in seconds', 'concat_video_list': 'concatenate multiple video files into a single output video using ffmpeg concat demuxer'}
```

