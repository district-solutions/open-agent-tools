# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/taskmaster2/agents.py

Prompts

```
['build a Taskmaster2Parser to load and parse Taskmaster-2 dialogue data across multiple domains', 'parse a list of dialogue segments into API call name and slot value dictionaries', 'setup TodStructuredEpisode objects from Taskmaster-2 data with user and assistant utterance rounds', 'load Taskmaster-2 ontology and conversation JSON files split into train, valid, and test folds', 'run a UserSimulatorTeacher to simulate user dialogue turns for Taskmaster-2 task completion domains', 'call build(opt) to download and set up the Taskmaster-2 dataset into the datapath directory', 'download all 14 Taskmaster-2 raw data and ontology JSON files for seven domains', 'check if the Taskmaster-2 dataset has already been built using build_data.built with version 1.1', 'remove an outdated version of the Taskmaster-2 dataset directory using build_data.remove_dir', 'review the build function that downloads Taskmaster-2 data files and marks them as built']
```

Usage

```
{'build_taskmaster2_parser': 'build a Taskmaster2Parser to load and parse Taskmaster-2 dialogue data across multiple domains', 'parse_segments_to_slots': 'parse a list of dialogue segments into API call name and slot value dictionaries', 'setup_episodes': 'setup TodStructuredEpisode objects from Taskmaster-2 data with user and assistant utterance rounds', 'load_taskmaster2_data': 'load Taskmaster-2 ontology and conversation JSON files split into train, valid, and test folds', 'run_user_simulator': 'run a UserSimulatorTeacher to simulate user dialogue turns for Taskmaster-2 task completion domains'}
```

## File: facebookresearch_parlai/parlai/tasks/taskmaster2/build.py

Prompts

```
['build a Taskmaster2Parser to load and parse Taskmaster-2 dialogue data across multiple domains', 'parse a list of dialogue segments into API call name and slot value dictionaries', 'setup TodStructuredEpisode objects from Taskmaster-2 data with user and assistant utterance rounds', 'load Taskmaster-2 ontology and conversation JSON files split into train, valid, and test folds', 'run a UserSimulatorTeacher to simulate user dialogue turns for Taskmaster-2 task completion domains', 'call build(opt) to download and set up the Taskmaster-2 dataset into the datapath directory', 'download all 14 Taskmaster-2 raw data and ontology JSON files for seven domains', 'check if the Taskmaster-2 dataset has already been built using build_data.built with version 1.1', 'remove an outdated version of the Taskmaster-2 dataset directory using build_data.remove_dir', 'review the build function that downloads Taskmaster-2 data files and marks them as built']
```

Usage

```
{'build_taskmaster2_data': 'call build(opt) to download and set up the Taskmaster-2 dataset into the datapath directory', 'download_taskmaster2_resources': 'download all 14 Taskmaster-2 raw data and ontology JSON files for seven domains', 'check_taskmaster2_built': 'check if the Taskmaster-2 dataset has already been built using build_data.built with version 1.1', 'remove_old_taskmaster2_data': 'remove an outdated version of the Taskmaster-2 dataset directory using build_data.remove_dir', 'review_build_function': 'review the build function that downloads Taskmaster-2 data files and marks them as built'}
```

