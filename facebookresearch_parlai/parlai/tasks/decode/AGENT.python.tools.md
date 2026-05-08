# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/decode/agents.py

Prompts

```
['build a Parlai DecodeTeacher to load DECODE dataset JSONL files for dialogue training', 'create a data path for the DECODE dataset using the _path function with datatype and test_type options', 'test the DecodeTeacher setup_data method to yield turns with contradiction labels from JSONL episodes', 'refactor the DecodeTeacher to support additional test types beyond vanilla, human-bot, a2t, and rct', 'review the DecodeTeacher __init__ method to understand how opt, datatype, and datafile are configured', 'build the DECODE dataset by downloading and extracting data to the ParlAI datapath directory', 'run the build function to download DECODE dataset resources and mark data as built', 'download the DECODE dataset zip file using the DownloadableFile resource list', 'check if the DECODE dataset is already built at the expected version string', 'remove outdated DECODE dataset files when an older version exists in the datapath']
```

Usage

```
{'build_decode_teacher': 'build a Parlai DecodeTeacher to load DECODE dataset JSONL files for dialogue training', 'create_decode_data_path': 'create a data path for the DECODE dataset using the _path function with datatype and test_type options', 'test_decode_setup_data': 'test the DecodeTeacher setup_data method to yield turns with contradiction labels from JSONL episodes', 'refactor_decode_test_types': 'refactor the DecodeTeacher to support additional test types beyond vanilla, human-bot, a2t, and rct', 'review_decode_teacher_init': 'review the DecodeTeacher __init__ method to understand how opt, datatype, and datafile are configured'}
```

## File: facebookresearch_parlai/parlai/tasks/decode/build.py

Prompts

```
['build a Parlai DecodeTeacher to load DECODE dataset JSONL files for dialogue training', 'create a data path for the DECODE dataset using the _path function with datatype and test_type options', 'test the DecodeTeacher setup_data method to yield turns with contradiction labels from JSONL episodes', 'refactor the DecodeTeacher to support additional test types beyond vanilla, human-bot, a2t, and rct', 'review the DecodeTeacher __init__ method to understand how opt, datatype, and datafile are configured', 'build the DECODE dataset by downloading and extracting data to the ParlAI datapath directory', 'run the build function to download DECODE dataset resources and mark data as built', 'download the DECODE dataset zip file using the DownloadableFile resource list', 'check if the DECODE dataset is already built at the expected version string', 'remove outdated DECODE dataset files when an older version exists in the datapath']
```

Usage

```
{'build_decode_dataset': 'build the DECODE dataset by downloading and extracting data to the ParlAI datapath directory', 'run_build_function': 'run the build function to download DECODE dataset resources and mark data as built', 'download_decode_resources': 'download the DECODE dataset zip file using the DownloadableFile resource list', 'check_decode_version': 'check if the DECODE dataset is already built at the expected version string', 'remove_old_decode_data': 'remove outdated DECODE dataset files when an older version exists in the datapath'}
```

