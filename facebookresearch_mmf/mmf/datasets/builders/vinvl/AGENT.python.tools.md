# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/vinvl/builder.py

Prompts

```
['build a VinVL dataset by instantiating a base dataset and wrapping it with augmented samples', 'load the VinVL builder with config and dataset type to get a VinVLDataset instance', 'get the default config path for the VinVL dataset builder returning defaults.yaml', 'review the VinVLBuilder __init__ method to understand dataset name and class initialization', 'refactor the VinVLBuilder load method to support additional base dataset types beyond vqa2', 'create a VinVLDataset and set a base dataset using set_base_dataset to enable augmented sample retrieval', 'test the load_item method to verify it returns augmented samples with random captions and labels', 'review the get_label_str method to understand how it converts image label IDs to human-readable label strings', 'summarize the load_label_map method that loads and parses a JSON label map file for VinVL object detection']
```

Usage

```
{'build_vinvl_dataset': 'build a VinVL dataset by instantiating a base dataset and wrapping it with augmented samples', 'load_vinvl_builder': 'load the VinVL builder with config and dataset type to get a VinVLDataset instance', 'get_vinvl_config_path': 'get the default config path for the VinVL dataset builder returning defaults.yaml', 'review_VinVLBuilder_init': 'review the VinVLBuilder __init__ method to understand dataset name and class initialization', 'refactor_VinVLBuilder_load': 'refactor the VinVLBuilder load method to support additional base dataset types beyond vqa2'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/vinvl/dataset.py

Prompts

```
['build a VinVL dataset by instantiating a base dataset and wrapping it with augmented samples', 'load the VinVL builder with config and dataset type to get a VinVLDataset instance', 'get the default config path for the VinVL dataset builder returning defaults.yaml', 'review the VinVLBuilder __init__ method to understand dataset name and class initialization', 'refactor the VinVLBuilder load method to support additional base dataset types beyond vqa2', 'create a VinVLDataset and set a base dataset using set_base_dataset to enable augmented sample retrieval', 'test the load_item method to verify it returns augmented samples with random captions and labels', 'review the get_label_str method to understand how it converts image label IDs to human-readable label strings', 'summarize the load_label_map method that loads and parses a JSON label map file for VinVL object detection']
```

Usage

```
{'build_vinvl_dataset': 'build a VinVLDataset instance that augments a base dataset with random captions and labels for VinVL finetuning', 'create_vinvl_dataset_with_base': 'create a VinVLDataset and set a base dataset using set_base_dataset to enable augmented sample retrieval', 'test_load_item_augmentation': 'test the load_item method to verify it returns augmented samples with random captions and labels', 'review_get_label_str': 'review the get_label_str method to understand how it converts image label IDs to human-readable label strings', 'summarize_load_label_map': 'summarize the load_label_map method that loads and parses a JSON label map file for VinVL object detection'}
```

