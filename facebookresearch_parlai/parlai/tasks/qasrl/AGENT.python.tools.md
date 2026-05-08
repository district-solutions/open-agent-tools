# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/qasrl/agents.py

Prompts

```
['build the QA-SRL dataset by calling the build function with an opt dictionary', 'create a QASRLTeacher instance with an opt dict to load QA-SRL dialog data', 'setup QA-SRL data by parsing wiki1 train dev or test files into question answer pairs', 'parse raw QA-SRL data lines into question and answer pairs using the convert_to_qa helper', 'get the QA-SRL data file path for train valid or test splits using the _path function', 'download the QA-SRL wiki1 train, dev, and test question-answer files from dada.cs.washington.edu', 'check whether the QA-SRL dataset has already been built in the ParlAI datapath directory', 'remove an older version of the QA-SRL dataset directory before rebuilding with fresh downloads', 'mark the QA-SRL dataset build as complete after all resource files have been downloaded']
```

Usage

```
{'build_qasrl_data': 'build the QA-SRL dataset by calling the build function with an opt dictionary', 'create_qasrl_teacher': 'create a QASRLTeacher instance with an opt dict to load QA-SRL dialog data', 'setup_qasrl_data': 'setup QA-SRL data by parsing wiki1 train dev or test files into question answer pairs', 'parse_qa_pairs': 'parse raw QA-SRL data lines into question and answer pairs using the convert_to_qa helper', 'get_qasrl_data_path': 'get the QA-SRL data file path for train valid or test splits using the _path function'}
```

## File: facebookresearch_parlai/parlai/tasks/qasrl/build.py

Prompts

```
['build the QA-SRL dataset by calling the build function with an opt dictionary', 'create a QASRLTeacher instance with an opt dict to load QA-SRL dialog data', 'setup QA-SRL data by parsing wiki1 train dev or test files into question answer pairs', 'parse raw QA-SRL data lines into question and answer pairs using the convert_to_qa helper', 'get the QA-SRL data file path for train valid or test splits using the _path function', 'download the QA-SRL wiki1 train, dev, and test question-answer files from dada.cs.washington.edu', 'check whether the QA-SRL dataset has already been built in the ParlAI datapath directory', 'remove an older version of the QA-SRL dataset directory before rebuilding with fresh downloads', 'mark the QA-SRL dataset build as complete after all resource files have been downloaded']
```

Usage

```
{'build_qasrl_data': 'build the QA-SRL dataset by downloading wiki1 train, dev, and test QA files into the ParlAI datapath', 'download_qasrl_resources': 'download the QA-SRL wiki1 train, dev, and test question-answer files from dada.cs.washington.edu', 'check_qasrl_built': 'check whether the QA-SRL dataset has already been built in the ParlAI datapath directory', 'remove_outdated_qasrl_data': 'remove an older version of the QA-SRL dataset directory before rebuilding with fresh downloads', 'mark_qasrl_done': 'mark the QA-SRL dataset build as complete after all resource files have been downloaded'}
```

