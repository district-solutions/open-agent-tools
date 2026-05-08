# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/saferdialogues/agents.py

Prompts

```
['create a SaferDialoguesTeacher instance to load and serve SaFeRDialogues dialogue data for training', 'create a SaferDialoguesBADTeacher instance to load adversarial SaFeRDialogues data with bad responses', 'configure the recovery utterance flag on SaferDialoguesTeacher to include or exclude recovery messages', 'setup SaFeRDialogues episode data to use signaling messages as labels instead of recovery utterances', 'get the SaFeRDialogues dataset file path for a given datatype using the _path helper function', 'run the build function to download and prepare the saferdialogues dataset into the specified datapath', 'download the saferdialogues v0.4 tar.gz resource file using the RESOURCES list of DownloadableFile objects', 'check if the saferdialogues dataset is already built for version v0.4 using build_data.built', 'remove an older version of the saferdialogues data directory using build_data.remove_dir', 'mark the saferdialogues dataset as built using build_data.mark_done with the version string']
```

Usage

```
{'create_saferdialogues_teacher': 'create a SaferDialoguesTeacher instance to load and serve SaFeRDialogues dialogue data for training', 'create_saferdialogues_bad_teacher': 'create a SaferDialoguesBADTeacher instance to load adversarial SaFeRDialogues data with bad responses', 'configure_recovery_option': 'configure the recovery utterance flag on SaferDialoguesTeacher to include or exclude recovery messages', 'setup_data_without_recovery': 'setup SaFeRDialogues episode data to use signaling messages as labels instead of recovery utterances', 'get_data_path': 'get the SaFeRDialogues dataset file path for a given datatype using the _path helper function'}
```

## File: facebookresearch_parlai/parlai/tasks/saferdialogues/build.py

Prompts

```
['create a SaferDialoguesTeacher instance to load and serve SaFeRDialogues dialogue data for training', 'create a SaferDialoguesBADTeacher instance to load adversarial SaFeRDialogues data with bad responses', 'configure the recovery utterance flag on SaferDialoguesTeacher to include or exclude recovery messages', 'setup SaFeRDialogues episode data to use signaling messages as labels instead of recovery utterances', 'get the SaFeRDialogues dataset file path for a given datatype using the _path helper function', 'run the build function to download and prepare the saferdialogues dataset into the specified datapath', 'download the saferdialogues v0.4 tar.gz resource file using the RESOURCES list of DownloadableFile objects', 'check if the saferdialogues dataset is already built for version v0.4 using build_data.built', 'remove an older version of the saferdialogues data directory using build_data.remove_dir', 'mark the saferdialogues dataset as built using build_data.mark_done with the version string']
```

Usage

```
{'build_saferdialogues_data': 'run the build function to download and prepare the saferdialogues dataset into the specified datapath', 'download_saferdialogues_resources': 'download the saferdialogues v0.4 tar.gz resource file using the RESOURCES list of DownloadableFile objects', 'check_saferdialogues_built': 'check if the saferdialogues dataset is already built for version v0.4 using build_data.built', 'remove_outdated_saferdialogues': 'remove an older version of the saferdialogues data directory using build_data.remove_dir', 'mark_saferdialogues_done': 'mark the saferdialogues dataset as built using build_data.mark_done with the version string'}
```

