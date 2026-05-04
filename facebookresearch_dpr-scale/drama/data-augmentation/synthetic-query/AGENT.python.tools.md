# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/drama/data-augmentation/synthetic-query/llama3.3-70b-generate-query-over-wiki.py

Prompts

```
['run the script to generate synthetic queries from a corpus shard using Llama-3.3-70B-Instruct via vLLM', 'run the script with a specific shard index to process a subset of the miracl-corpus dataset', 'format a text document into a few-shot chat template with system, user, and assistant messages for query generation', 'generate synthetic retrieval queries from corpus documents using vLLM with Llama-3.3-70B and prefix caching enabled', 'parse the LLM-generated text to extract task description, query, and language fields and write to JSONL']
```

Usage

```
{'run_synthetic_query_generation': 'run the script to generate synthetic queries from a corpus shard using Llama-3.3-70B-Instruct via vLLM', 'run_sharded_corpus_processing': 'run the script with a specific shard index to process a subset of the miracl-corpus dataset', 'format_massage_function': 'format a text document into a few-shot chat template with system, user, and assistant messages for query generation', 'generate_queries_with_vllm': 'generate synthetic retrieval queries from corpus documents using vLLM with Llama-3.3-70B and prefix caching enabled', 'parse_generated_outputs': 'parse the LLM-generated text to extract task description, query, and language fields and write to JSONL'}
```

