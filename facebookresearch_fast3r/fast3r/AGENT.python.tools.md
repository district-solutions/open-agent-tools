# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/eval.py

Prompts

```
['run the evaluate function to validate a Fast3R model checkpoint on a datamodule testset', 'run the main entry point to start Hydra-based evaluation with an eval.yaml config', 'test the evaluate function by passing a DictConfig with ckpt_path and data module settings', 'review the python_eval_resolver function that evaluates arbitrary Python code strings via eval', 'refactor the replace_dust3r_in_config helper to recursively replace dust3r module paths with fast3r.dust3r paths', 'run resume_train.py with a run directory path to resume training from the last checkpoint', 'run load_resume_config to load Hydra config and checkpoint path from a given run directory', 'test the resume_train function by passing a run directory path and verifying metric value is returned', 'review the load_resume_config function that loads Hydra config.yaml and sets checkpoint path for resuming', 'review the resume_train function that loads config, applies extras, trains model, and returns optimized metric value', 'run the fast3r model training pipeline using hydra config and lightning trainer', 'test the train function by passing a DictConfig with model and data module settings', 'refactor the train function to support custom checkpoint paths and test mode toggles']
```

Usage

```
{'run_evaluation': 'run the evaluate function to validate a Fast3R model checkpoint on a datamodule testset', 'run_main_entry': 'run the main entry point to start Hydra-based evaluation with an eval.yaml config', 'test_evaluate_function': 'test the evaluate function by passing a DictConfig with ckpt_path and data module settings', 'review_python_eval_resolver': 'review the python_eval_resolver function that evaluates arbitrary Python code strings via eval', 'refactor_replace_dust3r_in_config': 'refactor the replace_dust3r_in_config helper to recursively replace dust3r module paths with fast3r.dust3r paths'}
```

## File: facebookresearch_fast3r/fast3r/resume_train.py

Prompts

```
['run the evaluate function to validate a Fast3R model checkpoint on a datamodule testset', 'run the main entry point to start Hydra-based evaluation with an eval.yaml config', 'test the evaluate function by passing a DictConfig with ckpt_path and data module settings', 'review the python_eval_resolver function that evaluates arbitrary Python code strings via eval', 'refactor the replace_dust3r_in_config helper to recursively replace dust3r module paths with fast3r.dust3r paths', 'run resume_train.py with a run directory path to resume training from the last checkpoint', 'run load_resume_config to load Hydra config and checkpoint path from a given run directory', 'test the resume_train function by passing a run directory path and verifying metric value is returned', 'review the load_resume_config function that loads Hydra config.yaml and sets checkpoint path for resuming', 'review the resume_train function that loads config, applies extras, trains model, and returns optimized metric value', 'run the fast3r model training pipeline using hydra config and lightning trainer', 'test the train function by passing a DictConfig with model and data module settings', 'refactor the train function to support custom checkpoint paths and test mode toggles']
```

Usage

```
{'run_resume_train': 'run resume_train.py with a run directory path to resume training from the last checkpoint', 'run_load_resume_config': 'run load_resume_config to load Hydra config and checkpoint path from a given run directory', 'test_resume_train': 'test the resume_train function by passing a run directory path and verifying metric value is returned', 'review_load_resume_config': 'review the load_resume_config function that loads Hydra config.yaml and sets checkpoint path for resuming', 'review_resume_train': 'review the resume_train function that loads config, applies extras, trains model, and returns optimized metric value'}
```

## File: facebookresearch_fast3r/fast3r/train.py

Prompts

```
['run the evaluate function to validate a Fast3R model checkpoint on a datamodule testset', 'run the main entry point to start Hydra-based evaluation with an eval.yaml config', 'test the evaluate function by passing a DictConfig with ckpt_path and data module settings', 'review the python_eval_resolver function that evaluates arbitrary Python code strings via eval', 'refactor the replace_dust3r_in_config helper to recursively replace dust3r module paths with fast3r.dust3r paths', 'run resume_train.py with a run directory path to resume training from the last checkpoint', 'run load_resume_config to load Hydra config and checkpoint path from a given run directory', 'test the resume_train function by passing a run directory path and verifying metric value is returned', 'review the load_resume_config function that loads Hydra config.yaml and sets checkpoint path for resuming', 'review the resume_train function that loads config, applies extras, trains model, and returns optimized metric value', 'run the fast3r model training pipeline using hydra config and lightning trainer', 'test the train function by passing a DictConfig with model and data module settings', 'refactor the train function to support custom checkpoint paths and test mode toggles']
```

Usage

```
{'run_train_model': 'run the fast3r model training pipeline using hydra config and lightning trainer', 'run_main_entry': 'run the main training entry point with hydra config from train.yaml', 'test_train_function': 'test the train function by passing a DictConfig with model and data module settings', 'review_python_eval_resolver': 'review the python_eval_resolver function that evaluates Python code strings via eval', 'refactor_train_function': 'refactor the train function to support custom checkpoint paths and test mode toggles'}
```

