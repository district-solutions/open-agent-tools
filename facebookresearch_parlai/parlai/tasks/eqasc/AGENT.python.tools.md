# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/eqasc/agents.py

Prompts

```
['run the EqascStepByStepReasoningTeacher to load and iterate over E-QASC multihop QA reasoning chain data', 'review the get_data_for_fold method that yields questions, facts, steps, and answers from the E-QASC dataset', 'refactor the EqascStepByStepReasoningTeacher to customize extrinsic step randomization behavior for multihop QA examples', 'test the add_cmdline_args method to verify the extrinsic-step flag and task prompt defaults are set correctly', 'build the E-QASC dataset by calling the build function to download and prepare eqasc JSON files for training', 'download the eqasc_train_grc, eqasc_dev_grc, and eqasc_test_grc JSON files to the data path', 'check if the eQASC dataset has already been built at the given datapath and version', 'remove an older version of the eQASC dataset directory before rebuilding with the latest version', 'review the build function that manages downloading and versioning the eQASC dataset for ParlAI']
```

Usage

```
{'run_eqasc_teacher': 'run the EqascStepByStepReasoningTeacher to load and iterate over E-QASC multihop QA reasoning chain data', 'review_get_data_for_fold': 'review the get_data_for_fold method that yields questions, facts, steps, and answers from the E-QASC dataset', 'refactor_extrinsic_step': 'refactor the EqascStepByStepReasoningTeacher to customize extrinsic step randomization behavior for multihop QA examples', 'test_add_cmdline_args': 'test the add_cmdline_args method to verify the extrinsic-step flag and task prompt defaults are set correctly', 'build_eqasc_dataset': 'build the E-QASC dataset by calling the build function to download and prepare eqasc JSON files for training'}
```

## File: facebookresearch_parlai/parlai/tasks/eqasc/build.py

Prompts

```
['run the EqascStepByStepReasoningTeacher to load and iterate over E-QASC multihop QA reasoning chain data', 'review the get_data_for_fold method that yields questions, facts, steps, and answers from the E-QASC dataset', 'refactor the EqascStepByStepReasoningTeacher to customize extrinsic step randomization behavior for multihop QA examples', 'test the add_cmdline_args method to verify the extrinsic-step flag and task prompt defaults are set correctly', 'build the E-QASC dataset by calling the build function to download and prepare eqasc JSON files for training', 'download the eqasc_train_grc, eqasc_dev_grc, and eqasc_test_grc JSON files to the data path', 'check if the eQASC dataset has already been built at the given datapath and version', 'remove an older version of the eQASC dataset directory before rebuilding with the latest version', 'review the build function that manages downloading and versioning the eQASC dataset for ParlAI']
```

Usage

```
{'build_eqasc_dataset': 'run the build function to download the eQASC multihop QA dataset files from Google Drive', 'download_eqasc_resources': 'download the eqasc_train_grc, eqasc_dev_grc, and eqasc_test_grc JSON files to the data path', 'check_eqasc_built': 'check if the eQASC dataset has already been built at the given datapath and version', 'remove_old_eqasc_data': 'remove an older version of the eQASC dataset directory before rebuilding with the latest version', 'review_build_function': 'review the build function that manages downloading and versioning the eQASC dataset for ParlAI'}
```

