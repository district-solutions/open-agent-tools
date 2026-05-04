# Agent Python Tools

- repo: facebookresearch/eb/jepa
- repo_uri: https://github.com/facebookresearch/eb_jepa

## File: facebookresearch_eb_jepa/examples/ac_video_jepa/eval.py

Prompts

```
['run launch_plan_eval to evaluate the planning capabilities of a trained JEPA model', 'run launch_unroll_eval to evaluate the unrolling prediction capabilities of a trained JEPA model', 'test launch_plan_eval by passing a JEPA model, environment creator, and plan configuration', 'test launch_unroll_eval by passing a JEPA model, environment creator, and evaluation config', 'review launch_plan_eval to understand how it logs success rate and mean state distance', 'run the action-conditioned video JEPA training loop using a YAML config file and optional overrides', 'run evaluation only mode for the JEPA model with plan and unroll eval without training', 'resume training the JEPA model from a saved checkpoint path and continue optimizing', 'configure and run mixed precision AMP training with bfloat16 or float16 dtype for JEPA', 'launch plan and unroll evaluation episodes for the trained JEPA model in the DotWall environment']
```

Usage

```
{'run_launch_plan_eval': 'run launch_plan_eval to evaluate the planning capabilities of a trained JEPA model', 'run_launch_unroll_eval': 'run launch_unroll_eval to evaluate the unrolling prediction capabilities of a trained JEPA model', 'test_launch_plan_eval': 'test launch_plan_eval by passing a JEPA model, environment creator, and plan configuration', 'test_launch_unroll_eval': 'test launch_unroll_eval by passing a JEPA model, environment creator, and evaluation config', 'review_launch_plan_eval': 'review launch_plan_eval to understand how it logs success rate and mean state distance'}
```

## File: facebookresearch_eb_jepa/examples/ac_video_jepa/main.py

Prompts

```
['run launch_plan_eval to evaluate the planning capabilities of a trained JEPA model', 'run launch_unroll_eval to evaluate the unrolling prediction capabilities of a trained JEPA model', 'test launch_plan_eval by passing a JEPA model, environment creator, and plan configuration', 'test launch_unroll_eval by passing a JEPA model, environment creator, and evaluation config', 'review launch_plan_eval to understand how it logs success rate and mean state distance', 'run the action-conditioned video JEPA training loop using a YAML config file and optional overrides', 'run evaluation only mode for the JEPA model with plan and unroll eval without training', 'resume training the JEPA model from a saved checkpoint path and continue optimizing', 'configure and run mixed precision AMP training with bfloat16 or float16 dtype for JEPA', 'launch plan and unroll evaluation episodes for the trained JEPA model in the DotWall environment']
```

Usage

```
{'run_train_ac_video_jepa': 'run the action-conditioned video JEPA training loop using a YAML config file and optional overrides', 'run_eval_only_mode': 'run evaluation only mode for the JEPA model with plan and unroll eval without training', 'run_resume_training_from_checkpoint': 'resume training the JEPA model from a saved checkpoint path and continue optimizing', 'run_configure_mixed_precision_training': 'configure and run mixed precision AMP training with bfloat16 or float16 dtype for JEPA', 'run_launch_plan_and_unroll_eval': 'launch plan and unroll evaluation episodes for the trained JEPA model in the DotWall environment'}
```

