# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v20/agents.py

Prompts

```
['build the MultiWOZ 2.0 dataset by calling the build function to download and prepare data', 'create a MultiWozTeacher instance to load and serve MultiWOZ 2.0 dialogue data for training', 'get a dialogue turn and its label from the MultiWOZ dataset using the get method', 'count the total number of dialogue examples across all conversations in the MultiWOZ dataset', 'count the total number of dialogue episodes in the MultiWOZ dataset using num_episodes', 'build the multiwoz_v20 dataset by downloading MULTIWOZ2.zip to the ParlAI datapath directory', 'run the build function to download and set up the MultiWOZ 2.0 dialogue dataset', 'download the MultiWOZ 2.0 dataset resource file from the Cambridge repository', 'check if the multiwoz_v20 dataset has already been built using build_data.built', 'review the build function that downloads and marks the multiwoz_v20 dataset as complete']
```

Usage

```
{'build_multiwoz_dataset': 'build the MultiWOZ 2.0 dataset by calling the build function to download and prepare data', 'create_multiwoz_teacher': 'create a MultiWozTeacher instance to load and serve MultiWOZ 2.0 dialogue data for training', 'get_dialogue_example': 'get a dialogue turn and its label from the MultiWOZ dataset using the get method', 'count_multiwoz_examples': 'count the total number of dialogue examples across all conversations in the MultiWOZ dataset', 'count_multiwoz_episodes': 'count the total number of dialogue episodes in the MultiWOZ dataset using num_episodes'}
```

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v20/build.py

Prompts

```
['build the MultiWOZ 2.0 dataset by calling the build function to download and prepare data', 'create a MultiWozTeacher instance to load and serve MultiWOZ 2.0 dialogue data for training', 'get a dialogue turn and its label from the MultiWOZ dataset using the get method', 'count the total number of dialogue examples across all conversations in the MultiWOZ dataset', 'count the total number of dialogue episodes in the MultiWOZ dataset using num_episodes', 'build the multiwoz_v20 dataset by downloading MULTIWOZ2.zip to the ParlAI datapath directory', 'run the build function to download and set up the MultiWOZ 2.0 dialogue dataset', 'download the MultiWOZ 2.0 dataset resource file from the Cambridge repository', 'check if the multiwoz_v20 dataset has already been built using build_data.built', 'review the build function that downloads and marks the multiwoz_v20 dataset as complete']
```

Usage

```
{'build_multiwoz_v20_data': 'build the multiwoz_v20 dataset by downloading MULTIWOZ2.zip to the ParlAI datapath directory', 'run_build_function': 'run the build function to download and set up the MultiWOZ 2.0 dialogue dataset', 'download_multiwoz_resources': 'download the MultiWOZ 2.0 dataset resource file from the Cambridge repository', 'check_build_status': 'check if the multiwoz_v20 dataset has already been built using build_data.built', 'review_build_function': 'review the build function that downloads and marks the multiwoz_v20 dataset as complete'}
```

