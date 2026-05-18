# Agent Python Tools

- repo: facebookresearch/meru
- repo_uri: https://github.com/facebookresearch/meru

## File: facebookresearch_meru/meru/evaluation/catalog.py

Prompts

```
['build a dataset by calling DatasetCatalog.build with a name, root path, and split like train val or test', 'list all supported dataset names from the DatasetCatalog.CONSTRUCTORS dictionary keys', 'lookup the official train val and test split names for a dataset using DatasetCatalog.SPLITS', 'get the number of classes for an image classification dataset from DatasetCatalog.NUM_CLASSES', 'build a dataset with a custom transform by passing it to DatasetCatalog.build as the transform argument']
```

Usage

```
{'build_dataset_from_catalog': 'build a dataset by calling DatasetCatalog.build with a name, root path, and split like train val or test', 'list_supported_datasets': 'list all supported dataset names from the DatasetCatalog.CONSTRUCTORS dictionary keys', 'lookup_dataset_splits': 'lookup the official train val and test split names for a dataset using DatasetCatalog.SPLITS', 'get_num_classes': 'get the number of classes for an image classification dataset from DatasetCatalog.NUM_CLASSES', 'build_dataset_with_transform': 'build a dataset with a custom transform by passing it to DatasetCatalog.build as the transform argument'}
```

