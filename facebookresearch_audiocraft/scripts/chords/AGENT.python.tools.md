# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/scripts/chords/build_chord_maps.py

Prompts

```
['run the script to process parsed chords files and generate combined chord dictionary and chord-to-index mapping pickle files', 'run the script with a pre-defined chord-to-index map for evaluation purposes using --path_to_pre_defined_map', 'run the script to output chord maps to a custom directory using --output_directory flag', 'call get_chord_dict to parse .chords files from a folder and return a chord dictionary, distinct chords set, and chord-to-index mapping', 'call get_predefined_chord_to_index_map to load a pre-defined chord-to-index map and return a function that processes chord files using it', 'run the script to extract musical chords from a list of WAV audio files using Chordino', 'run bulk chord extraction on multiple audio files with 80 parallel extractors and preprocessors', 'create a callback function that saves extracted chord sequences as pickled files to a target directory', 'review the argparse setup that accepts a JSONL file path, output directory, and an override flag', 'review the save_to_db_cb function that pickles chord sequences with timestamps to individual .chords files']
```

Usage

```
{'run_build_chord_maps': 'run the script to process parsed chords files and generate combined chord dictionary and chord-to-index mapping pickle files', 'run_build_chord_maps_with_predefined': 'run the script with a pre-defined chord-to-index map for evaluation purposes using --path_to_pre_defined_map', 'run_build_chord_maps_custom_output': 'run the script to output chord maps to a custom directory using --output_directory flag', 'get_chord_dict': 'call get_chord_dict to parse .chords files from a folder and return a chord dictionary, distinct chords set, and chord-to-index mapping', 'get_predefined_chord_to_index_map': 'call get_predefined_chord_to_index_map to load a pre-defined chord-to-index map and return a function that processes chord files using it'}
```

## File: facebookresearch_audiocraft/scripts/chords/extract_chords.py

Prompts

```
['run the script to process parsed chords files and generate combined chord dictionary and chord-to-index mapping pickle files', 'run the script with a pre-defined chord-to-index map for evaluation purposes using --path_to_pre_defined_map', 'run the script to output chord maps to a custom directory using --output_directory flag', 'call get_chord_dict to parse .chords files from a folder and return a chord dictionary, distinct chords set, and chord-to-index mapping', 'call get_predefined_chord_to_index_map to load a pre-defined chord-to-index map and return a function that processes chord files using it', 'run the script to extract musical chords from a list of WAV audio files using Chordino', 'run bulk chord extraction on multiple audio files with 80 parallel extractors and preprocessors', 'create a callback function that saves extracted chord sequences as pickled files to a target directory', 'review the argparse setup that accepts a JSONL file path, output directory, and an override flag', 'review the save_to_db_cb function that pickles chord sequences with timestamps to individual .chords files']
```

Usage

```
{'run_chord_extraction': 'run the script to extract musical chords from a list of WAV audio files using Chordino', 'run_bulk_chord_extraction': 'run bulk chord extraction on multiple audio files with 80 parallel extractors and preprocessors', 'create_chord_callback': 'create a callback function that saves extracted chord sequences as pickled files to a target directory', 'review_parse_args': 'review the argparse setup that accepts a JSONL file path, output directory, and an override flag', 'review_save_to_db_cb': 'review the save_to_db_cb function that pickles chord sequences with timestamps to individual .chords files'}
```

