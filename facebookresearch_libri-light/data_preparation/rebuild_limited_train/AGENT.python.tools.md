# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/data_preparation/rebuild_limited_train/sample_10h.py

Prompts

```
['run the sample_10h script to select a limited subset of LibriLight speakers within time budget constraints', 'run do_split_10h to greedily select speakers whose audio duration falls within min and max seconds bounds', 'run get_args to parse command-line arguments for speaker time limits, target directory, seed, and data root paths', 'refactor do_split_10h to support a different speaker selection strategy beyond the current greedy approach', 'review the main block that iterates over genders and data roots to filter and materialize speaker subsets', 'run the select_1h script to filter LibriLight audio records by speaker and gender subsets', 'run do_split to filter audio records keeping a max number of seconds per speaker', 'review the do_split function that filters records by limiting audio duration per speaker using sample rate 16000', 'review the main block that filters LibriLight records by gender and subset then materializes to target directory', 'run the script to split 1-hour LibriLight audio into 10-minute segments by speaker', 'review the get_args function that defines argparse arguments for target_dir, seed, root_1h, and meta_path', 'parse a LibriSpeech speaker list file into Speaker namedtuples with id, gender, and subset', 'recursively find all FLAC audio files in a directory and return them with their sample lengths', 'build FileRecord objects from speaker data and audio file lengths for a LibriSpeech subset', 'copy or move audio files and transcripts into a speaker-book directory structure', 'print statistics about unique speakers, utterance counts, and audio duration from FileRecord list']
```

Usage

```
{'run_sample_10h_cli': 'run the sample_10h script to select a limited subset of LibriLight speakers within time budget constraints', 'run_do_split_10h': 'run do_split_10h to greedily select speakers whose audio duration falls within min and max seconds bounds', 'run_get_args': 'run get_args to parse command-line arguments for speaker time limits, target directory, seed, and data root paths', 'refactor_do_split_10h': 'refactor do_split_10h to support a different speaker selection strategy beyond the current greedy approach', 'review_sample_10h_main': 'review the main block that iterates over genders and data roots to filter and materialize speaker subsets'}
```

## File: facebookresearch_libri-light/data_preparation/rebuild_limited_train/select_1h.py

Prompts

```
['run the sample_10h script to select a limited subset of LibriLight speakers within time budget constraints', 'run do_split_10h to greedily select speakers whose audio duration falls within min and max seconds bounds', 'run get_args to parse command-line arguments for speaker time limits, target directory, seed, and data root paths', 'refactor do_split_10h to support a different speaker selection strategy beyond the current greedy approach', 'review the main block that iterates over genders and data roots to filter and materialize speaker subsets', 'run the select_1h script to filter LibriLight audio records by speaker and gender subsets', 'run do_split to filter audio records keeping a max number of seconds per speaker', 'review the do_split function that filters records by limiting audio duration per speaker using sample rate 16000', 'review the main block that filters LibriLight records by gender and subset then materializes to target directory', 'run the script to split 1-hour LibriLight audio into 10-minute segments by speaker', 'review the get_args function that defines argparse arguments for target_dir, seed, root_1h, and meta_path', 'parse a LibriSpeech speaker list file into Speaker namedtuples with id, gender, and subset', 'recursively find all FLAC audio files in a directory and return them with their sample lengths', 'build FileRecord objects from speaker data and audio file lengths for a LibriSpeech subset', 'copy or move audio files and transcripts into a speaker-book directory structure', 'print statistics about unique speakers, utterance counts, and audio duration from FileRecord list']
```

Usage

```
{'run_select_1h': 'run the select_1h script to filter LibriLight audio records by speaker and gender subsets', 'run_do_split': 'run do_split to filter audio records keeping a max number of seconds per speaker', 'run_get_args': 'run get_args to parse command line arguments for max seconds per speaker, target dir, seed, root, and meta path', 'review_do_split': 'review the do_split function that filters records by limiting audio duration per speaker using sample rate 16000', 'review_main': 'review the main block that filters LibriLight records by gender and subset then materializes to target directory'}
```

