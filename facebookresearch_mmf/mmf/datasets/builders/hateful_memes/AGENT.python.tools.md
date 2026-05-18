# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/hateful_memes/builder.py

Prompts

```
['build the hateful memes dataset by verifying data directory and calling parent build method', 'load the hateful memes dataset switching to features dataset when use_features config is true', 'get the default config path for the hateful memes dataset builder', 'register the text vocabulary size and number of final outputs in the MMF registry', 'review the HatefulMemesBuilder class and its dataset loading and building methods', 'build a HatefulMemesFeaturesDataset instance from config to load hateful memes features and text samples', 'build a HatefulMemesImageDataset instance from config to load raw images and text for hateful memes classification', 'test the process_fg_labels method to map fine-grained attack and protected category labels on samples', 'review the generate_binary_prediction function that converts model scores into binary hateful or not hateful labels', 'review the generate_multilabel_prediction function that applies sigmoid scores for multi-label hateful memes classification']
```

Usage

```
{'build_hateful_memes_dataset': 'build the hateful memes dataset by verifying data directory and calling parent build method', 'load_hateful_memes_with_features': 'load the hateful memes dataset switching to features dataset when use_features config is true', 'get_hateful_memes_config_path': 'get the default config path for the hateful memes dataset builder', 'register_hateful_memes_vocab_size': 'register the text vocabulary size and number of final outputs in the MMF registry', 'review_HatefulMemesBuilder': 'review the HatefulMemesBuilder class and its dataset loading and building methods'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/hateful_memes/dataset.py

Prompts

```
['build the hateful memes dataset by verifying data directory and calling parent build method', 'load the hateful memes dataset switching to features dataset when use_features config is true', 'get the default config path for the hateful memes dataset builder', 'register the text vocabulary size and number of final outputs in the MMF registry', 'review the HatefulMemesBuilder class and its dataset loading and building methods', 'build a HatefulMemesFeaturesDataset instance from config to load hateful memes features and text samples', 'build a HatefulMemesImageDataset instance from config to load raw images and text for hateful memes classification', 'test the process_fg_labels method to map fine-grained attack and protected category labels on samples', 'review the generate_binary_prediction function that converts model scores into binary hateful or not hateful labels', 'review the generate_multilabel_prediction function that applies sigmoid scores for multi-label hateful memes classification']
```

Usage

```
{'build_HatefulMemesFeaturesDataset': 'build a HatefulMemesFeaturesDataset instance from config to load hateful memes features and text samples', 'build_HatefulMemesImageDataset': 'build a HatefulMemesImageDataset instance from config to load raw images and text for hateful memes classification', 'test_process_fg_labels': 'test the process_fg_labels method to map fine-grained attack and protected category labels on samples', 'review_generate_binary_prediction': 'review the generate_binary_prediction function that converts model scores into binary hateful or not hateful labels', 'review_generate_multilabel_prediction': 'review the generate_multilabel_prediction function that applies sigmoid scores for multi-label hateful memes classification'}
```

