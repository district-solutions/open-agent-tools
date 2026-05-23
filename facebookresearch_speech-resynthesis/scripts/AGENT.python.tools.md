# Agent Python Tools

- repo: facebookresearch/speech-resynthesis
- repo_uri: https://github.com/facebookresearch/speech-resynthesis

## File: facebookresearch_speech-resynthesis/scripts/parse_cpc_codes.py

Prompts

```
['run the script to parse CPC codes from a manifest and split audio samples into train, val, and test sets', 'run the split function to divide audio samples into train, validation, and test sets using reference manifests or random ratios', 'run the parse_manifest function to extract audio file paths from a manifest file supporting JSON and plain text formats', 'run the save function to write train, validation, and test sample lists to text files in an output directory', 'run the CLI tool with --manifest, --wav-root, and --outdir arguments to process audio samples with CPC codes and filter by duration', 'run the script to parse HuBERT codes from a manifest and split into train/val/test sets', 'run the script with a minimum duration filter to exclude short audio samples from the split', 'run the script using reference train/val/test manifest files to align dataset splits', 'review the parse_manifest function that reads audio file paths from a manifest supporting JSON or plain text lines', 'review the split function that divides samples into train/val/test sets using reference manifests or random proportions', 'run the script to parse a VQ-VAE codes manifest and split samples into train, val, and test sets', 'run the script with reference train, val, and test manifests to split VQ-VAE samples by provided splits', 'run the script to parse VQ-VAE codes manifest filtering samples by minimum audio duration', 'parse a manifest file containing audio file paths or JSON objects and return a list of Path objects', 'split audio samples into train, val, and test sets using reference split manifests or random proportions', 'run the python module to preprocess audio files in a directory with multiprocessing support', 'run the python module to resample all audio files in a source directory to 16kHz sample rate', 'run the python module to trim silence from audio files using librosa with a threshold of 20', 'run the python module to pad audio files to a multiple of 1280 samples for model compatibility', 'run the python module to batch convert wav files from a source to output directory with 40 workers']
```

Usage

```
{'run_parse_cpc_codes': 'run the script to parse CPC codes from a manifest and split audio samples into train, val, and test sets', 'run_split_samples': 'run the split function to divide audio samples into train, validation, and test sets using reference manifests or random ratios', 'run_parse_manifest': 'run the parse_manifest function to extract audio file paths from a manifest file supporting JSON and plain text formats', 'run_save_splits': 'run the save function to write train, validation, and test sample lists to text files in an output directory', 'run_main_cli': 'run the CLI tool with --manifest, --wav-root, and --outdir arguments to process audio samples with CPC codes and filter by duration'}
```

## File: facebookresearch_speech-resynthesis/scripts/parse_hubert_codes.py

Prompts

```
['run the script to parse CPC codes from a manifest and split audio samples into train, val, and test sets', 'run the split function to divide audio samples into train, validation, and test sets using reference manifests or random ratios', 'run the parse_manifest function to extract audio file paths from a manifest file supporting JSON and plain text formats', 'run the save function to write train, validation, and test sample lists to text files in an output directory', 'run the CLI tool with --manifest, --wav-root, and --outdir arguments to process audio samples with CPC codes and filter by duration', 'run the script to parse HuBERT codes from a manifest and split into train/val/test sets', 'run the script with a minimum duration filter to exclude short audio samples from the split', 'run the script using reference train/val/test manifest files to align dataset splits', 'review the parse_manifest function that reads audio file paths from a manifest supporting JSON or plain text lines', 'review the split function that divides samples into train/val/test sets using reference manifests or random proportions', 'run the script to parse a VQ-VAE codes manifest and split samples into train, val, and test sets', 'run the script with reference train, val, and test manifests to split VQ-VAE samples by provided splits', 'run the script to parse VQ-VAE codes manifest filtering samples by minimum audio duration', 'parse a manifest file containing audio file paths or JSON objects and return a list of Path objects', 'split audio samples into train, val, and test sets using reference split manifests or random proportions', 'run the python module to preprocess audio files in a directory with multiprocessing support', 'run the python module to resample all audio files in a source directory to 16kHz sample rate', 'run the python module to trim silence from audio files using librosa with a threshold of 20', 'run the python module to pad audio files to a multiple of 1280 samples for model compatibility', 'run the python module to batch convert wav files from a source to output directory with 40 workers']
```

Usage

```
{'run_parse_hubert_codes': 'run the script to parse HuBERT codes from a manifest and split into train/val/test sets', 'run_parse_hubert_codes_with_min_dur': 'run the script with a minimum duration filter to exclude short audio samples from the split', 'run_parse_hubert_codes_with_ref_splits': 'run the script using reference train/val/test manifest files to align dataset splits', 'review_parse_manifest': 'review the parse_manifest function that reads audio file paths from a manifest supporting JSON or plain text lines', 'review_split': 'review the split function that divides samples into train/val/test sets using reference manifests or random proportions'}
```

