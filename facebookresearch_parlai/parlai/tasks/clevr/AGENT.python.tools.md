# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/clevr/agents.py

Prompts

```
['build a Parlai CLEVR DialogTeacher to load and serve visual reasoning questions with images', 'run the DefaultTeacher class to iterate over CLEVR dataset questions and answers by image episode', 'review the DefaultTeacher label_candidates method to get all possible CLEVR answer tokens', 'refactor the setup_data method to customize how CLEVR questions and image paths are yielded per episode', 'summarize the _path function to resolve CLEVR questions and images file paths from the opt config', 'run the build function to download and prepare the CLEVR v1.0 dataset into the specified datapath', 'download the CLEVR_v1.0.zip file from the Facebook AI Research public files server', 'check if the CLEVR dataset has already been built at the given datapath with version v1.0', 'remove an older version of the CLEVR dataset directory before rebuilding with the latest version', 'mark the CLEVR dataset build as complete with the version string v1.0']
```

Usage

```
{'build_clevr_teacher': 'build a Parlai CLEVR DialogTeacher to load and serve visual reasoning questions with images', 'run_default_teacher': 'run the DefaultTeacher class to iterate over CLEVR dataset questions and answers by image episode', 'review_label_candidates': 'review the DefaultTeacher label_candidates method to get all possible CLEVR answer tokens', 'refactor_setup_data': 'refactor the setup_data method to customize how CLEVR questions and image paths are yielded per episode', 'summarize_path_function': 'summarize the _path function to resolve CLEVR questions and images file paths from the opt config'}
```

## File: facebookresearch_parlai/parlai/tasks/clevr/build.py

Prompts

```
['build a Parlai CLEVR DialogTeacher to load and serve visual reasoning questions with images', 'run the DefaultTeacher class to iterate over CLEVR dataset questions and answers by image episode', 'review the DefaultTeacher label_candidates method to get all possible CLEVR answer tokens', 'refactor the setup_data method to customize how CLEVR questions and image paths are yielded per episode', 'summarize the _path function to resolve CLEVR questions and images file paths from the opt config', 'run the build function to download and prepare the CLEVR v1.0 dataset into the specified datapath', 'download the CLEVR_v1.0.zip file from the Facebook AI Research public files server', 'check if the CLEVR dataset has already been built at the given datapath with version v1.0', 'remove an older version of the CLEVR dataset directory before rebuilding with the latest version', 'mark the CLEVR dataset build as complete with the version string v1.0']
```

Usage

```
{'build_clevr_dataset': 'run the build function to download and prepare the CLEVR v1.0 dataset into the specified datapath', 'download_clevr_data': 'download the CLEVR_v1.0.zip file from the Facebook AI Research public files server', 'check_clevr_built': 'check if the CLEVR dataset has already been built at the given datapath with version v1.0', 'remove_old_clevr_data': 'remove an older version of the CLEVR dataset directory before rebuilding with the latest version', 'mark_clevr_done': 'mark the CLEVR dataset build as complete with the version string v1.0'}
```

