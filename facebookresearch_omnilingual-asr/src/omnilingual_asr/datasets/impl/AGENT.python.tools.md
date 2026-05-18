# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/impl/manifest_asr_dataset.py

Prompts

```
['create a ManifestAsrDataset by discovering splits from a dataset directory path', 'create a DataReader for a specific split using tokenizer and storage config', 'open a ManifestAsrDataset using a ManifestAsrDatasetConfig with a data path', 'review the ManifestAsrDatasetConfig dataclass for dataset directory path configuration', 'refactor the create_reader method to customize the storage and task pipeline stitching', 'create a MixtureParquetAsrDatasetConfig with a data path pointing to parquet corpora', 'build a MixtureParquetAsrDataset instance from a Path using the from_path class method', 'create a DataReader by calling create_reader with split, tokenizer, gangs, dtype, and configs', 'open a MixtureParquetAsrDataset from a MixtureParquetAsrDatasetConfig using open_mixture_parquet_asr_dataset', 'review the MixtureParquetAsrDataset create_reader method that stitches MixtureParquetStorage and AsrTask pipelines']
```

Usage

```
{'create_manifest_asr_dataset_from_path': 'create a ManifestAsrDataset by discovering splits from a dataset directory path', 'create_reader_for_split': 'create a DataReader for a specific split using tokenizer and storage config', 'open_manifest_asr_dataset_with_config': 'open a ManifestAsrDataset using a ManifestAsrDatasetConfig with a data path', 'review_manifest_asr_dataset_config': 'review the ManifestAsrDatasetConfig dataclass for dataset directory path configuration', 'refactor_create_reader_pipeline': 'refactor the create_reader method to customize the storage and task pipeline stitching'}
```

## File: facebookresearch_omnilingual-asr/src/omnilingual_asr/datasets/impl/mixture_parquet_asr_dataset.py

Prompts

```
['create a ManifestAsrDataset by discovering splits from a dataset directory path', 'create a DataReader for a specific split using tokenizer and storage config', 'open a ManifestAsrDataset using a ManifestAsrDatasetConfig with a data path', 'review the ManifestAsrDatasetConfig dataclass for dataset directory path configuration', 'refactor the create_reader method to customize the storage and task pipeline stitching', 'create a MixtureParquetAsrDatasetConfig with a data path pointing to parquet corpora', 'build a MixtureParquetAsrDataset instance from a Path using the from_path class method', 'create a DataReader by calling create_reader with split, tokenizer, gangs, dtype, and configs', 'open a MixtureParquetAsrDataset from a MixtureParquetAsrDatasetConfig using open_mixture_parquet_asr_dataset', 'review the MixtureParquetAsrDataset create_reader method that stitches MixtureParquetStorage and AsrTask pipelines']
```

Usage

```
{'create_config': 'create a MixtureParquetAsrDatasetConfig with a data path pointing to parquet corpora', 'build_dataset_from_path': 'build a MixtureParquetAsrDataset instance from a Path using the from_path class method', 'create_reader': 'create a DataReader by calling create_reader with split, tokenizer, gangs, dtype, and configs', 'open_dataset': 'open a MixtureParquetAsrDataset from a MixtureParquetAsrDatasetConfig using open_mixture_parquet_asr_dataset', 'review_pipeline': 'review the MixtureParquetAsrDataset create_reader method that stitches MixtureParquetStorage and AsrTask pipelines'}
```