## File: facebookresearch_speech-resynthesis/scripts/parse_vqvae_codes.py

Prompts

```
['run the script to parse CPC codes from a manifest and split audio samples into train, val, and test sets', 'run the split function to divide audio samples into train, validation, and test sets using reference manifests or random ratios', 'run the parse_manifest function to extract audio file paths from a manifest file supporting JSON and plain text formats', 'run the save function to write train, validation, and test sample lists to text files in an output directory', 'run the CLI tool with --manifest, --wav-root, and --outdir arguments to process audio samples with CPC codes and filter by duration', 'run the script to parse HuBERT codes from a manifest and split into train/val/test sets', 'run the script with a minimum duration filter to exclude short audio samples from the split', 'run the script using reference train/val/test manifest files to align dataset splits', 'review the parse_manifest function that reads audio file paths from a manifest supporting JSON or plain text lines', 'review the split function that divides samples into train/val/test sets using reference manifests or random proportions', 'run the script to parse a VQ-VAE codes manifest and split samples into train, val, and test sets', 'run the script with reference train, val, and test manifests to split VQ-VAE samples by provided splits', 'run the script to parse VQ-VAE codes manifest filtering samples by minimum audio duration', 'parse a manifest file containing audio file paths or JSON objects and return a list of Path objects', 'split audio samples into train, val, and test sets using reference split manifests or random proportions', 'run the python module to preprocess audio files in a directory with multiprocessing support', 'run the python module to resample all audio files in a source directory to 16kHz sample rate', 'run the python module to trim silence from audio files using librosa with a threshold of 20', 'run the python module to pad audio files to a multiple of 1280 samples for model compatibility', 'run the python module to batch convert wav files from a source to output directory with 40 workers']
```

Usage

```
{'run_parse_vqvae_manifest': 'run the script to parse a VQ-VAE codes manifest and split samples into train, val, and test sets', 'run_parse_vqvae_with_ref_splits': 'run the script with reference train, val, and test manifests to split VQ-VAE samples by provided splits', 'run_parse_vqvae_with_min_duration': 'run the script to parse VQ-VAE codes manifest filtering samples by minimum audio duration', 'parse_manifest_parse_manifest': 'parse a manifest file containing audio file paths or JSON objects and return a list of Path objects', 'split_samples_by_reference': 'split audio samples into train, val, and test sets using reference split manifests or random proportions'}
```

## File: facebookresearch_speech-resynthesis/scripts/preprocess.py

Prompts

```
['run the script to parse CPC codes from a manifest and split audio samples into train, val, and test sets', 'run the split function to divide audio samples into train, validation, and test sets using reference manifests or random ratios', 'run the parse_manifest function to extract audio file paths from a manifest file supporting JSON and plain text formats', 'run the save function to write train, validation, and test sample lists to text files in an output directory', 'run the CLI tool with --manifest, --wav-root, and --outdir arguments to process audio samples with CPC codes and filter by duration', 'run the script to parse HuBERT codes from a manifest and split into train/val/test sets', 'run the script with a minimum duration filter to exclude short audio samples from the split', 'run the script using reference train/val/test manifest files to align dataset splits', 'review the parse_manifest function that reads audio file paths from a manifest supporting JSON or plain text lines', 'review the split function that divides samples into train/val/test sets using reference manifests or random proportions', 'run the script to parse a VQ-VAE codes manifest and split samples into train, val, and test sets', 'run the script with reference train, val, and test manifests to split VQ-VAE samples by provided splits', 'run the script to parse VQ-VAE codes manifest filtering samples by minimum audio duration', 'parse a manifest file containing audio file paths or JSON objects and return a list of Path objects', 'split audio samples into train, val, and test sets using reference split manifests or random proportions', 'run the python module to preprocess audio files in a directory with multiprocessing support', 'run the python module to resample all audio files in a source directory to 16kHz sample rate', 'run the python module to trim silence from audio files using librosa with a threshold of 20', 'run the python module to pad audio files to a multiple of 1280 samples for model compatibility', 'run the python module to batch convert wav files from a source to output directory with 40 workers']
```

Usage

```
{'run_preprocess_audio': 'run the python module to preprocess audio files in a directory with multiprocessing support', 'run_resample_to_16k': 'run the python module to resample all audio files in a source directory to 16kHz sample rate', 'run_trim_silence': 'run the python module to trim silence from audio files using librosa with a threshold of 20', 'run_pad_audio': 'run the python module to pad audio files to a multiple of 1280 samples for model compatibility', 'run_batch_convert_wav': 'run the python module to batch convert wav files from a source to output directory with 40 workers'}
```

