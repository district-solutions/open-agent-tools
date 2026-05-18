# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/textcaps/builder.py

Prompts

```
['build a TextCapsBuilder to load the TextCaps dataset with default configuration', 'build a TextCapsBuilder with coco annotation style to load dataset using COCODataset class', 'review the TextCapsBuilder config_path method to get the defaults.yaml config location', 'review the TextCapsBuilder load method to understand annotation style switching logic', 'test the TextCapsBuilder __init__ to verify dataset_name and dataset_class defaults', 'preprocess sample info by adding dummy empty questions and mapping caption_id to question_id', 'postprocess an EvalAI entry by remapping question_id to caption_id and answer to caption', 'add answer info to a sample by converting caption_str and ref_strs to byte tensors', 'review the TextCapsDataset class and its methods for TextCaps dataset preprocessing and evaluation']
```

Usage

```
{'build_textcaps_dataset': 'build a TextCapsBuilder to load the TextCaps dataset with default configuration', 'build_textcaps_coco_style': 'build a TextCapsBuilder with coco annotation style to load dataset using COCODataset class', 'review_TextCapsBuilder_config_path': 'review the TextCapsBuilder config_path method to get the defaults.yaml config location', 'review_TextCapsBuilder_load': 'review the TextCapsBuilder load method to understand annotation style switching logic', 'test_TextCapsBuilder_init': 'test the TextCapsBuilder __init__ to verify dataset_name and dataset_class defaults'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/textcaps/dataset.py

Prompts

```
['build a TextCapsBuilder to load the TextCaps dataset with default configuration', 'build a TextCapsBuilder with coco annotation style to load dataset using COCODataset class', 'review the TextCapsBuilder config_path method to get the defaults.yaml config location', 'review the TextCapsBuilder load method to understand annotation style switching logic', 'test the TextCapsBuilder __init__ to verify dataset_name and dataset_class defaults', 'preprocess sample info by adding dummy empty questions and mapping caption_id to question_id', 'postprocess an EvalAI entry by remapping question_id to caption_id and answer to caption', 'add answer info to a sample by converting caption_str and ref_strs to byte tensors', 'review the TextCapsDataset class and its methods for TextCaps dataset preprocessing and evaluation']
```

Usage

```
{'build_textcaps_dataset': 'build a TextCapsDataset instance by extending TextVQADataset with textcaps-specific dataset name', 'preprocess_sample_info': 'preprocess sample info by adding dummy empty questions and mapping caption_id to question_id', 'postprocess_evalai_entry': 'postprocess an EvalAI entry by remapping question_id to caption_id and answer to caption', 'add_answer_info': 'add answer info to a sample by converting caption_str and ref_strs to byte tensors', 'review_textcaps_dataset_class': 'review the TextCapsDataset class and its methods for TextCaps dataset preprocessing and evaluation'}
```

