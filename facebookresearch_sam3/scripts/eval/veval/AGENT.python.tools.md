# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/scripts/eval/veval/saco_yt1b_annot_update.py

Prompts

```
['run the CLI to update YouTube1B annotations by filtering out entries for unavailable videos using media directory', 'run get_available_saco_yt1b_ids to find which video IDs have JPEG images in the media directory', 'run update_yt1b_annot_per_field to filter a specific annotation field by a list of available IDs', 'run update_yt1b_annot to load annotations, filter videos and related fields, and write updated JSON', 'review the update_yt1b_annot function to understand how it cascades video filtering to annotations and video_np_pairs', 'run the script to download YouTube videos from YT1B dataset using multiprocessing workers', 'run the script to extract frames at 6fps and 1080 width from downloaded YouTube videos', 'run the end-to-end pipeline to download videos and extract frames in parallel', 'review the download_and_extract_frames function that downloads a video and extracts frames using YtVideoPrep', 'review the main function that parses CLI args and launches a multiprocessing pool for video downloads', 'download a YouTube video to a local directory using yt_dlp with cookies for authentication', 'extract frames at 6fps with 1080px width from a downloaded video using ffmpeg', 'retrieve YouTube video ID, timestamps, start/end times, and expected frame count from a JSON mapping file', 'run the CLI tool to download a YouTube video and extract frames for a given saco_yt1b_id', 'check if the expected number of frames already exists in the output directory before re-extracting']
```

Usage

```
{'run_update_yt1b_annot_cli': 'run the CLI to update YouTube1B annotations by filtering out entries for unavailable videos using media directory', 'run_get_available_saco_yt1b_ids': 'run get_available_saco_yt1b_ids to find which video IDs have JPEG images in the media directory', 'run_update_yt1b_annot_per_field': 'run update_yt1b_annot_per_field to filter a specific annotation field by a list of available IDs', 'run_update_yt1b_annot': 'run update_yt1b_annot to load annotations, filter videos and related fields, and write updated JSON', 'review_update_yt1b_annot': 'review the update_yt1b_annot function to understand how it cascades video filtering to annotations and video_np_pairs'}
```

## File: facebookresearch_sam3/scripts/eval/veval/saco_yt1b_downloader.py

Prompts

```
['run the CLI to update YouTube1B annotations by filtering out entries for unavailable videos using media directory', 'run get_available_saco_yt1b_ids to find which video IDs have JPEG images in the media directory', 'run update_yt1b_annot_per_field to filter a specific annotation field by a list of available IDs', 'run update_yt1b_annot to load annotations, filter videos and related fields, and write updated JSON', 'review the update_yt1b_annot function to understand how it cascades video filtering to annotations and video_np_pairs', 'run the script to download YouTube videos from YT1B dataset using multiprocessing workers', 'run the script to extract frames at 6fps and 1080 width from downloaded YouTube videos', 'run the end-to-end pipeline to download videos and extract frames in parallel', 'review the download_and_extract_frames function that downloads a video and extracts frames using YtVideoPrep', 'review the main function that parses CLI args and launches a multiprocessing pool for video downloads', 'download a YouTube video to a local directory using yt_dlp with cookies for authentication', 'extract frames at 6fps with 1080px width from a downloaded video using ffmpeg', 'retrieve YouTube video ID, timestamps, start/end times, and expected frame count from a JSON mapping file', 'run the CLI tool to download a YouTube video and extract frames for a given saco_yt1b_id', 'check if the expected number of frames already exists in the output directory before re-extracting']
```

Usage

```
{'run_download_yt1b_videos': 'run the script to download YouTube videos from YT1B dataset using multiprocessing workers', 'run_extract_frames_from_videos': 'run the script to extract frames at 6fps and 1080 width from downloaded YouTube videos', 'run_download_and_extract_pipeline': 'run the end-to-end pipeline to download videos and extract frames in parallel', 'review_download_and_extract_frames': 'review the download_and_extract_frames function that downloads a video and extracts frames using YtVideoPrep', 'review_main_cli': 'review the main function that parses CLI args and launches a multiprocessing pool for video downloads'}
```

## File: facebookresearch_sam3/scripts/eval/veval/saco_yt1b_frame_prep_util.py

Prompts

```
['run the CLI to update YouTube1B annotations by filtering out entries for unavailable videos using media directory', 'run get_available_saco_yt1b_ids to find which video IDs have JPEG images in the media directory', 'run update_yt1b_annot_per_field to filter a specific annotation field by a list of available IDs', 'run update_yt1b_annot to load annotations, filter videos and related fields, and write updated JSON', 'review the update_yt1b_annot function to understand how it cascades video filtering to annotations and video_np_pairs', 'run the script to download YouTube videos from YT1B dataset using multiprocessing workers', 'run the script to extract frames at 6fps and 1080 width from downloaded YouTube videos', 'run the end-to-end pipeline to download videos and extract frames in parallel', 'review the download_and_extract_frames function that downloads a video and extracts frames using YtVideoPrep', 'review the main function that parses CLI args and launches a multiprocessing pool for video downloads', 'download a YouTube video to a local directory using yt_dlp with cookies for authentication', 'extract frames at 6fps with 1080px width from a downloaded video using ffmpeg', 'retrieve YouTube video ID, timestamps, start/end times, and expected frame count from a JSON mapping file', 'run the CLI tool to download a YouTube video and extract frames for a given saco_yt1b_id', 'check if the expected number of frames already exists in the output directory before re-extracting']
```

Usage

```
{'download_youtube_video': 'download a YouTube video to a local directory using yt_dlp with cookies for authentication', 'extract_frames_from_video': 'extract frames at 6fps with 1080px width from a downloaded video using ffmpeg', 'get_video_metadata': 'retrieve YouTube video ID, timestamps, start/end times, and expected frame count from a JSON mapping file', 'run_frame_prep_cli': 'run the CLI tool to download a YouTube video and extract frames for a given saco_yt1b_id', 'check_frame_extraction_status': 'check if the expected number of frames already exists in the output directory before re-extracting'}
```

