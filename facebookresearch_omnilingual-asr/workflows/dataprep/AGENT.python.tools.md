# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/workflows/dataprep/audio_tools.py

Prompts

```
['create an AudioTableProcessor to decode, resample, and convert audio in a PyArrow table to compressed bytes', 'use AudioTableProcessor to read a list of audio file paths and return resampled waveforms', 'use AudioTableProcessor to decode a list of audio byte arrays and return resampled waveforms', 'convert a numpy array of audio bytes to a flattened waveform numpy array at a target sample rate', 'convert a PyArrow BinaryArray to a ListArray of int8 values preserving nulls', 'test MixtureParquetAsrDataset by building a reader and iterating over batches with corpus and language statistics', 'run the dataloader example CLI to iterate over ASR dataset batches with a specified tokenizer and split', 'create a data reader from a dataset path using MixtureParquetAsrDataset with storage and task configuration', 'configure MixtureParquetStorageConfig with fragment streaming and loading settings for parquet-based ASR data', 'configure AsrTaskConfig with audio length limits, shuffle windows, and batch constraints for ASR tasks', 'run the full ASR data preparation pipeline ingesting MLS and FLEURS datasets to an output directory', 'run a short ASR data preparation pipeline ingesting only 2 FLEURS languages for quick testing', 'ingest Multilingual LibriSpeech datasets for multiple languages and splits into partitioned Parquet files', 'ingest FLEURS datasets for multiple languages and splits into partitioned Parquet files', 'compute language and corpus distribution statistics from processed Parquet datasets and save to TSV', 'normalize text by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including references like biblical citations', 'normalize text while preserving standalone numbers instead of removing digit-only words', 'normalize text without converting to lowercase while still removing punctuation and extra spaces', 'review the text_normalize function to understand its normalization pipeline for ASR text preprocessing']
```

Usage

```
{'process_audio_table': 'create an AudioTableProcessor to decode, resample, and convert audio in a PyArrow table to compressed bytes', 'read_audio_files': 'use AudioTableProcessor to read a list of audio file paths and return resampled waveforms', 'read_audio_bytes': 'use AudioTableProcessor to decode a list of audio byte arrays and return resampled waveforms', 'bytes_to_tensor': 'convert a numpy array of audio bytes to a flattened waveform numpy array at a target sample rate', 'binary_to_list_int8': 'convert a PyArrow BinaryArray to a ListArray of int8 values preserving nulls'}
```

## File: facebookresearch_omnilingual-asr/workflows/dataprep/dataloader_example.py

Prompts

```
['create an AudioTableProcessor to decode, resample, and convert audio in a PyArrow table to compressed bytes', 'use AudioTableProcessor to read a list of audio file paths and return resampled waveforms', 'use AudioTableProcessor to decode a list of audio byte arrays and return resampled waveforms', 'convert a numpy array of audio bytes to a flattened waveform numpy array at a target sample rate', 'convert a PyArrow BinaryArray to a ListArray of int8 values preserving nulls', 'test MixtureParquetAsrDataset by building a reader and iterating over batches with corpus and language statistics', 'run the dataloader example CLI to iterate over ASR dataset batches with a specified tokenizer and split', 'create a data reader from a dataset path using MixtureParquetAsrDataset with storage and task configuration', 'configure MixtureParquetStorageConfig with fragment streaming and loading settings for parquet-based ASR data', 'configure AsrTaskConfig with audio length limits, shuffle windows, and batch constraints for ASR tasks', 'run the full ASR data preparation pipeline ingesting MLS and FLEURS datasets to an output directory', 'run a short ASR data preparation pipeline ingesting only 2 FLEURS languages for quick testing', 'ingest Multilingual LibriSpeech datasets for multiple languages and splits into partitioned Parquet files', 'ingest FLEURS datasets for multiple languages and splits into partitioned Parquet files', 'compute language and corpus distribution statistics from processed Parquet datasets and save to TSV', 'normalize text by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including references like biblical citations', 'normalize text while preserving standalone numbers instead of removing digit-only words', 'normalize text without converting to lowercase while still removing punctuation and extra spaces', 'review the text_normalize function to understand its normalization pipeline for ASR text preprocessing']
```

Usage

```
{'test_MixtureParquetAsrDataset': 'test MixtureParquetAsrDataset by building a reader and iterating over batches with corpus and language statistics', 'run_dataloader_example_cli': 'run the dataloader example CLI to iterate over ASR dataset batches with a specified tokenizer and split', 'create_reader_from_path': 'create a data reader from a dataset path using MixtureParquetAsrDataset with storage and task configuration', 'configure_MixtureParquetStorageConfig': 'configure MixtureParquetStorageConfig with fragment streaming and loading settings for parquet-based ASR data', 'configure_AsrTaskConfig': 'configure AsrTaskConfig with audio length limits, shuffle windows, and batch constraints for ASR tasks'}
```

