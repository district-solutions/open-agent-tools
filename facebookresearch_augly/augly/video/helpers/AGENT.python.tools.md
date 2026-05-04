# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/video/helpers/ffmpeg.py

Prompts

```
['combine a directory of raw image frames with an optional audio track into an MP4 video file at a given framerate', 'extract the audio track from a video file and save it as an AAC or WAV audio file', 'extract all frames from a video file into a directory as JPEG images with optional scaling and quality settings', 'probe a video file and return metadata including frame rate, frame count, dimensions, and duration', 'merge a video file with an optional audio track into a single output MP4 using libx264 encoding', 'compute the blur intensity score from a sigma value normalized to a 0 to 100 scale', 'compute the brightness intensity score from a level value between negative 1 and 1', 'compute the color jitter intensity from brightness, contrast, and saturation factor parameters', 'compute the video speed change intensity from a speed factor normalized to a 0 to 100 scale', 'compute the time crop or pad intensity from metadata with source and destination video durations', 'compute new source and destination segment pairs after applying a temporal crop to a video', 'compute updated matching segments for video transforms like speed change, loop, concat, or time crop', 'compute matching source to destination segment pairs given transform kwargs and previously applied metadata', 'extract and merge function kwargs with source video info and fps for a video transform', 'append a metadata entry with segment mappings and intensity for a video transform applied to a clip', 'create a solid color video with a specified RGB color, duration, height, and width', 'create a video from a single image file with a specified duration using ffmpeg', 'copy a video file to an output path and optionally record metadata', 'validate video input and output paths and return their local resolved paths', 'get the local filesystem path for a video file that may be remote']
```

Usage

```
{'combine_frames_and_audio_to_file': 'combine a directory of raw image frames with an optional audio track into an MP4 video file at a given framerate', 'extract_audio_to_file': 'extract the audio track from a video file and save it as an AAC or WAV audio file', 'extract_frames_to_dir': 'extract all frames from a video file into a directory as JPEG images with optional scaling and quality settings', 'get_video_info': 'probe a video file and return metadata including frame rate, frame count, dimensions, and duration', 'merge_video_and_audio': 'merge a video file with an optional audio track into a single output MP4 using libx264 encoding'}
```

## File: facebookresearch_augly/augly/video/helpers/intensity.py

Prompts

```
['combine a directory of raw image frames with an optional audio track into an MP4 video file at a given framerate', 'extract the audio track from a video file and save it as an AAC or WAV audio file', 'extract all frames from a video file into a directory as JPEG images with optional scaling and quality settings', 'probe a video file and return metadata including frame rate, frame count, dimensions, and duration', 'merge a video file with an optional audio track into a single output MP4 using libx264 encoding', 'compute the blur intensity score from a sigma value normalized to a 0 to 100 scale', 'compute the brightness intensity score from a level value between negative 1 and 1', 'compute the color jitter intensity from brightness, contrast, and saturation factor parameters', 'compute the video speed change intensity from a speed factor normalized to a 0 to 100 scale', 'compute the time crop or pad intensity from metadata with source and destination video durations', 'compute new source and destination segment pairs after applying a temporal crop to a video', 'compute updated matching segments for video transforms like speed change, loop, concat, or time crop', 'compute matching source to destination segment pairs given transform kwargs and previously applied metadata', 'extract and merge function kwargs with source video info and fps for a video transform', 'append a metadata entry with segment mappings and intensity for a video transform applied to a clip', 'create a solid color video with a specified RGB color, duration, height, and width', 'create a video from a single image file with a specified duration using ffmpeg', 'copy a video file to an output path and optionally record metadata', 'validate video input and output paths and return their local resolved paths', 'get the local filesystem path for a video file that may be remote']
```

Usage

```
{'compute_blur_intensity': 'compute the blur intensity score from a sigma value normalized to a 0 to 100 scale', 'compute_brightness_intensity': 'compute the brightness intensity score from a level value between negative 1 and 1', 'compute_color_jitter_intensity': 'compute the color jitter intensity from brightness, contrast, and saturation factor parameters', 'compute_change_video_speed_intensity': 'compute the video speed change intensity from a speed factor normalized to a 0 to 100 scale', 'compute_time_crop_intensity': 'compute the time crop or pad intensity from metadata with source and destination video durations'}
```

