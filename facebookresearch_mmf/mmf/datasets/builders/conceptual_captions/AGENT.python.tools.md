# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/conceptual_captions/builder.py

Prompts

```
['build a ConceptualCaptionsBuilder to load and register the conceptual_captions dataset for MMF training', 'create a ConceptualCaptionsBuilder instance that extends COCOBuilder with conceptual_captions as the dataset name', 'review the ConceptualCaptionsBuilder config_path method that returns the defaults YAML path for conceptual_captions', 'test the ConceptualCaptionsBuilder init method that sets ConceptualCaptionsDataset as the dataset class', 'summarize the ConceptualCaptionsBuilder class that registers conceptual_captions with the MMF registry and inherits from COCOBuilder', 'load a single Conceptual Captions sample by index with processed text and image features', 'review the ConceptualCaptionsDataset constructor to understand config and dataset type initialization', 'review the load_item method to understand how samples are processed with text and image features', 'summarize the ConceptualCaptionsDataset class that extends COCODataset for loading image-caption pairs', 'build a masked conceptual captions dataset using MaskedConceptualCaptionsBuilder registered in MMF', 'create a MaskedConceptualCaptionsBuilder instance that sets dataset_name and configures MaskedConceptualCaptionsDataset', 'review the config_path classmethod that returns the masked conceptual captions YAML config path', 'refactor MaskedConceptualCaptionsBuilder to customize behavior inherited from MaskedCOCOBuilder', 'test that MaskedConceptualCaptionsBuilder is registered under masked_conceptual_captions in the MMF registry']
```

Usage

```
{'build_conceptual_captions_dataset': 'build a ConceptualCaptionsBuilder to load and register the conceptual_captions dataset for MMF training', 'create_conceptual_captions_builder': 'create a ConceptualCaptionsBuilder instance that extends COCOBuilder with conceptual_captions as the dataset name', 'review_config_path': 'review the ConceptualCaptionsBuilder config_path method that returns the defaults YAML path for conceptual_captions', 'test_set_dataset_class': 'test the ConceptualCaptionsBuilder init method that sets ConceptualCaptionsDataset as the dataset class', 'summarize_conceptual_captions_builder': 'summarize the ConceptualCaptionsBuilder class that registers conceptual_captions with the MMF registry and inherits from COCOBuilder'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/conceptual_captions/dataset.py

Prompts

```
['build a ConceptualCaptionsBuilder to load and register the conceptual_captions dataset for MMF training', 'create a ConceptualCaptionsBuilder instance that extends COCOBuilder with conceptual_captions as the dataset name', 'review the ConceptualCaptionsBuilder config_path method that returns the defaults YAML path for conceptual_captions', 'test the ConceptualCaptionsBuilder init method that sets ConceptualCaptionsDataset as the dataset class', 'summarize the ConceptualCaptionsBuilder class that registers conceptual_captions with the MMF registry and inherits from COCOBuilder', 'load a single Conceptual Captions sample by index with processed text and image features', 'review the ConceptualCaptionsDataset constructor to understand config and dataset type initialization', 'review the load_item method to understand how samples are processed with text and image features', 'summarize the ConceptualCaptionsDataset class that extends COCODataset for loading image-caption pairs', 'build a masked conceptual captions dataset using MaskedConceptualCaptionsBuilder registered in MMF', 'create a MaskedConceptualCaptionsBuilder instance that sets dataset_name and configures MaskedConceptualCaptionsDataset', 'review the config_path classmethod that returns the masked conceptual captions YAML config path', 'refactor MaskedConceptualCaptionsBuilder to customize behavior inherited from MaskedCOCOBuilder', 'test that MaskedConceptualCaptionsBuilder is registered under masked_conceptual_captions in the MMF registry']
```

Usage

```
{'build_conceptual_captions_dataset': 'build a ConceptualCaptionsDataset instance from config and dataset type for image captioning tasks', 'load_item_conceptual_captions': 'load a single Conceptual Captions sample by index with processed text and image features', 'review_ConceptualCaptionsDataset_init': 'review the ConceptualCaptionsDataset constructor to understand config and dataset type initialization', 'review_ConceptualCaptionsDataset_load_item': 'review the load_item method to understand how samples are processed with text and image features', 'summarize_ConceptualCaptionsDataset': 'summarize the ConceptualCaptionsDataset class that extends COCODataset for loading image-caption pairs'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/conceptual_captions/masked_builder.py

Prompts

```
['build a ConceptualCaptionsBuilder to load and register the conceptual_captions dataset for MMF training', 'create a ConceptualCaptionsBuilder instance that extends COCOBuilder with conceptual_captions as the dataset name', 'review the ConceptualCaptionsBuilder config_path method that returns the defaults YAML path for conceptual_captions', 'test the ConceptualCaptionsBuilder init method that sets ConceptualCaptionsDataset as the dataset class', 'summarize the ConceptualCaptionsBuilder class that registers conceptual_captions with the MMF registry and inherits from COCOBuilder', 'load a single Conceptual Captions sample by index with processed text and image features', 'review the ConceptualCaptionsDataset constructor to understand config and dataset type initialization', 'review the load_item method to understand how samples are processed with text and image features', 'summarize the ConceptualCaptionsDataset class that extends COCODataset for loading image-caption pairs', 'build a masked conceptual captions dataset using MaskedConceptualCaptionsBuilder registered in MMF', 'create a MaskedConceptualCaptionsBuilder instance that sets dataset_name and configures MaskedConceptualCaptionsDataset', 'review the config_path classmethod that returns the masked conceptual captions YAML config path', 'refactor MaskedConceptualCaptionsBuilder to customize behavior inherited from MaskedCOCOBuilder', 'test that MaskedConceptualCaptionsBuilder is registered under masked_conceptual_captions in the MMF registry']
```

Usage

```
{'build_masked_conceptual_captions_dataset': 'build a masked conceptual captions dataset using MaskedConceptualCaptionsBuilder registered in MMF', 'create_masked_builder_instance': 'create a MaskedConceptualCaptionsBuilder instance that sets dataset_name and configures MaskedConceptualCaptionsDataset', 'review_config_path_method': 'review the config_path classmethod that returns the masked conceptual captions YAML config path', 'refactor_masked_builder_inheritance': 'refactor MaskedConceptualCaptionsBuilder to customize behavior inherited from MaskedCOCOBuilder', 'test_masked_dataset_registration': 'test that MaskedConceptualCaptionsBuilder is registered under masked_conceptual_captions in the MMF registry'}
```

