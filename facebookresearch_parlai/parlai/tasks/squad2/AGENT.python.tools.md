# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/squad2/agents.py

Prompts

```
['run the IndexTeacher to load SQuAD2 data and serve context plus question examples with answer start indices', 'run the DefaultTeacher to iterate over SQuAD2 data yielding context and question pairs with answer labels', 'run the OpenSquadTeacher to serve SQuAD2 questions without context paragraphs for open-domain QA tasks', 'run the TitleTeacher to serve SQuAD2 examples that include the Wikipedia article title alongside context and question', 'run the SentenceIndexTeacher to serve SQuAD2 examples where labels are the sentences containing the true answer', 'build the SQuAD2 dataset by downloading train and dev JSON files into the datapath directory', 'run the build function to download SQuAD2 train and dev data files to a specified path', 'download the SQuAD2 train-v2.0 and dev-v2.0 JSON files using the RESOURCES list', 'check if the SQuAD2 dataset has already been built in the given datapath directory', 'remove outdated SQuAD2 data files before rebuilding the dataset with fresh downloads']
```

Usage

```
{'run_IndexTeacher': 'run the IndexTeacher to load SQuAD2 data and serve context plus question examples with answer start indices', 'run_DefaultTeacher': 'run the DefaultTeacher to iterate over SQuAD2 data yielding context and question pairs with answer labels', 'run_OpenSquadTeacher': 'run the OpenSquadTeacher to serve SQuAD2 questions without context paragraphs for open-domain QA tasks', 'run_TitleTeacher': 'run the TitleTeacher to serve SQuAD2 examples that include the Wikipedia article title alongside context and question', 'run_SentenceIndexTeacher': 'run the SentenceIndexTeacher to serve SQuAD2 examples where labels are the sentences containing the true answer'}
```

## File: facebookresearch_parlai/parlai/tasks/squad2/build.py

Prompts

```
['run the IndexTeacher to load SQuAD2 data and serve context plus question examples with answer start indices', 'run the DefaultTeacher to iterate over SQuAD2 data yielding context and question pairs with answer labels', 'run the OpenSquadTeacher to serve SQuAD2 questions without context paragraphs for open-domain QA tasks', 'run the TitleTeacher to serve SQuAD2 examples that include the Wikipedia article title alongside context and question', 'run the SentenceIndexTeacher to serve SQuAD2 examples where labels are the sentences containing the true answer', 'build the SQuAD2 dataset by downloading train and dev JSON files into the datapath directory', 'run the build function to download SQuAD2 train and dev data files to a specified path', 'download the SQuAD2 train-v2.0 and dev-v2.0 JSON files using the RESOURCES list', 'check if the SQuAD2 dataset has already been built in the given datapath directory', 'remove outdated SQuAD2 data files before rebuilding the dataset with fresh downloads']
```

Usage

```
{'build_squad2_dataset': 'build the SQuAD2 dataset by downloading train and dev JSON files into the datapath directory', 'run_build_function': 'run the build function to download SQuAD2 train and dev data files to a specified path', 'download_squad2_resources': 'download the SQuAD2 train-v2.0 and dev-v2.0 JSON files using the RESOURCES list', 'check_squad2_built_status': 'check if the SQuAD2 dataset has already been built in the given datapath directory', 'remove_outdated_squad2_data': 'remove outdated SQuAD2 data files before rebuilding the dataset with fresh downloads'}
```

