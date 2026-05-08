# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/reframe_thoughts/agents.py

Prompts

```
['build the reframe thoughts dataset by calling the build function with an opt dictionary', 'create a ReframeThoughtsTeacher instance with an opt dict to load the reframe thoughts task data', 'setup reframe thoughts data by parsing JSON lines and yielding input reframe pairs with persona pattern and thought tokens', 'get the reframe thoughts dataset file path for a given datatype using the _path helper function', 'use the DefaultTeacher class as an alias for ReframeThoughtsTeacher to load reframe thoughts task data', 'build the reframe_thoughts dataset checking for existing versions and removing outdated data first', 'download the reframe_thoughts tar.gz resource file to the data directory using DownloadableFile', 'review the build function that manages downloading and versioning reframe_thoughts dataset data', 'summarize the reframe_thoughts build module that handles data download and directory management']
```

Usage

```
{'build_reframe_thoughts_data': 'build the reframe thoughts dataset by calling the build function with an opt dictionary', 'create_reframe_thoughts_teacher': 'create a ReframeThoughtsTeacher instance with an opt dict to load the reframe thoughts task data', 'setup_reframe_data': 'setup reframe thoughts data by parsing JSON lines and yielding input reframe pairs with persona pattern and thought tokens', 'get_reframe_data_path': 'get the reframe thoughts dataset file path for a given datatype using the _path helper function', 'use_default_teacher': 'use the DefaultTeacher class as an alias for ReframeThoughtsTeacher to load reframe thoughts task data'}
```

## File: facebookresearch_parlai/parlai/tasks/reframe_thoughts/build.py

Prompts

```
['build the reframe thoughts dataset by calling the build function with an opt dictionary', 'create a ReframeThoughtsTeacher instance with an opt dict to load the reframe thoughts task data', 'setup reframe thoughts data by parsing JSON lines and yielding input reframe pairs with persona pattern and thought tokens', 'get the reframe thoughts dataset file path for a given datatype using the _path helper function', 'use the DefaultTeacher class as an alias for ReframeThoughtsTeacher to load reframe thoughts task data', 'build the reframe_thoughts dataset checking for existing versions and removing outdated data first', 'download the reframe_thoughts tar.gz resource file to the data directory using DownloadableFile', 'review the build function that manages downloading and versioning reframe_thoughts dataset data', 'summarize the reframe_thoughts build module that handles data download and directory management']
```

Usage

```
{'build_reframe_thoughts_data': 'build the reframe_thoughts dataset by downloading and extracting data to the specified datapath', 'build_reframe_thoughts_version_check': 'build the reframe_thoughts dataset checking for existing versions and removing outdated data first', 'download_reframe_thoughts_resources': 'download the reframe_thoughts tar.gz resource file to the data directory using DownloadableFile', 'review_build_function': 'review the build function that manages downloading and versioning reframe_thoughts dataset data', 'summarize_build_module': 'summarize the reframe_thoughts build module that handles data download and directory management'}
```

