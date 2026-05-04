# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/utils/asserts.py

Prompts

```
['validate that a file path points to a valid audio or video file using magic MIME detection', 'validate that a file path points to a valid image file using magic MIME type detection', 'validate that a file path points to a valid video file using magic MIME and heuristic detection', 'check if a file is a video by detecting MIME type or scanning for ISO media, Matroska, WebM, AVI, QuickTime, or MPEG indicators', 'validate that an RGB color tuple has exactly 3 values each between 0 and 255', 'create a Segment NamedTuple with start, end, and optional src_id fields', 'create a Segment with a start time, end time, and source identifier string', 'apply start and end deltas to a Segment and return a new shifted Segment', 'validate that a delta operation does not produce an invalid segment where start exceeds end', 'review the Segment NamedTuple class and its delta method for time range manipulation', 'check that ffmpeg and ffprobe are installed and accessible on the system PATH', 'get the conditional tuple indicating whether video tests should be skipped', 'review the ffmpeg and ffprobe path configuration and environment variable setup', 'summarize the ffmpeg utility module that validates ffmpeg and ffprobe availability', 'test that the AUGLY_FFMPEG_PATH and AUGLY_FFPROBE_PATH environment variables resolve correctly', 'compute new source and destination time segments after applying a temporal crop with a speed factor', 'compute cropped segments when the crop start falls inside a matching segment pair', 'compute cropped segments when the crop end truncates the end of a matching segment pair', 'handle segment pairs that are entirely outside the crop range and produce no output', 'review the compute_time_crop_segments function for temporal crop segment calculation logic']
```

Usage

```
{'validate_audio_path': 'validate that a file path points to a valid audio or video file using magic MIME detection', 'validate_image_path': 'validate that a file path points to a valid image file using magic MIME type detection', 'validate_video_path': 'validate that a file path points to a valid video file using magic MIME and heuristic detection', 'is_video_file': 'check if a file is a video by detecting MIME type or scanning for ISO media, Matroska, WebM, AVI, QuickTime, or MPEG indicators', 'validate_rgb_color': 'validate that an RGB color tuple has exactly 3 values each between 0 and 255'}
```

## File: facebookresearch_augly/augly/utils/classes.py

Prompts

```
['validate that a file path points to a valid audio or video file using magic MIME detection', 'validate that a file path points to a valid image file using magic MIME type detection', 'validate that a file path points to a valid video file using magic MIME and heuristic detection', 'check if a file is a video by detecting MIME type or scanning for ISO media, Matroska, WebM, AVI, QuickTime, or MPEG indicators', 'validate that an RGB color tuple has exactly 3 values each between 0 and 255', 'create a Segment NamedTuple with start, end, and optional src_id fields', 'create a Segment with a start time, end time, and source identifier string', 'apply start and end deltas to a Segment and return a new shifted Segment', 'validate that a delta operation does not produce an invalid segment where start exceeds end', 'review the Segment NamedTuple class and its delta method for time range manipulation', 'check that ffmpeg and ffprobe are installed and accessible on the system PATH', 'get the conditional tuple indicating whether video tests should be skipped', 'review the ffmpeg and ffprobe path configuration and environment variable setup', 'summarize the ffmpeg utility module that validates ffmpeg and ffprobe availability', 'test that the AUGLY_FFMPEG_PATH and AUGLY_FFPROBE_PATH environment variables resolve correctly', 'compute new source and destination time segments after applying a temporal crop with a speed factor', 'compute cropped segments when the crop start falls inside a matching segment pair', 'compute cropped segments when the crop end truncates the end of a matching segment pair', 'handle segment pairs that are entirely outside the crop range and produce no output', 'review the compute_time_crop_segments function for temporal crop segment calculation logic']
```

Usage

```
{'create_segment': 'create a Segment NamedTuple with start, end, and optional src_id fields', 'create_segment_with_src_id': 'create a Segment with a start time, end time, and source identifier string', 'delta_segment': 'apply start and end deltas to a Segment and return a new shifted Segment', 'delta_segment_validation': 'validate that a delta operation does not produce an invalid segment where start exceeds end', 'review_segment_class': 'review the Segment NamedTuple class and its delta method for time range manipulation'}
```

## File: facebookresearch_augly/augly/utils/ffmpeg.py

Prompts

