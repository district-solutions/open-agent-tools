# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/pe/clip_benchmark/cli.py

Prompts

```
['run zero-shot classification evaluation on a dataset using a pre-trained CLIP model', 'run zero-shot retrieval evaluation with recall metrics on a dataset using a CLIP model', 'run linear probe evaluation with few-shot learning on a dataset using a pre-trained model', 'build a CSV benchmark file from multiple JSON evaluation result files', 'run multiclass retrieval evaluation on a dataset using a pre-trained CLIP model', 'create a function that reads a CSV file and returns a list of comma-split rows', 'summarize the python get_model_collection_from_file function that parses a file into comma-separated rows', 'review the python get_model_collection_from_file function for file handling best practices', 'test the python get_model_collection_from_file function with a sample CSV file path', 'refactor the python get_model_collection_from_file to use a context manager for file handling', 'convert a CLIP_benchmark dataset to webdataset TAR format with configurable image format and shard size', 'convert a retrieval dataset with image caption pairs to webdataset TAR format', 'run the CLI tool to convert a named dataset split to webdataset format in an output directory', 'create a transform function that converts PIL images to bytes in webp png or jpg format', 'save dataset classnames and zero-shot classification templates to text files in the output folder']
```

Usage

```
{'eval_zeroshot_classification': 'run zero-shot classification evaluation on a dataset using a pre-trained CLIP model', 'eval_zeroshot_retrieval': 'run zero-shot retrieval evaluation with recall metrics on a dataset using a CLIP model', 'eval_linear_probe': 'run linear probe evaluation with few-shot learning on a dataset using a pre-trained model', 'build_benchmark_csv': 'build a CSV benchmark file from multiple JSON evaluation result files', 'eval_multiclass_retrieval': 'run multiclass retrieval evaluation on a dataset using a pre-trained CLIP model'}
```

## File: facebookresearch_perceptionmodels/apps/pe/clip_benchmark/model_collection.py

Prompts

```
['run zero-shot classification evaluation on a dataset using a pre-trained CLIP model', 'run zero-shot retrieval evaluation with recall metrics on a dataset using a CLIP model', 'run linear probe evaluation with few-shot learning on a dataset using a pre-trained model', 'build a CSV benchmark file from multiple JSON evaluation result files', 'run multiclass retrieval evaluation on a dataset using a pre-trained CLIP model', 'create a function that reads a CSV file and returns a list of comma-split rows', 'summarize the python get_model_collection_from_file function that parses a file into comma-separated rows', 'review the python get_model_collection_from_file function for file handling best practices', 'test the python get_model_collection_from_file function with a sample CSV file path', 'refactor the python get_model_collection_from_file to use a context manager for file handling', 'convert a CLIP_benchmark dataset to webdataset TAR format with configurable image format and shard size', 'convert a retrieval dataset with image caption pairs to webdataset TAR format', 'run the CLI tool to convert a named dataset split to webdataset format in an output directory', 'create a transform function that converts PIL images to bytes in webp png or jpg format', 'save dataset classnames and zero-shot classification templates to text files in the output folder']
```

Usage

```
{'parse_model_collection_file': 'create a function that reads a CSV file and returns a list of comma-split rows', 'summarize_get_model_collection_from_file': 'summarize the python get_model_collection_from_file function that parses a file into comma-separated rows', 'review_get_model_collection_from_file': 'review the python get_model_collection_from_file function for file handling best practices', 'test_get_model_collection_from_file': 'test the python get_model_collection_from_file function with a sample CSV file path', 'refactor_get_model_collection_from_file': 'refactor the python get_model_collection_from_file to use a context manager for file handling'}
```

## File: facebookresearch_perceptionmodels/apps/pe/clip_benchmark/webdataset_builder.py

Prompts

```
['run zero-shot classification evaluation on a dataset using a pre-trained CLIP model', 'run zero-shot retrieval evaluation with recall metrics on a dataset using a CLIP model', 'run linear probe evaluation with few-shot learning on a dataset using a pre-trained model', 'build a CSV benchmark file from multiple JSON evaluation result files', 'run multiclass retrieval evaluation on a dataset using a pre-trained CLIP model', 'create a function that reads a CSV file and returns a list of comma-split rows', 'summarize the python get_model_collection_from_file function that parses a file into comma-separated rows', 'review the python get_model_collection_from_file function for file handling best practices', 'test the python get_model_collection_from_file function with a sample CSV file path', 'refactor the python get_model_collection_from_file to use a context manager for file handling', 'convert a CLIP_benchmark dataset to webdataset TAR format with configurable image format and shard size', 'convert a retrieval dataset with image caption pairs to webdataset TAR format', 'run the CLI tool to convert a named dataset split to webdataset format in an output directory', 'create a transform function that converts PIL images to bytes in webp png or jpg format', 'save dataset classnames and zero-shot classification templates to text files in the output folder']
```

Usage

```
{'convert_dataset_to_webdataset': 'convert a CLIP_benchmark dataset to webdataset TAR format with configurable image format and shard size', 'convert_retrieval_dataset_to_webdataset': 'convert a retrieval dataset with image caption pairs to webdataset TAR format', 'run_cli_conversion': 'run the CLI tool to convert a named dataset split to webdataset format in an output directory', 'create_pil_to_bytes_transform': 'create a transform function that converts PIL images to bytes in webp png or jpg format', 'save_classnames_and_templates': 'save dataset classnames and zero-shot classification templates to text files in the output folder'}
```

