# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/data_pipeline/quality/dedup_minhash.py

Prompts

```
['run minhash deduplication on a JSONL file using Ray and a configurable Jaccard similarity threshold', 'normalize text by lowercasing, removing punctuation, articles, and extra whitespace for SQuAD-style preprocessing', 'process a data row to extract text, compute a MinHash fingerprint, and assign a unique ID', 'deserialize serialized LeanMinHash bytes back into a LeanMinHash object for duplicate comparison', 'review the Ray-remote run_remotely function that performs distributed MinHash LSH deduplication on JSONL datasets']
```

Usage

```
{'run_minhash_dedup': 'run minhash deduplication on a JSONL file using Ray and a configurable Jaccard similarity threshold', 'normalize_text': 'normalize text by lowercasing, removing punctuation, articles, and extra whitespace for SQuAD-style preprocessing', 'process_row_minhash': 'process a data row to extract text, compute a MinHash fingerprint, and assign a unique ID', 'deserialize_minhash': 'deserialize serialized LeanMinHash bytes back into a LeanMinHash object for duplicate comparison', 'review_run_remotely': 'review the Ray-remote run_remotely function that performs distributed MinHash LSH deduplication on JSONL datasets'}
```

