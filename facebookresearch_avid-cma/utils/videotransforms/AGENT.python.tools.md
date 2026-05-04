# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/utils/videotransforms/functional.py

Prompts

```
['crop a list of numpy array video frames using specified height and width coordinates', 'crop a list of PIL Image video frames using specified bounding box coordinates', 'resize a list of numpy array video frames to a target size with bilinear or nearest interpolation', 'resize a list of PIL Image video frames to a target size with bilinear or nearest interpolation', 'compute the output height and width for resizing an image while preserving aspect ratio', 'build a python module that uses Compose to chain multiple video transforms on a clip of frames', 'create a function that uses RandomDrop to randomly select a fixed number of frames from a video clip', 'create a function that uses UniformDrop to uniformly subsample frames from a video clip by count or ratio', 'build a python module that uses RandomResizedCrop to crop and resize video frames with random scale and aspect ratio', 'create a function that uses TemporalJitter to temporally subsample a video clip with configurable time scale']
```

Usage

```
{'crop_video_clip_numpy': 'crop a list of numpy array video frames using specified height and width coordinates', 'crop_video_clip_pil': 'crop a list of PIL Image video frames using specified bounding box coordinates', 'resize_video_clip_numpy': 'resize a list of numpy array video frames to a target size with bilinear or nearest interpolation', 'resize_video_clip_pil': 'resize a list of PIL Image video frames to a target size with bilinear or nearest interpolation', 'compute_resize_dimensions': 'compute the output height and width for resizing an image while preserving aspect ratio'}
```

## File: facebookresearch_avid-cma/utils/videotransforms/video_transforms.py

Prompts

```
['crop a list of numpy array video frames using specified height and width coordinates', 'crop a list of PIL Image video frames using specified bounding box coordinates', 'resize a list of numpy array video frames to a target size with bilinear or nearest interpolation', 'resize a list of PIL Image video frames to a target size with bilinear or nearest interpolation', 'compute the output height and width for resizing an image while preserving aspect ratio', 'build a python module that uses Compose to chain multiple video transforms on a clip of frames', 'create a function that uses RandomDrop to randomly select a fixed number of frames from a video clip', 'create a function that uses UniformDrop to uniformly subsample frames from a video clip by count or ratio', 'build a python module that uses RandomResizedCrop to crop and resize video frames with random scale and aspect ratio', 'create a function that uses TemporalJitter to temporally subsample a video clip with configurable time scale']
```

Usage

```
{'compose_video_transforms': 'build a python module that uses Compose to chain multiple video transforms on a clip of frames', 'random_drop_frames': 'create a function that uses RandomDrop to randomly select a fixed number of frames from a video clip', 'uniform_drop_frames': 'create a function that uses UniformDrop to uniformly subsample frames from a video clip by count or ratio', 'random_resized_crop_clip': 'build a python module that uses RandomResizedCrop to crop and resize video frames with random scale and aspect ratio', 'temporal_jitter_clip': 'create a function that uses TemporalJitter to temporally subsample a video clip with configurable time scale'}
```

