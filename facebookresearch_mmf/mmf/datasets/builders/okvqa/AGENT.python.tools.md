# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/okvqa/builder.py

Prompts

```
['build an OKVQA dataset using the OKVQABuilder registered in the MMF registry', 'register the OKVQABuilder class with the MMF registry under the okvqa key', 'get the default YAML config path for the OKVQA dataset from the builder class', 'review the OKVQABuilder class and its inheritance from MMFDatasetBuilder', 'summarize the OKVQABuilder init method and config_path classmethod', 'build an OKVQAAnnotationDatabase instance from a config and comma-separated paths to questions and annotations JSON files', 'load OK-VQA annotation data from two JSON files into a linear format with merged questions and answers', 'create an OKVQA dataset loader that parses questions and annotations JSON into a unified data structure', 'review the OKVQAAnnotationDatabase class and its load_annotation_db method for merging questions with annotations', 'refactor the load_annotation_db method to handle additional OK-VQA data fields or validation', 'build an OKVQADataset instance with config, dataset_type, and index for OK-VQA multimodal data loading', 'create a call to get_image_path that returns a COCO image path for a given image_id', 'test the OKVQADataset __getitem__ method to retrieve a processed Sample with question, image, and answer data', 'review the format_for_prediction method that collapses graph and regular answer scores and returns top-5 predictions', 'refactor the add_answer_info method to process soft copy answers and attach targets to the sample']
```

Usage

```
{'build_okvqa_dataset': 'build an OKVQA dataset using the OKVQABuilder registered in the MMF registry', 'register_okvqa_builder': 'register the OKVQABuilder class with the MMF registry under the okvqa key', 'get_okvqa_config_path': 'get the default YAML config path for the OKVQA dataset from the builder class', 'review_okvqabuilder_class': 'review the OKVQABuilder class and its inheritance from MMFDatasetBuilder', 'summarize_okvqa_builder': 'summarize the OKVQABuilder init method and config_path classmethod'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/okvqa/database.py

Prompts

```
['build an OKVQA dataset using the OKVQABuilder registered in the MMF registry', 'register the OKVQABuilder class with the MMF registry under the okvqa key', 'get the default YAML config path for the OKVQA dataset from the builder class', 'review the OKVQABuilder class and its inheritance from MMFDatasetBuilder', 'summarize the OKVQABuilder init method and config_path classmethod', 'build an OKVQAAnnotationDatabase instance from a config and comma-separated paths to questions and annotations JSON files', 'load OK-VQA annotation data from two JSON files into a linear format with merged questions and answers', 'create an OKVQA dataset loader that parses questions and annotations JSON into a unified data structure', 'review the OKVQAAnnotationDatabase class and its load_annotation_db method for merging questions with annotations', 'refactor the load_annotation_db method to handle additional OK-VQA data fields or validation', 'build an OKVQADataset instance with config, dataset_type, and index for OK-VQA multimodal data loading', 'create a call to get_image_path that returns a COCO image path for a given image_id', 'test the OKVQADataset __getitem__ method to retrieve a processed Sample with question, image, and answer data', 'review the format_for_prediction method that collapses graph and regular answer scores and returns top-5 predictions', 'refactor the add_answer_info method to process soft copy answers and attach targets to the sample']
```

Usage

```
{'build_OKVQAAnnotationDatabase': 'build an OKVQAAnnotationDatabase instance from a config and comma-separated paths to questions and annotations JSON files', 'load_annotation_db_OKVQA': 'load OK-VQA annotation data from two JSON files into a linear format with merged questions and answers', 'create_OKVQA_dataset_loader': 'create an OKVQA dataset loader that parses questions and annotations JSON into a unified data structure', 'review_OKVQAAnnotationDatabase_class': 'review the OKVQAAnnotationDatabase class and its load_annotation_db method for merging questions with annotations', 'refactor_load_annotation_db': 'refactor the load_annotation_db method to handle additional OK-VQA data fields or validation'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/okvqa/dataset.py

Prompts

```
['build an OKVQA dataset using the OKVQABuilder registered in the MMF registry', 'register the OKVQABuilder class with the MMF registry under the okvqa key', 'get the default YAML config path for the OKVQA dataset from the builder class', 'review the OKVQABuilder class and its inheritance from MMFDatasetBuilder', 'summarize the OKVQABuilder init method and config_path classmethod', 'build an OKVQAAnnotationDatabase instance from a config and comma-separated paths to questions and annotations JSON files', 'load OK-VQA annotation data from two JSON files into a linear format with merged questions and answers', 'create an OKVQA dataset loader that parses questions and annotations JSON into a unified data structure', 'review the OKVQAAnnotationDatabase class and its load_annotation_db method for merging questions with annotations', 'refactor the load_annotation_db method to handle additional OK-VQA data fields or validation', 'build an OKVQADataset instance with config, dataset_type, and index for OK-VQA multimodal data loading', 'create a call to get_image_path that returns a COCO image path for a given image_id', 'test the OKVQADataset __getitem__ method to retrieve a processed Sample with question, image, and answer data', 'review the format_for_prediction method that collapses graph and regular answer scores and returns top-5 predictions', 'refactor the add_answer_info method to process soft copy answers and attach targets to the sample']
```

Usage

```
{'build_OKVQADataset': 'build an OKVQADataset instance with config, dataset_type, and index for OK-VQA multimodal data loading', 'create_get_image_path': 'create a call to get_image_path that returns a COCO image path for a given image_id', 'test___getitem__': 'test the OKVQADataset __getitem__ method to retrieve a processed Sample with question, image, and answer data', 'review_format_for_prediction': 'review the format_for_prediction method that collapses graph and regular answer scores and returns top-5 predictions', 'refactor_add_answer_info': 'refactor the add_answer_info method to process soft copy answers and attach targets to the sample'}
```

