# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/MMPT/mmpt_cli/localjob.py

Prompts

```
['run a LocalJob to submit a fairseq training job from a YAML config file', 'create a LocalJob with dryrun mode to preview the fairseq training command without executing', 'review the BaseJob class and its _normalize_cmd method for replacing yaml placeholders in command lists', 'test the JobStatus class to check job completion status and retrieve stdout or stderr output', 'refactor the LocalJob CMD_CONFIG dictionary to add new job types like local_predict or local_big', 'run the MMPT CLI to evaluate all checkpoints and print best metrics for a test config', 'run the MMPT CLI predictor loop to generate visual predictions from a vis config file', 'build a DataLoader with meta, video, text processors and an aligner for MMPT test data', 'review the MMPT predict main function that loads config, builds model, and runs evaluation or prediction', 'test the MMPT predictor by running predict_loop with a loaded model and test dataloader']
```

Usage

```
{'run_localjob_submit': 'run a LocalJob to submit a fairseq training job from a YAML config file', 'create_localjob_dryrun': 'create a LocalJob with dryrun mode to preview the fairseq training command without executing', 'review_basejob_normalize_cmd': 'review the BaseJob class and its _normalize_cmd method for replacing yaml placeholders in command lists', 'test_jobstatus_result': 'test the JobStatus class to check job completion status and retrieve stdout or stderr output', 'refactor_localjob_cmd_config': 'refactor the LocalJob CMD_CONFIG dictionary to add new job types like local_predict or local_big'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt_cli/predict.py

Prompts

```
['run a LocalJob to submit a fairseq training job from a YAML config file', 'create a LocalJob with dryrun mode to preview the fairseq training command without executing', 'review the BaseJob class and its _normalize_cmd method for replacing yaml placeholders in command lists', 'test the JobStatus class to check job completion status and retrieve stdout or stderr output', 'refactor the LocalJob CMD_CONFIG dictionary to add new job types like local_predict or local_big', 'run the MMPT CLI to evaluate all checkpoints and print best metrics for a test config', 'run the MMPT CLI predictor loop to generate visual predictions from a vis config file', 'build a DataLoader with meta, video, text processors and an aligner for MMPT test data', 'review the MMPT predict main function that loads config, builds model, and runs evaluation or prediction', 'test the MMPT predictor by running predict_loop with a loaded model and test dataloader']
```

Usage

```
{'run_mmpt_test_evaluation': 'run the MMPT CLI to evaluate all checkpoints and print best metrics for a test config', 'run_mmpt_visualization': 'run the MMPT CLI predictor loop to generate visual predictions from a vis config file', 'build_mmpt_dataloader': 'build a DataLoader with meta, video, text processors and an aligner for MMPT test data', 'review_mmpt_main': 'review the MMPT predict main function that loads config, builds model, and runs evaluation or prediction', 'test_mmpt_predictor': 'test the MMPT predictor by running predict_loop with a loaded model and test dataloader'}
```

