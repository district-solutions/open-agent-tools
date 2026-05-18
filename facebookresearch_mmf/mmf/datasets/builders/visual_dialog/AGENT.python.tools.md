# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/visual_dialog/builder.py

Prompts

```
['build a visual dialog dataset by downloading imdb, vocabs, and features for training', 'create a VisualDialogBuilder instance to register and configure the visual dialog dataset builder', 'get the default YAML config path for the visual dialog dataset from the builder class', 'download and extract imdb data for a specific dataset type like train, val, or test', 'download and extract visual dialog and COCO features for the dataset into the data folder', 'create a VisualDialogDatabase instance by passing a JSON imdb file path to the constructor', 'load a JSON imdb file containing questions, answers, and dialogs into a PyTorch Dataset', 'get a specific dialog round by index using the __getitem__ method on VisualDialogDatabase', 'review the VisualDialogDatabase __init__ method to understand how it loads JSON and sets metadata', 'refactor the VisualDialogDatabase __getitem__ method to fix the missing return statement and incomplete answers assignment']
```

Usage

```
{'build_visual_dialog_dataset': 'build a visual dialog dataset by downloading imdb, vocabs, and features for training', 'create_visual_dialog_builder': 'create a VisualDialogBuilder instance to register and configure the visual dialog dataset builder', 'get_config_path': 'get the default YAML config path for the visual dialog dataset from the builder class', 'download_imdb_data': 'download and extract imdb data for a specific dataset type like train, val, or test', 'download_features': 'download and extract visual dialog and COCO features for the dataset into the data folder'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/visual_dialog/database.py

Prompts

```
['build a visual dialog dataset by downloading imdb, vocabs, and features for training', 'create a VisualDialogBuilder instance to register and configure the visual dialog dataset builder', 'get the default YAML config path for the visual dialog dataset from the builder class', 'download and extract imdb data for a specific dataset type like train, val, or test', 'download and extract visual dialog and COCO features for the dataset into the data folder', 'create a VisualDialogDatabase instance by passing a JSON imdb file path to the constructor', 'load a JSON imdb file containing questions, answers, and dialogs into a PyTorch Dataset', 'get a specific dialog round by index using the __getitem__ method on VisualDialogDatabase', 'review the VisualDialogDatabase __init__ method to understand how it loads JSON and sets metadata', 'refactor the VisualDialogDatabase __getitem__ method to fix the missing return statement and incomplete answers assignment']
```

Usage

```
{'create_VisualDialogDataset': 'create a VisualDialogDatabase instance by passing a JSON imdb file path to the constructor', 'load_json_dialogs': 'load a JSON imdb file containing questions, answers, and dialogs into a PyTorch Dataset', 'get_dialog_round': 'get a specific dialog round by index using the __getitem__ method on VisualDialogDatabase', 'review_VisualDialogDatabase_init': 'review the VisualDialogDatabase __init__ method to understand how it loads JSON and sets metadata', 'refactor_VisualDialogDatabase_getitem': 'refactor the VisualDialogDatabase __getitem__ method to fix the missing return statement and incomplete answers assignment'}
```

