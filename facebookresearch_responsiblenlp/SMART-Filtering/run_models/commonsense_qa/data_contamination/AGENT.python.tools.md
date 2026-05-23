# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/commonsense_qa/data_contamination/evaluate_hf.py

Prompts

```
['run a HuggingFace causal LM model to evaluate multiple choice questions on a dataset and save accuracy results', 'evaluate a model on test data by computing per-choice softmax probabilities and accuracy for a subject', 'generate a few-shot prompt from training examples for a multiple choice question subject', 'format a single row from a DataFrame as a multiple choice question prompt with optional answer', 'load a pretrained model and tokenizer, iterate over subjects, run evaluation, and save CSV results']
```

Usage

```
{'run_model_evaluation': 'run a HuggingFace causal LM model to evaluate multiple choice questions on a dataset and save accuracy results', 'eval_function': 'evaluate a model on test data by computing per-choice softmax probabilities and accuracy for a subject', 'gen_prompt_function': 'generate a few-shot prompt from training examples for a multiple choice question subject', 'format_example_function': 'format a single row from a DataFrame as a multiple choice question prompt with optional answer', 'main_function': 'load a pretrained model and tokenizer, iterate over subjects, run evaluation, and save CSV results'}
```

