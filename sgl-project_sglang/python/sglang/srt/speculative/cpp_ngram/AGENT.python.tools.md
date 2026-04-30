# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/speculative/cpp_ngram/external_corpus.py

Prompts

```
['iterate over a JSONL corpus file and yield fixed-size token chunks using a tokenizer and max token limit', 'iterate over a JSONL corpus yielding token chunks with a custom chunk size instead of the default 4096', 'iterate over a JSONL corpus with SEPARATOR_TOKEN inserted between documents to delimit boundaries', 'validate a JSONL corpus file path, tokenizer availability, and positive max_tokens before streaming', 'iterate over a JSONL corpus skipping empty lines and zero-length tokenized records', 'create an NgramCorpus instance with configurable trie depth, BFS breadth, and draft token count', 'build a batch of token sequences into the n-gram corpus for speculative decoding', 'test batch_get to match tokens against the corpus and return decoding IDs and masks', 'remove an external corpus by ID and update the token budget bookkeeping', 'summarize debug_result to log decoded draft paths from matching masks']
```

Usage

```
{'iter_external_corpus_chunks': 'iterate over a JSONL corpus file and yield fixed-size token chunks using a tokenizer and max token limit', 'iter_external_corpus_chunks_chunk_size': 'iterate over a JSONL corpus yielding token chunks with a custom chunk size instead of the default 4096', 'iter_external_corpus_chunks_separator': 'iterate over a JSONL corpus with SEPARATOR_TOKEN inserted between documents to delimit boundaries', 'iter_external_corpus_chunks_validate': 'validate a JSONL corpus file path, tokenizer availability, and positive max_tokens before streaming', 'iter_external_corpus_chunks_skip_empty': 'iterate over a JSONL corpus skipping empty lines and zero-length tokenized records'}
```

## File: sgl-project_sglang/python/sglang/srt/speculative/cpp_ngram/ngram_corpus.py

Prompts

```
['iterate over a JSONL corpus file and yield fixed-size token chunks using a tokenizer and max token limit', 'iterate over a JSONL corpus yielding token chunks with a custom chunk size instead of the default 4096', 'iterate over a JSONL corpus with SEPARATOR_TOKEN inserted between documents to delimit boundaries', 'validate a JSONL corpus file path, tokenizer availability, and positive max_tokens before streaming', 'iterate over a JSONL corpus skipping empty lines and zero-length tokenized records', 'create an NgramCorpus instance with configurable trie depth, BFS breadth, and draft token count', 'build a batch of token sequences into the n-gram corpus for speculative decoding', 'test batch_get to match tokens against the corpus and return decoding IDs and masks', 'remove an external corpus by ID and update the token budget bookkeeping', 'summarize debug_result to log decoded draft paths from matching masks']
```

Usage

```
{'create_ngram_corpus': 'create an NgramCorpus instance with configurable trie depth, BFS breadth, and draft token count', 'build_batch_put': 'build a batch of token sequences into the n-gram corpus for speculative decoding', 'test_batch_get': 'test batch_get to match tokens against the corpus and return decoding IDs and masks', 'remove_external_corpus': 'remove an external corpus by ID and update the token budget bookkeeping', 'summarize_debug_result': 'summarize debug_result to log decoded draft paths from matching masks'}
```

