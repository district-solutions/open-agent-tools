# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/ai2_arc/entire_dataset/evaluate_hf.py

Prompts

```
['run a HuggingFace causal LM to evaluate multiple choice questions on the ai2_arc dataset and save accuracy results', "evaluate a single subject's test set by computing per-choice softmax probabilities and comparing predictions to labels", 'generate a few-shot prompt from training examples for a given subject to prepend to test questions', 'format a single row from a CSV dataframe into a multiple choice question prompt with optional answer', 'format an underscore-separated subject name into a human-readable spaced string for prompts']
```

Usage

```
{'run_hf_model_evaluation': 'run a HuggingFace causal LM to evaluate multiple choice questions on the ai2_arc dataset and save accuracy results', 'eval_subject_accuracy': "evaluate a single subject's test set by computing per-choice softmax probabilities and comparing predictions to labels", 'gen_prompt_few_shot': 'generate a few-shot prompt from training examples for a given subject to prepend to test questions', 'format_example_prompt': 'format a single row from a CSV dataframe into a multiple choice question prompt with optional answer', 'format_subject_name': 'format an underscore-separated subject name into a human-readable spaced string for prompts'}
```

