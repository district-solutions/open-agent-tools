# Agent Python Tools

- repo: facebookresearch/kilt
- repo_uri: https://github.com/facebookresearch/kilt

## File: facebookresearch_kilt/scripts/create_kilt_data_paragraphs.py

Prompts

```
['run the preprocess step to load all Wikipedia documents from the knowledge source and store them as pickled chunks', 'run the main step to chunk Wikipedia documents into paragraphs using spaCy NLP with configurable token chunk size', 'run the merge step to combine all per-rank JSONL output files into a single kilt.jsonl file', 'create a chunk dictionary from a token buffer with adjusted anchor offsets for a given paragraph and section', 'run a threaded NLP processing pass over a batch of documents to produce paragraph chunks with anchors', 'run a retrieval evaluation using a specified retriever model like DPR or BM25 on test data', 'execute a retriever model with a custom configuration file and output folder for results', 'run DrQA tf-idf retrieval using default or custom configuration on test data', 'run DPR dense passage retrieval with optional configuration file and output folder', 'run BM25 retrieval using default or custom configuration on test data', 'run the script to download TriviaQA data and update KILT JSONL files with question inputs', 'create a function that extracts a tar.gz file to a path with a tqdm progress bar', 'build a python module that streams a file download from a URL with a tqdm progress bar', 'create a function that reads TriviaQA JSON files and builds a question ID to question text mapping', 'refactor KILT JSONL files to populate the input field using a question ID mapping', 'run the script to convert TAC-KBP2010 train and test JSONL files to KILT format', 'run write_output to serialize a list of dictionaries as newline-delimited JSON to a file', 'review the KnowledgeSource usage for looking up Wikipedia pages by title and ID', 'review the manual_labels_correspondance dict that maps TAC-KBP entity IDs to Wikipedia IDs as fallback', 'refactor the entity mention tokenization using START_ENT and END_ENT markers in input text']
```

Usage

```
{'preprocess_wikipedia_documents': 'run the preprocess step to load all Wikipedia documents from the knowledge source and store them as pickled chunks', 'run_main_chunking_pipeline': 'run the main step to chunk Wikipedia documents into paragraphs using spaCy NLP with configurable token chunk size', 'merge_jsonl_output_files': 'run the merge step to combine all per-rank JSONL output files into a single kilt.jsonl file', 'create_chunk_from_tokens': 'create a chunk dictionary from a token buffer with adjusted anchor offsets for a given paragraph and section', 'run_thread_on_document_batch': 'run a threaded NLP processing pass over a batch of documents to produce paragraph chunks with anchors'}
```

## File: facebookresearch_kilt/scripts/execute_retrieval.py

Prompts

```
['run the preprocess step to load all Wikipedia documents from the knowledge source and store them as pickled chunks', 'run the main step to chunk Wikipedia documents into paragraphs using spaCy NLP with configurable token chunk size', 'run the merge step to combine all per-rank JSONL output files into a single kilt.jsonl file', 'create a chunk dictionary from a token buffer with adjusted anchor offsets for a given paragraph and section', 'run a threaded NLP processing pass over a batch of documents to produce paragraph chunks with anchors', 'run a retrieval evaluation using a specified retriever model like DPR or BM25 on test data', 'execute a retriever model with a custom configuration file and output folder for results', 'run DrQA tf-idf retrieval using default or custom configuration on test data', 'run DPR dense passage retrieval with optional configuration file and output folder', 'run BM25 retrieval using default or custom configuration on test data', 'run the script to download TriviaQA data and update KILT JSONL files with question inputs', 'create a function that extracts a tar.gz file to a path with a tqdm progress bar', 'build a python module that streams a file download from a URL with a tqdm progress bar', 'create a function that reads TriviaQA JSON files and builds a question ID to question text mapping', 'refactor KILT JSONL files to populate the input field using a question ID mapping', 'run the script to convert TAC-KBP2010 train and test JSONL files to KILT format', 'run write_output to serialize a list of dictionaries as newline-delimited JSON to a file', 'review the KnowledgeSource usage for looking up Wikipedia pages by title and ID', 'review the manual_labels_correspondance dict that maps TAC-KBP entity IDs to Wikipedia IDs as fallback', 'refactor the entity mention tokenization using START_ENT and END_ENT markers in input text']
```

Usage

```
{'run_retrieval_evaluation': 'run a retrieval evaluation using a specified retriever model like DPR or BM25 on test data', 'execute_retriever_with_config': 'execute a retriever model with a custom configuration file and output folder for results', 'run_drqa_tfidf_retrieval': 'run DrQA tf-idf retrieval using default or custom configuration on test data', 'run_dpr_retrieval': 'run DPR dense passage retrieval with optional configuration file and output folder', 'run_bm25_retrieval': 'run BM25 retrieval using default or custom configuration on test data'}
```

