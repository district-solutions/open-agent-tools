# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/sst/agents.py

Prompts

```
['build the SST sentiment analysis dataset by calling the build function with opt configuration', 'create an SSTTeacher instance with opt dict to load sentiment analysis data for training', 'setup SST data by reading CSV file and yielding labeled sentence examples for sentiment classification', 'get the SST label candidates which return negative and positive sentiment labels', 'review the SSTTeacher class that extends DialogTeacher for Stanford Sentiment Treebank binary classification', 'build the SST dataset by downloading train, dev, and test binary sentiment CSV files', 'download the SST binary sentiment CSV files from the OpenAI generating reviews repository', 'check if the SST dataset has already been built in the specified datapath directory', 'remove outdated SST dataset files when an older version exists in the datapath', 'mark the SST dataset as built and complete in the build data directory']
```

Usage

```
{'build_sst_data': 'build the SST sentiment analysis dataset by calling the build function with opt configuration', 'create_sst_teacher': 'create an SSTTeacher instance with opt dict to load sentiment analysis data for training', 'setup_sst_data': 'setup SST data by reading CSV file and yielding labeled sentence examples for sentiment classification', 'get_sst_label_candidates': 'get the SST label candidates which return negative and positive sentiment labels', 'review_sst_teacher_class': 'review the SSTTeacher class that extends DialogTeacher for Stanford Sentiment Treebank binary classification'}
```

## File: facebookresearch_parlai/parlai/tasks/sst/build.py

Prompts

```
['build the SST sentiment analysis dataset by calling the build function with opt configuration', 'create an SSTTeacher instance with opt dict to load sentiment analysis data for training', 'setup SST data by reading CSV file and yielding labeled sentence examples for sentiment classification', 'get the SST label candidates which return negative and positive sentiment labels', 'review the SSTTeacher class that extends DialogTeacher for Stanford Sentiment Treebank binary classification', 'build the SST dataset by downloading train, dev, and test binary sentiment CSV files', 'download the SST binary sentiment CSV files from the OpenAI generating reviews repository', 'check if the SST dataset has already been built in the specified datapath directory', 'remove outdated SST dataset files when an older version exists in the datapath', 'mark the SST dataset as built and complete in the build data directory']
```

Usage

```
{'build_sst_dataset': 'build the SST dataset by downloading train, dev, and test binary sentiment CSV files', 'download_sst_resources': 'download the SST binary sentiment CSV files from the OpenAI generating reviews repository', 'check_sst_data_built': 'check if the SST dataset has already been built in the specified datapath directory', 'remove_outdated_sst_data': 'remove outdated SST dataset files when an older version exists in the datapath', 'mark_sst_data_done': 'mark the SST dataset as built and complete in the build data directory'}
```

