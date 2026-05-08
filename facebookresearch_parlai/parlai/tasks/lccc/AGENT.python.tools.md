# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/lccc/agents.py

Prompts

```
['build the LCCC dataset by calling the build function to download and prepare conversation data', 'create an LCCCTeacher instance to load and serve the LCCC conversational dataset for training', 'configure the LCCC teacher to use firstspeaker, secondspeaker, or both as label turns', 'get the path to the LCCC JSON data file for a given datatype using the _path function', 'review the LCCCTeacher class and its add_cmdline_args method for LCCC task argument configuration', 'build the LCCC dataset by downloading and converting it to Parlai ConversationTeacher format', 'run the build function to download LCCC data and create train valid and test splits', 'create Parlai format JSON files from LCCC base split data for train valid and test sets', 'download the LCCC base split zip file from Google Drive using the DownloadableFile resource', 'convert LCCC dialog episodes into ConversationTeacher format with alternating partner IDs and cleaned text']
```

Usage

```
{'build_lccc_data': 'build the LCCC dataset by calling the build function to download and prepare conversation data', 'create_lccc_teacher': 'create an LCCCTeacher instance to load and serve the LCCC conversational dataset for training', 'configure_label_turns': 'configure the LCCC teacher to use firstspeaker, secondspeaker, or both as label turns', 'get_lccc_data_path': 'get the path to the LCCC JSON data file for a given datatype using the _path function', 'review_lccc_teacher': 'review the LCCCTeacher class and its add_cmdline_args method for LCCC task argument configuration'}
```

## File: facebookresearch_parlai/parlai/tasks/lccc/build.py

Prompts

```
['build the LCCC dataset by calling the build function to download and prepare conversation data', 'create an LCCCTeacher instance to load and serve the LCCC conversational dataset for training', 'configure the LCCC teacher to use firstspeaker, secondspeaker, or both as label turns', 'get the path to the LCCC JSON data file for a given datatype using the _path function', 'review the LCCCTeacher class and its add_cmdline_args method for LCCC task argument configuration', 'build the LCCC dataset by downloading and converting it to Parlai ConversationTeacher format', 'run the build function to download LCCC data and create train valid and test splits', 'create Parlai format JSON files from LCCC base split data for train valid and test sets', 'download the LCCC base split zip file from Google Drive using the DownloadableFile resource', 'convert LCCC dialog episodes into ConversationTeacher format with alternating partner IDs and cleaned text']
```

Usage

```
{'build_lccc_dataset': 'build the LCCC dataset by downloading and converting it to Parlai ConversationTeacher format', 'run_build_function': 'run the build function to download LCCC data and create train valid and test splits', 'create_parlai_format': 'create Parlai format JSON files from LCCC base split data for train valid and test sets', 'download_lccc_resources': 'download the LCCC base split zip file from Google Drive using the DownloadableFile resource', 'convert_dialog_episodes': 'convert LCCC dialog episodes into ConversationTeacher format with alternating partner IDs and cleaned text'}
```