## File: facebookresearch_libri-light/data_preparation/rebuild_limited_train/split_1h_in10min.py

Prompts

```
['run the sample_10h script to select a limited subset of LibriLight speakers within time budget constraints', 'run do_split_10h to greedily select speakers whose audio duration falls within min and max seconds bounds', 'run get_args to parse command-line arguments for speaker time limits, target directory, seed, and data root paths', 'refactor do_split_10h to support a different speaker selection strategy beyond the current greedy approach', 'review the main block that iterates over genders and data roots to filter and materialize speaker subsets', 'run the select_1h script to filter LibriLight audio records by speaker and gender subsets', 'run do_split to filter audio records keeping a max number of seconds per speaker', 'review the do_split function that filters records by limiting audio duration per speaker using sample rate 16000', 'review the main block that filters LibriLight records by gender and subset then materializes to target directory', 'run the script to split 1-hour LibriLight audio into 10-minute segments by speaker', 'review the get_args function that defines argparse arguments for target_dir, seed, root_1h, and meta_path', 'parse a LibriSpeech speaker list file into Speaker namedtuples with id, gender, and subset', 'recursively find all FLAC audio files in a directory and return them with their sample lengths', 'build FileRecord objects from speaker data and audio file lengths for a LibriSpeech subset', 'copy or move audio files and transcripts into a speaker-book directory structure', 'print statistics about unique speakers, utterance counts, and audio duration from FileRecord list']
```

Usage

```
{'run_split_1h_in10min': 'run the script to split 1-hour LibriLight audio into 10-minute segments by speaker', 'run_do_split': 'run the do_split function to group audio records by speaker ID', 'run_get_args': 'run the get_args function to parse CLI arguments for target directory, seed, root, and meta path', 'review_do_split': 'review the do_split function that yields speaker-grouped record lists from a record collection', 'review_get_args': 'review the get_args function that defines argparse arguments for target_dir, seed, root_1h, and meta_path'}
```

## File: facebookresearch_libri-light/data_preparation/rebuild_limited_train/utils.py

Prompts

```
['run the sample_10h script to select a limited subset of LibriLight speakers within time budget constraints', 'run do_split_10h to greedily select speakers whose audio duration falls within min and max seconds bounds', 'run get_args to parse command-line arguments for speaker time limits, target directory, seed, and data root paths', 'refactor do_split_10h to support a different speaker selection strategy beyond the current greedy approach', 'review the main block that iterates over genders and data roots to filter and materialize speaker subsets', 'run the select_1h script to filter LibriLight audio records by speaker and gender subsets', 'run do_split to filter audio records keeping a max number of seconds per speaker', 'review the do_split function that filters records by limiting audio duration per speaker using sample rate 16000', 'review the main block that filters LibriLight records by gender and subset then materializes to target directory', 'run the script to split 1-hour LibriLight audio into 10-minute segments by speaker', 'review the get_args function that defines argparse arguments for target_dir, seed, root_1h, and meta_path', 'parse a LibriSpeech speaker list file into Speaker namedtuples with id, gender, and subset', 'recursively find all FLAC audio files in a directory and return them with their sample lengths', 'build FileRecord objects from speaker data and audio file lengths for a LibriSpeech subset', 'copy or move audio files and transcripts into a speaker-book directory structure', 'print statistics about unique speakers, utterance counts, and audio duration from FileRecord list']
```

Usage

```
{'parse_speakers_from_file': 'parse a LibriSpeech speaker list file into Speaker namedtuples with id, gender, and subset', 'traverse_audio_tree': 'recursively find all FLAC audio files in a directory and return them with their sample lengths', 'build_file_records': 'build FileRecord objects from speaker data and audio file lengths for a LibriSpeech subset', 'materialize_dataset': 'copy or move audio files and transcripts into a speaker-book directory structure', 'print_dataset_stats': 'print statistics about unique speakers, utterance counts, and audio duration from FileRecord list'}
```

