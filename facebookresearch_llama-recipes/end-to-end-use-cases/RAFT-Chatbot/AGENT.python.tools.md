# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/RAFT-Chatbot/config.py

Prompts

```
['load a YAML configuration file and return it as a Python dictionary', 'review the load_config function that reads and parses YAML config files', 'test the load_config function by loading a sample YAML config file', 'refactor the load_config function to add validation or default config fallback', 'summarize the load_config function that uses PyYAML to parse config files', 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'run the format module to convert a dataset to chat format with a custom system prompt', 'review the DatasetConverter class and its convert method for dataset format resolution and export', 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run raft.py to generate and convert a QA dataset to a specified output format', 'review the main function that generates question pairs and saves the dataset to disk', 'review the parse_arguments function that defines CLI args for model, chunk size, and output format', 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute ROUGE scores between a list of generated answers and reference answers', 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model', 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate chain-of-thought answers for each question given its document chunk context', 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples']
```

Usage

```
{'load_config_yaml': 'load a YAML configuration file and return it as a Python dictionary', 'review_load_config': 'review the load_config function that reads and parses YAML config files', 'test_load_config': 'test the load_config function by loading a sample YAML config file', 'refactor_load_config': 'refactor the load_config function to add validation or default config fallback', 'summarize_load_config': 'summarize the load_config function that uses PyYAML to parse config files'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/RAFT-Chatbot/format.py

Prompts

```
['load a YAML configuration file and return it as a Python dictionary', 'review the load_config function that reads and parses YAML config files', 'test the load_config function by loading a sample YAML config file', 'refactor the load_config function to add validation or default config fallback', 'summarize the load_config function that uses PyYAML to parse config files', 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'run the format module to convert a dataset to chat format with a custom system prompt', 'review the DatasetConverter class and its convert method for dataset format resolution and export', 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run raft.py to generate and convert a QA dataset to a specified output format', 'review the main function that generates question pairs and saves the dataset to disk', 'review the parse_arguments function that defines CLI args for model, chunk size, and output format', 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute ROUGE scores between a list of generated answers and reference answers', 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model', 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate chain-of-thought answers for each question given its document chunk context', 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples']
```

Usage

```
{'convert_dataset_to_openai_chat': 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'convert_dataset_to_openai_completion': 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'export_dataset_to_parquet': 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'convert_dataset_with_system_prompt': 'run the format module to convert a dataset to chat format with a custom system prompt', 'review_DatasetConverter_convert': 'review the DatasetConverter class and its convert method for dataset format resolution and export'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/RAFT-Chatbot/raft.py

Prompts

```
['load a YAML configuration file and return it as a Python dictionary', 'review the load_config function that reads and parses YAML config files', 'test the load_config function by loading a sample YAML config file', 'refactor the load_config function to add validation or default config fallback', 'summarize the load_config function that uses PyYAML to parse config files', 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'run the format module to convert a dataset to chat format with a custom system prompt', 'review the DatasetConverter class and its convert method for dataset format resolution and export', 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run raft.py to generate and convert a QA dataset to a specified output format', 'review the main function that generates question pairs and saves the dataset to disk', 'review the parse_arguments function that defines CLI args for model, chunk size, and output format', 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute ROUGE scores between a list of generated answers and reference answers', 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model', 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate chain-of-thought answers for each question given its document chunk context', 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples']
```

Usage

```
{'run_raft_generate_qa_pairs': 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run_raft_with_custom_model': 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run_raft_convert_dataset': 'run raft.py to generate and convert a QA dataset to a specified output format', 'review_main_function': 'review the main function that generates question pairs and saves the dataset to disk', 'review_parse_arguments': 'review the parse_arguments function that defines CLI args for model, chunk size, and output format'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/RAFT-Chatbot/raft_eval.py

Prompts

```
['load a YAML configuration file and return it as a Python dictionary', 'review the load_config function that reads and parses YAML config files', 'test the load_config function by loading a sample YAML config file', 'refactor the load_config function to add validation or default config fallback', 'summarize the load_config function that uses PyYAML to parse config files', 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'run the format module to convert a dataset to chat format with a custom system prompt', 'review the DatasetConverter class and its convert method for dataset format resolution and export', 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run raft.py to generate and convert a QA dataset to a specified output format', 'review the main function that generates question pairs and saves the dataset to disk', 'review the parse_arguments function that defines CLI args for model, chunk size, and output format', 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute ROUGE scores between a list of generated answers and reference answers', 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model', 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate chain-of-thought answers for each question given its document chunk context', 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples']
```

Usage

```
{'run_RAFT_eval': 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build_retriever': 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate_answers_with_RAG': 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute_rouge_score': 'compute ROUGE scores between a list of generated answers and reference answers', 'compute_judge_score': 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/RAFT-Chatbot/raft_utils.py

Prompts

```
['load a YAML configuration file and return it as a Python dictionary', 'review the load_config function that reads and parses YAML config files', 'test the load_config function by loading a sample YAML config file', 'refactor the load_config function to add validation or default config fallback', 'summarize the load_config function that uses PyYAML to parse config files', 'run the format module to convert a HuggingFace dataset to OpenAI chat fine-tuning JSONL format', 'run the format module to convert a HuggingFace dataset to OpenAI completion fine-tuning JSONL format', 'run the format module to convert and export a HuggingFace dataset to a Parquet file', 'run the format module to convert a dataset to chat format with a custom system prompt', 'review the DatasetConverter class and its convert method for dataset format resolution and export', 'run raft.py to generate RAFT question/answer/context pairs from documentation using an LLM', 'run raft.py with a custom model and endpoint URL to generate question pairs', 'run raft.py to generate and convert a QA dataset to a specified output format', 'review the main function that generates question pairs and saves the dataset to disk', 'review the parse_arguments function that defines CLI args for model, chunk size, and output format', 'run the RAFT chatbot evaluation pipeline comparing model-only and RAG answers across multiple LLMs', 'build a FAISS vector store retriever from a directory of documents using HuggingFace embeddings', 'generate answers using a LLM with retrieved context documents via a RAG pipeline', 'compute ROUGE scores between a list of generated answers and reference answers', 'compute an LLM-as-judge score by comparing generated answers against ground truth with a judge model', 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate chain-of-thought answers for each question given its document chunk context', 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples']
```

Usage

```
{'read_documents_from_sitemap_or_folder': 'read documents from a local sitemap XML file or directory folder using langchain loaders', 'chunk_documents_with_overlap': 'split a list of documents into overlapping text chunks using RecursiveCharacterTextSplitter', 'generate_questions_from_chunks': 'generate questions for each document chunk using an LLM via the OpenAI API protocol', 'generate_COT_answers': 'generate chain-of-thought answers for each question given its document chunk context', 'build_RAFT_dataset': 'build a RAFT fine-tuning dataset with Q-A-D triplets and optional refusal examples'}
```

