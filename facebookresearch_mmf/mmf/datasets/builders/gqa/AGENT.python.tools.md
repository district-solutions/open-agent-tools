# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/gqa/builder.py

Prompts

```
['build a GQA dataset builder using GQABuilder to load visual question answering data', 'create a GQABuilder instance with a custom dataset name and GQADataset class', 'review the GQABuilder config_path method to find the default YAML configuration path', 'test the update_registry_for_model method to register text vocab size and answer output counts', 'summarize the GQABuilder class which extends MMFDatasetBuilder for GQA dataset registration', 'create a Sample object with text, image features, and answer info by indexing into the dataset', 'test the add_answer_info method to process soft copy answers and set target scores on a sample', 'review the format_for_prediction method to convert model scores into questionId and prediction pairs', 'refactor the __getitem__ method to support transformer bbox processing on image features', 'review the MaskedGQABuilder class and its inheritance from GQABuilder for masked GQA dataset support', 'summarize the MaskedGQABuilder class which registers masked_gqa as a dataset builder with MaskedGQADataset', 'test the MaskedGQABuilder config_path classmethod to verify it returns the correct masked YAML config path', 'refactor the MaskedGQABuilder class to support additional masked dataset configurations beyond GQA', 'create a masked GQA dataset builder instance using MaskedGQABuilder with the MaskedGQADataset class']
```

Usage

```
{'build_gqa_dataset': 'build a GQA dataset builder using GQABuilder to load visual question answering data', 'create_gqa_builder': 'create a GQABuilder instance with a custom dataset name and GQADataset class', 'review_config_path': 'review the GQABuilder config_path method to find the default YAML configuration path', 'test_update_registry': 'test the update_registry_for_model method to register text vocab size and answer output counts', 'summarize_gqa_builder': 'summarize the GQABuilder class which extends MMFDatasetBuilder for GQA dataset registration'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/gqa/dataset.py

Prompts

```
['build a GQA dataset builder using GQABuilder to load visual question answering data', 'create a GQABuilder instance with a custom dataset name and GQADataset class', 'review the GQABuilder config_path method to find the default YAML configuration path', 'test the update_registry_for_model method to register text vocab size and answer output counts', 'summarize the GQABuilder class which extends MMFDatasetBuilder for GQA dataset registration', 'create a Sample object with text, image features, and answer info by indexing into the dataset', 'test the add_answer_info method to process soft copy answers and set target scores on a sample', 'review the format_for_prediction method to convert model scores into questionId and prediction pairs', 'refactor the __getitem__ method to support transformer bbox processing on image features', 'review the MaskedGQABuilder class and its inheritance from GQABuilder for masked GQA dataset support', 'summarize the MaskedGQABuilder class which registers masked_gqa as a dataset builder with MaskedGQADataset', 'test the MaskedGQABuilder config_path classmethod to verify it returns the correct masked YAML config path', 'refactor the MaskedGQABuilder class to support additional masked dataset configurations beyond GQA', 'create a masked GQA dataset builder instance using MaskedGQABuilder with the MaskedGQADataset class']
```

Usage

```
{'build_gqa_dataset': 'build a GQADataset instance from config and dataset type to load GQA visual reasoning data', 'create_sample_from_index': 'create a Sample object with text, image features, and answer info by indexing into the dataset', 'test_add_answer_info': 'test the add_answer_info method to process soft copy answers and set target scores on a sample', 'review_format_for_prediction': 'review the format_for_prediction method to convert model scores into questionId and prediction pairs', 'refactor_getitem_for_features': 'refactor the __getitem__ method to support transformer bbox processing on image features'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/gqa/masked_builder.py

Prompts

```
['build a GQA dataset builder using GQABuilder to load visual question answering data', 'create a GQABuilder instance with a custom dataset name and GQADataset class', 'review the GQABuilder config_path method to find the default YAML configuration path', 'test the update_registry_for_model method to register text vocab size and answer output counts', 'summarize the GQABuilder class which extends MMFDatasetBuilder for GQA dataset registration', 'create a Sample object with text, image features, and answer info by indexing into the dataset', 'test the add_answer_info method to process soft copy answers and set target scores on a sample', 'review the format_for_prediction method to convert model scores into questionId and prediction pairs', 'refactor the __getitem__ method to support transformer bbox processing on image features', 'review the MaskedGQABuilder class and its inheritance from GQABuilder for masked GQA dataset support', 'summarize the MaskedGQABuilder class which registers masked_gqa as a dataset builder with MaskedGQADataset', 'test the MaskedGQABuilder config_path classmethod to verify it returns the correct masked YAML config path', 'refactor the MaskedGQABuilder class to support additional masked dataset configurations beyond GQA', 'create a masked GQA dataset builder instance using MaskedGQABuilder with the MaskedGQADataset class']
```

Usage

```
{'review_MaskedGQABuilder': 'review the MaskedGQABuilder class and its inheritance from GQABuilder for masked GQA dataset support', 'summarize_MaskedGQABuilder': 'summarize the MaskedGQABuilder class which registers masked_gqa as a dataset builder with MaskedGQADataset', 'test_MaskedGQABuilder_config_path': 'test the MaskedGQABuilder config_path classmethod to verify it returns the correct masked YAML config path', 'refactor_MaskedGQABuilder': 'refactor the MaskedGQABuilder class to support additional masked dataset configurations beyond GQA', 'create_masked_gqa_builder': 'create a masked GQA dataset builder instance using MaskedGQABuilder with the MaskedGQADataset class'}
```

