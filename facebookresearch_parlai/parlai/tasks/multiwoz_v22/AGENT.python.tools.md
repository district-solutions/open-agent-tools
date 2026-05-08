# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v22/agents.py

Prompts

```
['load API schemas from schema.json for MultiWOZ 2.2 task domains and intents', 'load domain lookup databases into pandas DataFrames for MultiWOZ 2.2 services', 'parse raw MultiWOZ 2.2 dialogues into TodStructuredEpisode objects with API calls and responses', 'evaluate dialogue state tracking model predictions against ground truth using joint goal accuracy', 'load and yield dialogue examples with belief state labels for DST training or evaluation', 'build the MultiWOZ 2.2 dataset by downloading dialogue files and domain databases to the datapath directory', 'build the MultiWOZ 2.2 dataset and check if version 1.0 is already built before downloading', 'build the MultiWOZ 2.2 dataset by removing any older version and downloading fresh data', 'review the build function that downloads MultiWOZ 2.2 dialogue and database JSON files', 'summarize the RESOURCES list of DownloadableFile objects for MultiWOZ 2.2 train dev test and db files', 'run the checksum function to compute the SHA-256 hash of a given file path', 'review the checksum function that reads a file in binary mode and returns its SHA-256 hex digest', 'refactor the checksum function to support streaming large files without loading them entirely into memory', 'test the checksum function by computing the SHA-256 hash of a known file and verifying the output', "summarize the checksum function which uses hashlib.sha256 to compute a file's hash in 64KB blocks"]
```

Usage

```
{'load_schemas_MultiwozV22Parser': 'load API schemas from schema.json for MultiWOZ 2.2 task domains and intents', 'load_dbs_MultiwozV22Parser': 'load domain lookup databases into pandas DataFrames for MultiWOZ 2.2 services', 'setup_episodes_MultiwozV22Parser': 'parse raw MultiWOZ 2.2 dialogues into TodStructuredEpisode objects with API calls and responses', 'custom_evaluation_MultiWOZv22DSTTeacher': 'evaluate dialogue state tracking model predictions against ground truth using joint goal accuracy', 'setup_data_MultiWOZv22DSTTeacher': 'load and yield dialogue examples with belief state labels for DST training or evaluation'}
```

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v22/build.py

Prompts

```
['load API schemas from schema.json for MultiWOZ 2.2 task domains and intents', 'load domain lookup databases into pandas DataFrames for MultiWOZ 2.2 services', 'parse raw MultiWOZ 2.2 dialogues into TodStructuredEpisode objects with API calls and responses', 'evaluate dialogue state tracking model predictions against ground truth using joint goal accuracy', 'load and yield dialogue examples with belief state labels for DST training or evaluation', 'build the MultiWOZ 2.2 dataset by downloading dialogue files and domain databases to the datapath directory', 'build the MultiWOZ 2.2 dataset and check if version 1.0 is already built before downloading', 'build the MultiWOZ 2.2 dataset by removing any older version and downloading fresh data', 'review the build function that downloads MultiWOZ 2.2 dialogue and database JSON files', 'summarize the RESOURCES list of DownloadableFile objects for MultiWOZ 2.2 train dev test and db files', 'run the checksum function to compute the SHA-256 hash of a given file path', 'review the checksum function that reads a file in binary mode and returns its SHA-256 hex digest', 'refactor the checksum function to support streaming large files without loading them entirely into memory', 'test the checksum function by computing the SHA-256 hash of a known file and verifying the output', "summarize the checksum function which uses hashlib.sha256 to compute a file's hash in 64KB blocks"]
```

Usage

```
{'build_multiwoz_v22_dataset': 'build the MultiWOZ 2.2 dataset by downloading dialogue files and domain databases to the datapath directory', 'build_multiwoz_v22_check_version': 'build the MultiWOZ 2.2 dataset and check if version 1.0 is already built before downloading', 'build_multiwoz_v22_remove_old': 'build the MultiWOZ 2.2 dataset by removing any older version and downloading fresh data', 'review_build_function': 'review the build function that downloads MultiWOZ 2.2 dialogue and database JSON files', 'summarize_resources_list': 'summarize the RESOURCES list of DownloadableFile objects for MultiWOZ 2.2 train dev test and db files'}
```

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v22/build_sha_check_script.py

Prompts

```
['load API schemas from schema.json for MultiWOZ 2.2 task domains and intents', 'load domain lookup databases into pandas DataFrames for MultiWOZ 2.2 services', 'parse raw MultiWOZ 2.2 dialogues into TodStructuredEpisode objects with API calls and responses', 'evaluate dialogue state tracking model predictions against ground truth using joint goal accuracy', 'load and yield dialogue examples with belief state labels for DST training or evaluation', 'build the MultiWOZ 2.2 dataset by downloading dialogue files and domain databases to the datapath directory', 'build the MultiWOZ 2.2 dataset and check if version 1.0 is already built before downloading', 'build the MultiWOZ 2.2 dataset by removing any older version and downloading fresh data', 'review the build function that downloads MultiWOZ 2.2 dialogue and database JSON files', 'summarize the RESOURCES list of DownloadableFile objects for MultiWOZ 2.2 train dev test and db files', 'run the checksum function to compute the SHA-256 hash of a given file path', 'review the checksum function that reads a file in binary mode and returns its SHA-256 hex digest', 'refactor the checksum function to support streaming large files without loading them entirely into memory', 'test the checksum function by computing the SHA-256 hash of a known file and verifying the output', "summarize the checksum function which uses hashlib.sha256 to compute a file's hash in 64KB blocks"]
```

Usage

```
{'run_checksum': 'run the checksum function to compute the SHA-256 hash of a given file path', 'review_checksum': 'review the checksum function that reads a file in binary mode and returns its SHA-256 hex digest', 'refactor_checksum': 'refactor the checksum function to support streaming large files without loading them entirely into memory', 'test_checksum': 'test the checksum function by computing the SHA-256 hash of a known file and verifying the output', 'summarize_checksum': "summarize the checksum function which uses hashlib.sha256 to compute a file's hash in 64KB blocks"}
```

