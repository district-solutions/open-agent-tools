# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/SMART-Filtering/run_models/commonsense_qa/entire_dataset/evaluate_hf.py

Prompts

```
['run a HuggingFace causal LM model on the CommonsenseQA dataset and save accuracy results to CSV', 'evaluate a model on a test dataframe by computing per-choice softmax probabilities and accuracy', 'generate an in-context learning prompt from training examples for a multiple choice question subject', 'format a single row from a CSV dataframe into a multiple choice question prompt with optional answer', 'load a pretrained causal LM, iterate over subjects, evaluate, and save results with choice probabilities']
```

Usage

```
{'run_evaluation': 'run a HuggingFace causal LM model on the CommonsenseQA dataset and save accuracy results to CSV', 'eval_function': 'evaluate a model on a test dataframe by computing per-choice softmax probabilities and accuracy', 'gen_prompt': 'generate an in-context learning prompt from training examples for a multiple choice question subject', 'format_example': 'format a single row from a CSV dataframe into a multiple choice question prompt with optional answer', 'main_function': 'load a pretrained causal LM, iterate over subjects, evaluate, and save results with choice probabilities'}
```

