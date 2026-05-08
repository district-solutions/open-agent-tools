# Agent Python Tools

- repo: facebookresearch/blink
- repo_uri: https://github.com/facebookresearch/blink

## File: facebookresearch_blink/scripts/create_BLINK_benchmark_data.py

Prompts

```
['extract entity linking questions from a CoNLL format TSV file into structured datapoints with context', 'convert extracted question datapoints into BLINK benchmark format with left and right context fields', 'store a list of question datapoints as a JSONL file with one JSON object per line', 'fetch a Wikipedia page ID from the Wikipedia API given a page title string', 'create BLINK benchmark JSONL files from AIDA-YAGO2 and WNED dataset CoNLL files', 'run the script to encode a candidate pool using a biencoder model and save embeddings', 'run encode_candidate to batch encode a candidate pool tensor using a biencoder reranker', 'run load_candidate_pool to load a pre-generated candidate pool from a torch file', 'test encoding a subsample of 10 entities by passing the --test flag', 'compare generated candidate embeddings against previously saved baseline embeddings', 'load biencoder outputs, candidate scores, and mention bounds from saved prediction directories for entity linking', 'filter duplicate predicted entity triples by entity ID keeping only the highest scoring prediction', 'filter overlapping predicted entity mention spans by greedily keeping the highest scoring non-overlapping mentions', 'filter predicted entity triples that repeat the same entity ID and overlap in token span', 'compute combined scores from mention and candidate distributions then threshold and sort by descending score']
```

Usage

```
{'extract_questions_from_conll': 'extract entity linking questions from a CoNLL format TSV file into structured datapoints with context', 'convert_to_BLINK_format': 'convert extracted question datapoints into BLINK benchmark format with left and right context fields', 'store_questions_to_jsonl': 'store a list of question datapoints as a JSONL file with one JSON object per line', 'get_wikipedia_pageid': 'fetch a Wikipedia page ID from the Wikipedia API given a page title string', 'create_BLINK_benchmark_data': 'create BLINK benchmark JSONL files from AIDA-YAGO2 and WNED dataset CoNLL files'}
```

## File: facebookresearch_blink/scripts/generate_candidates.py

Prompts

```
['extract entity linking questions from a CoNLL format TSV file into structured datapoints with context', 'convert extracted question datapoints into BLINK benchmark format with left and right context fields', 'store a list of question datapoints as a JSONL file with one JSON object per line', 'fetch a Wikipedia page ID from the Wikipedia API given a page title string', 'create BLINK benchmark JSONL files from AIDA-YAGO2 and WNED dataset CoNLL files', 'run the script to encode a candidate pool using a biencoder model and save embeddings', 'run encode_candidate to batch encode a candidate pool tensor using a biencoder reranker', 'run load_candidate_pool to load a pre-generated candidate pool from a torch file', 'test encoding a subsample of 10 entities by passing the --test flag', 'compare generated candidate embeddings against previously saved baseline embeddings', 'load biencoder outputs, candidate scores, and mention bounds from saved prediction directories for entity linking', 'filter duplicate predicted entity triples by entity ID keeping only the highest scoring prediction', 'filter overlapping predicted entity mention spans by greedily keeping the highest scoring non-overlapping mentions', 'filter predicted entity triples that repeat the same entity ID and overlap in token span', 'compute combined scores from mention and candidate distributions then threshold and sort by descending score']
```

Usage

```
{'run_generate_candidates': 'run the script to encode a candidate pool using a biencoder model and save embeddings', 'run_encode_candidate': 'run encode_candidate to batch encode a candidate pool tensor using a biencoder reranker', 'run_load_candidate_pool': 'run load_candidate_pool to load a pre-generated candidate pool from a torch file', 'test_encode_candidate_subsample': 'test encoding a subsample of 10 entities by passing the --test flag', 'compare_saved_embeddings': 'compare generated candidate embeddings against previously saved baseline embeddings'}
```

## File: facebookresearch_blink/scripts/tune_hyperparams_new.py

Prompts

```
['extract entity linking questions from a CoNLL format TSV file into structured datapoints with context', 'convert extracted question datapoints into BLINK benchmark format with left and right context fields', 'store a list of question datapoints as a JSONL file with one JSON object per line', 'fetch a Wikipedia page ID from the Wikipedia API given a page title string', 'create BLINK benchmark JSONL files from AIDA-YAGO2 and WNED dataset CoNLL files', 'run the script to encode a candidate pool using a biencoder model and save embeddings', 'run encode_candidate to batch encode a candidate pool tensor using a biencoder reranker', 'run load_candidate_pool to load a pre-generated candidate pool from a torch file', 'test encoding a subsample of 10 entities by passing the --test flag', 'compare generated candidate embeddings against previously saved baseline embeddings', 'load biencoder outputs, candidate scores, and mention bounds from saved prediction directories for entity linking', 'filter duplicate predicted entity triples by entity ID keeping only the highest scoring prediction', 'filter overlapping predicted entity mention spans by greedily keeping the highest scoring non-overlapping mentions', 'filter predicted entity triples that repeat the same entity ID and overlap in token span', 'compute combined scores from mention and candidate distributions then threshold and sort by descending score']
```

Usage

```
{'run_load_dists': 'load biencoder outputs, candidate scores, and mention bounds from saved prediction directories for entity linking', 'run_filter_repeats': 'filter duplicate predicted entity triples by entity ID keeping only the highest scoring prediction', 'run_filter_overlaps': 'filter overlapping predicted entity mention spans by greedily keeping the highest scoring non-overlapping mentions', 'run_filter_repeat_overlaps': 'filter predicted entity triples that repeat the same entity ID and overlap in token span', 'run_get_threshold_mask_and_sort': 'compute combined scores from mention and candidate distributions then threshold and sort by descending score'}
```

