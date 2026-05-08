# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/convai_chitchat/agents.py

Prompts

```
['build and download the ConvAI ChitChat dataset using the ParlAI build function', 'create learning examples by zipping opponent utterances with answer utterances from a dialog', 'fold consecutive utterances from the same user into a single text entry in a dialog', 'generate training examples for both users from a list of dialog threads with context', 'load a JSON file of dialogs and return a generator of learning examples', 'download the Turing conversational dataset tar.gz file using the RESOURCES list of DownloadableFile objects', 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check if the ConvAI ChitChat dataset has already been built using build_data.built with a version string', 'review the build function that manages downloading, extracting, and versioning the ConvAI ChitChat dataset']
```

Usage

```
{'build_convai_chitchat_data': 'build and download the ConvAI ChitChat dataset using the ParlAI build function', 'create_learning_examples_from_dialogs': 'create learning examples by zipping opponent utterances with answer utterances from a dialog', 'fold_consecutive_utterances': 'fold consecutive utterances from the same user into a single text entry in a dialog', 'generate_training_data_from_dialogs': 'generate training examples for both users from a list of dialog threads with context', 'load_and_parse_dialog_json': 'load a JSON file of dialogs and return a generator of learning examples'}
```

## File: facebookresearch_parlai/parlai/tasks/convai_chitchat/build.py

Prompts

```
['build and download the ConvAI ChitChat dataset using the ParlAI build function', 'create learning examples by zipping opponent utterances with answer utterances from a dialog', 'fold consecutive utterances from the same user into a single text entry in a dialog', 'generate training examples for both users from a list of dialog threads with context', 'load a JSON file of dialogs and return a generator of learning examples', 'download the Turing conversational dataset tar.gz file using the RESOURCES list of DownloadableFile objects', 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check if the ConvAI ChitChat dataset has already been built using build_data.built with a version string', 'review the build function that manages downloading, extracting, and versioning the ConvAI ChitChat dataset']
```

Usage

```
{'build_convai_chitchat_data': 'run the build function to download and prepare the ConvAI ChitChat dataset for ParlAI', 'download_convai_chitchat_resources': 'download the Turing conversational dataset tar.gz file using the RESOURCES list of DownloadableFile objects', 'rename_convai_chitchat_json_files': 'rename the downloaded data_train and data_test JSON files to train.json and test.json', 'check_convai_chitchat_data_built': 'check if the ConvAI ChitChat dataset has already been built using build_data.built with a version string', 'review_build_function': 'review the build function that manages downloading, extracting, and versioning the ConvAI ChitChat dataset'}
```