## File: facebookresearch_kilt/scripts/get_triviaqa_input.py

Prompts

```
['run the preprocess step to load all Wikipedia documents from the knowledge source and store them as pickled chunks', 'run the main step to chunk Wikipedia documents into paragraphs using spaCy NLP with configurable token chunk size', 'run the merge step to combine all per-rank JSONL output files into a single kilt.jsonl file', 'create a chunk dictionary from a token buffer with adjusted anchor offsets for a given paragraph and section', 'run a threaded NLP processing pass over a batch of documents to produce paragraph chunks with anchors', 'run a retrieval evaluation using a specified retriever model like DPR or BM25 on test data', 'execute a retriever model with a custom configuration file and output folder for results', 'run DrQA tf-idf retrieval using default or custom configuration on test data', 'run DPR dense passage retrieval with optional configuration file and output folder', 'run BM25 retrieval using default or custom configuration on test data', 'run the script to download TriviaQA data and update KILT JSONL files with question inputs', 'create a function that extracts a tar.gz file to a path with a tqdm progress bar', 'build a python module that streams a file download from a URL with a tqdm progress bar', 'create a function that reads TriviaQA JSON files and builds a question ID to question text mapping', 'refactor KILT JSONL files to populate the input field using a question ID mapping', 'run the script to convert TAC-KBP2010 train and test JSONL files to KILT format', 'run write_output to serialize a list of dictionaries as newline-delimited JSON to a file', 'review the KnowledgeSource usage for looking up Wikipedia pages by title and ID', 'review the manual_labels_correspondance dict that maps TAC-KBP entity IDs to Wikipedia IDs as fallback', 'refactor the entity mention tokenization using START_ENT and END_ENT markers in input text']
```

Usage

```
{'run_triviaqa_data_pipeline': 'run the script to download TriviaQA data and update KILT JSONL files with question inputs', 'decompress_tar_with_progress': 'create a function that extracts a tar.gz file to a path with a tqdm progress bar', 'download_file_with_progress': 'build a python module that streams a file download from a URL with a tqdm progress bar', 'extract_question_ids': 'create a function that reads TriviaQA JSON files and builds a question ID to question text mapping', 'update_kilt_jsonl_inputs': 'refactor KILT JSONL files to populate the input field using a question ID mapping'}
```

## File: facebookresearch_kilt/scripts/map_TAC-KBP2010_to_KILT.py

Prompts

```
['run the preprocess step to load all Wikipedia documents from the knowledge source and store them as pickled chunks', 'run the main step to chunk Wikipedia documents into paragraphs using spaCy NLP with configurable token chunk size', 'run the merge step to combine all per-rank JSONL output files into a single kilt.jsonl file', 'create a chunk dictionary from a token buffer with adjusted anchor offsets for a given paragraph and section', 'run a threaded NLP processing pass over a batch of documents to produce paragraph chunks with anchors', 'run a retrieval evaluation using a specified retriever model like DPR or BM25 on test data', 'execute a retriever model with a custom configuration file and output folder for results', 'run DrQA tf-idf retrieval using default or custom configuration on test data', 'run DPR dense passage retrieval with optional configuration file and output folder', 'run BM25 retrieval using default or custom configuration on test data', 'run the script to download TriviaQA data and update KILT JSONL files with question inputs', 'create a function that extracts a tar.gz file to a path with a tqdm progress bar', 'build a python module that streams a file download from a URL with a tqdm progress bar', 'create a function that reads TriviaQA JSON files and builds a question ID to question text mapping', 'refactor KILT JSONL files to populate the input field using a question ID mapping', 'run the script to convert TAC-KBP2010 train and test JSONL files to KILT format', 'run write_output to serialize a list of dictionaries as newline-delimited JSON to a file', 'review the KnowledgeSource usage for looking up Wikipedia pages by title and ID', 'review the manual_labels_correspondance dict that maps TAC-KBP entity IDs to Wikipedia IDs as fallback', 'refactor the entity mention tokenization using START_ENT and END_ENT markers in input text']
```

Usage

```
{'run_convert_tac_kbp_to_kilt': 'run the script to convert TAC-KBP2010 train and test JSONL files to KILT format', 'run_write_output_jsonl': 'run write_output to serialize a list of dictionaries as newline-delimited JSON to a file', 'review_knowledge_source_lookup': 'review the KnowledgeSource usage for looking up Wikipedia pages by title and ID', 'review_manual_labels_correspondance': 'review the manual_labels_correspondance dict that maps TAC-KBP entity IDs to Wikipedia IDs as fallback', 'refactor_entity_tokenization': 'refactor the entity mention tokenization using START_ENT and END_ENT markers in input text'}
```

