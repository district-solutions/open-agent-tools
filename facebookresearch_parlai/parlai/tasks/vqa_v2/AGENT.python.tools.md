# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/vqa_v2/agents.py

Prompts

```
['run the VQA v2.0 Open-Ended teacher to load questions and annotations from JSON data files', 'create a teacher action dict with question text, image ID, and answer labels for an episode', 'run the next example method to queue up the next VQA example with background image loading', 'run the AllTeacher act method to get VQA actions with multiple choice answer labels included', 'review the OeTeacher _setup_data method that loads VQA questions and annotations from JSON files', 'run the build function to download and set up the VQA-v2 dataset files', 'download the VQA-v2 train val and test question and annotation zip files', 'check if the VQA-v2 dataset has already been built in the datapath directory', 'remove outdated VQA-v2 dataset files before rebuilding the data directory', 'summarize the build function that downloads VQA-v2 resources and marks data as built']
```

Usage

```
{'run_OeTeacher': 'run the VQA v2.0 Open-Ended teacher to load questions and annotations from JSON data files', 'create_OeTeacher_get': 'create a teacher action dict with question text, image ID, and answer labels for an episode', 'run_OeTeacher_next_example': 'run the next example method to queue up the next VQA example with background image loading', 'run_AllTeacher_act': 'run the AllTeacher act method to get VQA actions with multiple choice answer labels included', 'review_OeTeacher_setup_data': 'review the OeTeacher _setup_data method that loads VQA questions and annotations from JSON files'}
```

## File: facebookresearch_parlai/parlai/tasks/vqa_v2/build.py

Prompts

```
['run the VQA v2.0 Open-Ended teacher to load questions and annotations from JSON data files', 'create a teacher action dict with question text, image ID, and answer labels for an episode', 'run the next example method to queue up the next VQA example with background image loading', 'run the AllTeacher act method to get VQA actions with multiple choice answer labels included', 'review the OeTeacher _setup_data method that loads VQA questions and annotations from JSON files', 'run the build function to download and set up the VQA-v2 dataset files', 'download the VQA-v2 train val and test question and annotation zip files', 'check if the VQA-v2 dataset has already been built in the datapath directory', 'remove outdated VQA-v2 dataset files before rebuilding the data directory', 'summarize the build function that downloads VQA-v2 resources and marks data as built']
```

Usage

```
{'build_vqa_v2_dataset': 'run the build function to download and set up the VQA-v2 dataset files', 'download_vqa_v2_resources': 'download the VQA-v2 train val and test question and annotation zip files', 'check_vqa_v2_built': 'check if the VQA-v2 dataset has already been built in the datapath directory', 'remove_vqa_v2_outdated': 'remove outdated VQA-v2 dataset files before rebuilding the data directory', 'summarize_build_function': 'summarize the build function that downloads VQA-v2 resources and marks data as built'}
```

