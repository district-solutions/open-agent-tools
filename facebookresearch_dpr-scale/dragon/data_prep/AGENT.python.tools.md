# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/dragon/data_prep/convert_trec_to_train.py

Prompts

```
['run the script to convert TREC results and query TSV into JSON training data', 'run the read_query function to parse a TSV file into a query ID to query text dictionary', 'build training data JSON from TREC ranking results by extracting top-10 positives and ranks 45-50 as hard negatives', 'refactor the read_query function to support additional TSV column formats or delimiters', 'review the convert_trec_to_train script to understand how it extracts positive and hard negative contexts from TREC results', 'run the crop_sentence module to crop sentences from a TSV doc file into ICT training data', 'run process_wiki_ict to load wiki passages and generate in-context training query-passage pairs', 'run prep_wiki_psgs_w100 to parse a TSV wiki file into a title-keyed document dictionary', 'run get_ict_data to generate random query-passage pairs from a list of sentences for ICT training', 'run process_passage to split a single passage into ICT data tuples with query and context', 'run the script to convert BEIR evaluation data from JSONL to TSV format for a given data directory', 'create a function that converts JSONL files to TSV format with configurable metadata fields and optional headers', 'build a TSV collection file from a corpus JSONL file with id, text, and title columns', 'build a TSV query file from a queries JSONL file with id and text columns', 'convert BEIR qrels TSV format to DPR qrels format by skipping the header and adding a 0 separator column', 'run the cli tool to prepare msmarco train and dev jsonl files from query and triples files', 'build a train and dev split of msmarco data from query and qidpid triples files', 'review the main function to understand how msmarco train and dev jsonl files are generated']
```

Usage

```
{'run_convert_trec_to_train': 'run the script to convert TREC results and query TSV into JSON training data', 'run_read_query': 'run the read_query function to parse a TSV file into a query ID to query text dictionary', 'build_train_data_from_trec': 'build training data JSON from TREC ranking results by extracting top-10 positives and ranks 45-50 as hard negatives', 'refactor_read_query': 'refactor the read_query function to support additional TSV column formats or delimiters', 'review_convert_trec_to_train': 'review the convert_trec_to_train script to understand how it extracts positive and hard negative contexts from TREC results'}
```

## File: facebookresearch_dpr-scale/dragon/data_prep/crop_sentence.py

Prompts

```
['run the script to convert TREC results and query TSV into JSON training data', 'run the read_query function to parse a TSV file into a query ID to query text dictionary', 'build training data JSON from TREC ranking results by extracting top-10 positives and ranks 45-50 as hard negatives', 'refactor the read_query function to support additional TSV column formats or delimiters', 'review the convert_trec_to_train script to understand how it extracts positive and hard negative contexts from TREC results', 'run the crop_sentence module to crop sentences from a TSV doc file into ICT training data', 'run process_wiki_ict to load wiki passages and generate in-context training query-passage pairs', 'run prep_wiki_psgs_w100 to parse a TSV wiki file into a title-keyed document dictionary', 'run get_ict_data to generate random query-passage pairs from a list of sentences for ICT training', 'run process_passage to split a single passage into ICT data tuples with query and context', 'run the script to convert BEIR evaluation data from JSONL to TSV format for a given data directory', 'create a function that converts JSONL files to TSV format with configurable metadata fields and optional headers', 'build a TSV collection file from a corpus JSONL file with id, text, and title columns', 'build a TSV query file from a queries JSONL file with id and text columns', 'convert BEIR qrels TSV format to DPR qrels format by skipping the header and adding a 0 separator column', 'run the cli tool to prepare msmarco train and dev jsonl files from query and triples files', 'build a train and dev split of msmarco data from query and qidpid triples files', 'review the main function to understand how msmarco train and dev jsonl files are generated']
```

Usage

```
{'run_crop_sentence_cli': 'run the crop_sentence module to crop sentences from a TSV doc file into ICT training data', 'run_process_wiki_ict': 'run process_wiki_ict to load wiki passages and generate in-context training query-passage pairs', 'run_prep_wiki_psgs_w100': 'run prep_wiki_psgs_w100 to parse a TSV wiki file into a title-keyed document dictionary', 'run_get_ict_data': 'run get_ict_data to generate random query-passage pairs from a list of sentences for ICT training', 'run_process_passage': 'run process_passage to split a single passage into ICT data tuples with query and context'}
```

