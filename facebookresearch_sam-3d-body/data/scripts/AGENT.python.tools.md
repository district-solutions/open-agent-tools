# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/data/scripts/create_webdataset.py

Prompts

```
['create a webdataset shard from parquet annotation files using create_webdataset_shard_multiprocess', 'get the annotation key for an image row from egoexo4d, egohumans, 3dpw, aic, coco, or mpii datasets', 'get the image file path for coco, mpii, or aic datasets using get_img_name', 'run the CLI to create webdataset shards from parquet annotations with configurable max workers and shard indices', 'create a single webdataset tar shard from one parquet file using create_webdatset_shard', 'run the download script to download the facebook sam-3d-body-dataset from Hugging Face to a local directory', 'run the download script with --splits flag to download only specific dataset splits like train or test', 'run the download script with --max_workers flag to control parallel download process count', 'review the download_file function that uses hf_hub_download to fetch a single file from a Hugging Face repo', 'review the download_files_multiprocess function that uses ProcessPoolExecutor to parallelize file downloads across multiple workers']
```

Usage

```
{'create_webdataset_from_parquet': 'create a webdataset shard from parquet annotation files using create_webdataset_shard_multiprocess', 'get_anno_key_for_dataset': 'get the annotation key for an image row from egoexo4d, egohumans, 3dpw, aic, coco, or mpii datasets', 'get_img_name_for_dataset': 'get the image file path for coco, mpii, or aic datasets using get_img_name', 'run_create_webdataset_cli': 'run the CLI to create webdataset shards from parquet annotations with configurable max workers and shard indices', 'create_webdataset_single_shard': 'create a single webdataset tar shard from one parquet file using create_webdatset_shard'}
```

## File: facebookresearch_sam-3d-body/data/scripts/download.py

Prompts

```
['create a webdataset shard from parquet annotation files using create_webdataset_shard_multiprocess', 'get the annotation key for an image row from egoexo4d, egohumans, 3dpw, aic, coco, or mpii datasets', 'get the image file path for coco, mpii, or aic datasets using get_img_name', 'run the CLI to create webdataset shards from parquet annotations with configurable max workers and shard indices', 'create a single webdataset tar shard from one parquet file using create_webdatset_shard', 'run the download script to download the facebook sam-3d-body-dataset from Hugging Face to a local directory', 'run the download script with --splits flag to download only specific dataset splits like train or test', 'run the download script with --max_workers flag to control parallel download process count', 'review the download_file function that uses hf_hub_download to fetch a single file from a Hugging Face repo', 'review the download_files_multiprocess function that uses ProcessPoolExecutor to parallelize file downloads across multiple workers']
```

Usage

```
{'run_download_sam3dbody_dataset': 'run the download script to download the facebook sam-3d-body-dataset from Hugging Face to a local directory', 'run_download_specific_splits': 'run the download script with --splits flag to download only specific dataset splits like train or test', 'run_download_with_workers': 'run the download script with --max_workers flag to control parallel download process count', 'review_download_file_function': 'review the download_file function that uses hf_hub_download to fetch a single file from a Hugging Face repo', 'review_multiprocess_download': 'review the download_files_multiprocess function that uses ProcessPoolExecutor to parallelize file downloads across multiple workers'}
```

