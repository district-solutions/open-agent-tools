# Agent Python Tools

- repo: facebookresearch/contriever
- repo_uri: https://github.com/facebookresearch/contriever

## File: facebookresearch_contriever/data_scripts/convertmrtydi2beir.py

Prompts

```
['convert MR TyDi dataset to BEIR format by transforming queries, corpus, and qrels files', 'run the convert2beir script with data_path and output_path as command line arguments', 'transform MR TyDi topic.tsv queries into BEIR queries.jsonl format with _id and text fields', 'transform MR TyDi docs.jsonl corpus into BEIR corpus.jsonl format with _id, text, and title fields', 'transform MR TyDi qrels split files into BEIR qrels TSV format with query-id, corpus-id, and score columns', 'preprocess the xMKQA dataset by splitting multilingual QA examples into per-language JSONL files with English answers', 'run the xMKQA preprocessing script with an input JSONL file path and output directory as CLI arguments', 'filter xMKQA answers to exclude unanswerable, binary, and long answer types keeping only short answers and aliases', 'split xMKQA examples into separate JSONL files for each of the 26 supported languages', 'review the preprocess_xmkqa function to understand how it parses multilingual queries and filters answer types']
```

Usage

```
{'convert_mrtydi_to_beir': 'convert MR TyDi dataset to BEIR format by transforming queries, corpus, and qrels files', 'run_convert2beir_cli': 'run the convert2beir script with data_path and output_path as command line arguments', 'transform_mrtydi_queries': 'transform MR TyDi topic.tsv queries into BEIR queries.jsonl format with _id and text fields', 'transform_mrtydi_corpus': 'transform MR TyDi docs.jsonl corpus into BEIR corpus.jsonl format with _id, text, and title fields', 'transform_mrtydi_qrels': 'transform MR TyDi qrels split files into BEIR qrels TSV format with query-id, corpus-id, and score columns'}
```

## File: facebookresearch_contriever/data_scripts/preprocess_xmkqa.py

Prompts

```
['convert MR TyDi dataset to BEIR format by transforming queries, corpus, and qrels files', 'run the convert2beir script with data_path and output_path as command line arguments', 'transform MR TyDi topic.tsv queries into BEIR queries.jsonl format with _id and text fields', 'transform MR TyDi docs.jsonl corpus into BEIR corpus.jsonl format with _id, text, and title fields', 'transform MR TyDi qrels split files into BEIR qrels TSV format with query-id, corpus-id, and score columns', 'preprocess the xMKQA dataset by splitting multilingual QA examples into per-language JSONL files with English answers', 'run the xMKQA preprocessing script with an input JSONL file path and output directory as CLI arguments', 'filter xMKQA answers to exclude unanswerable, binary, and long answer types keeping only short answers and aliases', 'split xMKQA examples into separate JSONL files for each of the 26 supported languages', 'review the preprocess_xmkqa function to understand how it parses multilingual queries and filters answer types']
```

Usage

```
{'preprocess_xmkqa': 'preprocess the xMKQA dataset by splitting multilingual QA examples into per-language JSONL files with English answers', 'run_preprocess_xmkqa_cli': 'run the xMKQA preprocessing script with an input JSONL file path and output directory as CLI arguments', 'filter_xmkqa_answers': 'filter xMKQA answers to exclude unanswerable, binary, and long answer types keeping only short answers and aliases', 'split_xmkqa_by_language': 'split xMKQA examples into separate JSONL files for each of the 26 supported languages', 'review_preprocess_xmkqa': 'review the preprocess_xmkqa function to understand how it parses multilingual queries and filters answer types'}
```

