# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/mmlu_cot/utils/extract_cot_as_queries.py

Prompts

```
['extract chain-of-thought reasoning from model outputs in JSON files and save as JSONL queries', 'load a JSON file from a given path and return the parsed data', 'write a list of dictionaries to a JSONL file with one JSON object per line', 'read all JSON files in a directory, extract queries from model outputs, and write to JSONL', 'split model output text on the answer delimiter to isolate the chain-of-thought reasoning portion']
```

Usage

```
{'extract_cot_as_queries': 'extract chain-of-thought reasoning from model outputs in JSON files and save as JSONL queries', 'load_json_file': 'load a JSON file from a given path and return the parsed data', 'write_jsonl_data': 'write a list of dictionaries to a JSONL file with one JSON object per line', 'format_query_from_dir': 'read all JSON files in a directory, extract queries from model outputs, and write to JSONL', 'split_cot_from_answer': 'split model output text on the answer delimiter to isolate the chain-of-thought reasoning portion'}
```

