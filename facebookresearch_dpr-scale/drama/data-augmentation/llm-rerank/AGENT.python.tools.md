# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/drama/data-augmentation/llm-rerank/llama3.3-70b-rerank.py

Prompts

```
['run the Llama-3.3-70B reranking script on an input JSONL file with queries and passages', 'run format_message to build a chat template for ranking 20 passages by relevance to a query', 'run vllm LLM generate with sampling params to produce reranking outputs for batched prompts', 'run the tokenizer encode and decode to truncate passage text to 256 tokens', 'run the script to read query-passage JSONL input and write reranked JSONL output']
```

Usage

```
{'run_llm_rerank': 'run the Llama-3.3-70B reranking script on an input JSONL file with queries and passages', 'run_format_message': 'run format_message to build a chat template for ranking 20 passages by relevance to a query', 'run_vllm_generate': 'run vllm LLM generate with sampling params to produce reranking outputs for batched prompts', 'run_tokenizer_truncate': 'run the tokenizer encode and decode to truncate passage text to 256 tokens', 'run_jsonl_io': 'run the script to read query-passage JSONL input and write reranked JSONL output'}
```

