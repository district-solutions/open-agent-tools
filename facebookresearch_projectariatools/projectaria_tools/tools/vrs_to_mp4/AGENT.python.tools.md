# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projectaria_tools/tools/vrs_to_mp4/vrs_to_mp4.py

Prompts

```
['convert a VRS recording file to an MP4 video with optional audio channels and downsampling', 'run the vrs_to_mp4 CLI tool to convert a VRS file to MP4 with a specified stream ID', 'parse command line arguments for VRS to MP4 conversion including stream ID and audio channels', 'convert the default RGB stream 214-1 from a VRS file to an MP4 video', 'convert a VRS file to MP4 with specific audio channel indices from the glasses microphones', "extract VRS device timestamps from an MP4 file's description metadata tag using ffprobe", "embed a list of VRS device timestamps into an MP4 file's description tag using ffmpeg", 'generate an RGB frame array for a given MP4 timestamp from a VRS file', 'extract and normalize audio data for a given timestamp from a VRS file']
```

Usage

```
{'convert_vrs_to_mp4': 'convert a VRS recording file to an MP4 video with optional audio channels and downsampling', 'run_vrs_to_mp4_cli': 'run the vrs_to_mp4 CLI tool to convert a VRS file to MP4 with a specified stream ID', 'parse_vrs_to_mp4_args': 'parse command line arguments for VRS to MP4 conversion including stream ID and audio channels', 'convert_vrs_rgb_stream': 'convert the default RGB stream 214-1 from a VRS file to an MP4 video', 'convert_vrs_with_audio': 'convert a VRS file to MP4 with specific audio channel indices from the glasses microphones'}
```

## File: facebookresearch_projectariatools/projectaria_tools/tools/vrs_to_mp4/vrs_to_mp4_utils.py

Prompts

```
['convert a VRS recording file to an MP4 video with optional audio channels and downsampling', 'run the vrs_to_mp4 CLI tool to convert a VRS file to MP4 with a specified stream ID', 'parse command line arguments for VRS to MP4 conversion including stream ID and audio channels', 'convert the default RGB stream 214-1 from a VRS file to an MP4 video', 'convert a VRS file to MP4 with specific audio channel indices from the glasses microphones', "extract VRS device timestamps from an MP4 file's description metadata tag using ffprobe", "embed a list of VRS device timestamps into an MP4 file's description tag using ffmpeg", 'generate an RGB frame array for a given MP4 timestamp from a VRS file', 'extract and normalize audio data for a given timestamp from a VRS file']
```

Usage

```
{'convert_vrs_to_mp4': 'convert a VRS file to an MP4 video with optional audio channels and down-sampling', 'get_timestamp_from_mp4': "extract VRS device timestamps from an MP4 file's description metadata tag using ffprobe", 'save_timestamp_to_mp4': "embed a list of VRS device timestamps into an MP4 file's description tag using ffmpeg", 'Vrs2Mp4Converter_make_frame': 'generate an RGB frame array for a given MP4 timestamp from a VRS file', 'Vrs2Mp4Converter_make_audio_data': 'extract and normalize audio data for a given timestamp from a VRS file'}
```

