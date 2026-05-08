# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/generation/filtering/filter_questions.py

Prompts

```
['run the filter_questions CLI to retrieve docs and generate answers for generated questions using a config file', 'run retrieve_documents_for_generated_questions to load a retriever and retrieve documents for generated questions from a JSONL file', 'run generate_answers_for_generated_questions_with_retrieved_docs to load a reader and generate answers for questions with retrieved documents', 'run filter_generated_questions_and_write_to_file to retrieve documents, generate answers, and write filtered questions to an output file', 'review the filter_questions module to understand the retrieval and answer generation pipeline for filtering generated questions', 'use load_retriever with a config dict to instantiate a LocalFilteringRetriever, GlobalFilteringRetriever, or DummyFilteringRetriever', 'use load_reader with a config dict to instantiate a FIDReader or DummyReader for answer generation', 'use GlobalFilteringRetriever to retrieve relevant documents for questions using DPR embeddings and a FAISS index', 'use FIDReader.generate_answers to generate answers from retrieved contexts and compute exact match scores', 'use the _load_corpus function to parse a TSV or JSONL corpus file into a passage_id keyed dictionary']
```

Usage

```
{'run_filter_generated_questions_cli': 'run the filter_questions CLI to retrieve docs and generate answers for generated questions using a config file', 'run_retrieve_documents_for_generated_questions': 'run retrieve_documents_for_generated_questions to load a retriever and retrieve documents for generated questions from a JSONL file', 'run_generate_answers_for_generated_questions': 'run generate_answers_for_generated_questions_with_retrieved_docs to load a reader and generate answers for questions with retrieved documents', 'run_filter_generated_questions_and_write': 'run filter_generated_questions_and_write_to_file to retrieve documents, generate answers, and write filtered questions to an output file', 'review_filter_questions_module': 'review the filter_questions module to understand the retrieval and answer generation pipeline for filtering generated questions'}
```

## File: facebookresearch_paq/paq/generation/filtering/filterer.py

Prompts

```
['run the filter_questions CLI to retrieve docs and generate answers for generated questions using a config file', 'run retrieve_documents_for_generated_questions to load a retriever and retrieve documents for generated questions from a JSONL file', 'run generate_answers_for_generated_questions_with_retrieved_docs to load a reader and generate answers for questions with retrieved documents', 'run filter_generated_questions_and_write_to_file to retrieve documents, generate answers, and write filtered questions to an output file', 'review the filter_questions module to understand the retrieval and answer generation pipeline for filtering generated questions', 'use load_retriever with a config dict to instantiate a LocalFilteringRetriever, GlobalFilteringRetriever, or DummyFilteringRetriever', 'use load_reader with a config dict to instantiate a FIDReader or DummyReader for answer generation', 'use GlobalFilteringRetriever to retrieve relevant documents for questions using DPR embeddings and a FAISS index', 'use FIDReader.generate_answers to generate answers from retrieved contexts and compute exact match scores', 'use the _load_corpus function to parse a TSV or JSONL corpus file into a passage_id keyed dictionary']
```

Usage

```
{'load_retriever_from_config': 'use load_retriever with a config dict to instantiate a LocalFilteringRetriever, GlobalFilteringRetriever, or DummyFilteringRetriever', 'load_reader_from_config': 'use load_reader with a config dict to instantiate a FIDReader or DummyReader for answer generation', 'retrieve_documents_global': 'use GlobalFilteringRetriever to retrieve relevant documents for questions using DPR embeddings and a FAISS index', 'generate_answers_fid': 'use FIDReader.generate_answers to generate answers from retrieved contexts and compute exact match scores', 'load_corpus_for_retrieval': 'use the _load_corpus function to parse a TSV or JSONL corpus file into a passage_id keyed dictionary'}
```

