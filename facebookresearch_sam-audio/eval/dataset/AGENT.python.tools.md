# Agent Python Tools

- repo: facebookresearch/sam-audio
- repo_uri: https://github.com/facebookresearch/sam-audio

## File: facebookresearch_sam-audio/eval/dataset/musdb.py

Prompts

```
['create a MUSDB dataset instance with a custom collate function and sample rate', 'run MUSDB getitem to decode and resample a WAV audio clip by index', 'test the MUSDB collate method to batch audio waveforms and descriptions together', 'review the cache_file function that downloads and caches a URL to a local file', 'summarize the MUSDB get_dataset method that downloads, extracts, and loads the musdb18hq test dataset', 'create a SAMAudioBench dataset instance with a cache path and collate function for audio-visual evaluation', 'get an Item with audio samples, masked video frames, and anchors from the dataset by index', 'collate a list of Item objects into batched descriptions, audios, anchors, and masked videos', 'resolve a video file path from video ID, source dataset, and time offsets using fallback naming patterns', 'extract masked video frames by applying a mask to decoded video frames and interpolating to match dimensions']
```

Usage

```
{'create_MUSDB_dataset': 'create a MUSDB dataset instance with a custom collate function and sample rate', 'run_MUSDB_getitem': 'run MUSDB getitem to decode and resample a WAV audio clip by index', 'test_MUSDB_collate': 'test the MUSDB collate method to batch audio waveforms and descriptions together', 'review_cache_file': 'review the cache_file function that downloads and caches a URL to a local file', 'summarize_MUSDB_get_dataset': 'summarize the MUSDB get_dataset method that downloads, extracts, and loads the musdb18hq test dataset'}
```

## File: facebookresearch_sam-audio/eval/dataset/sam_audio_bench.py

Prompts

```
['create a MUSDB dataset instance with a custom collate function and sample rate', 'run MUSDB getitem to decode and resample a WAV audio clip by index', 'test the MUSDB collate method to batch audio waveforms and descriptions together', 'review the cache_file function that downloads and caches a URL to a local file', 'summarize the MUSDB get_dataset method that downloads, extracts, and loads the musdb18hq test dataset', 'create a SAMAudioBench dataset instance with a cache path and collate function for audio-visual evaluation', 'get an Item with audio samples, masked video frames, and anchors from the dataset by index', 'collate a list of Item objects into batched descriptions, audios, anchors, and masked videos', 'resolve a video file path from video ID, source dataset, and time offsets using fallback naming patterns', 'extract masked video frames by applying a mask to decoded video frames and interpolating to match dimensions']
```

Usage

```
{'create_dataset_instance': 'create a SAMAudioBench dataset instance with a cache path and collate function for audio-visual evaluation', 'get_dataset_item': 'get an Item with audio samples, masked video frames, and anchors from the dataset by index', 'collate_batch_items': 'collate a list of Item objects into batched descriptions, audios, anchors, and masked videos', 'resolve_video_path': 'resolve a video file path from video ID, source dataset, and time offsets using fallback naming patterns', 'extract_masked_video': 'extract masked video frames by applying a mask to decoded video frames and interpolating to match dimensions'}
```

