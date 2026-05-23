# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/gpqa/src/eval/evaluate.py

Prompts

```
['run the evaluate.py CLI to evaluate model outputs on GPQA, Math500, AIME, or LiveCode datasets', 'run the evaluate.py CLI with --apply_backoff to fall back to normal outputs when main answers are invalid', 'extract the final answer from model output using boxed, code block, or Final Information patterns', 'evaluate a single model prediction against a labeled answer and compute EM, accuracy, F1, and math equality metrics', 'normalize a QA answer string by lowercasing, removing articles, punctuation, and fixing whitespace']
```

Usage

```
{'run_evaluation_cli': 'run the evaluate.py CLI to evaluate model outputs on GPQA, Math500, AIME, or LiveCode datasets', 'run_evaluation_with_backoff': 'run the evaluate.py CLI with --apply_backoff to fall back to normal outputs when main answers are invalid', 'extract_answer': 'extract the final answer from model output using boxed, code block, or Final Information patterns', 'evaluate_predictions': 'evaluate a single model prediction against a labeled answer and compute EM, accuracy, F1, and math equality metrics', 'normalize_answer_qa': 'normalize a QA answer string by lowercasing, removing articles, punctuation, and fixing whitespace'}
```

