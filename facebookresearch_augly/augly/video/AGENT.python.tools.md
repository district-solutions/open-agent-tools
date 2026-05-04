# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/video/functional.py

Prompts

```
['apply gaussian blur to a video file with configurable sigma strength', 'speed up or slow down a video by a given factor', 'concatenate multiple video files together with optional transitions between clips', 'overlay random or custom text onto video frames with configurable fonts and colors', 'trim a video to a specified start and end time in seconds', 'create a Blur transform class to apply Gaussian blur with configurable sigma to a video file', 'create a Brightness transform class to brighten or darken a video by a specified level factor', 'create a RandomBlur transform class to randomly blur a video with sigma chosen from a min-max range', 'create a composition of video transforms like Blur, Brightness, and HFlip to apply multiple augmentations in sequence', 'create an Overlay transform class to overlay an image or video onto another video at a specified position', 'apply an image augmentation function to each frame of a video and reassemble with audio', 'apply an image augmentation function combining frames from two separate videos into one output', 'apply a CV2-based video augmenter to a video file and save the augmented result', 'get a dictionary with an image directory path and its listed image files', 'review the video utility functions for frame extraction, augmentation, and reassembly patterns']
```

Usage

```
{'blur_video': 'apply gaussian blur to a video file with configurable sigma strength', 'change_video_speed': 'speed up or slow down a video by a given factor', 'concat_videos': 'concatenate multiple video files together with optional transitions between clips', 'overlay_text_on_video': 'overlay random or custom text onto video frames with configurable fonts and colors', 'trim_video': 'trim a video to a specified start and end time in seconds'}
```

## File: facebookresearch_augly/augly/video/transforms.py

Prompts

```
['apply gaussian blur to a video file with configurable sigma strength', 'speed up or slow down a video by a given factor', 'concatenate multiple video files together with optional transitions between clips', 'overlay random or custom text onto video frames with configurable fonts and colors', 'trim a video to a specified start and end time in seconds', 'create a Blur transform class to apply Gaussian blur with configurable sigma to a video file', 'create a Brightness transform class to brighten or darken a video by a specified level factor', 'create a RandomBlur transform class to randomly blur a video with sigma chosen from a min-max range', 'create a composition of video transforms like Blur, Brightness, and HFlip to apply multiple augmentations in sequence', 'create an Overlay transform class to overlay an image or video onto another video at a specified position', 'apply an image augmentation function to each frame of a video and reassemble with audio', 'apply an image augmentation function combining frames from two separate videos into one output', 'apply a CV2-based video augmenter to a video file and save the augmented result', 'get a dictionary with an image directory path and its listed image files', 'review the video utility functions for frame extraction, augmentation, and reassembly patterns']
```

Usage

```
{'create_blur_transform': 'create a Blur transform class to apply Gaussian blur with configurable sigma to a video file', 'create_brightness_transform': 'create a Brightness transform class to brighten or darken a video by a specified level factor', 'create_randomblur_transform': 'create a RandomBlur transform class to randomly blur a video with sigma chosen from a min-max range', 'create_compose_transforms': 'create a composition of video transforms like Blur, Brightness, and HFlip to apply multiple augmentations in sequence', 'create_overlay_transform': 'create an Overlay transform class to overlay an image or video onto another video at a specified position'}
```

## File: facebookresearch_augly/augly/video/utils.py

Prompts

```
['apply gaussian blur to a video file with configurable sigma strength', 'speed up or slow down a video by a given factor', 'concatenate multiple video files together with optional transitions between clips', 'overlay random or custom text onto video frames with configurable fonts and colors', 'trim a video to a specified start and end time in seconds', 'create a Blur transform class to apply Gaussian blur with configurable sigma to a video file', 'create a Brightness transform class to brighten or darken a video by a specified level factor', 'create a RandomBlur transform class to randomly blur a video with sigma chosen from a min-max range', 'create a composition of video transforms like Blur, Brightness, and HFlip to apply multiple augmentations in sequence', 'create an Overlay transform class to overlay an image or video onto another video at a specified position', 'apply an image augmentation function to each frame of a video and reassemble with audio', 'apply an image augmentation function combining frames from two separate videos into one output', 'apply a CV2-based video augmenter to a video file and save the augmented result', 'get a dictionary with an image directory path and its listed image files', 'review the video utility functions for frame extraction, augmentation, and reassembly patterns']
```

Usage

```
{'apply_to_each_frame': 'apply an image augmentation function to each frame of a video and reassemble with audio', 'apply_to_frames': 'apply an image augmentation function combining frames from two separate videos into one output', 'apply_cv2_augmenter': 'apply a CV2-based video augmenter to a video file and save the augmented result', 'get_image_kwargs': 'get a dictionary with an image directory path and its listed image files', 'review_utils': 'review the video utility functions for frame extraction, augmentation, and reassembly patterns'}
```

