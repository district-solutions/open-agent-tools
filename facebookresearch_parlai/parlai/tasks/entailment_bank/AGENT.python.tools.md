# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/entailment_bank/agents.py

Prompts

```
['run the EntailmentBankStepByStepReasoningTeacher to load and serve ARC science entailment tree data for training', 'parse a context string with sent1 sent2 labels into a plain sentence list using _parse_context', 'extract reasoning steps from a full text proof string using _get_steps to split on BECAUSE AND INFER tokens', 'configure the teacher with --task-id 1 2 or 3 to select which entailment task dataset to use', 'enable extrinsic step mode with --extrinsic-step to inject a random step from another example into each data point', 'build the entailment_bank dataset by downloading and extracting data to the ParlAI datapath directory', 'download the entailment trees EMNLP 2021 dataset v3 from Google Drive using the build function', 'check if the entailment_bank dataset has already been built using build_data.built with a version string', 'remove outdated versions of the entailment_bank dataset directory using build_data.remove_dir before rebuilding', 'mark the entailment_bank dataset as built and complete using build_data.mark_done with a version string']
```

Usage

```
{'run_entailment_bank_teacher': 'run the EntailmentBankStepByStepReasoningTeacher to load and serve ARC science entailment tree data for training', 'parse_context_sentences': 'parse a context string with sent1 sent2 labels into a plain sentence list using _parse_context', 'extract_entailment_steps': 'extract reasoning steps from a full text proof string using _get_steps to split on BECAUSE AND INFER tokens', 'configure_task_id': 'configure the teacher with --task-id 1 2 or 3 to select which entailment task dataset to use', 'enable_extrinsic_step': 'enable extrinsic step mode with --extrinsic-step to inject a random step from another example into each data point'}
```

## File: facebookresearch_parlai/parlai/tasks/entailment_bank/build.py

Prompts

```
['run the EntailmentBankStepByStepReasoningTeacher to load and serve ARC science entailment tree data for training', 'parse a context string with sent1 sent2 labels into a plain sentence list using _parse_context', 'extract reasoning steps from a full text proof string using _get_steps to split on BECAUSE AND INFER tokens', 'configure the teacher with --task-id 1 2 or 3 to select which entailment task dataset to use', 'enable extrinsic step mode with --extrinsic-step to inject a random step from another example into each data point', 'build the entailment_bank dataset by downloading and extracting data to the ParlAI datapath directory', 'download the entailment trees EMNLP 2021 dataset v3 from Google Drive using the build function', 'check if the entailment_bank dataset has already been built using build_data.built with a version string', 'remove outdated versions of the entailment_bank dataset directory using build_data.remove_dir before rebuilding', 'mark the entailment_bank dataset as built and complete using build_data.mark_done with a version string']
```

Usage

```
{'build_entailment_bank_data': 'build the entailment_bank dataset by downloading and extracting data to the ParlAI datapath directory', 'download_entailment_trees': 'download the entailment trees EMNLP 2021 dataset v3 from Google Drive using the build function', 'check_data_built': 'check if the entailment_bank dataset has already been built using build_data.built with a version string', 'remove_old_data': 'remove outdated versions of the entailment_bank dataset directory using build_data.remove_dir before rebuilding', 'mark_data_done': 'mark the entailment_bank dataset as built and complete using build_data.mark_done with a version string'}
```

