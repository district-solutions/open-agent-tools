# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/eval/CPC_loader.py

Prompts

```
['download a CPC checkpoint state dict from the Facebook AI Libri-Light public URL by model name', 'load a CPC feature extraction model from a downloaded state dict with encoder and AR network', 'extract CPC features from an audio file by loading it with torchaudio and chunking through the feature maker', 'use the FeatureModule wrapper to extract and normalize CPC features from batched audio tensor data', 'run the CLI to download a CPC model checkpoint (600h, 6kh, or 60kh) and save it to a file', 'run the ABX evaluation script to compute within and across speaker scores on audio features', 'run the ABX evaluation in within speaker mode using cosine distance on precomputed features', 'run the ABX evaluation in across speaker mode sampling multiple speakers per AB pair', 'run the ABX evaluation using a CPC checkpoint to extract features from raw audio files', 'run the ABX evaluation with CUDA enabled for faster distance computation on the GPU', 'run the train command to train a phone error rate model on audio data with CPC features', 'run the per command to compute phone error rate on a dataset using a trained checkpoint', 'use find_all_files to recursively find all audio files with a given extension in a directory', 'use parse_phone_labels to read a phone label file and return a dictionary mapping utterance IDs to phone sequences', 'use filter_seq to filter a list of sequence files based on a selection file containing utterance IDs', 'run the letter classifier training on Libri-Light audio data with CTC loss over multiple epochs', 'evaluate word error rate on a dataset using multiprocessing workers and a WlDecoder', 'run a single training step with a CTC criterion, optimizer, and downsampling factor on a data loader', 'run a single validation step with a CTC criterion and downsampling factor on a data loader', 'prepare batched sequence and label data for CUDA processing with optional device placement']
```

Usage

```
{'download_cpc_state_dict': 'download a CPC checkpoint state dict from the Facebook AI Libri-Light public URL by model name', 'load_cpc_features_from_state_dict': 'load a CPC feature extraction model from a downloaded state dict with encoder and AR network', 'build_features_from_audio_file': 'extract CPC features from an audio file by loading it with torchaudio and chunking through the feature maker', 'use_feature_module_for_extraction': 'use the FeatureModule wrapper to extract and normalize CPC features from batched audio tensor data', 'download_and_save_cpc_model_cli': 'run the CLI to download a CPC model checkpoint (600h, 6kh, or 60kh) and save it to a file'}
```

## File: facebookresearch_libri-light/eval/eval_ABX.py

Prompts

```
['download a CPC checkpoint state dict from the Facebook AI Libri-Light public URL by model name', 'load a CPC feature extraction model from a downloaded state dict with encoder and AR network', 'extract CPC features from an audio file by loading it with torchaudio and chunking through the feature maker', 'use the FeatureModule wrapper to extract and normalize CPC features from batched audio tensor data', 'run the CLI to download a CPC model checkpoint (600h, 6kh, or 60kh) and save it to a file', 'run the ABX evaluation script to compute within and across speaker scores on audio features', 'run the ABX evaluation in within speaker mode using cosine distance on precomputed features', 'run the ABX evaluation in across speaker mode sampling multiple speakers per AB pair', 'run the ABX evaluation using a CPC checkpoint to extract features from raw audio files', 'run the ABX evaluation with CUDA enabled for faster distance computation on the GPU', 'run the train command to train a phone error rate model on audio data with CPC features', 'run the per command to compute phone error rate on a dataset using a trained checkpoint', 'use find_all_files to recursively find all audio files with a given extension in a directory', 'use parse_phone_labels to read a phone label file and return a dictionary mapping utterance IDs to phone sequences', 'use filter_seq to filter a list of sequence files based on a selection file containing utterance IDs', 'run the letter classifier training on Libri-Light audio data with CTC loss over multiple epochs', 'evaluate word error rate on a dataset using multiprocessing workers and a WlDecoder', 'run a single training step with a CTC criterion, optimizer, and downsampling factor on a data loader', 'run a single validation step with a CTC criterion and downsampling factor on a data loader', 'prepare batched sequence and label data for CUDA processing with optional device placement']
```

Usage

```
{'run_ABX_evaluation': 'run the ABX evaluation script to compute within and across speaker scores on audio features', 'run_ABX_within_mode': 'run the ABX evaluation in within speaker mode using cosine distance on precomputed features', 'run_ABX_across_mode': 'run the ABX evaluation in across speaker mode sampling multiple speakers per AB pair', 'run_ABX_with_checkpoint': 'run the ABX evaluation using a CPC checkpoint to extract features from raw audio files', 'run_ABX_gpu': 'run the ABX evaluation with CUDA enabled for faster distance computation on the GPU'}
```

