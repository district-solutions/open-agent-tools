# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/k2r/lightqa/task/agents.py

Prompts

```
['build a SummaryQATeacher to load and serve the SummaryQA dataset for dialogue training', 'setup SummaryQA episode data by loading JSON and yielding examples with episode_done flags', 'evaluate a model response against labels using normalized F1, exact match, and knowledge answer accuracy metrics', 'compute the normalized F1 score between a model response and ground truth labels using F1Metric', 'run the DefaultTeacher which inherits SummaryQATeacher for standard SummaryQA dialogue training', 'run the build function to download and prepare the LightQA train valid and test datasets', 'download the LightQA summaryqa2 train valid and test JSON files from parl.ai to the data path', 'check if the LightQA dataset version v1.0.0 is already built in the datapath directory', 'remove an older version of the LightQA dataset directory before rebuilding with the current version', 'copy a local checkpoint file to the LightQA data directory instead of downloading from the remote URL']
```

Usage

```
{'build_summaryqa_teacher': 'build a SummaryQATeacher to load and serve the SummaryQA dataset for dialogue training', 'setup_summaryqa_data': 'setup SummaryQA episode data by loading JSON and yielding examples with episode_done flags', 'evaluate_summaryqa_response': 'evaluate a model response against labels using normalized F1, exact match, and knowledge answer accuracy metrics', 'compute_normalized_f1': 'compute the normalized F1 score between a model response and ground truth labels using F1Metric', 'run_default_teacher': 'run the DefaultTeacher which inherits SummaryQATeacher for standard SummaryQA dialogue training'}
```

## File: facebookresearch_parlai/projects/k2r/lightqa/task/build.py

Prompts

```
['build a SummaryQATeacher to load and serve the SummaryQA dataset for dialogue training', 'setup SummaryQA episode data by loading JSON and yielding examples with episode_done flags', 'evaluate a model response against labels using normalized F1, exact match, and knowledge answer accuracy metrics', 'compute the normalized F1 score between a model response and ground truth labels using F1Metric', 'run the DefaultTeacher which inherits SummaryQATeacher for standard SummaryQA dialogue training', 'run the build function to download and prepare the LightQA train valid and test datasets', 'download the LightQA summaryqa2 train valid and test JSON files from parl.ai to the data path', 'check if the LightQA dataset version v1.0.0 is already built in the datapath directory', 'remove an older version of the LightQA dataset directory before rebuilding with the current version', 'copy a local checkpoint file to the LightQA data directory instead of downloading from the remote URL']
```

Usage

```
{'build_lightqa_dataset': 'run the build function to download and prepare the LightQA train valid and test datasets', 'download_lightqa_resources': 'download the LightQA summaryqa2 train valid and test JSON files from parl.ai to the data path', 'check_lightqa_version': 'check if the LightQA dataset version v1.0.0 is already built in the datapath directory', 'remove_outdated_lightqa': 'remove an older version of the LightQA dataset directory before rebuilding with the current version', 'copy_checkpoint_lightqa': 'copy a local checkpoint file to the LightQA data directory instead of downloading from the remote URL'}
```

