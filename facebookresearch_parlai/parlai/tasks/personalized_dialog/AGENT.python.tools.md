# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/personalized_dialog/build.py

Prompts

```
['run the build function to download and prepare the personalized dialog dataset into the ParlAI datapath directory', 'download the personalized dialog dataset tarball from Dropbox and extract it into the specified data path', 'check whether the personalized dialog dataset has already been built in the ParlAI data directory', 'remove an older version of the personalized dialog dataset before rebuilding it with the latest files', 'mark the personalized dialog dataset as fully built and ready for use by ParlAI tasks']
```

Usage

```
{'build_personalized_dialog_dataset': 'run the build function to download and prepare the personalized dialog dataset into the ParlAI datapath directory', 'download_personalized_dialog_data': 'download the personalized dialog dataset tarball from Dropbox and extract it into the specified data path', 'check_dataset_built_status': 'check whether the personalized dialog dataset has already been built in the ParlAI data directory', 'remove_outdated_dataset': 'remove an older version of the personalized dialog dataset before rebuilding it with the latest files', 'mark_dataset_done': 'mark the personalized dialog dataset as fully built and ready for use by ParlAI tasks'}
```