## File: facebookresearch_dpr-scale/dragon/data_prep/prep_beir_eval.py

Prompts

```
['run the script to convert TREC results and query TSV into JSON training data', 'run the read_query function to parse a TSV file into a query ID to query text dictionary', 'build training data JSON from TREC ranking results by extracting top-10 positives and ranks 45-50 as hard negatives', 'refactor the read_query function to support additional TSV column formats or delimiters', 'review the convert_trec_to_train script to understand how it extracts positive and hard negative contexts from TREC results', 'run the crop_sentence module to crop sentences from a TSV doc file into ICT training data', 'run process_wiki_ict to load wiki passages and generate in-context training query-passage pairs', 'run prep_wiki_psgs_w100 to parse a TSV wiki file into a title-keyed document dictionary', 'run get_ict_data to generate random query-passage pairs from a list of sentences for ICT training', 'run process_passage to split a single passage into ICT data tuples with query and context', 'run the script to convert BEIR evaluation data from JSONL to TSV format for a given data directory', 'create a function that converts JSONL files to TSV format with configurable metadata fields and optional headers', 'build a TSV collection file from a corpus JSONL file with id, text, and title columns', 'build a TSV query file from a queries JSONL file with id and text columns', 'convert BEIR qrels TSV format to DPR qrels format by skipping the header and adding a 0 separator column', 'run the cli tool to prepare msmarco train and dev jsonl files from query and triples files', 'build a train and dev split of msmarco data from query and qidpid triples files', 'review the main function to understand how msmarco train and dev jsonl files are generated']
```

Usage

```
{'run_beir_eval_prep': 'run the script to convert BEIR evaluation data from JSONL to TSV format for a given data directory', 'create_json_to_tsv_conversion': 'create a function that converts JSONL files to TSV format with configurable metadata fields and optional headers', 'build_corpus_tsv': 'build a TSV collection file from a corpus JSONL file with id, text, and title columns', 'build_query_tsv': 'build a TSV query file from a queries JSONL file with id and text columns', 'convert_qrel_format': 'convert BEIR qrels TSV format to DPR qrels format by skipping the header and adding a 0 separator column'}
```

## File: facebookresearch_dpr-scale/dragon/data_prep/prep_msmarco_train.py

Prompts

```
['run the script to convert TREC results and query TSV into JSON training data', 'run the read_query function to parse a TSV file into a query ID to query text dictionary', 'build training data JSON from TREC ranking results by extracting top-10 positives and ranks 45-50 as hard negatives', 'refactor the read_query function to support additional TSV column formats or delimiters', 'review the convert_trec_to_train script to understand how it extracts positive and hard negative contexts from TREC results', 'run the crop_sentence module to crop sentences from a TSV doc file into ICT training data', 'run process_wiki_ict to load wiki passages and generate in-context training query-passage pairs', 'run prep_wiki_psgs_w100 to parse a TSV wiki file into a title-keyed document dictionary', 'run get_ict_data to generate random query-passage pairs from a list of sentences for ICT training', 'run process_passage to split a single passage into ICT data tuples with query and context', 'run the script to convert BEIR evaluation data from JSONL to TSV format for a given data directory', 'create a function that converts JSONL files to TSV format with configurable metadata fields and optional headers', 'build a TSV collection file from a corpus JSONL file with id, text, and title columns', 'build a TSV query file from a queries JSONL file with id and text columns', 'convert BEIR qrels TSV format to DPR qrels format by skipping the header and adding a 0 separator column', 'run the cli tool to prepare msmarco train and dev jsonl files from query and triples files', 'build a train and dev split of msmarco data from query and qidpid triples files', 'review the main function to understand how msmarco train and dev jsonl files are generated']
```

Usage

```
{'run_prep_msmarco_train': 'run the cli tool to prepare msmarco train and dev jsonl files from query and triples files', 'run_read_query': 'run the read_query function to parse a tsv file of query ids and queries into a dictionary', 'build_msmarco_train_dev_split': 'build a train and dev split of msmarco data from query and qidpid triples files', 'refactor_read_query': 'refactor the read_query function to support additional delimiters or file formats', 'review_main': 'review the main function to understand how msmarco train and dev jsonl files are generated'}
```

