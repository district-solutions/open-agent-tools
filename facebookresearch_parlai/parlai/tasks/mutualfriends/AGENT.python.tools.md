# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/mutualfriends/agents.py

Prompts

```
['run the DefaultTeacher to load and serve MutualFriends dialog data for training', 'review the DefaultTeacher class that extends DialogTeacher for the MutualFriends dataset', 'summarize the setup_data method that loads JSON conversations and yields dialog turns', 'test the act method that overrides DialogTeacher act to set Teacher id on intro messages', 'refactor the DefaultTeacher __init__ to support additional datatypes beyond training data', 'run the build function to download and set up the MutualFriends dataset into the specified datapath directory', 'review the build function to understand how it checks for existing data and downloads resources', 'summarize the RESOURCES list to see which DownloadableFile entries are configured for the MutualFriends task', 'test the build function by passing an opt dictionary with a datapath key to verify data download', 'refactor the build function to add a version string for tracking dataset updates']
```

Usage

```
{'run_mutualfriends_teacher': 'run the DefaultTeacher to load and serve MutualFriends dialog data for training', 'review_DefaultTeacher_class': 'review the DefaultTeacher class that extends DialogTeacher for the MutualFriends dataset', 'summarize_setup_data_method': 'summarize the setup_data method that loads JSON conversations and yields dialog turns', 'test_act_method': 'test the act method that overrides DialogTeacher act to set Teacher id on intro messages', 'refactor_DefaultTeacher_init': 'refactor the DefaultTeacher __init__ to support additional datatypes beyond training data'}
```

## File: facebookresearch_parlai/parlai/tasks/mutualfriends/build.py

Prompts

```
['run the DefaultTeacher to load and serve MutualFriends dialog data for training', 'review the DefaultTeacher class that extends DialogTeacher for the MutualFriends dataset', 'summarize the setup_data method that loads JSON conversations and yields dialog turns', 'test the act method that overrides DialogTeacher act to set Teacher id on intro messages', 'refactor the DefaultTeacher __init__ to support additional datatypes beyond training data', 'run the build function to download and set up the MutualFriends dataset into the specified datapath directory', 'review the build function to understand how it checks for existing data and downloads resources', 'summarize the RESOURCES list to see which DownloadableFile entries are configured for the MutualFriends task', 'test the build function by passing an opt dictionary with a datapath key to verify data download', 'refactor the build function to add a version string for tracking dataset updates']
```

Usage

```
{'build_mutualfriends_data': 'run the build function to download and set up the MutualFriends dataset into the specified datapath directory', 'review_build_function': 'review the build function to understand how it checks for existing data and downloads resources', 'summarize_resources_list': 'summarize the RESOURCES list to see which DownloadableFile entries are configured for the MutualFriends task', 'test_build_function': 'test the build function by passing an opt dictionary with a datapath key to verify data download', 'refactor_build_function': 'refactor the build function to add a version string for tracking dataset updates'}
```