## File: facebookresearch_omnilingual-asr/workflows/dataprep/hf_dataset_ingestion_example.py

Prompts

```
['create an AudioTableProcessor to decode, resample, and convert audio in a PyArrow table to compressed bytes', 'use AudioTableProcessor to read a list of audio file paths and return resampled waveforms', 'use AudioTableProcessor to decode a list of audio byte arrays and return resampled waveforms', 'convert a numpy array of audio bytes to a flattened waveform numpy array at a target sample rate', 'convert a PyArrow BinaryArray to a ListArray of int8 values preserving nulls', 'test MixtureParquetAsrDataset by building a reader and iterating over batches with corpus and language statistics', 'run the dataloader example CLI to iterate over ASR dataset batches with a specified tokenizer and split', 'create a data reader from a dataset path using MixtureParquetAsrDataset with storage and task configuration', 'configure MixtureParquetStorageConfig with fragment streaming and loading settings for parquet-based ASR data', 'configure AsrTaskConfig with audio length limits, shuffle windows, and batch constraints for ASR tasks', 'run the full ASR data preparation pipeline ingesting MLS and FLEURS datasets to an output directory', 'run a short ASR data preparation pipeline ingesting only 2 FLEURS languages for quick testing', 'ingest Multilingual LibriSpeech datasets for multiple languages and splits into partitioned Parquet files', 'ingest FLEURS datasets for multiple languages and splits into partitioned Parquet files', 'compute language and corpus distribution statistics from processed Parquet datasets and save to TSV', 'normalize text by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including references like biblical citations', 'normalize text while preserving standalone numbers instead of removing digit-only words', 'normalize text without converting to lowercase while still removing punctuation and extra spaces', 'review the text_normalize function to understand its normalization pipeline for ASR text preprocessing']
```

Usage

```
{'run_full_pipeline': 'run the full ASR data preparation pipeline ingesting MLS and FLEURS datasets to an output directory', 'run_short_pipeline': 'run a short ASR data preparation pipeline ingesting only 2 FLEURS languages for quick testing', 'ingest_mls': 'ingest Multilingual LibriSpeech datasets for multiple languages and splits into partitioned Parquet files', 'ingest_fleurs': 'ingest FLEURS datasets for multiple languages and splits into partitioned Parquet files', 'compute_stats': 'compute language and corpus distribution statistics from processed Parquet datasets and save to TSV'}
```

## File: facebookresearch_omnilingual-asr/workflows/dataprep/text_tools.py

Prompts

```
['create an AudioTableProcessor to decode, resample, and convert audio in a PyArrow table to compressed bytes', 'use AudioTableProcessor to read a list of audio file paths and return resampled waveforms', 'use AudioTableProcessor to decode a list of audio byte arrays and return resampled waveforms', 'convert a numpy array of audio bytes to a flattened waveform numpy array at a target sample rate', 'convert a PyArrow BinaryArray to a ListArray of int8 values preserving nulls', 'test MixtureParquetAsrDataset by building a reader and iterating over batches with corpus and language statistics', 'run the dataloader example CLI to iterate over ASR dataset batches with a specified tokenizer and split', 'create a data reader from a dataset path using MixtureParquetAsrDataset with storage and task configuration', 'configure MixtureParquetStorageConfig with fragment streaming and loading settings for parquet-based ASR data', 'configure AsrTaskConfig with audio length limits, shuffle windows, and batch constraints for ASR tasks', 'run the full ASR data preparation pipeline ingesting MLS and FLEURS datasets to an output directory', 'run a short ASR data preparation pipeline ingesting only 2 FLEURS languages for quick testing', 'ingest Multilingual LibriSpeech datasets for multiple languages and splits into partitioned Parquet files', 'ingest FLEURS datasets for multiple languages and splits into partitioned Parquet files', 'compute language and corpus distribution statistics from processed Parquet datasets and save to TSV', 'normalize text by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including references like biblical citations', 'normalize text while preserving standalone numbers instead of removing digit-only words', 'normalize text without converting to lowercase while still removing punctuation and extra spaces', 'review the text_normalize function to understand its normalization pipeline for ASR text preprocessing']
```

Usage

```
{'normalize_text': 'normalize text by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize_text_with_brackets': 'normalize text and remove all bracketed content including references like biblical citations', 'normalize_text_keep_numbers': 'normalize text while preserving standalone numbers instead of removing digit-only words', 'normalize_text_preserve_case': 'normalize text without converting to lowercase while still removing punctuation and extra spaces', 'review_text_normalize': 'review the text_normalize function to understand its normalization pipeline for ASR text preprocessing'}
```

