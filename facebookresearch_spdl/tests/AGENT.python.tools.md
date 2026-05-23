# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/tests/fixture.py

Prompts

```
['run an ffmpeg command and return a single generated sample file as SrcInfo', 'run an ffmpeg command and return all generated sample files as a list of SrcInfo', 'decode a video file via ffmpeg into a numpy array with a specified shape and pixel format', 'decode an image file via ffmpeg into a numpy array with a specified shape and pixel format', 'use the SrcInfo dataclass to hold a file path and its associated temporary directory']
```

Usage

```
{'get_sample': 'run an ffmpeg command and return a single generated sample file as SrcInfo', 'get_samples': 'run an ffmpeg command and return all generated sample files as a list of SrcInfo', 'load_ref_video': 'decode a video file via ffmpeg into a numpy array with a specified shape and pixel format', 'load_ref_image': 'decode an image file via ffmpeg into a numpy array with a specified shape and pixel format', 'SrcInfo': 'use the SrcInfo dataclass to hold a file path and its associated temporary directory'}
```

