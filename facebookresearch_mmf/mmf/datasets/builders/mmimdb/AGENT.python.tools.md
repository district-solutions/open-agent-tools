# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/mmimdb/builder.py

Prompts

```
['build a python module that creates an MMIMDbBuilder instance to load MMIMDb datasets', 'create a function that returns the default config path for the MMIMDb dataset', 'test the MMIMDbBuilder load method with a config object and dataset type', 'refactor the MMIMDbBuilder load method to support additional dataset class selection logic', 'review the MMIMDbBuilder class and its inheritance from VQA2Builder for dataset loading', 'build a MMIMDbFeaturesDataset class to load movie plot text and visual features for multimodal training', 'build a MMIMDbImageDataset class to load movie plot text and raw images for multimodal training', 'review the MMIMDbFeaturesDataset __getitem__ method to understand how it processes plot text and genre labels', 'review the MMIMDbImageDataset init_processors method to see how image transforms are assigned', 'refactor the MMIMDbFeaturesDataset __getitem__ to customize transformer bbox processing for image_info_0 features', 'build a masked multimodal IMDB dataset builder registered under the name masked_mmimdb in MMF', 'create a MaskedMMImdbBuilder instance that extends VQA2Builder with masked_mmimdb as the dataset name', 'review the MaskedMMImdbBuilder config_path method that returns configs/datasets/mmimdb/masked.yaml', 'test that MaskedMMImdbBuilder is registered in the MMF registry under the key masked_mmimdb', 'refactor the MaskedMMImdbBuilder to use a different dataset class instead of MaskedMMImdbDataset', 'create a Sample with image features and masked question tokens by calling load_item with an index', 'test the _add_masked_question method to verify plot and genre tokenization via masked_token_processor', 'review the MaskedMMImdbDataset init to understand config options like add_answer and use_image_feature_masks', 'refactor the _add_masked_question method to customize how text_a and text_b are passed to masked_token_processor']
```

Usage

