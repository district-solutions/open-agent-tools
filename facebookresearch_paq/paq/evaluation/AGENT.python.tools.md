# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/evaluation/eval_reranker.py

Prompts

```
['run the eval_reranker CLI to compute exact match scores between predictions and gold answers', 'run exact match evaluation on JSONL prediction and reference files using argparse arguments', 'evaluate exact match scores between a list of predictions and references using evaluate_exact_match', 'summarize the evaluate_exact_match function that computes average exact match over ground truths', 'review the eval_reranker CLI tool that compares predicted answers against gold answers', 'run the eval_retriever CLI to evaluate retrieval results against gold answers with hits@k metrics', 'run the eval_retriever CLI with custom hits@k values like 1,5,20 for retrieval evaluation', 'eval the eval_retriever function to compute exact match scores for retrieved QAs against references', 'review the eval_retriever function and its exact match scoring logic for retrieved question-answer pairs', 'refactor the eval_retriever function to fix the undefined K variable bug in the skip warning message', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute an exact match score between a prediction and ground truth after normalization', 'compute the maximum metric score across all prediction and ground truth pairs', 'normalize text by removing articles like a, an, and the before comparison', 'evaluate exact match across multiple predictions against multiple ground truth answers']
```

Usage

```
{'run_eval_reranker_cli': 'run the eval_reranker CLI to compute exact match scores between predictions and gold answers', 'run_exact_match_evaluation': 'run exact match evaluation on JSONL prediction and reference files using argparse arguments', 'evaluate_exact_match_function': 'evaluate exact match scores between a list of predictions and references using evaluate_exact_match', 'summarize_evaluate_exact_match': 'summarize the evaluate_exact_match function that computes average exact match over ground truths', 'review_eval_reranker_cli': 'review the eval_reranker CLI tool that compares predicted answers against gold answers'}
```

## File: facebookresearch_paq/paq/evaluation/eval_retriever.py

Prompts

```
['run the eval_reranker CLI to compute exact match scores between predictions and gold answers', 'run exact match evaluation on JSONL prediction and reference files using argparse arguments', 'evaluate exact match scores between a list of predictions and references using evaluate_exact_match', 'summarize the evaluate_exact_match function that computes average exact match over ground truths', 'review the eval_reranker CLI tool that compares predicted answers against gold answers', 'run the eval_retriever CLI to evaluate retrieval results against gold answers with hits@k metrics', 'run the eval_retriever CLI with custom hits@k values like 1,5,20 for retrieval evaluation', 'eval the eval_retriever function to compute exact match scores for retrieved QAs against references', 'review the eval_retriever function and its exact match scoring logic for retrieved question-answer pairs', 'refactor the eval_retriever function to fix the undefined K variable bug in the skip warning message', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute an exact match score between a prediction and ground truth after normalization', 'compute the maximum metric score across all prediction and ground truth pairs', 'normalize text by removing articles like a, an, and the before comparison', 'evaluate exact match across multiple predictions against multiple ground truth answers']
```

Usage

```
{'run_eval_retriever_cli': 'run the eval_retriever CLI to evaluate retrieval results against gold answers with hits@k metrics', 'run_eval_retriever_hits_at_k': 'run the eval_retriever CLI with custom hits@k values like 1,5,20 for retrieval evaluation', 'eval_eval_retriever_function': 'eval the eval_retriever function to compute exact match scores for retrieved QAs against references', 'review_eval_retriever_function': 'review the eval_retriever function and its exact match scoring logic for retrieved question-answer pairs', 'refactor_eval_retriever_function': 'refactor the eval_retriever function to fix the undefined K variable bug in the skip warning message'}
```

## File: facebookresearch_paq/paq/evaluation/eval_utils.py

Prompts

```
['run the eval_reranker CLI to compute exact match scores between predictions and gold answers', 'run exact match evaluation on JSONL prediction and reference files using argparse arguments', 'evaluate exact match scores between a list of predictions and references using evaluate_exact_match', 'summarize the evaluate_exact_match function that computes average exact match over ground truths', 'review the eval_reranker CLI tool that compares predicted answers against gold answers', 'run the eval_retriever CLI to evaluate retrieval results against gold answers with hits@k metrics', 'run the eval_retriever CLI with custom hits@k values like 1,5,20 for retrieval evaluation', 'eval the eval_retriever function to compute exact match scores for retrieved QAs against references', 'review the eval_retriever function and its exact match scoring logic for retrieved question-answer pairs', 'refactor the eval_retriever function to fix the undefined K variable bug in the skip warning message', 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'compute an exact match score between a prediction and ground truth after normalization', 'compute the maximum metric score across all prediction and ground truth pairs', 'normalize text by removing articles like a, an, and the before comparison', 'evaluate exact match across multiple predictions against multiple ground truth answers']
```

Usage

```
{'normalize_answer_text': 'normalize an answer string by lowercasing, removing punctuation, articles, and extra whitespace', 'exact_match_score_prediction': 'compute an exact match score between a prediction and ground truth after normalization', 'metric_max_over_ground_truths': 'compute the maximum metric score across all prediction and ground truth pairs', 'normalize_answer_remove_articles': 'normalize text by removing articles like a, an, and the before comparison', 'exact_match_score_multiple_predictions': 'evaluate exact match across multiple predictions against multiple ground truth answers'}
```

