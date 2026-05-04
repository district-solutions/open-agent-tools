# Agent Python Tools

- repo: facebookresearch/audiobox-aesthetics
- repo_uri: https://github.com/facebookresearch/audiobox-aesthetics

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/cli.py

Prompts

```
['run audiobox-aesthetics inference on an input JSONL file with a specified batch size', 'run audiobox-aesthetics inference via SLURM array jobs with chunked metadata and GPU constraints', 'parse command line arguments for the audiobox-aesthetics CLI including batch size and SLURM options', 'run the main app entry point that loads dataset metadata and executes prediction locally or remotely', 'chunk metadata into fixed-size batches for parallel SLURM array job execution', 'run main_predict to batch predict audio aesthetic scores from a JSONL metadata file using a checkpoint', 'initialize an AesPredictor from a local checkpoint or HuggingFace model to predict audio aesthetics', 'run AesPredictor forward on a batch of audio metadata to get CE, CU, PC, PQ aesthetic scores', 'create inference batches by chunking audio waveforms into fixed window segments with masks and weights', 'read a WAV file with optional start and end time clipping and auto mono conversion', 'download a file from a URL to a local destination with a progress bar', 'load the audiobox aesthetics model checkpoint from HuggingFace or a local path', 'create a function that streams a file download with a tqdm progress bar', 'load the audiobox aesthetics checkpoint from the facebook HuggingFace repo', 'review the download_file function that streams files with chunked writes and progress tracking']
```

Usage

```
{'run_audiobox_aesthetics_inference': 'run audiobox-aesthetics inference on an input JSONL file with a specified batch size', 'run_audiobox_aesthetics_slurm': 'run audiobox-aesthetics inference via SLURM array jobs with chunked metadata and GPU constraints', 'parse_args_cli': 'parse command line arguments for the audiobox-aesthetics CLI including batch size and SLURM options', 'app_main_entry': 'run the main app entry point that loads dataset metadata and executes prediction locally or remotely', 'chunk_metadata_for_slurm': 'chunk metadata into fixed-size batches for parallel SLURM array job execution'}
```

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/infer.py

Prompts

```
['run audiobox-aesthetics inference on an input JSONL file with a specified batch size', 'run audiobox-aesthetics inference via SLURM array jobs with chunked metadata and GPU constraints', 'parse command line arguments for the audiobox-aesthetics CLI including batch size and SLURM options', 'run the main app entry point that loads dataset metadata and executes prediction locally or remotely', 'chunk metadata into fixed-size batches for parallel SLURM array job execution', 'run main_predict to batch predict audio aesthetic scores from a JSONL metadata file using a checkpoint', 'initialize an AesPredictor from a local checkpoint or HuggingFace model to predict audio aesthetics', 'run AesPredictor forward on a batch of audio metadata to get CE, CU, PC, PQ aesthetic scores', 'create inference batches by chunking audio waveforms into fixed window segments with masks and weights', 'read a WAV file with optional start and end time clipping and auto mono conversion', 'download a file from a URL to a local destination with a progress bar', 'load the audiobox aesthetics model checkpoint from HuggingFace or a local path', 'create a function that streams a file download with a tqdm progress bar', 'load the audiobox aesthetics checkpoint from the facebook HuggingFace repo', 'review the download_file function that streams files with chunked writes and progress tracking']
```

Usage

```
{'run_main_predict': 'run main_predict to batch predict audio aesthetic scores from a JSONL metadata file using a checkpoint', 'initialize_AesPredictor': 'initialize an AesPredictor from a local checkpoint or HuggingFace model to predict audio aesthetics', 'run_AesPredictor_forward': 'run AesPredictor forward on a batch of audio metadata to get CE, CU, PC, PQ aesthetic scores', 'create_make_inference_batch': 'create inference batches by chunking audio waveforms into fixed window segments with masks and weights', 'read_wav_with_time_range': 'read a WAV file with optional start and end time clipping and auto mono conversion'}
```

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/utils.py

Prompts

```
['run audiobox-aesthetics inference on an input JSONL file with a specified batch size', 'run audiobox-aesthetics inference via SLURM array jobs with chunked metadata and GPU constraints', 'parse command line arguments for the audiobox-aesthetics CLI including batch size and SLURM options', 'run the main app entry point that loads dataset metadata and executes prediction locally or remotely', 'chunk metadata into fixed-size batches for parallel SLURM array job execution', 'run main_predict to batch predict audio aesthetic scores from a JSONL metadata file using a checkpoint', 'initialize an AesPredictor from a local checkpoint or HuggingFace model to predict audio aesthetics', 'run AesPredictor forward on a batch of audio metadata to get CE, CU, PC, PQ aesthetic scores', 'create inference batches by chunking audio waveforms into fixed window segments with masks and weights', 'read a WAV file with optional start and end time clipping and auto mono conversion', 'download a file from a URL to a local destination with a progress bar', 'load the audiobox aesthetics model checkpoint from HuggingFace or a local path', 'create a function that streams a file download with a tqdm progress bar', 'load the audiobox aesthetics checkpoint from the facebook HuggingFace repo', 'review the download_file function that streams files with chunked writes and progress tracking']
```

Usage

```
{'download_file_from_url': 'download a file from a URL to a local destination with a progress bar', 'load_model_checkpoint': 'load the audiobox aesthetics model checkpoint from HuggingFace or a local path', 'download_file_with_tqdm': 'create a function that streams a file download with a tqdm progress bar', 'load_model_from_hf': 'load the audiobox aesthetics checkpoint from the facebook HuggingFace repo', 'review_download_file': 'review the download_file function that streams files with chunked writes and progress tracking'}
```

