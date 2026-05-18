# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/visual_correspondence/visual_correspondence_qa_engine_coor_2_coor.py

Prompts

```
['build a training dataset of visual correspondence QA samples from parquet camera overlap data', 'build a validation dataset of visual correspondence QA samples from parquet camera overlap data', 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build a single visual correspondence QA sample from a row of overlap information and visibility data', 'convert a parquet DataFrame containing key-value pairs back into a Python dictionary']
```

Usage

```
{'build_train_dataset': 'build a training dataset of visual correspondence QA samples from parquet camera overlap data', 'build_val_dataset': 'build a validation dataset of visual correspondence QA samples from parquet camera overlap data', 'sample_dataframe': 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build_training_sample': 'build a single visual correspondence QA sample from a row of overlap information and visibility data', 'convert_parquet_to_dict': 'convert a parquet DataFrame containing key-value pairs back into a Python dictionary'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/visual_correspondence/visual_correspondence_qa_engine_dot_2_multichoice.py

Prompts

```
['build a training dataset of visual correspondence QA samples from parquet camera overlap data', 'build a validation dataset of visual correspondence QA samples from parquet camera overlap data', 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover', 'build a single visual correspondence QA sample from a row of overlap information and visibility data', 'convert a parquet DataFrame containing key-value pairs back into a Python dictionary']
```

Usage

```
{'build_train_dataset': 'build a training dataset for visual correspondence QA by sampling image pairs and generating annotated multichoice samples', 'build_val_dataset': 'build a validation dataset for visual correspondence QA from camera overlap parquet files with multichoice annotations', 'build_training_sample': 'build a single visual correspondence training sample with annotated images and multichoice question answer pairs', 'sample_dataframe': 'sample a DataFrame by overlap bins distributing quota evenly across bins with leftover carryover mechanism', 'convert_parquet_to_dict': 'convert a parquet DataFrame with key and value columns back into a Python dictionary'}
```

