# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dialog_babi/build.py

Prompts

```
['build the dialog_babi dataset by downloading and extracting data to the specified datapath directory', 'run the build function to download dialog_babi.tar.gz and mark the data as built', 'download the dialog_babi resources using the RESOURCES list of DownloadableFile entries', 'check if the dialog_babi dataset has already been built using build_data.built', 'remove outdated dialog_babi data files using build_data.remove_dir before rebuilding']
```

Usage

```
{'build_dialog_babi_data': 'build the dialog_babi dataset by downloading and extracting data to the specified datapath directory', 'run_build_function': 'run the build function to download dialog_babi.tar.gz and mark the data as built', 'download_dialog_babi_resources': 'download the dialog_babi resources using the RESOURCES list of DownloadableFile entries', 'check_dialog_babi_built': 'check if the dialog_babi dataset has already been built using build_data.built', 'remove_outdated_dialog_babi': 'remove outdated dialog_babi data files using build_data.remove_dir before rebuilding'}
```

