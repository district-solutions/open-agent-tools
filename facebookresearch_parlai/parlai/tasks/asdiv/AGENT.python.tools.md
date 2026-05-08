# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/asdiv/agents.py

Prompts

```
['run the ASDivStepByStepReasoningTeacher to load and serve math word problems from the ASDiv dataset', 'load math word problems from ASDiv.xml by parsing question, solution, and equation fields', 'split the ASDiv dataset into train, test, and validation folds using get_data_for_fold', 'configure the ASDiv teacher command line arguments with task prompt and thought token defaults', 'review the ASDivStepByStepReasoningTeacher class and its XML parsing and data splitting logic', 'run the build function to download and set up the ASDIV dataset into the data directory', 'review the build function that checks version, creates directories, and downloads ASDIV data files', 'refactor the build function to support additional downloadable resources or a different dataset URL', 'summarize the build function logic for downloading and versioning the ASDIV dataset', 'test the build function to verify it downloads ASDIV.xml and marks the data directory as built']
```

Usage

```
{'run_asdiv_teacher': 'run the ASDivStepByStepReasoningTeacher to load and serve math word problems from the ASDiv dataset', 'load_asdiv_data': 'load math word problems from ASDiv.xml by parsing question, solution, and equation fields', 'split_asdiv_folds': 'split the ASDiv dataset into train, test, and validation folds using get_data_for_fold', 'configure_asdiv_args': 'configure the ASDiv teacher command line arguments with task prompt and thought token defaults', 'review_asdiv_teacher': 'review the ASDivStepByStepReasoningTeacher class and its XML parsing and data splitting logic'}
```

## File: facebookresearch_parlai/parlai/tasks/asdiv/build.py

Prompts

```
['run the ASDivStepByStepReasoningTeacher to load and serve math word problems from the ASDiv dataset', 'load math word problems from ASDiv.xml by parsing question, solution, and equation fields', 'split the ASDiv dataset into train, test, and validation folds using get_data_for_fold', 'configure the ASDiv teacher command line arguments with task prompt and thought token defaults', 'review the ASDivStepByStepReasoningTeacher class and its XML parsing and data splitting logic', 'run the build function to download and set up the ASDIV dataset into the data directory', 'review the build function that checks version, creates directories, and downloads ASDIV data files', 'refactor the build function to support additional downloadable resources or a different dataset URL', 'summarize the build function logic for downloading and versioning the ASDIV dataset', 'test the build function to verify it downloads ASDIV.xml and marks the data directory as built']
```

Usage

```
{'build_asdiv_dataset': 'run the build function to download and set up the ASDIV dataset into the data directory', 'review_build_function': 'review the build function that checks version, creates directories, and downloads ASDIV data files', 'refactor_build_function': 'refactor the build function to support additional downloadable resources or a different dataset URL', 'summarize_build_function': 'summarize the build function logic for downloading and versioning the ASDIV dataset', 'test_build_function': 'test the build function to verify it downloads ASDIV.xml and marks the data directory as built'}
```

