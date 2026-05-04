# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/vq-wav2vec_featurize.py

Prompts

```
['run the CLI script to pre-compute vector quantized wav2vec embeddings for a flashlight dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms in batches', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for inference', 'run the FilesDataset getitem method to load a single wav file and its corresponding label', 'run the wav2vec_featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'embed an entire audio dataset split using EmbeddingDatasetWriter to pre-compute and store wav2vec features', 'run wav2vec_manifest to index flac files in a directory and generate train and valid TSV manifests', 'run wav2vec_manifest with a custom file extension to index wav files instead of flac', 'run wav2vec_manifest with --path-must-contain to filter files by a substring in their path', 'run wav2vec_manifest with a custom --valid-percent to control the train validation split ratio', 'review the main function that scans audio files, reads frame counts, and writes train and valid TSV files']
```

Usage

```
{'run_vq_wav2vec_featurize': 'run the CLI script to pre-compute vector quantized wav2vec embeddings for a flashlight dataset', 'run_DatasetWriter_process_splits': 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run_DatasetWriter_iterate': 'run the iterate method to extract vector quantized indices from audio waveforms in batches', 'run_DatasetWriter_load_model': 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for inference', 'run_FilesDataset_getitem': 'run the FilesDataset getitem method to load a single wav file and its corresponding label'}
```

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/wav2vec_featurize.py

Prompts

```
['run the CLI script to pre-compute vector quantized wav2vec embeddings for a flashlight dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms in batches', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for inference', 'run the FilesDataset getitem method to load a single wav file and its corresponding label', 'run the wav2vec_featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'embed an entire audio dataset split using EmbeddingDatasetWriter to pre-compute and store wav2vec features', 'run wav2vec_manifest to index flac files in a directory and generate train and valid TSV manifests', 'run wav2vec_manifest with a custom file extension to index wav files instead of flac', 'run wav2vec_manifest with --path-must-contain to filter files by a substring in their path', 'run wav2vec_manifest with a custom --valid-percent to control the train validation split ratio', 'review the main function that scans audio files, reads frame counts, and writes train and valid TSV files']
```

Usage

```
{'run_wav2vec_featurize': 'run the wav2vec_featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create_pretrained_wav2vec_model': 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create_prediction_wrapper': 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on GPU', 'write_h5_features': 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'embed_audio_dataset': 'embed an entire audio dataset split using EmbeddingDatasetWriter to pre-compute and store wav2vec features'}
```

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/wav2vec_manifest.py

Prompts

```
['run the CLI script to pre-compute vector quantized wav2vec embeddings for a flashlight dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms in batches', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for inference', 'run the FilesDataset getitem method to load a single wav file and its corresponding label', 'run the wav2vec_featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'embed an entire audio dataset split using EmbeddingDatasetWriter to pre-compute and store wav2vec features', 'run wav2vec_manifest to index flac files in a directory and generate train and valid TSV manifests', 'run wav2vec_manifest with a custom file extension to index wav files instead of flac', 'run wav2vec_manifest with --path-must-contain to filter files by a substring in their path', 'run wav2vec_manifest with a custom --valid-percent to control the train validation split ratio', 'review the main function that scans audio files, reads frame counts, and writes train and valid TSV files']
```

Usage

```
{'run_wav2vec_manifest': 'run wav2vec_manifest to index flac files in a directory and generate train and valid TSV manifests', 'run_manifest_with_custom_ext': 'run wav2vec_manifest with a custom file extension to index wav files instead of flac', 'run_manifest_with_path_filter': 'run wav2vec_manifest with --path-must-contain to filter files by a substring in their path', 'run_manifest_with_valid_split': 'run wav2vec_manifest with a custom --valid-percent to control the train validation split ratio', 'review_main_function': 'review the main function that scans audio files, reads frame counts, and writes train and valid TSV files'}
```

