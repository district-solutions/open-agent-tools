# Agent Python Tools

- repo: facebookresearch/mobilellm
- repo_uri: https://github.com/facebookresearch/mobilellm

## File: facebookresearch_mobilellm/eval.py

Prompts

```
['run the eval script to compute WikiText-2 perplexity for a Llama model', 'run the train function to evaluate a pretrained Llama model on wikitext test data', 'create a configured logger with INFO level and console handler for mobileLLM', 'review the train function that loads a Llama model and evaluates perplexity on wikitext', 'refactor the get_logger function to support custom log levels and file handlers', 'run the distributed pretraining loop for a Llama model using JSONL token data', 'create a JSONLIterator to shard and stream token IDs from a JSONL file across ranks', 'build a PyTorch DataLoader from an iterator with custom collate for input_ids and labels', 'get a configured Python logger with INFO level and console stream handler', 'get a list of subdirectory paths from a given parent directory']
```

Usage

```
{'run_eval_wikitext_ppl': 'run the eval script to compute WikiText-2 perplexity for a Llama model', 'run_train_function': 'run the train function to evaluate a pretrained Llama model on wikitext test data', 'create_logger': 'create a configured logger with INFO level and console handler for mobileLLM', 'review_train_function': 'review the train function that loads a Llama model and evaluates perplexity on wikitext', 'refactor_get_logger': 'refactor the get_logger function to support custom log levels and file handlers'}
```

## File: facebookresearch_mobilellm/pretrain.py

Prompts

```
['run the eval script to compute WikiText-2 perplexity for a Llama model', 'run the train function to evaluate a pretrained Llama model on wikitext test data', 'create a configured logger with INFO level and console handler for mobileLLM', 'review the train function that loads a Llama model and evaluates perplexity on wikitext', 'refactor the get_logger function to support custom log levels and file handlers', 'run the distributed pretraining loop for a Llama model using JSONL token data', 'create a JSONLIterator to shard and stream token IDs from a JSONL file across ranks', 'build a PyTorch DataLoader from an iterator with custom collate for input_ids and labels', 'get a configured Python logger with INFO level and console stream handler', 'get a list of subdirectory paths from a given parent directory']
```

Usage

```
{'run_pretrain_llm': 'run the distributed pretraining loop for a Llama model using JSONL token data', 'create_jsonl_iterator': 'create a JSONLIterator to shard and stream token IDs from a JSONL file across ranks', 'build_iterable_dataloader': 'build a PyTorch DataLoader from an iterator with custom collate for input_ids and labels', 'get_logger': 'get a configured Python logger with INFO level and console stream handler', 'get_folder_paths': 'get a list of subdirectory paths from a given parent directory'}
```

