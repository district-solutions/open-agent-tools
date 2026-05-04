# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/wav2vec/vq-wav2vec_featurize.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract vector quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset to load audio wav files and their corresponding labels from disk', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on a GPU', 'create an H5Writer to save feature arrays as HDF5 files in flashlight compatible format', 'create an EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for a dataset split', 'build a wav2vec manifest by indexing audio files in a directory into train and validation TSV files', 'run the wav2vec manifest tool on a directory of wav files using the --ext flag', 'create a wav2vec manifest that includes only files whose path contains a specific substring', 'run the wav2vec manifest tool with a custom validation percentage to split audio data', 'review the wav2vec manifest argument parser to understand supported options like root, dest, ext, and seed']
```

Usage

```
{'run_vq_wav2vec_featurize': 'run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run_DatasetWriter_process_splits': 'run the DatasetWriter to process audio data splits and extract vector quantized features from wav files', 'run_DatasetWriter_iterate': 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run_FilesDataset_getitem': 'run the FilesDataset to load audio wav files and their corresponding labels from disk', 'run_DatasetWriter_load_model': 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/wav2vec/wav2vec_featurize.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract vector quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset to load audio wav files and their corresponding labels from disk', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on a GPU', 'create an H5Writer to save feature arrays as HDF5 files in flashlight compatible format', 'create an EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for a dataset split', 'build a wav2vec manifest by indexing audio files in a directory into train and validation TSV files', 'run the wav2vec manifest tool on a directory of wav files using the --ext flag', 'create a wav2vec manifest that includes only files whose path contains a specific substring', 'run the wav2vec manifest tool with a custom validation percentage to split audio data', 'review the wav2vec manifest argument parser to understand supported options like root, dest, ext, and seed']
```

Usage

```
{'run_wav2vec_featurize': 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create_PretrainedWav2VecModel': 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create_Prediction': 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on a GPU', 'create_H5Writer': 'create an H5Writer to save feature arrays as HDF5 files in flashlight compatible format', 'create_EmbeddingDatasetWriter': 'create an EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for a dataset split'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/wav2vec/wav2vec_manifest.py

Prompts

```
['run the vq-wav2vec script to pre-compute vector quantized embeddings for a flashlight audio dataset', 'run the DatasetWriter to process audio data splits and extract vector quantized features from wav files', 'run the iterate method to extract vector quantized indices from audio waveforms using a fairseq model', 'run the FilesDataset to load audio wav files and their corresponding labels from disk', 'run the load_model method to load a fairseq vq-wav2vec checkpoint and prepare it for feature extraction', 'run the wav2vec featurize script to pre-compute embeddings for a flashlight dataset using a pretrained model', 'create a PretrainedWav2VecModel from a checkpoint file to extract feature and context vectors from audio', 'create a Prediction wrapper to extract wav2vec embeddings from raw audio waveforms on a GPU', 'create an H5Writer to save feature arrays as HDF5 files in flashlight compatible format', 'create an EmbeddingDatasetWriter to pre-compute and store wav2vec embeddings for a dataset split', 'build a wav2vec manifest by indexing audio files in a directory into train and validation TSV files', 'run the wav2vec manifest tool on a directory of wav files using the --ext flag', 'create a wav2vec manifest that includes only files whose path contains a specific substring', 'run the wav2vec manifest tool with a custom validation percentage to split audio data', 'review the wav2vec manifest argument parser to understand supported options like root, dest, ext, and seed']
```

Usage

```
{'build_wav2vec_manifest': 'build a wav2vec manifest by indexing audio files in a directory into train and validation TSV files', 'run_wav2vec_manifest_with_custom_ext': 'run the wav2vec manifest tool on a directory of wav files using the --ext flag', 'create_wav2vec_manifest_with_path_filter': 'create a wav2vec manifest that includes only files whose path contains a specific substring', 'run_wav2vec_manifest_with_custom_split': 'run the wav2vec manifest tool with a custom validation percentage to split audio data', 'review_wav2vec_manifest_parser': 'review the wav2vec manifest argument parser to understand supported options like root, dest, ext, and seed'}
```