```
['validate that a file path points to a valid audio or video file using magic MIME detection', 'validate that a file path points to a valid image file using magic MIME type detection', 'validate that a file path points to a valid video file using magic MIME and heuristic detection', 'check if a file is a video by detecting MIME type or scanning for ISO media, Matroska, WebM, AVI, QuickTime, or MPEG indicators', 'validate that an RGB color tuple has exactly 3 values each between 0 and 255', 'create a Segment NamedTuple with start, end, and optional src_id fields', 'create a Segment with a start time, end time, and source identifier string', 'apply start and end deltas to a Segment and return a new shifted Segment', 'validate that a delta operation does not produce an invalid segment where start exceeds end', 'review the Segment NamedTuple class and its delta method for time range manipulation', 'check that ffmpeg and ffprobe are installed and accessible on the system PATH', 'get the conditional tuple indicating whether video tests should be skipped', 'review the ffmpeg and ffprobe path configuration and environment variable setup', 'summarize the ffmpeg utility module that validates ffmpeg and ffprobe availability', 'test that the AUGLY_FFMPEG_PATH and AUGLY_FFPROBE_PATH environment variables resolve correctly', 'compute new source and destination time segments after applying a temporal crop with a speed factor', 'compute cropped segments when the crop start falls inside a matching segment pair', 'compute cropped segments when the crop end truncates the end of a matching segment pair', 'handle segment pairs that are entirely outside the crop range and produce no output', 'review the compute_time_crop_segments function for temporal crop segment calculation logic']
```

Usage

```
{'check_ffmpeg_availability': 'check that ffmpeg and ffprobe are installed and accessible on the system PATH', 'get_conditional_for_skipping_video_tests': 'get the conditional tuple indicating whether video tests should be skipped', 'review_ffmpeg_config': 'review the ffmpeg and ffprobe path configuration and environment variable setup', 'summarize_ffmpeg_module': 'summarize the ffmpeg utility module that validates ffmpeg and ffprobe availability', 'test_ffmpeg_paths': 'test that the AUGLY_FFMPEG_PATH and AUGLY_FFPROBE_PATH environment variables resolve correctly'}
```

## File: facebookresearch_augly/augly/utils/functions.py

Prompts

```
['validate that a file path points to a valid audio or video file using magic MIME detection', 'validate that a file path points to a valid image file using magic MIME type detection', 'validate that a file path points to a valid video file using magic MIME and heuristic detection', 'check if a file is a video by detecting MIME type or scanning for ISO media, Matroska, WebM, AVI, QuickTime, or MPEG indicators', 'validate that an RGB color tuple has exactly 3 values each between 0 and 255', 'create a Segment NamedTuple with start, end, and optional src_id fields', 'create a Segment with a start time, end time, and source identifier string', 'apply start and end deltas to a Segment and return a new shifted Segment', 'validate that a delta operation does not produce an invalid segment where start exceeds end', 'review the Segment NamedTuple class and its delta method for time range manipulation', 'check that ffmpeg and ffprobe are installed and accessible on the system PATH', 'get the conditional tuple indicating whether video tests should be skipped', 'review the ffmpeg and ffprobe path configuration and environment variable setup', 'summarize the ffmpeg utility module that validates ffmpeg and ffprobe availability', 'test that the AUGLY_FFMPEG_PATH and AUGLY_FFPROBE_PATH environment variables resolve correctly', 'compute new source and destination time segments after applying a temporal crop with a speed factor', 'compute cropped segments when the crop start falls inside a matching segment pair', 'compute cropped segments when the crop end truncates the end of a matching segment pair', 'handle segment pairs that are entirely outside the crop range and produce no output', 'review the compute_time_crop_segments function for temporal crop segment calculation logic']
```

Usage

```
{'compute_time_crop_segments': 'compute new source and destination time segments after applying a temporal crop with a speed factor', 'compute_crop_segments_partial_overlap_start': 'compute cropped segments when the crop start falls inside a matching segment pair', 'compute_crop_segments_partial_overlap_end': 'compute cropped segments when the crop end truncates the end of a matching segment pair', 'compute_crop_segments_no_overlap': 'handle segment pairs that are entirely outside the crop range and produce no output', 'review_compute_time_crop_segments': 'review the compute_time_crop_segments function for temporal crop segment calculation logic'}
```

