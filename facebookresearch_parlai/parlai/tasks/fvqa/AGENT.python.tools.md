# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/fvqa/agents.py

Prompts

```
['run the SplitTeacher class to serve FVQA visual question answering data with image and question pairs', 'run the DefaultTeacher class as the default FVQA teacher for visual question answering tasks', 'test the SplitTeacher act method to return questions with images and labels for training', 'review the SplitTeacher observe method to evaluate student responses against expected answers and facts', 'refactor the SplitTeacher _setup_data method to load questions from JSON and filter by image list', 'run the build function to download and set up the FVQA dataset into the specified datapath directory', 'review the build function that checks for existing data, removes outdated versions, and downloads FVQA resources', 'summarize the build function logic for downloading FVQA dataset files and marking the data as built', 'test the build function by passing an opt dictionary with a datapath key to download FVQA data', 'refactor the build function to support versioned downloads of the FVQA dataset with a specific version string']
```

Usage

```
{'run_split_teacher': 'run the SplitTeacher class to serve FVQA visual question answering data with image and question pairs', 'run_default_teacher': 'run the DefaultTeacher class as the default FVQA teacher for visual question answering tasks', 'test_split_teacher_act': 'test the SplitTeacher act method to return questions with images and labels for training', 'review_split_teacher_observe': 'review the SplitTeacher observe method to evaluate student responses against expected answers and facts', 'refactor_split_teacher_setup_data': 'refactor the SplitTeacher _setup_data method to load questions from JSON and filter by image list'}
```

## File: facebookresearch_parlai/parlai/tasks/fvqa/build.py

Prompts

```
['run the SplitTeacher class to serve FVQA visual question answering data with image and question pairs', 'run the DefaultTeacher class as the default FVQA teacher for visual question answering tasks', 'test the SplitTeacher act method to return questions with images and labels for training', 'review the SplitTeacher observe method to evaluate student responses against expected answers and facts', 'refactor the SplitTeacher _setup_data method to load questions from JSON and filter by image list', 'run the build function to download and set up the FVQA dataset into the specified datapath directory', 'review the build function that checks for existing data, removes outdated versions, and downloads FVQA resources', 'summarize the build function logic for downloading FVQA dataset files and marking the data as built', 'test the build function by passing an opt dictionary with a datapath key to download FVQA data', 'refactor the build function to support versioned downloads of the FVQA dataset with a specific version string']
```

Usage

```
{'build_fvqa_dataset': 'run the build function to download and set up the FVQA dataset into the specified datapath directory', 'review_build_function': 'review the build function that checks for existing data, removes outdated versions, and downloads FVQA resources', 'summarize_build_function': 'summarize the build function logic for downloading FVQA dataset files and marking the data as built', 'test_build_function': 'test the build function by passing an opt dictionary with a datapath key to download FVQA data', 'refactor_build_function': 'refactor the build function to support versioned downloads of the FVQA dataset with a specific version string'}
```

