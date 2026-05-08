# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/cnn_dm/agents.py

Prompts

```
['build the CNN/DailyMail dataset by calling the build function to download and prepare data files', 'create a CNNDMTeacher instance with opt dict containing datapath and datatype for CNN/DailyMail dialogue tasks', 'setup CNN/DailyMail story data by loading articles and highlights from the input path file', 'fix lines missing terminal punctuation by appending a period when no end token is found', 'use the DefaultTeacher class as an alias for CNNDMTeacher to load CNN/DailyMail dialogue data', 'build the CNN/DailyMail dataset by downloading resources and creating train valid test splits', 'download CNN and DailyMail story archives and wayback URL list files to the data path', 'generate train valid and test split files from wayback URL lists using SHA1 hashed filenames', 'check if the CNN_DM dataset has already been built at the given data path', 'review the build function that downloads data and processes CNN and DailyMail URL lists into splits']
```

Usage

```
{'build_cnndm_data': 'build the CNN/DailyMail dataset by calling the build function to download and prepare data files', 'create_cnndm_teacher': 'create a CNNDMTeacher instance with opt dict containing datapath and datatype for CNN/DailyMail dialogue tasks', 'setup_cnndm_data': 'setup CNN/DailyMail story data by loading articles and highlights from the input path file', 'fix_missing_period': 'fix lines missing terminal punctuation by appending a period when no end token is found', 'use_default_teacher': 'use the DefaultTeacher class as an alias for CNNDMTeacher to load CNN/DailyMail dialogue data'}
```

## File: facebookresearch_parlai/parlai/tasks/cnn_dm/build.py

Prompts

```
['build the CNN/DailyMail dataset by calling the build function to download and prepare data files', 'create a CNNDMTeacher instance with opt dict containing datapath and datatype for CNN/DailyMail dialogue tasks', 'setup CNN/DailyMail story data by loading articles and highlights from the input path file', 'fix lines missing terminal punctuation by appending a period when no end token is found', 'use the DefaultTeacher class as an alias for CNNDMTeacher to load CNN/DailyMail dialogue data', 'build the CNN/DailyMail dataset by downloading resources and creating train valid test splits', 'download CNN and DailyMail story archives and wayback URL list files to the data path', 'generate train valid and test split files from wayback URL lists using SHA1 hashed filenames', 'check if the CNN_DM dataset has already been built at the given data path', 'review the build function that downloads data and processes CNN and DailyMail URL lists into splits']
```

Usage

```
{'build_cnn_dm_dataset': 'build the CNN/DailyMail dataset by downloading resources and creating train valid test splits', 'download_cnn_dm_resources': 'download CNN and DailyMail story archives and wayback URL list files to the data path', 'generate_split_files': 'generate train valid and test split files from wayback URL lists using SHA1 hashed filenames', 'check_build_status': 'check if the CNN_DM dataset has already been built at the given data path', 'review_build_function': 'review the build function that downloads data and processes CNN and DailyMail URL lists into splits'}
```

