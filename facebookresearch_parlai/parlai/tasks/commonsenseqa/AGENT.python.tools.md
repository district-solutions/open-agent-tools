# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/commonsenseqa/agents.py

Prompts

```
['build a CommonSenseQA teacher that loads multiple-choice QA episodes from JSONL data files', 'setup the CommonSenseQA dataset by loading train or test episodes from JSONL files with an 80/10/10 split', 'get a CommonSenseQA episode with the question stem, answer labels, and multiple-choice candidates', 'share CommonSenseQA episodes across teacher instances for multi-worker data loading', 'review the CommonSenseQATeacher class and its methods for loading and serving multiple-choice QA data', 'build the CommonSenseQA dataset by downloading train and dev splits to the ParlAI datapath directory', 'download the CommonSenseQA train and dev JSONL files from S3 using the RESOURCES list', 'check if the CommonSenseQA dataset has already been built using build_data.built with version string', 'remove an existing CommonSenseQA data directory using build_data.remove_dir before rebuilding', 'mark the CommonSenseQA dataset build as complete using build_data.mark_done with the version string']
```

Usage

```
{'build_commonsenseqa_teacher': 'build a CommonSenseQA teacher that loads multiple-choice QA episodes from JSONL data files', 'setup_commonsenseqa_data': 'setup the CommonSenseQA dataset by loading train or test episodes from JSONL files with an 80/10/10 split', 'get_commonsenseqa_episode': 'get a CommonSenseQA episode with the question stem, answer labels, and multiple-choice candidates', 'share_commonsenseqa_episodes': 'share CommonSenseQA episodes across teacher instances for multi-worker data loading', 'review_commonsenseqa_teacher': 'review the CommonSenseQATeacher class and its methods for loading and serving multiple-choice QA data'}
```

## File: facebookresearch_parlai/parlai/tasks/commonsenseqa/build.py

Prompts

```
['build a CommonSenseQA teacher that loads multiple-choice QA episodes from JSONL data files', 'setup the CommonSenseQA dataset by loading train or test episodes from JSONL files with an 80/10/10 split', 'get a CommonSenseQA episode with the question stem, answer labels, and multiple-choice candidates', 'share CommonSenseQA episodes across teacher instances for multi-worker data loading', 'review the CommonSenseQATeacher class and its methods for loading and serving multiple-choice QA data', 'build the CommonSenseQA dataset by downloading train and dev splits to the ParlAI datapath directory', 'download the CommonSenseQA train and dev JSONL files from S3 using the RESOURCES list', 'check if the CommonSenseQA dataset has already been built using build_data.built with version string', 'remove an existing CommonSenseQA data directory using build_data.remove_dir before rebuilding', 'mark the CommonSenseQA dataset build as complete using build_data.mark_done with the version string']
```

Usage

```
{'build_commonsenseqa_data': 'build the CommonSenseQA dataset by downloading train and dev splits to the ParlAI datapath directory', 'download_commonsenseqa_resources': 'download the CommonSenseQA train and dev JSONL files from S3 using the RESOURCES list', 'check_commonsenseqa_built': 'check if the CommonSenseQA dataset has already been built using build_data.built with version string', 'remove_commonsenseqa_data': 'remove an existing CommonSenseQA data directory using build_data.remove_dir before rebuilding', 'mark_commonsenseqa_done': 'mark the CommonSenseQA dataset build as complete using build_data.mark_done with the version string'}
```

