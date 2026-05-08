# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/taskntalk/agents.py

Prompts

```
['run the SmallTeacher to load and serve examples from the taskntalk small dataset', 'run the LargeTeacher to load and serve examples from the taskntalk large dataset', 'review the AbstractTaskNTalk act method that selects a random image and associates a random task with it', 'review the AbstractTaskNTalk _setup_data method that reads a JSON file and stores images and task definitions', 'test the _path function to return the correct JSON file path for train or valid datatypes', 'run the build function to generate small and large taskntalk train and validation JSON datasets', 'build the small taskntalk dataset with 64 shape combinations split into train and validation sets', 'build the large taskntalk dataset with 512 shape combinations split into train and validation sets', 'review the build function that creates synthetic shape attribute data for the taskntalk ParlAI task', 'refactor the build function to change the train validation split ratios for small or large datasets']
```

Usage

```
{'run_taskntalk_small_teacher': 'run the SmallTeacher to load and serve examples from the taskntalk small dataset', 'run_taskntalk_large_teacher': 'run the LargeTeacher to load and serve examples from the taskntalk large dataset', 'review_abstracttaskntalk_act': 'review the AbstractTaskNTalk act method that selects a random image and associates a random task with it', 'review_abstracttaskntalk_setup_data': 'review the AbstractTaskNTalk _setup_data method that reads a JSON file and stores images and task definitions', 'test_taskntalk_path': 'test the _path function to return the correct JSON file path for train or valid datatypes'}
```

## File: facebookresearch_parlai/parlai/tasks/taskntalk/build.py

Prompts

```
['run the SmallTeacher to load and serve examples from the taskntalk small dataset', 'run the LargeTeacher to load and serve examples from the taskntalk large dataset', 'review the AbstractTaskNTalk act method that selects a random image and associates a random task with it', 'review the AbstractTaskNTalk _setup_data method that reads a JSON file and stores images and task definitions', 'test the _path function to return the correct JSON file path for train or valid datatypes', 'run the build function to generate small and large taskntalk train and validation JSON datasets', 'build the small taskntalk dataset with 64 shape combinations split into train and validation sets', 'build the large taskntalk dataset with 512 shape combinations split into train and validation sets', 'review the build function that creates synthetic shape attribute data for the taskntalk ParlAI task', 'refactor the build function to change the train validation split ratios for small or large datasets']
```

Usage

```
{'build_taskntalk_data': 'run the build function to generate small and large taskntalk train and validation JSON datasets', 'generate_taskntalk_small_dataset': 'build the small taskntalk dataset with 64 shape combinations split into train and validation sets', 'generate_taskntalk_large_dataset': 'build the large taskntalk dataset with 512 shape combinations split into train and validation sets', 'review_build_function': 'review the build function that creates synthetic shape attribute data for the taskntalk ParlAI task', 'refactor_build_split_ratios': 'refactor the build function to change the train validation split ratios for small or large datasets'}
```

