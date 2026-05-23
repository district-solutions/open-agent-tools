# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/mmlu/entire_dataset/evaluate_hf.py

Prompts

```
['run a HuggingFace causal LM model on the MMLU benchmark dataset and save accuracy results', 'evaluate a single MMLU subject by running k-shot inference and computing per-question accuracy', 'generate a few-shot prompt from training examples for a given MMLU subject', 'format a single MMLU multiple choice question row into a prompt string with optional answer', 'save MMLU evaluation results including subcategory, category, and weighted accuracy to a JSON file']
```

Usage

```
{'run_MMLU_evaluation': 'run a HuggingFace causal LM model on the MMLU benchmark dataset and save accuracy results', 'eval_subject_accuracy': 'evaluate a single MMLU subject by running k-shot inference and computing per-question accuracy', 'gen_prompt_fewshot': 'generate a few-shot prompt from training examples for a given MMLU subject', 'format_example_prompt': 'format a single MMLU multiple choice question row into a prompt string with optional answer', 'save_results_json': 'save MMLU evaluation results including subcategory, category, and weighted accuracy to a JSON file'}
```

