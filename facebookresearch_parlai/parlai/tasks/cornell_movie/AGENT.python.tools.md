# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/cornell_movie/agents.py

Prompts

```
['run the DefaultTeacher to load Cornell Movie dialog data for training a dialogue model', 'run the DoubleTeacher to create text-label pairs from both speaker perspectives in Cornell Movie corpus', 'review the DefaultTeacher setup_data method that parses movie_lines.txt and movie_conversations.txt into dialog pairs', 'refactor the DefaultTeacher class to change the train-valid-test fold splitting logic based on conversation index', 'summarize the _path helper function that constructs file paths under the CornellMovie datapath directory', 'run the build function to download and set up the Cornell Movie Dialogs Corpus dataset', 'review the build function that checks version, downloads resources, and marks data as built', 'summarize the build logic that handles versioned data downloads and directory management', 'test the build function version check to ensure outdated data is removed before rebuilding', 'refactor the RESOURCES list to add additional DownloadableFile entries for the Cornell Movie dataset']
```

Usage

```
{'run_DefaultTeacher': 'run the DefaultTeacher to load Cornell Movie dialog data for training a dialogue model', 'run_DoubleTeacher': 'run the DoubleTeacher to create text-label pairs from both speaker perspectives in Cornell Movie corpus', 'review_DefaultTeacher_setup_data': 'review the DefaultTeacher setup_data method that parses movie_lines.txt and movie_conversations.txt into dialog pairs', 'refactor_DefaultTeacher': 'refactor the DefaultTeacher class to change the train-valid-test fold splitting logic based on conversation index', 'summarize_path': 'summarize the _path helper function that constructs file paths under the CornellMovie datapath directory'}
```

## File: facebookresearch_parlai/parlai/tasks/cornell_movie/build.py

Prompts

```
['run the DefaultTeacher to load Cornell Movie dialog data for training a dialogue model', 'run the DoubleTeacher to create text-label pairs from both speaker perspectives in Cornell Movie corpus', 'review the DefaultTeacher setup_data method that parses movie_lines.txt and movie_conversations.txt into dialog pairs', 'refactor the DefaultTeacher class to change the train-valid-test fold splitting logic based on conversation index', 'summarize the _path helper function that constructs file paths under the CornellMovie datapath directory', 'run the build function to download and set up the Cornell Movie Dialogs Corpus dataset', 'review the build function that checks version, downloads resources, and marks data as built', 'summarize the build logic that handles versioned data downloads and directory management', 'test the build function version check to ensure outdated data is removed before rebuilding', 'refactor the RESOURCES list to add additional DownloadableFile entries for the Cornell Movie dataset']
```

Usage

```
{'run_build_cornell_movie': 'run the build function to download and set up the Cornell Movie Dialogs Corpus dataset', 'review_build_function': 'review the build function that checks version, downloads resources, and marks data as built', 'summarize_build_logic': 'summarize the build logic that handles versioned data downloads and directory management', 'test_build_version_check': 'test the build function version check to ensure outdated data is removed before rebuilding', 'refactor_build_resources': 'refactor the RESOURCES list to add additional DownloadableFile entries for the Cornell Movie dataset'}
```