## File: facebookresearch_augly/augly/video/helpers/metadata.py

Prompts

```
['combine a directory of raw image frames with an optional audio track into an MP4 video file at a given framerate', 'extract the audio track from a video file and save it as an AAC or WAV audio file', 'extract all frames from a video file into a directory as JPEG images with optional scaling and quality settings', 'probe a video file and return metadata including frame rate, frame count, dimensions, and duration', 'merge a video file with an optional audio track into a single output MP4 using libx264 encoding', 'compute the blur intensity score from a sigma value normalized to a 0 to 100 scale', 'compute the brightness intensity score from a level value between negative 1 and 1', 'compute the color jitter intensity from brightness, contrast, and saturation factor parameters', 'compute the video speed change intensity from a speed factor normalized to a 0 to 100 scale', 'compute the time crop or pad intensity from metadata with source and destination video durations', 'compute new source and destination segment pairs after applying a temporal crop to a video', 'compute updated matching segments for video transforms like speed change, loop, concat, or time crop', 'compute matching source to destination segment pairs given transform kwargs and previously applied metadata', 'extract and merge function kwargs with source video info and fps for a video transform', 'append a metadata entry with segment mappings and intensity for a video transform applied to a clip', 'create a solid color video with a specified RGB color, duration, height, and width', 'create a video from a single image file with a specified duration using ffmpeg', 'copy a video file to an output path and optionally record metadata', 'validate video input and output paths and return their local resolved paths', 'get the local filesystem path for a video file that may be remote']
```

Usage

```
{'compute_time_crop_segments': 'compute new source and destination segment pairs after applying a temporal crop to a video', 'compute_changed_segments': 'compute updated matching segments for video transforms like speed change, loop, concat, or time crop', 'compute_segments': 'compute matching source to destination segment pairs given transform kwargs and previously applied metadata', 'get_func_kwargs': 'extract and merge function kwargs with source video info and fps for a video transform', 'get_metadata': 'append a metadata entry with segment mappings and intensity for a video transform applied to a clip'}
```

## File: facebookresearch_augly/augly/video/helpers/utils.py

Prompts

```
['combine a directory of raw image frames with an optional audio track into an MP4 video file at a given framerate', 'extract the audio track from a video file and save it as an AAC or WAV audio file', 'extract all frames from a video file into a directory as JPEG images with optional scaling and quality settings', 'probe a video file and return metadata including frame rate, frame count, dimensions, and duration', 'merge a video file with an optional audio track into a single output MP4 using libx264 encoding', 'compute the blur intensity score from a sigma value normalized to a 0 to 100 scale', 'compute the brightness intensity score from a level value between negative 1 and 1', 'compute the color jitter intensity from brightness, contrast, and saturation factor parameters', 'compute the video speed change intensity from a speed factor normalized to a 0 to 100 scale', 'compute the time crop or pad intensity from metadata with source and destination video durations', 'compute new source and destination segment pairs after applying a temporal crop to a video', 'compute updated matching segments for video transforms like speed change, loop, concat, or time crop', 'compute matching source to destination segment pairs given transform kwargs and previously applied metadata', 'extract and merge function kwargs with source video info and fps for a video transform', 'append a metadata entry with segment mappings and intensity for a video transform applied to a clip', 'create a solid color video with a specified RGB color, duration, height, and width', 'create a video from a single image file with a specified duration using ffmpeg', 'copy a video file to an output path and optionally record metadata', 'validate video input and output paths and return their local resolved paths', 'get the local filesystem path for a video file that may be remote']
```

Usage

```
{'create_color_video': 'create a solid color video with a specified RGB color, duration, height, and width', 'create_video_from_image': 'create a video from a single image file with a specified duration using ffmpeg', 'identity_function': 'copy a video file to an output path and optionally record metadata', 'validate_input_and_output_paths': 'validate video input and output paths and return their local resolved paths', 'get_local_path': 'get the local filesystem path for a video file that may be remote'}
```

