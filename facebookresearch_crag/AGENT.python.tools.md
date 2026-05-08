# Agent Python Tools

- repo: facebookresearch/crag
- repo_uri: https://github.com/facebookresearch/crag

## File: facebookresearch_crag/local_evaluation.py

Prompts

```
['generate predictions from a dataset using a participant model that supports batch_generate_answer', 'evaluate model predictions against ground truth answers using an OpenAI chat model for scoring', 'attempt an OpenAI chat completion API call with automatic retries on connection or rate limit errors', 'parse an LLM response string to extract an explanation and binary score using regex', 'load compressed JSONL dataset files in batches as a generator for memory-efficient processing']
```

Usage

```
{'generate_predictions': 'generate predictions from a dataset using a participant model that supports batch_generate_answer', 'evaluate_predictions': 'evaluate model predictions against ground truth answers using an OpenAI chat model for scoring', 'attempt_api_call': 'attempt an OpenAI chat completion API call with automatic retries on connection or rate limit errors', 'parse_response': 'parse an LLM response string to extract an explanation and binary score using regex', 'load_data_in_batches': 'load compressed JSONL dataset files in batches as a generator for memory-efficient processing'}
```