```
{'build_MMIMDbBuilder': 'build a python module that creates an MMIMDbBuilder instance to load MMIMDb datasets', 'create_MMIMDbBuilder_config_path': 'create a function that returns the default config path for the MMIMDb dataset', 'test_MMIMDbBuilder_load': 'test the MMIMDbBuilder load method with a config object and dataset type', 'refactor_MMIMDbBuilder_load': 'refactor the MMIMDbBuilder load method to support additional dataset class selection logic', 'review_MMIMDbBuilder': 'review the MMIMDbBuilder class and its inheritance from VQA2Builder for dataset loading'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/mmimdb/dataset.py

Prompts

```
['build a python module that creates an MMIMDbBuilder instance to load MMIMDb datasets', 'create a function that returns the default config path for the MMIMDb dataset', 'test the MMIMDbBuilder load method with a config object and dataset type', 'refactor the MMIMDbBuilder load method to support additional dataset class selection logic', 'review the MMIMDbBuilder class and its inheritance from VQA2Builder for dataset loading', 'build a MMIMDbFeaturesDataset class to load movie plot text and visual features for multimodal training', 'build a MMIMDbImageDataset class to load movie plot text and raw images for multimodal training', 'review the MMIMDbFeaturesDataset __getitem__ method to understand how it processes plot text and genre labels', 'review the MMIMDbImageDataset init_processors method to see how image transforms are assigned', 'refactor the MMIMDbFeaturesDataset __getitem__ to customize transformer bbox processing for image_info_0 features', 'build a masked multimodal IMDB dataset builder registered under the name masked_mmimdb in MMF', 'create a MaskedMMImdbBuilder instance that extends VQA2Builder with masked_mmimdb as the dataset name', 'review the MaskedMMImdbBuilder config_path method that returns configs/datasets/mmimdb/masked.yaml', 'test that MaskedMMImdbBuilder is registered in the MMF registry under the key masked_mmimdb', 'refactor the MaskedMMImdbBuilder to use a different dataset class instead of MaskedMMImdbDataset', 'create a Sample with image features and masked question tokens by calling load_item with an index', 'test the _add_masked_question method to verify plot and genre tokenization via masked_token_processor', 'review the MaskedMMImdbDataset init to understand config options like add_answer and use_image_feature_masks', 'refactor the _add_masked_question method to customize how text_a and text_b are passed to masked_token_processor']
```

Usage

```
{'build_MMIMDbFeaturesDataset': 'build a MMIMDbFeaturesDataset class to load movie plot text and visual features for multimodal training', 'build_MMIMDbImageDataset': 'build a MMIMDbImageDataset class to load movie plot text and raw images for multimodal training', 'review_MMIMDbFeaturesDataset_getitem': 'review the MMIMDbFeaturesDataset __getitem__ method to understand how it processes plot text and genre labels', 'review_MMIMDbImageDataset_init_processors': 'review the MMIMDbImageDataset init_processors method to see how image transforms are assigned', 'refactor_MMIMDbFeaturesDataset_bbox': 'refactor the MMIMDbFeaturesDataset __getitem__ to customize transformer bbox processing for image_info_0 features'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/mmimdb/masked_builder.py

Prompts

```
['build a python module that creates an MMIMDbBuilder instance to load MMIMDb datasets', 'create a function that returns the default config path for the MMIMDb dataset', 'test the MMIMDbBuilder load method with a config object and dataset type', 'refactor the MMIMDbBuilder load method to support additional dataset class selection logic', 'review the MMIMDbBuilder class and its inheritance from VQA2Builder for dataset loading', 'build a MMIMDbFeaturesDataset class to load movie plot text and visual features for multimodal training', 'build a MMIMDbImageDataset class to load movie plot text and raw images for multimodal training', 'review the MMIMDbFeaturesDataset __getitem__ method to understand how it processes plot text and genre labels', 'review the MMIMDbImageDataset init_processors method to see how image transforms are assigned', 'refactor the MMIMDbFeaturesDataset __getitem__ to customize transformer bbox processing for image_info_0 features', 'build a masked multimodal IMDB dataset builder registered under the name masked_mmimdb in MMF', 'create a MaskedMMImdbBuilder instance that extends VQA2Builder with masked_mmimdb as the dataset name', 'review the MaskedMMImdbBuilder config_path method that returns configs/datasets/mmimdb/masked.yaml', 'test that MaskedMMImdbBuilder is registered in the MMF registry under the key masked_mmimdb', 'refactor the MaskedMMImdbBuilder to use a different dataset class instead of MaskedMMImdbDataset', 'create a Sample with image features and masked question tokens by calling load_item with an index', 'test the _add_masked_question method to verify plot and genre tokenization via masked_token_processor', 'review the MaskedMMImdbDataset init to understand config options like add_answer and use_image_feature_masks', 'refactor the _add_masked_question method to customize how text_a and text_b are passed to masked_token_processor']
```

Usage

```
{'build_masked_mmimdb_dataset': 'build a masked multimodal IMDB dataset builder registered under the name masked_mmimdb in MMF', 'create_masked_mmimdb_builder': 'create a MaskedMMImdbBuilder instance that extends VQA2Builder with masked_mmimdb as the dataset name', 'review_config_path': 'review the MaskedMMImdbBuilder config_path method that returns configs/datasets/mmimdb/masked.yaml', 'test_masked_mmimdb_registration': 'test that MaskedMMImdbBuilder is registered in the MMF registry under the key masked_mmimdb', 'refactor_masked_mmimdb_dataset_class': 'refactor the MaskedMMImdbBuilder to use a different dataset class instead of MaskedMMImdbDataset'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/mmimdb/masked_dataset.py

Prompts

```
['build a python module that creates an MMIMDbBuilder instance to load MMIMDb datasets', 'create a function that returns the default config path for the MMIMDb dataset', 'test the MMIMDbBuilder load method with a config object and dataset type', 'refactor the MMIMDbBuilder load method to support additional dataset class selection logic', 'review the MMIMDbBuilder class and its inheritance from VQA2Builder for dataset loading', 'build a MMIMDbFeaturesDataset class to load movie plot text and visual features for multimodal training', 'build a MMIMDbImageDataset class to load movie plot text and raw images for multimodal training', 'review the MMIMDbFeaturesDataset __getitem__ method to understand how it processes plot text and genre labels', 'review the MMIMDbImageDataset init_processors method to see how image transforms are assigned', 'refactor the MMIMDbFeaturesDataset __getitem__ to customize transformer bbox processing for image_info_0 features', 'build a masked multimodal IMDB dataset builder registered under the name masked_mmimdb in MMF', 'create a MaskedMMImdbBuilder instance that extends VQA2Builder with masked_mmimdb as the dataset name', 'review the MaskedMMImdbBuilder config_path method that returns configs/datasets/mmimdb/masked.yaml', 'test that MaskedMMImdbBuilder is registered in the MMF registry under the key masked_mmimdb', 'refactor the MaskedMMImdbBuilder to use a different dataset class instead of MaskedMMImdbDataset', 'create a Sample with image features and masked question tokens by calling load_item with an index', 'test the _add_masked_question method to verify plot and genre tokenization via masked_token_processor', 'review the MaskedMMImdbDataset init to understand config options like add_answer and use_image_feature_masks', 'refactor the _add_masked_question method to customize how text_a and text_b are passed to masked_token_processor']
```

Usage

```
{'build_masked_mmimdb_dataset': 'build a MaskedMMImdbDataset instance from config and imdb_file_index for masked language modeling on movie plots', 'create_load_item_sample': 'create a Sample with image features and masked question tokens by calling load_item with an index', 'test_masked_question_processing': 'test the _add_masked_question method to verify plot and genre tokenization via masked_token_processor', 'review_masked_mmimdb_init': 'review the MaskedMMImdbDataset init to understand config options like add_answer and use_image_feature_masks', 'refactor_masked_token_processor': 'refactor the _add_masked_question method to customize how text_a and text_b are passed to masked_token_processor'}
```

