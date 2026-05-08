# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/ccpe/agents.py

Prompts

```
['initialize a CCPEAllTeacher with opt config to load and prepare CCPE dialogue training data', 'call _setup_data to load ccpe.json, flatten utterances, and separate user and assistant dialogue episodes', 'retrieve a specific dialogue entry by episode and entry index returning text, labels, and segments', 'initialize a CCPEAssistantTeacher to load only assistant-side dialogue data from the CCPE dataset', 'call share to return a shared data dictionary for multi-worker training with CCPE dialogue data', 'run the build function to download and prepare the CCPE dataset for ParlAI', 'download the CCPE data.json file from the Google Research datasets repository', 'review the build function that checks version and downloads CCPE data files', 'summarize the CCPE dataset build process including download and versioning steps', 'test the build function with a ParlAI opt dictionary containing datapath']
```

Usage

```
{'init_CCPEAllTeacher': 'initialize a CCPEAllTeacher with opt config to load and prepare CCPE dialogue training data', 'setup_data_CCPEAllTeacher': 'call _setup_data to load ccpe.json, flatten utterances, and separate user and assistant dialogue episodes', 'get_CCPEAllTeacher': 'retrieve a specific dialogue entry by episode and entry index returning text, labels, and segments', 'init_CCPEAssistantTeacher': 'initialize a CCPEAssistantTeacher to load only assistant-side dialogue data from the CCPE dataset', 'share_CCPEAllTeacher': 'call share to return a shared data dictionary for multi-worker training with CCPE dialogue data'}
```

## File: facebookresearch_parlai/parlai/tasks/ccpe/build.py

Prompts

```
['initialize a CCPEAllTeacher with opt config to load and prepare CCPE dialogue training data', 'call _setup_data to load ccpe.json, flatten utterances, and separate user and assistant dialogue episodes', 'retrieve a specific dialogue entry by episode and entry index returning text, labels, and segments', 'initialize a CCPEAssistantTeacher to load only assistant-side dialogue data from the CCPE dataset', 'call share to return a shared data dictionary for multi-worker training with CCPE dialogue data', 'run the build function to download and prepare the CCPE dataset for ParlAI', 'download the CCPE data.json file from the Google Research datasets repository', 'review the build function that checks version and downloads CCPE data files', 'summarize the CCPE dataset build process including download and versioning steps', 'test the build function with a ParlAI opt dictionary containing datapath']
```

Usage

```
{'build_ccpe_dataset': 'run the build function to download and prepare the CCPE dataset for ParlAI', 'download_ccpe_data': 'download the CCPE data.json file from the Google Research datasets repository', 'review_build_function': 'review the build function that checks version and downloads CCPE data files', 'summarize_build_process': 'summarize the CCPE dataset build process including download and versioning steps', 'test_build_function': 'test the build function with a ParlAI opt dictionary containing datapath'}
```

