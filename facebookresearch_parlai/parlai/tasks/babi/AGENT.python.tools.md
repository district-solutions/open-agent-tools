# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/babi/agents.py

Prompts

```
['create a Task1kTeacher instance to load and serve a single bAbI task with 1k training examples', 'create a Task10kTeacher instance to load and serve a single bAbI task with 10k training examples', 'create an All1kTeacher instance to train on all 20 bAbI tasks with 1k examples each', 'use mod_labels to replace commas with spaces in bAbI task 8 or 19 answer labels', 'use DefaultTeacher to train on all 20 bAbI tasks as the default multi-task teacher', 'run the build function to download and set up the bAbI task dataset', 'review the build function that downloads bAbI data and marks it as built', 'summarize the build function logic for downloading and setting up bAbI task data', 'test the build function to verify it downloads bAbI data to the correct datapath', 'refactor the build function to support multiple bAbI dataset versions']
```

Usage

```
{'create_Task1kTeacher': 'create a Task1kTeacher instance to load and serve a single bAbI task with 1k training examples', 'create_Task10kTeacher': 'create a Task10kTeacher instance to load and serve a single bAbI task with 10k training examples', 'create_All1kTeacher': 'create an All1kTeacher instance to train on all 20 bAbI tasks with 1k examples each', 'use_mod_labels': 'use mod_labels to replace commas with spaces in bAbI task 8 or 19 answer labels', 'use_DefaultTeacher': 'use DefaultTeacher to train on all 20 bAbI tasks as the default multi-task teacher'}
```

## File: facebookresearch_parlai/parlai/tasks/babi/build.py

Prompts

```
['create a Task1kTeacher instance to load and serve a single bAbI task with 1k training examples', 'create a Task10kTeacher instance to load and serve a single bAbI task with 10k training examples', 'create an All1kTeacher instance to train on all 20 bAbI tasks with 1k examples each', 'use mod_labels to replace commas with spaces in bAbI task 8 or 19 answer labels', 'use DefaultTeacher to train on all 20 bAbI tasks as the default multi-task teacher', 'run the build function to download and set up the bAbI task dataset', 'review the build function that downloads bAbI data and marks it as built', 'summarize the build function logic for downloading and setting up bAbI task data', 'test the build function to verify it downloads bAbI data to the correct datapath', 'refactor the build function to support multiple bAbI dataset versions']
```

Usage

```
{'build_babi_data': 'run the build function to download and set up the bAbI task dataset', 'review_build_function': 'review the build function that downloads bAbI data and marks it as built', 'summarize_build_function': 'summarize the build function logic for downloading and setting up bAbI task data', 'test_build_function': 'test the build function to verify it downloads bAbI data to the correct datapath', 'refactor_build_function': 'refactor the build function to support multiple bAbI dataset versions'}
```

