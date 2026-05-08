# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dstc7/agents.py

Prompts

```
['review the DSTC7Teacher class that loads and serves the DSTC7 Ubuntu dialogue dataset for dialogue response selection', 'review the DSTC7Teacher get method that returns text, labels, and label_candidates for a given episode index', 'review the DSTC7TeacherAugmented class that splits single episodes across multiple entries for multi-turn dialogue training', 'review the DSTC7TeacherAugmentedSampled class that limits training candidates to 16 responses including the correct one', 'summarize the DSTC7Teacher share method that returns shared data for multi-worker parallel training', 'build the DSTC7 dataset by downloading and extracting data to the ParlAI datapath directory', 'review the build function that downloads DSTC7 data and marks it as built with version tracking', 'summarize the RESOURCES list containing DownloadableFile entries for the DSTC7 dataset archive', 'test the build function version check logic that removes outdated data before downloading', 'refactor the build function to support additional DSTC7 downloadable resources or alternate data paths']
```

Usage

```
{'review_DSTC7Teacher_class': 'review the DSTC7Teacher class that loads and serves the DSTC7 Ubuntu dialogue dataset for dialogue response selection', 'review_DSTC7Teacher_get_method': 'review the DSTC7Teacher get method that returns text, labels, and label_candidates for a given episode index', 'review_DSTC7TeacherAugmented_class': 'review the DSTC7TeacherAugmented class that splits single episodes across multiple entries for multi-turn dialogue training', 'review_DSTC7TeacherAugmentedSampled_class': 'review the DSTC7TeacherAugmentedSampled class that limits training candidates to 16 responses including the correct one', 'summarize_DSTC7Teacher_share_method': 'summarize the DSTC7Teacher share method that returns shared data for multi-worker parallel training'}
```

## File: facebookresearch_parlai/parlai/tasks/dstc7/build.py

Prompts

```
['review the DSTC7Teacher class that loads and serves the DSTC7 Ubuntu dialogue dataset for dialogue response selection', 'review the DSTC7Teacher get method that returns text, labels, and label_candidates for a given episode index', 'review the DSTC7TeacherAugmented class that splits single episodes across multiple entries for multi-turn dialogue training', 'review the DSTC7TeacherAugmentedSampled class that limits training candidates to 16 responses including the correct one', 'summarize the DSTC7Teacher share method that returns shared data for multi-worker parallel training', 'build the DSTC7 dataset by downloading and extracting data to the ParlAI datapath directory', 'review the build function that downloads DSTC7 data and marks it as built with version tracking', 'summarize the RESOURCES list containing DownloadableFile entries for the DSTC7 dataset archive', 'test the build function version check logic that removes outdated data before downloading', 'refactor the build function to support additional DSTC7 downloadable resources or alternate data paths']
```

Usage

```
{'build_dstc7_dataset': 'build the DSTC7 dataset by downloading and extracting data to the ParlAI datapath directory', 'review_build_function': 'review the build function that downloads DSTC7 data and marks it as built with version tracking', 'summarize_resources_list': 'summarize the RESOURCES list containing DownloadableFile entries for the DSTC7 dataset archive', 'test_build_version_check': 'test the build function version check logic that removes outdated data before downloading', 'refactor_build_download': 'refactor the build function to support additional DSTC7 downloadable resources or alternate data paths'}
```

