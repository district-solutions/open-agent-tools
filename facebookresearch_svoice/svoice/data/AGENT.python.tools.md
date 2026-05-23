# Agent Python Tools

- repo: facebookresearch/svoice
- repo_uri: https://github.com/facebookresearch/svoice

## File: facebookresearch_svoice/svoice/data/audio.py

Prompts

```
['recursively find all audio files in a directory and return their paths with duration metadata', 'create an Audioset dataset from a list of audio files with configurable length stride and padding', 'load an audio file with a specific offset and frame count using torchaudio', 'apply an augmentation function to audio data when loading from the Audioset dataset', 'pad an audio tensor to a specified length using torch functional padding', 'create a Trainset from a JSON directory with configurable segment length and stride for training', 'create a Validset from a JSON directory to load entire wav files for validation', 'create an EvalDataset from a mix directory or JSON file with specified batch size', 'use EvalDataLoader with custom collate function to load padded mixture audio batches', 'pad a list of tensors to uniform length using pad_list with a specified pad value', 'run the preprocess_one_dir function to scan a directory of WAV files and generate a JSON manifest with file paths and sample counts', 'run the preprocess function to generate JSON manifests for noisy and clean audio across training, validation, and test splits', 'run the preprocess_alldirs function to generate JSON manifests for all subdirectories within a given input directory', 'run the CLI with --one_dir flag to generate a single JSON manifest from a specific directory of WAV files', 'run the CLI with --all_dirs flag to generate JSON manifests for all subdirectories in a given input directory']
```

Usage

```
{'find_audio_files': 'recursively find all audio files in a directory and return their paths with duration metadata', 'create_audioset_dataset': 'create an Audioset dataset from a list of audio files with configurable length stride and padding', 'load_audio_with_offset': 'load an audio file with a specific offset and frame count using torchaudio', 'apply_augmentation_to_audio': 'apply an augmentation function to audio data when loading from the Audioset dataset', 'pad_audio_tensor': 'pad an audio tensor to a specified length using torch functional padding'}
```

## File: facebookresearch_svoice/svoice/data/data.py

Prompts

```
['recursively find all audio files in a directory and return their paths with duration metadata', 'create an Audioset dataset from a list of audio files with configurable length stride and padding', 'load an audio file with a specific offset and frame count using torchaudio', 'apply an augmentation function to audio data when loading from the Audioset dataset', 'pad an audio tensor to a specified length using torch functional padding', 'create a Trainset from a JSON directory with configurable segment length and stride for training', 'create a Validset from a JSON directory to load entire wav files for validation', 'create an EvalDataset from a mix directory or JSON file with specified batch size', 'use EvalDataLoader with custom collate function to load padded mixture audio batches', 'pad a list of tensors to uniform length using pad_list with a specified pad value', 'run the preprocess_one_dir function to scan a directory of WAV files and generate a JSON manifest with file paths and sample counts', 'run the preprocess function to generate JSON manifests for noisy and clean audio across training, validation, and test splits', 'run the preprocess_alldirs function to generate JSON manifests for all subdirectories within a given input directory', 'run the CLI with --one_dir flag to generate a single JSON manifest from a specific directory of WAV files', 'run the CLI with --all_dirs flag to generate JSON manifests for all subdirectories in a given input directory']
```

Usage

```
{'create_trainset': 'create a Trainset from a JSON directory with configurable segment length and stride for training', 'create_validset': 'create a Validset from a JSON directory to load entire wav files for validation', 'create_eval_dataset': 'create an EvalDataset from a mix directory or JSON file with specified batch size', 'use_eval_dataloader': 'use EvalDataLoader with custom collate function to load padded mixture audio batches', 'pad_tensor_list': 'pad a list of tensors to uniform length using pad_list with a specified pad value'}
```

## File: facebookresearch_svoice/svoice/data/preprocess.py

Prompts

```
['recursively find all audio files in a directory and return their paths with duration metadata', 'create an Audioset dataset from a list of audio files with configurable length stride and padding', 'load an audio file with a specific offset and frame count using torchaudio', 'apply an augmentation function to audio data when loading from the Audioset dataset', 'pad an audio tensor to a specified length using torch functional padding', 'create a Trainset from a JSON directory with configurable segment length and stride for training', 'create a Validset from a JSON directory to load entire wav files for validation', 'create an EvalDataset from a mix directory or JSON file with specified batch size', 'use EvalDataLoader with custom collate function to load padded mixture audio batches', 'pad a list of tensors to uniform length using pad_list with a specified pad value', 'run the preprocess_one_dir function to scan a directory of WAV files and generate a JSON manifest with file paths and sample counts', 'run the preprocess function to generate JSON manifests for noisy and clean audio across training, validation, and test splits', 'run the preprocess_alldirs function to generate JSON manifests for all subdirectories within a given input directory', 'run the CLI with --one_dir flag to generate a single JSON manifest from a specific directory of WAV files', 'run the CLI with --all_dirs flag to generate JSON manifests for all subdirectories in a given input directory']
```

Usage

```
{'preprocess_one_dir': 'run the preprocess_one_dir function to scan a directory of WAV files and generate a JSON manifest with file paths and sample counts', 'preprocess_wsj0': 'run the preprocess function to generate JSON manifests for noisy and clean audio across training, validation, and test splits', 'preprocess_alldirs': 'run the preprocess_alldirs function to generate JSON manifests for all subdirectories within a given input directory', 'cli_one_dir': 'run the CLI with --one_dir flag to generate a single JSON manifest from a specific directory of WAV files', 'cli_all_dirs': 'run the CLI with --all_dirs flag to generate JSON manifests for all subdirectories in a given input directory'}
```

