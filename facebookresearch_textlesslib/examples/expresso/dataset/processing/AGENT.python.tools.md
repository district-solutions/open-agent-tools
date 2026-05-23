# Agent Python Tools

- repo: facebookresearch/textlesslib
- repo_uri: https://github.com/facebookresearch/textlesslib

## File: facebookresearch_textlesslib/examples/expresso/dataset/processing/convert_to_16k.py

Prompts

```
['convert all audio files in a directory to 16kHz mono wav format using sox', 'convert stereo audio files in a directory to 16kHz wav format preserving stereo channels', 'find all audio files with a specific extension recursively in a directory tree', 'convert a single audio file to 16kHz wav format using the sox command line tool', 'batch convert audio files to 16kHz wav with an option to overwrite existing output files', 'run the CLI to create short audio segments dataset from Expresso audio with VAD and split files', 'create a manifest of all audio files in a directory with duration and frame information', 'read a split file containing audio filenames and optional time segments for train dev test subsets', 'read VAD segments file and return a dictionary mapping filenames to voice activity detection intervals', 'compute short audio segments within min and max length bounds by trimming long VAD segments', 'run the perform_operations script to process copy, link, and segment operations from an operations file', 'read operations from a tab-separated operations file with src_root_dir and tgt_root_dir headers', 'group multiple segment operations from the same source file to process them efficiently at once', 'segment a WAV audio file by start and end time frames with optional channel selection', 'copy or create symbolic links for audio files from source to target directories']
```

Usage

```
{'convert_audio_to_16k': 'convert all audio files in a directory to 16kHz mono wav format using sox', 'convert_stereo_audio_to_16k': 'convert stereo audio files in a directory to 16kHz wav format preserving stereo channels', 'find_audio_files_by_extension': 'find all audio files with a specific extension recursively in a directory tree', 'convert_single_audio_file': 'convert a single audio file to 16kHz wav format using the sox command line tool', 'batch_convert_with_overwrite': 'batch convert audio files to 16kHz wav with an option to overwrite existing output files'}
```

## File: facebookresearch_textlesslib/examples/expresso/dataset/processing/create_short_segments_dataset.py

Prompts

```
['convert all audio files in a directory to 16kHz mono wav format using sox', 'convert stereo audio files in a directory to 16kHz wav format preserving stereo channels', 'find all audio files with a specific extension recursively in a directory tree', 'convert a single audio file to 16kHz wav format using the sox command line tool', 'batch convert audio files to 16kHz wav with an option to overwrite existing output files', 'run the CLI to create short audio segments dataset from Expresso audio with VAD and split files', 'create a manifest of all audio files in a directory with duration and frame information', 'read a split file containing audio filenames and optional time segments for train dev test subsets', 'read VAD segments file and return a dictionary mapping filenames to voice activity detection intervals', 'compute short audio segments within min and max length bounds by trimming long VAD segments', 'run the perform_operations script to process copy, link, and segment operations from an operations file', 'read operations from a tab-separated operations file with src_root_dir and tgt_root_dir headers', 'group multiple segment operations from the same source file to process them efficiently at once', 'segment a WAV audio file by start and end time frames with optional channel selection', 'copy or create symbolic links for audio files from source to target directories']
```

Usage

```
{'create_short_segments_dataset': 'run the CLI to create short audio segments dataset from Expresso audio with VAD and split files', 'get_manifest_audio_files': 'create a manifest of all audio files in a directory with duration and frame information', 'read_split_file': 'read a split file containing audio filenames and optional time segments for train dev test subsets', 'read_vad_segments': 'read VAD segments file and return a dictionary mapping filenames to voice activity detection intervals', 'get_short_segments': 'compute short audio segments within min and max length bounds by trimming long VAD segments'}
```

## File: facebookresearch_textlesslib/examples/expresso/dataset/processing/perform_operations.py

Prompts

```
['convert all audio files in a directory to 16kHz mono wav format using sox', 'convert stereo audio files in a directory to 16kHz wav format preserving stereo channels', 'find all audio files with a specific extension recursively in a directory tree', 'convert a single audio file to 16kHz wav format using the sox command line tool', 'batch convert audio files to 16kHz wav with an option to overwrite existing output files', 'run the CLI to create short audio segments dataset from Expresso audio with VAD and split files', 'create a manifest of all audio files in a directory with duration and frame information', 'read a split file containing audio filenames and optional time segments for train dev test subsets', 'read VAD segments file and return a dictionary mapping filenames to voice activity detection intervals', 'compute short audio segments within min and max length bounds by trimming long VAD segments', 'run the perform_operations script to process copy, link, and segment operations from an operations file', 'read operations from a tab-separated operations file with src_root_dir and tgt_root_dir headers', 'group multiple segment operations from the same source file to process them efficiently at once', 'segment a WAV audio file by start and end time frames with optional channel selection', 'copy or create symbolic links for audio files from source to target directories']
```

Usage

```
{'run_perform_operations': 'run the perform_operations script to process copy, link, and segment operations from an operations file', 'read_operations_file': 'read operations from a tab-separated operations file with src_root_dir and tgt_root_dir headers', 'group_segment_operations': 'group multiple segment operations from the same source file to process them efficiently at once', 'segment_audio_file': 'segment a WAV audio file by start and end time frames with optional channel selection', 'copy_or_link_files': 'copy or create symbolic links for audio files from source to target directories'}
```

