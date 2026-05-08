# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/woz/agents.py

Prompts

```
['build the WoZ dataset by calling the build function to download and prepare dialogue data', 'create a WoZTeacher instance with an opt dictionary to load and serve WoZ dialogue data', 'setup WoZ dialogue data by loading JSON transcripts and yielding context-question-answer tuples', 'get the WoZ data file path for train, valid, or test splits using the _path function', 'review the WoZTeacher class and its setup_data method for dialogue state tracking behavior', 'run the build function to download and prepare the WoZ dataset files into the data directory', 'download the WoZ test English JSON file using the RESOURCES list of DownloadableFile objects', 'download the WoZ train English JSON file using the RESOURCES list of DownloadableFile objects', 'download the WoZ validate English JSON file using the RESOURCES list of DownloadableFile objects', 'check if the WoZ dataset has already been built using build_data.built with the data path']
```

Usage

```
{'build_woz_data': 'build the WoZ dataset by calling the build function to download and prepare dialogue data', 'create_woz_teacher': 'create a WoZTeacher instance with an opt dictionary to load and serve WoZ dialogue data', 'setup_woz_dialogue_data': 'setup WoZ dialogue data by loading JSON transcripts and yielding context-question-answer tuples', 'get_woz_data_path': 'get the WoZ data file path for train, valid, or test splits using the _path function', 'review_woz_teacher_class': 'review the WoZTeacher class and its setup_data method for dialogue state tracking behavior'}
```

## File: facebookresearch_parlai/parlai/tasks/woz/build.py

Prompts

```
['build the WoZ dataset by calling the build function to download and prepare dialogue data', 'create a WoZTeacher instance with an opt dictionary to load and serve WoZ dialogue data', 'setup WoZ dialogue data by loading JSON transcripts and yielding context-question-answer tuples', 'get the WoZ data file path for train, valid, or test splits using the _path function', 'review the WoZTeacher class and its setup_data method for dialogue state tracking behavior', 'run the build function to download and prepare the WoZ dataset files into the data directory', 'download the WoZ test English JSON file using the RESOURCES list of DownloadableFile objects', 'download the WoZ train English JSON file using the RESOURCES list of DownloadableFile objects', 'download the WoZ validate English JSON file using the RESOURCES list of DownloadableFile objects', 'check if the WoZ dataset has already been built using build_data.built with the data path']
```

Usage

```
{'build_woz_dataset': 'run the build function to download and prepare the WoZ dataset files into the data directory', 'download_woz_test_data': 'download the WoZ test English JSON file using the RESOURCES list of DownloadableFile objects', 'download_woz_train_data': 'download the WoZ train English JSON file using the RESOURCES list of DownloadableFile objects', 'download_woz_validate_data': 'download the WoZ validate English JSON file using the RESOURCES list of DownloadableFile objects', 'check_woz_data_built': 'check if the WoZ dataset has already been built using build_data.built with the data path'}
```

