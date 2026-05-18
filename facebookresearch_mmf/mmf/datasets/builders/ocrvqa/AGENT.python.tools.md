# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/ocrvqa/builder.py

Prompts

```
['build an OCR-VQA dataset builder by instantiating OCRVQABuilder to load and process OCR-VQA data', 'create a config path for the OCR-VQA dataset by calling OCRVQABuilder.config_path to get defaults.yaml', 'register the OCRVQABuilder class with the MMF registry using the register_builder decorator with key ocrvqa', 'review the OCRVQABuilder init method to understand how it sets dataset_name and calls set_dataset_class', 'test the inherited update_registry_for_model method to verify text and answer processor registration for OCR-VQA', 'create an OCRVQADataset instance with config, dataset_type, and imdb_file_index arguments', 'call preprocess_sample_info on OCRVQADataset to pass through sample_info unchanged', 'call format_for_prediction on OCRVQADataset to convert model report into prediction entries', 'access an OCRVQADataset item by index to get a Sample with question and answer data', 'call add_answer_info on OCRVQADataset to process and attach answer data to a sample']
```

Usage

```
{'build_ocrvqa_dataset': 'build an OCR-VQA dataset builder by instantiating OCRVQABuilder to load and process OCR-VQA data', 'create_ocrvqa_config': 'create a config path for the OCR-VQA dataset by calling OCRVQABuilder.config_path to get defaults.yaml', 'register_ocrvqa_builder': 'register the OCRVQABuilder class with the MMF registry using the register_builder decorator with key ocrvqa', 'review_ocrvqa_builder_init': 'review the OCRVQABuilder init method to understand how it sets dataset_name and calls set_dataset_class', 'test_ocrvqa_update_registry': 'test the inherited update_registry_for_model method to verify text and answer processor registration for OCR-VQA'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/ocrvqa/dataset.py

Prompts

```
['build an OCR-VQA dataset builder by instantiating OCRVQABuilder to load and process OCR-VQA data', 'create a config path for the OCR-VQA dataset by calling OCRVQABuilder.config_path to get defaults.yaml', 'register the OCRVQABuilder class with the MMF registry using the register_builder decorator with key ocrvqa', 'review the OCRVQABuilder init method to understand how it sets dataset_name and calls set_dataset_class', 'test the inherited update_registry_for_model method to verify text and answer processor registration for OCR-VQA', 'create an OCRVQADataset instance with config, dataset_type, and imdb_file_index arguments', 'call preprocess_sample_info on OCRVQADataset to pass through sample_info unchanged', 'call format_for_prediction on OCRVQADataset to convert model report into prediction entries', 'access an OCRVQADataset item by index to get a Sample with question and answer data', 'call add_answer_info on OCRVQADataset to process and attach answer data to a sample']
```

Usage

```
{'init_OCRVQADataset': 'create an OCRVQADataset instance with config, dataset_type, and imdb_file_index arguments', 'preprocess_sample_info_OCRVQADataset': 'call preprocess_sample_info on OCRVQADataset to pass through sample_info unchanged', 'format_for_prediction_TextVQA': 'call format_for_prediction on OCRVQADataset to convert model report into prediction entries', 'getitem_OCRVQADataset': 'access an OCRVQADataset item by index to get a Sample with question and answer data', 'add_answer_info_TextVQA': 'call add_answer_info on OCRVQADataset to process and attach answer data to a sample'}
```

