# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/vqacp_v2/builder.py

Prompts

```
['build a VQACPv2 dataset by instantiating VQACPv2Builder with config and dataset type', 'register the VQACPv2Builder class with the MMF registry using the vqacp_v2 key', 'get the default YAML config path for the vqacp_v2 dataset from the builder class', 'review the VQACPv2Builder class to understand how it extends MMFDatasetBuilder for v2 dataset support', 'summarize the VQACPv2Builder init method that accepts dataset name and dataset class parameters', 'build a VQACPv2 annotation database by loading questions and annotations JSON files into a linear format', 'load VQACPv2 annotation data from two JSON paths merging questions with their corresponding annotations', 'review the VQACPv2AnnotationDatabase class that extends OKVQAAnnotationDatabase for visual question answering datasets', 'refactor the load_annotation_db method to support additional JSON file formats beyond the current two-path requirement', 'test the VQACPv2AnnotationDatabase class by providing mock question and annotation JSON files and verifying data merging', 'build the VQACPv2 annotation database from the config and annotation path', 'get the COCO image file path by image_id and coco_split', 'retrieve a VQACPv2 sample with question, image, and answer targets by index', 'review the VQACPv2Dataset class that extends OKVQADataset for visual question answering', 'initialize a VQACPv2Dataset instance with config, dataset_type, and index parameters']
```

Usage

```
{'build_vqacp_v2_dataset': 'build a VQACPv2 dataset by instantiating VQACPv2Builder with config and dataset type', 'register_vqacp_v2_builder': 'register the VQACPv2Builder class with the MMF registry using the vqacp_v2 key', 'get_config_path': 'get the default YAML config path for the vqacp_v2 dataset from the builder class', 'review_vqacp_v2_builder': 'review the VQACPv2Builder class to understand how it extends MMFDatasetBuilder for v2 dataset support', 'summarize_vqacp_v2_init': 'summarize the VQACPv2Builder init method that accepts dataset name and dataset class parameters'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/vqacp_v2/database.py

Prompts

```
['build a VQACPv2 dataset by instantiating VQACPv2Builder with config and dataset type', 'register the VQACPv2Builder class with the MMF registry using the vqacp_v2 key', 'get the default YAML config path for the vqacp_v2 dataset from the builder class', 'review the VQACPv2Builder class to understand how it extends MMFDatasetBuilder for v2 dataset support', 'summarize the VQACPv2Builder init method that accepts dataset name and dataset class parameters', 'build a VQACPv2 annotation database by loading questions and annotations JSON files into a linear format', 'load VQACPv2 annotation data from two JSON paths merging questions with their corresponding annotations', 'review the VQACPv2AnnotationDatabase class that extends OKVQAAnnotationDatabase for visual question answering datasets', 'refactor the load_annotation_db method to support additional JSON file formats beyond the current two-path requirement', 'test the VQACPv2AnnotationDatabase class by providing mock question and annotation JSON files and verifying data merging', 'build the VQACPv2 annotation database from the config and annotation path', 'get the COCO image file path by image_id and coco_split', 'retrieve a VQACPv2 sample with question, image, and answer targets by index', 'review the VQACPv2Dataset class that extends OKVQADataset for visual question answering', 'initialize a VQACPv2Dataset instance with config, dataset_type, and index parameters']
```

Usage

```
{'build_vqacpv2_database': 'build a VQACPv2 annotation database by loading questions and annotations JSON files into a linear format', 'load_annotation_db': 'load VQACPv2 annotation data from two JSON paths merging questions with their corresponding annotations', 'review_VQACPv2AnnotationDatabase': 'review the VQACPv2AnnotationDatabase class that extends OKVQAAnnotationDatabase for visual question answering datasets', 'refactor_load_annotation_db': 'refactor the load_annotation_db method to support additional JSON file formats beyond the current two-path requirement', 'test_VQACPv2AnnotationDatabase': 'test the VQACPv2AnnotationDatabase class by providing mock question and annotation JSON files and verifying data merging'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/vqacp_v2/dataset.py

Prompts

```
['build a VQACPv2 dataset by instantiating VQACPv2Builder with config and dataset type', 'register the VQACPv2Builder class with the MMF registry using the vqacp_v2 key', 'get the default YAML config path for the vqacp_v2 dataset from the builder class', 'review the VQACPv2Builder class to understand how it extends MMFDatasetBuilder for v2 dataset support', 'summarize the VQACPv2Builder init method that accepts dataset name and dataset class parameters', 'build a VQACPv2 annotation database by loading questions and annotations JSON files into a linear format', 'load VQACPv2 annotation data from two JSON paths merging questions with their corresponding annotations', 'review the VQACPv2AnnotationDatabase class that extends OKVQAAnnotationDatabase for visual question answering datasets', 'refactor the load_annotation_db method to support additional JSON file formats beyond the current two-path requirement', 'test the VQACPv2AnnotationDatabase class by providing mock question and annotation JSON files and verifying data merging', 'build the VQACPv2 annotation database from the config and annotation path', 'get the COCO image file path by image_id and coco_split', 'retrieve a VQACPv2 sample with question, image, and answer targets by index', 'review the VQACPv2Dataset class that extends OKVQADataset for visual question answering', 'initialize a VQACPv2Dataset instance with config, dataset_type, and index parameters']
```

Usage

```
{'build_annotation_db': 'build the VQACPv2 annotation database from the config and annotation path', 'get_image_path': 'get the COCO image file path by image_id and coco_split', 'getitem_sample': 'retrieve a VQACPv2 sample with question, image, and answer targets by index', 'review_VQACPv2Dataset': 'review the VQACPv2Dataset class that extends OKVQADataset for visual question answering', 'init_VQACPv2Dataset': 'initialize a VQACPv2Dataset instance with config, dataset_type, and index parameters'}
```

