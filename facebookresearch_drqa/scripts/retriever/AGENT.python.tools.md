# Agent Python Tools

- repo: facebookresearch/drqa
- repo_uri: https://github.com/facebookresearch/drqa

## File: facebookresearch_drqa/scripts/retriever/build_db.py

Prompts

```
['build a sqlite database from JSON-encoded document files with multiprocessing support', 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run iter_files to walk through all files located under a root path or directory', 'run import_module to dynamically import a Python module given a full file path', 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get document frequencies showing how many documents each word appears in', 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config', 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run the regex_match function to test if a pattern is contained within a text string', 'run the has_answer function to check if a document contains a given answer string', 'run the get_score function to search top retrieved docs for a matching answer', 'run the init function to initialize tokenizer and document database in multiprocessing workers', 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'call process to retrieve and display the top k closest documents for a query', 'call usage to print the interactive retriever help banner and available commands', 'review the process function that queries the ranker and prints a ranked document table', 'refactor the process function to support custom output formats beyond prettytable', 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize a Wikipedia article by setting its id field to the article title']
```

Usage

```
{'build_sqlite_document_db': 'build a sqlite database from JSON-encoded document files with multiprocessing support', 'run_store_contents': 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run_get_contents': 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run_iter_files': 'run iter_files to walk through all files located under a root path or directory', 'run_import_module': 'run import_module to dynamically import a Python module given a full file path'}
```

## File: facebookresearch_drqa/scripts/retriever/build_tfidf.py

Prompts

```
['build a sqlite database from JSON-encoded document files with multiprocessing support', 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run iter_files to walk through all files located under a root path or directory', 'run import_module to dynamically import a Python module given a full file path', 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get document frequencies showing how many documents each word appears in', 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config', 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run the regex_match function to test if a pattern is contained within a text string', 'run the has_answer function to check if a document contains a given answer string', 'run the get_score function to search top retrieved docs for a matching answer', 'run the init function to initialize tokenizer and document database in multiprocessing workers', 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'call process to retrieve and display the top k closest documents for a query', 'call usage to print the interactive retriever help banner and available commands', 'review the process function that queries the ranker and prints a ranked document table', 'refactor the process function to support custom output formats beyond prettytable', 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize a Wikipedia article by setting its id field to the article title']
```

Usage

```
{'build_tfidf_matrix': 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run_count_matrix': 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute_tfidf_vectors': 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get_doc_frequencies': 'get document frequencies showing how many documents each word appears in', 'save_sparse_matrix': 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config'}
```

## File: facebookresearch_drqa/scripts/retriever/eval.py

Prompts

```
['build a sqlite database from JSON-encoded document files with multiprocessing support', 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run iter_files to walk through all files located under a root path or directory', 'run import_module to dynamically import a Python module given a full file path', 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get document frequencies showing how many documents each word appears in', 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config', 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run the regex_match function to test if a pattern is contained within a text string', 'run the has_answer function to check if a document contains a given answer string', 'run the get_score function to search top retrieved docs for a matching answer', 'run the init function to initialize tokenizer and document database in multiprocessing workers', 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'call process to retrieve and display the top k closest documents for a query', 'call usage to print the interactive retriever help banner and available commands', 'review the process function that queries the ranker and prints a ranked document table', 'refactor the process function to support custom output formats beyond prettytable', 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize a Wikipedia article by setting its id field to the article title']
```

Usage

```
{'run_eval_retriever': 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run_regex_match': 'run the regex_match function to test if a pattern is contained within a text string', 'run_has_answer': 'run the has_answer function to check if a document contains a given answer string', 'run_get_score': 'run the get_score function to search top retrieved docs for a matching answer', 'run_init_workers': 'run the init function to initialize tokenizer and document database in multiprocessing workers'}
```

## File: facebookresearch_drqa/scripts/retriever/interactive.py

Prompts

```
['build a sqlite database from JSON-encoded document files with multiprocessing support', 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run iter_files to walk through all files located under a root path or directory', 'run import_module to dynamically import a Python module given a full file path', 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get document frequencies showing how many documents each word appears in', 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config', 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run the regex_match function to test if a pattern is contained within a text string', 'run the has_answer function to check if a document contains a given answer string', 'run the get_score function to search top retrieved docs for a matching answer', 'run the init function to initialize tokenizer and document database in multiprocessing workers', 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'call process to retrieve and display the top k closest documents for a query', 'call usage to print the interactive retriever help banner and available commands', 'review the process function that queries the ranker and prints a ranked document table', 'refactor the process function to support custom output formats beyond prettytable', 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize a Wikipedia article by setting its id field to the article title']
```

Usage

```
{'run_interactive_retriever': 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'process_query': 'call process to retrieve and display the top k closest documents for a query', 'usage_help': 'call usage to print the interactive retriever help banner and available commands', 'review_process_function': 'review the process function that queries the ranker and prints a ranked document table', 'refactor_process_function': 'refactor the process function to support custom output formats beyond prettytable'}
```

## File: facebookresearch_drqa/scripts/retriever/prep_wikipedia.py

Prompts

```
['build a sqlite database from JSON-encoded document files with multiprocessing support', 'run store_contents to preprocess and store a corpus of documents into a sqlite database', 'run get_contents to parse a file of JSON-encoded documents and extract id and text fields', 'run iter_files to walk through all files located under a root path or directory', 'run import_module to dynamically import a Python module given a full file path', 'build a tf-idf document matrix from a SQLite database of documents using multiprocessing', 'run the script to create a sparse word-to-document count matrix with hashed ngrams', 'compute tf-idf vectors from a word count matrix using smoothed inverse document frequency', 'get document frequencies showing how many documents each word appears in', 'save a sparse CSR matrix with metadata including doc frequencies and tokenizer config', 'run the DrQA retriever evaluation script on a dataset with a tfidf model and doc database', 'run the regex_match function to test if a pattern is contained within a text string', 'run the has_answer function to check if a document contains a given answer string', 'run the get_score function to search top retrieved docs for a matching answer', 'run the init function to initialize tokenizer and document database in multiprocessing workers', 'run the interactive TF-IDF DrQA retriever with a model path via --model argument', 'call process to retrieve and display the top k closest documents for a query', 'call usage to print the interactive retriever help banner and available commands', 'review the process function that queries the ranker and prints a ranked document table', 'refactor the process function to support custom output formats beyond prettytable', 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize a Wikipedia article by setting its id field to the article title']
```

Usage

```
{'preprocess_wikipedia_article': 'preprocess a Wikipedia article dict to unescape HTML and filter disambiguation pages', 'filter_disambiguation_pages': 'filter out Wikipedia disambiguation pages by checking article title for disambiguation keywords', 'unescape_html_entities': 'unescape HTML entities in a Wikipedia article dict using HTMLParser', 'filter_list_index_outline_pages': 'filter out Wikipedia List, Index, or Outline pages that contain mostly links', 'normalize_article_id': 'normalize a Wikipedia article by setting its id field to the article title'}
```

