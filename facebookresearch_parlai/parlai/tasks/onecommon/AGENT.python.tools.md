# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/onecommon/agents.py

Prompts

```
['build a OneCommonTeacher instance to load and serve the OneCommon reference resolution dataset for dialogue training', 'create a function call to get_tag that extracts token values between XML-style tags from a token list', 'test the OneCommonTeacher observe method to compute selection accuracy and referent exact match metrics', 'review the OneCommonTeacher _split_dialogue method that parses raw dialogue tokens into alternating utterance turns', 'refactor the OneCommonTeacher _split_referents method to parse raw referent data into structured begin end target dictionaries', 'run the build function to download and set up the onecommon dataset in the ParlAI datapath', 'download the onecommon v1.0 zip archive from the Alab-NII GitHub repository', 'review the build function to understand how it manages versioned data directories', 'summarize the RESOURCES list containing DownloadableFile entries for the onecommon dataset', 'refactor the build function to support a newer version of the onecommon dataset']
```

Usage

```
{'build_OneCommonTeacher': 'build a OneCommonTeacher instance to load and serve the OneCommon reference resolution dataset for dialogue training', 'create_get_tag': 'create a function call to get_tag that extracts token values between XML-style tags from a token list', 'test_OneCommonTeacher_observe': 'test the OneCommonTeacher observe method to compute selection accuracy and referent exact match metrics', 'review_OneCommonTeacher_split_dialogue': 'review the OneCommonTeacher _split_dialogue method that parses raw dialogue tokens into alternating utterance turns', 'refactor_OneCommonTeacher_split_referents': 'refactor the OneCommonTeacher _split_referents method to parse raw referent data into structured begin end target dictionaries'}
```

## File: facebookresearch_parlai/parlai/tasks/onecommon/build.py

Prompts

```
['build a OneCommonTeacher instance to load and serve the OneCommon reference resolution dataset for dialogue training', 'create a function call to get_tag that extracts token values between XML-style tags from a token list', 'test the OneCommonTeacher observe method to compute selection accuracy and referent exact match metrics', 'review the OneCommonTeacher _split_dialogue method that parses raw dialogue tokens into alternating utterance turns', 'refactor the OneCommonTeacher _split_referents method to parse raw referent data into structured begin end target dictionaries', 'run the build function to download and set up the onecommon dataset in the ParlAI datapath', 'download the onecommon v1.0 zip archive from the Alab-NII GitHub repository', 'review the build function to understand how it manages versioned data directories', 'summarize the RESOURCES list containing DownloadableFile entries for the onecommon dataset', 'refactor the build function to support a newer version of the onecommon dataset']
```

Usage

```
{'build_onecommon_dataset': 'run the build function to download and set up the onecommon dataset in the ParlAI datapath', 'download_onecommon_resources': 'download the onecommon v1.0 zip archive from the Alab-NII GitHub repository', 'review_build_function': 'review the build function to understand how it manages versioned data directories', 'summarize_RESOURCES': 'summarize the RESOURCES list containing DownloadableFile entries for the onecommon dataset', 'refactor_build_versioning': 'refactor the build function to support a newer version of the onecommon dataset'}
```

