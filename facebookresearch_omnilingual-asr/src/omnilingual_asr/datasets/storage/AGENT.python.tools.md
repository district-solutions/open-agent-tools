# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/storage/manifest_storage.py

Prompts

```
['create a raw data pipeline from a manifest TSV file to load audio and optional text transcriptions', 'discover dataset splits by scanning a directory for TSV manifest files and returning split names', 'retrieve the audio directory path from the header line of a manifest TSV file', 'read a TSV manifest file and build a data pipeline with audio paths and sample lengths', 'read a WRD transcription file and build a data pipeline returning text entries', 'create a MixtureParquetStorage instance from a parquet path and MixtureParquetStorageConfig to read multilingual ASR datasets', 'build a mixed data pipeline with weighted partition sampling using create_mixed_pipeline for training splits', 'compute partition sample weights from a dataset summary TSV using beta corpus and beta language parameters', 'filter parquet partitions by split and corpus using fix_partition_filters to get filtered file paths', 'create a single partition reading pipeline using reading_one_partition_pipeline with fragment streaming and loading configs']
```

Usage

```
{'create_raw_data_pipeline': 'create a raw data pipeline from a manifest TSV file to load audio and optional text transcriptions', 'discover_splits': 'discover dataset splits by scanning a directory for TSV manifest files and returning split names', 'retrieve_audio_directory': 'retrieve the audio directory path from the header line of a manifest TSV file', 'read_tsv_file': 'read a TSV manifest file and build a data pipeline with audio paths and sample lengths', 'read_wrd_file': 'read a WRD transcription file and build a data pipeline returning text entries'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/storage/mixture_parquet_storage.py

Prompts

```
['create a raw data pipeline from a manifest TSV file to load audio and optional text transcriptions', 'discover dataset splits by scanning a directory for TSV manifest files and returning split names', 'retrieve the audio directory path from the header line of a manifest TSV file', 'read a TSV manifest file and build a data pipeline with audio paths and sample lengths', 'read a WRD transcription file and build a data pipeline returning text entries', 'create a MixtureParquetStorage instance from a parquet path and MixtureParquetStorageConfig to read multilingual ASR datasets', 'build a mixed data pipeline with weighted partition sampling using create_mixed_pipeline for training splits', 'compute partition sample weights from a dataset summary TSV using beta corpus and beta language parameters', 'filter parquet partitions by split and corpus using fix_partition_filters to get filtered file paths', 'create a single partition reading pipeline using reading_one_partition_pipeline with fragment streaming and loading configs']
```

Usage

```
{'create_mixture_parquet_storage': 'create a MixtureParquetStorage instance from a parquet path and MixtureParquetStorageConfig to read multilingual ASR datasets', 'build_weighted_sampling_pipeline': 'build a mixed data pipeline with weighted partition sampling using create_mixed_pipeline for training splits', 'compute_partition_weights_from_betas': 'compute partition sample weights from a dataset summary TSV using beta corpus and beta language parameters', 'filter_parquet_partitions': 'filter parquet partitions by split and corpus using fix_partition_filters to get filtered file paths', 'create_single_partition_pipeline': 'create a single partition reading pipeline using reading_one_partition_pipeline with fragment streaming and loading configs'}
```

