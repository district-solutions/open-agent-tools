# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/eval/eval_cli.py

Prompts

```
['run evaluation on a pre-trained model using the hf backend with default lm-eval tasks', 'run evaluation on a model using the vllm backend with custom tensor parallel size', 'run evaluation on tasks sequentially with automatic retry on out of memory errors', 'run evaluation on a diffusion model with CLIP metrics and custom guidance scale', 'parse a comma separated string of vllm arguments into a typed dictionary of kwargs', 'run model evaluation for a quantized model using lm_eval with specified tasks and batch size', 'evaluate a HuggingFace model instance with a tokenizer on specified lm_eval tasks', 'run lm_eval simple_evaluate with a model type string and model arguments', 'evaluate a diffusion model by generating images from prompts and computing metrics', 'prepare a quantized model for evaluation by dispatching blocks and setting dtype']
```

Usage

```
{'run_eval_model': 'run evaluation on a pre-trained model using the hf backend with default lm-eval tasks', 'run_eval_vllm': 'run evaluation on a model using the vllm backend with custom tensor parallel size', 'run_eval_task_by_task': 'run evaluation on tasks sequentially with automatic retry on out of memory errors', 'run_eval_diffusion': 'run evaluation on a diffusion model with CLIP metrics and custom guidance scale', 'parse_vllm_args': 'parse a comma separated string of vllm arguments into a typed dictionary of kwargs'}
```

## File: intel_auto-round/auto_round/eval/evaluation.py

Prompts

```
['run evaluation on a pre-trained model using the hf backend with default lm-eval tasks', 'run evaluation on a model using the vllm backend with custom tensor parallel size', 'run evaluation on tasks sequentially with automatic retry on out of memory errors', 'run evaluation on a diffusion model with CLIP metrics and custom guidance scale', 'parse a comma separated string of vllm arguments into a typed dictionary of kwargs', 'run model evaluation for a quantized model using lm_eval with specified tasks and batch size', 'evaluate a HuggingFace model instance with a tokenizer on specified lm_eval tasks', 'run lm_eval simple_evaluate with a model type string and model arguments', 'evaluate a diffusion model by generating images from prompts and computing metrics', 'prepare a quantized model for evaluation by dispatching blocks and setting dtype']
```

Usage

```
{'run_model_evaluation': 'run model evaluation for a quantized model using lm_eval with specified tasks and batch size', 'simple_evaluate_user_model': 'evaluate a HuggingFace model instance with a tokenizer on specified lm_eval tasks', 'simple_evaluate': 'run lm_eval simple_evaluate with a model type string and model arguments', 'evaluate_diffusion_model': 'evaluate a diffusion model by generating images from prompts and computing metrics', 'prepare_model_for_eval': 'prepare a quantized model for evaluation by dispatching blocks and setting dtype'}
```

