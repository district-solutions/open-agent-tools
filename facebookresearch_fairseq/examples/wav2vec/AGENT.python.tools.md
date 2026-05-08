# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/wav2vec/vq-wav2vec_featurize.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset getitem method to load a wav file and return its audio tensor and label', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a fairseq checkpoint file and extract feature and context vectors', 'create a Prediction wrapper to extract wav2vec embeddings from audio waveforms on a GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'run EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for all audio files in a dataset split', 'build a wav2vec train and valid TSV manifest from a directory of audio files', 'create a wav2vec manifest with a configurable percentage of data reserved for validation', 'build a wav2vec manifest that only includes audio files whose path contains a specific substring', 'run the wav2vec manifest tool on audio files with a custom file extension like wav or flac', 'review the wav2vec manifest generation logic that uses soundfile to count audio frames and split into train and valid sets']
```

Usage

```
{'run_vq_wav2vec_featurize': 'run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run_DatasetWriter_process_splits': 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run_DatasetWriter_iterate': 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run_FilesDataset_getitem': 'run the FilesDataset getitem method to load a wav file and return its audio tensor and label', 'run_DatasetWriter_load_model': 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction'}
```

## File: facebookresearch_fairseq/examples/wav2vec/wav2vec_featurize.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset getitem method to load a wav file and return its audio tensor and label', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a fairseq checkpoint file and extract feature and context vectors', 'create a Prediction wrapper to extract wav2vec embeddings from audio waveforms on a GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'run EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for all audio files in a dataset split', 'build a wav2vec train and valid TSV manifest from a directory of audio files', 'create a wav2vec manifest with a configurable percentage of data reserved for validation', 'build a wav2vec manifest that only includes audio files whose path contains a specific substring', 'run the wav2vec manifest tool on audio files with a custom file extension like wav or flac', 'review the wav2vec manifest generation logic that uses soundfile to count audio frames and split into train and valid sets']
```

Usage

```
{'run_wav2vec_featurize_cli': 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create_pretrained_wav2vec_model': 'create a PretrainedWav2VecModel from a fairseq checkpoint file and extract feature and context vectors', 'create_prediction_wrapper': 'create a Prediction wrapper to extract wav2vec embeddings from audio waveforms on a GPU', 'write_h5_features': 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'run_embedding_dataset_writer': 'run EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for all audio files in a dataset split'}
```

## File: facebookresearch_fairseq/examples/wav2vec/wav2vec_manifest.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset getitem method to load a wav file and return its audio tensor and label', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a fairseq checkpoint file and extract feature and context vectors', 'create a Prediction wrapper to extract wav2vec embeddings from audio waveforms on a GPU', 'write audio feature embeddings to an HDF5 file in flashlight compatible format using H5Writer', 'run EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for all audio files in a dataset split', 'build a wav2vec train and valid TSV manifest from a directory of audio files', 'create a wav2vec manifest with a configurable percentage of data reserved for validation', 'build a wav2vec manifest that only includes audio files whose path contains a specific substring', 'run the wav2vec manifest tool on audio files with a custom file extension like wav or flac', 'review the wav2vec manifest generation logic that uses soundfile to count audio frames and split into train and valid sets']
```

Usage

```
{'build_wav2vec_manifest': 'build a wav2vec train and valid TSV manifest from a directory of audio files', 'create_manifest_with_validation_split': 'create a wav2vec manifest with a configurable percentage of data reserved for validation', 'filter_manifest_by_path': 'build a wav2vec manifest that only includes audio files whose path contains a specific substring', 'run_manifest_for_custom_extension': 'run the wav2vec manifest tool on audio files with a custom file extension like wav or flac', 'review_manifest_generation': 'review the wav2vec manifest generation logic that uses soundfile to count audio frames and split into train and valid sets'}
```