## File: facebookresearch_libri-light/eval/eval_PER.py

Prompts

```
['download a CPC checkpoint state dict from the Facebook AI Libri-Light public URL by model name', 'load a CPC feature extraction model from a downloaded state dict with encoder and AR network', 'extract CPC features from an audio file by loading it with torchaudio and chunking through the feature maker', 'use the FeatureModule wrapper to extract and normalize CPC features from batched audio tensor data', 'run the CLI to download a CPC model checkpoint (600h, 6kh, or 60kh) and save it to a file', 'run the ABX evaluation script to compute within and across speaker scores on audio features', 'run the ABX evaluation in within speaker mode using cosine distance on precomputed features', 'run the ABX evaluation in across speaker mode sampling multiple speakers per AB pair', 'run the ABX evaluation using a CPC checkpoint to extract features from raw audio files', 'run the ABX evaluation with CUDA enabled for faster distance computation on the GPU', 'run the train command to train a phone error rate model on audio data with CPC features', 'run the per command to compute phone error rate on a dataset using a trained checkpoint', 'use find_all_files to recursively find all audio files with a given extension in a directory', 'use parse_phone_labels to read a phone label file and return a dictionary mapping utterance IDs to phone sequences', 'use filter_seq to filter a list of sequence files based on a selection file containing utterance IDs', 'run the letter classifier training on Libri-Light audio data with CTC loss over multiple epochs', 'evaluate word error rate on a dataset using multiprocessing workers and a WlDecoder', 'run a single training step with a CTC criterion, optimizer, and downsampling factor on a data loader', 'run a single validation step with a CTC criterion and downsampling factor on a data loader', 'prepare batched sequence and label data for CUDA processing with optional device placement']
```

Usage

```
{'train_phone_error_rate_model': 'run the train command to train a phone error rate model on audio data with CPC features', 'compute_phone_error_rate': 'run the per command to compute phone error rate on a dataset using a trained checkpoint', 'find_audio_files_in_directory': 'use find_all_files to recursively find all audio files with a given extension in a directory', 'parse_phone_label_file': 'use parse_phone_labels to read a phone label file and return a dictionary mapping utterance IDs to phone sequences', 'filter_sequences_by_selection_file': 'use filter_seq to filter a list of sequence files based on a selection file containing utterance IDs'}
```

## File: facebookresearch_libri-light/eval/eval_WER.py

Prompts

```
['download a CPC checkpoint state dict from the Facebook AI Libri-Light public URL by model name', 'load a CPC feature extraction model from a downloaded state dict with encoder and AR network', 'extract CPC features from an audio file by loading it with torchaudio and chunking through the feature maker', 'use the FeatureModule wrapper to extract and normalize CPC features from batched audio tensor data', 'run the CLI to download a CPC model checkpoint (600h, 6kh, or 60kh) and save it to a file', 'run the ABX evaluation script to compute within and across speaker scores on audio features', 'run the ABX evaluation in within speaker mode using cosine distance on precomputed features', 'run the ABX evaluation in across speaker mode sampling multiple speakers per AB pair', 'run the ABX evaluation using a CPC checkpoint to extract features from raw audio files', 'run the ABX evaluation with CUDA enabled for faster distance computation on the GPU', 'run the train command to train a phone error rate model on audio data with CPC features', 'run the per command to compute phone error rate on a dataset using a trained checkpoint', 'use find_all_files to recursively find all audio files with a given extension in a directory', 'use parse_phone_labels to read a phone label file and return a dictionary mapping utterance IDs to phone sequences', 'use filter_seq to filter a list of sequence files based on a selection file containing utterance IDs', 'run the letter classifier training on Libri-Light audio data with CTC loss over multiple epochs', 'evaluate word error rate on a dataset using multiprocessing workers and a WlDecoder', 'run a single training step with a CTC criterion, optimizer, and downsampling factor on a data loader', 'run a single validation step with a CTC criterion and downsampling factor on a data loader', 'prepare batched sequence and label data for CUDA processing with optional device placement']
```

Usage

```
{'run_letter_classifier_training': 'run the letter classifier training on Libri-Light audio data with CTC loss over multiple epochs', 'eval_wer_on_dataset': 'evaluate word error rate on a dataset using multiprocessing workers and a WlDecoder', 'train_step_ctc_criterion': 'run a single training step with a CTC criterion, optimizer, and downsampling factor on a data loader', 'val_step_ctc_criterion': 'run a single validation step with a CTC criterion and downsampling factor on a data loader', 'prepare_data_for_cuda': 'prepare batched sequence and label data for CUDA processing with optional device placement'}
```

