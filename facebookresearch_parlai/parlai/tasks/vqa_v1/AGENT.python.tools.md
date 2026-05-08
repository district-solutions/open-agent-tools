# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/vqa_v1/agents.py

Prompts

```
['build a VQA dictionary agent that tokenizes questions and answers with frequency tracking', 'create an open-ended VQA teacher that loads JSON data and serves question-answer examples', 'create a multiple-choice VQA teacher that provides label candidates alongside question-answer pairs', 'create a VQA teacher that provides both open-ended labels and multiple-choice candidates', 'run the MCB tokenizer on a question string to produce a cleaned token list', 'run the build function to download and prepare the VQA-v1 dataset into the specified datapath', 'download the VQA-v1 Questions and Annotations zip files for train, val, and test splits', 'check whether the VQA-v1 dataset has already been built in the given datapath directory', 'remove an older version of the VQA-v1 dataset directory before rebuilding', 'review the build function that downloads VQA-v1 MS COCO data and marks the directory as done']
```

Usage

```
{'build_VqaDictionaryAgent': 'build a VQA dictionary agent that tokenizes questions and answers with frequency tracking', 'create_OeTeacher': 'create an open-ended VQA teacher that loads JSON data and serves question-answer examples', 'create_McTeacher': 'create a multiple-choice VQA teacher that provides label candidates alongside question-answer pairs', 'create_AllTeacher': 'create a VQA teacher that provides both open-ended labels and multiple-choice candidates', 'run_tokenize_mcb': 'run the MCB tokenizer on a question string to produce a cleaned token list'}
```

## File: facebookresearch_parlai/parlai/tasks/vqa_v1/build.py

Prompts

```
['build a VQA dictionary agent that tokenizes questions and answers with frequency tracking', 'create an open-ended VQA teacher that loads JSON data and serves question-answer examples', 'create a multiple-choice VQA teacher that provides label candidates alongside question-answer pairs', 'create a VQA teacher that provides both open-ended labels and multiple-choice candidates', 'run the MCB tokenizer on a question string to produce a cleaned token list', 'run the build function to download and prepare the VQA-v1 dataset into the specified datapath', 'download the VQA-v1 Questions and Annotations zip files for train, val, and test splits', 'check whether the VQA-v1 dataset has already been built in the given datapath directory', 'remove an older version of the VQA-v1 dataset directory before rebuilding', 'review the build function that downloads VQA-v1 MS COCO data and marks the directory as done']
```

Usage

```
{'build_vqa_v1_dataset': 'run the build function to download and prepare the VQA-v1 dataset into the specified datapath', 'download_vqa_v1_resources': 'download the VQA-v1 Questions and Annotations zip files for train, val, and test splits', 'check_vqa_v1_built_status': 'check whether the VQA-v1 dataset has already been built in the given datapath directory', 'remove_outdated_vqa_v1_data': 'remove an older version of the VQA-v1 dataset directory before rebuilding', 'review_build_function': 'review the build function that downloads VQA-v1 MS COCO data and marks the directory as done'}
```

