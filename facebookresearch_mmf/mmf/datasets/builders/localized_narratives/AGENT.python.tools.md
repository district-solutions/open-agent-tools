# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/localized_narratives/database.py

Prompts

```
['create a TimedPoint NamedTuple with x, y coordinates and a time value', 'create a TimedUtterance NamedTuple with utterance text and start and end time values', 'create a LocalizedNarrative NamedTuple with dataset_id, image_id, caption, timed captions, and traces', 'load a JSONL file of localized narrative annotations into an annotation database', 'compute the feature file path for an image with MSCOCO zero-padding support', 'build a MaskedLocalizedNarrativesBuilder to download and prepare masked localized narratives dataset resources', 'create a MaskedLocalizedNarrativesBuilder instance with a custom dataset name and dataset class', 'review the MaskedLocalizedNarrativesBuilder config_path method to get the YAML config location', 'test the MaskedLocalizedNarrativesBuilder build method to download dataset requirements from the zoo config', 'summarize the MaskedLocalizedNarrativesBuilder class registered under masked_localized_narratives in the MMF registry', 'build a LocalizedNarrativesAnnotationDatabase from config and annotation path using the dataset mixin', 'retrieve a Sample with masked caption, image ID, and features by index from the dataset', 'initialize image processor transforms on the image database when using images mode', 'create a MaskedLocalizedNarrativesDataset instance with config, dataset type, and index parameters', 'review the masked token processor that processes caption text with text_a and is_correct fields']
```

Usage

```
{'create_TimedPoint': 'create a TimedPoint NamedTuple with x, y coordinates and a time value', 'create_TimedUtterance': 'create a TimedUtterance NamedTuple with utterance text and start and end time values', 'create_LocalizedNarrative': 'create a LocalizedNarrative NamedTuple with dataset_id, image_id, caption, timed captions, and traces', 'load_LocalizedNarrativesAnnotationDatabase': 'load a JSONL file of localized narrative annotations into an annotation database', 'compute_feature_path': 'compute the feature file path for an image with MSCOCO zero-padding support'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/localized_narratives/masked_builder.py

Prompts

```
['create a TimedPoint NamedTuple with x, y coordinates and a time value', 'create a TimedUtterance NamedTuple with utterance text and start and end time values', 'create a LocalizedNarrative NamedTuple with dataset_id, image_id, caption, timed captions, and traces', 'load a JSONL file of localized narrative annotations into an annotation database', 'compute the feature file path for an image with MSCOCO zero-padding support', 'build a MaskedLocalizedNarrativesBuilder to download and prepare masked localized narratives dataset resources', 'create a MaskedLocalizedNarrativesBuilder instance with a custom dataset name and dataset class', 'review the MaskedLocalizedNarrativesBuilder config_path method to get the YAML config location', 'test the MaskedLocalizedNarrativesBuilder build method to download dataset requirements from the zoo config', 'summarize the MaskedLocalizedNarrativesBuilder class registered under masked_localized_narratives in the MMF registry', 'build a LocalizedNarrativesAnnotationDatabase from config and annotation path using the dataset mixin', 'retrieve a Sample with masked caption, image ID, and features by index from the dataset', 'initialize image processor transforms on the image database when using images mode', 'create a MaskedLocalizedNarrativesDataset instance with config, dataset type, and index parameters', 'review the masked token processor that processes caption text with text_a and is_correct fields']
```

Usage

```
{'build_masked_localized_narratives_dataset': 'build a MaskedLocalizedNarrativesBuilder to download and prepare masked localized narratives dataset resources', 'create_masked_builder_instance': 'create a MaskedLocalizedNarrativesBuilder instance with a custom dataset name and dataset class', 'review_config_path': 'review the MaskedLocalizedNarrativesBuilder config_path method to get the YAML config location', 'test_masked_dataset_builder': 'test the MaskedLocalizedNarrativesBuilder build method to download dataset requirements from the zoo config', 'summarize_masked_builder_class': 'summarize the MaskedLocalizedNarrativesBuilder class registered under masked_localized_narratives in the MMF registry'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/localized_narratives/masked_dataset.py

Prompts

```
['create a TimedPoint NamedTuple with x, y coordinates and a time value', 'create a TimedUtterance NamedTuple with utterance text and start and end time values', 'create a LocalizedNarrative NamedTuple with dataset_id, image_id, caption, timed captions, and traces', 'load a JSONL file of localized narrative annotations into an annotation database', 'compute the feature file path for an image with MSCOCO zero-padding support', 'build a MaskedLocalizedNarrativesBuilder to download and prepare masked localized narratives dataset resources', 'create a MaskedLocalizedNarrativesBuilder instance with a custom dataset name and dataset class', 'review the MaskedLocalizedNarrativesBuilder config_path method to get the YAML config location', 'test the MaskedLocalizedNarrativesBuilder build method to download dataset requirements from the zoo config', 'summarize the MaskedLocalizedNarrativesBuilder class registered under masked_localized_narratives in the MMF registry', 'build a LocalizedNarrativesAnnotationDatabase from config and annotation path using the dataset mixin', 'retrieve a Sample with masked caption, image ID, and features by index from the dataset', 'initialize image processor transforms on the image database when using images mode', 'create a MaskedLocalizedNarrativesDataset instance with config, dataset type, and index parameters', 'review the masked token processor that processes caption text with text_a and is_correct fields']
```

Usage

```
{'build_annotation_db': 'build a LocalizedNarrativesAnnotationDatabase from config and annotation path using the dataset mixin', 'getitem_sample': 'retrieve a Sample with masked caption, image ID, and features by index from the dataset', 'init_processors': 'initialize image processor transforms on the image database when using images mode', 'create_masked_dataset': 'create a MaskedLocalizedNarrativesDataset instance with config, dataset type, and index parameters', 'review_masked_token_processor': 'review the masked token processor that processes caption text with text_a and is_correct fields'}
```

