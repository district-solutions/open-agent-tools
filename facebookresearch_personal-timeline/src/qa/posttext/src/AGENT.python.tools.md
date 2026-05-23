# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/qa/posttext/src/posttext.py

Prompts

```
['run the PostText CLI tool to answer questions using view-based QA on a dataset directory', 'create a PostText instance with a config dictionary and dataset directory path', 'query the PostText instance with a natural language question to get a view-based answer', 'review the PostText class and its query method for view-based question answering logic', 'refactor the PostText query method to re-enable the commented out RAG-based retrieval QA', 'build a RetrievalBasedQA instance that loads a pickled vectorstore and configures a LangChain RAG chain with a ChatOpenAI LLM', 'create a function that loads a pickled FAISS vectorstore from a file path for use in retrieval-based QA', 'query the RetrievalBasedQA chain with a natural language question and get an answer with source citations', 'review the RetrievalBasedQA class initialization that sets up a ChatOpenAI LLM and a RetrievalQAWithSourcesChain retriever', 'summarize the RetrievalBasedQA class that provides retrieval-augmented generation QA using LangChain and a pickled vectorstore', 'use ViewBasedQA to answer a natural language question against SQLite views and return SQL results', 'match a user question to the most relevant view table using OpenAI embeddings and cosine similarity', 'generate a provenance SQL query that traces which base tuples contributed to a given query result', 'load or generate view metadata embeddings from CSV or via the OpenAI embedding model', 'translate a SQL query result table into a natural language English sentence using an LLM', 'read a views catalog file and parse table metadata into a dictionary', 'rewrite a SQL query to add fuzzy matching using embedding-based CLOSE function', 'get an OpenAI text embedding with disk-based caching to avoid redundant API calls', 'perform fuzzy string matching between two strings using cosine similarity on embeddings', 'return a list of JSON-serialized view descriptions from a views catalog dictionary']
```

Usage

```
{'run_posttext_cli': 'run the PostText CLI tool to answer questions using view-based QA on a dataset directory', 'create_posttext_instance': 'create a PostText instance with a config dictionary and dataset directory path', 'query_posttext': 'query the PostText instance with a natural language question to get a view-based answer', 'review_posttext_class': 'review the PostText class and its query method for view-based question answering logic', 'refactor_posttext_query': 'refactor the PostText query method to re-enable the commented out RAG-based retrieval QA'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/src/retrieval_qa.py

Prompts

```
['run the PostText CLI tool to answer questions using view-based QA on a dataset directory', 'create a PostText instance with a config dictionary and dataset directory path', 'query the PostText instance with a natural language question to get a view-based answer', 'review the PostText class and its query method for view-based question answering logic', 'refactor the PostText query method to re-enable the commented out RAG-based retrieval QA', 'build a RetrievalBasedQA instance that loads a pickled vectorstore and configures a LangChain RAG chain with a ChatOpenAI LLM', 'create a function that loads a pickled FAISS vectorstore from a file path for use in retrieval-based QA', 'query the RetrievalBasedQA chain with a natural language question and get an answer with source citations', 'review the RetrievalBasedQA class initialization that sets up a ChatOpenAI LLM and a RetrievalQAWithSourcesChain retriever', 'summarize the RetrievalBasedQA class that provides retrieval-augmented generation QA using LangChain and a pickled vectorstore', 'use ViewBasedQA to answer a natural language question against SQLite views and return SQL results', 'match a user question to the most relevant view table using OpenAI embeddings and cosine similarity', 'generate a provenance SQL query that traces which base tuples contributed to a given query result', 'load or generate view metadata embeddings from CSV or via the OpenAI embedding model', 'translate a SQL query result table into a natural language English sentence using an LLM', 'read a views catalog file and parse table metadata into a dictionary', 'rewrite a SQL query to add fuzzy matching using embedding-based CLOSE function', 'get an OpenAI text embedding with disk-based caching to avoid redundant API calls', 'perform fuzzy string matching between two strings using cosine similarity on embeddings', 'return a list of JSON-serialized view descriptions from a views catalog dictionary']
```

Usage

```
{'build_RetrievalBasedQA': 'build a RetrievalBasedQA instance that loads a pickled vectorstore and configures a LangChain RAG chain with a ChatOpenAI LLM', 'create_load_source_vectorstore': 'create a function that loads a pickled FAISS vectorstore from a file path for use in retrieval-based QA', 'query_RetrievalBasedQA': 'query the RetrievalBasedQA chain with a natural language question and get an answer with source citations', 'review_RetrievalBasedQA_init': 'review the RetrievalBasedQA class initialization that sets up a ChatOpenAI LLM and a RetrievalQAWithSourcesChain retriever', 'summarize_RetrievalBasedQA': 'summarize the RetrievalBasedQA class that provides retrieval-augmented generation QA using LangChain and a pickled vectorstore'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/src/views_qa.py

Prompts

```
['run the PostText CLI tool to answer questions using view-based QA on a dataset directory', 'create a PostText instance with a config dictionary and dataset directory path', 'query the PostText instance with a natural language question to get a view-based answer', 'review the PostText class and its query method for view-based question answering logic', 'refactor the PostText query method to re-enable the commented out RAG-based retrieval QA', 'build a RetrievalBasedQA instance that loads a pickled vectorstore and configures a LangChain RAG chain with a ChatOpenAI LLM', 'create a function that loads a pickled FAISS vectorstore from a file path for use in retrieval-based QA', 'query the RetrievalBasedQA chain with a natural language question and get an answer with source citations', 'review the RetrievalBasedQA class initialization that sets up a ChatOpenAI LLM and a RetrievalQAWithSourcesChain retriever', 'summarize the RetrievalBasedQA class that provides retrieval-augmented generation QA using LangChain and a pickled vectorstore', 'use ViewBasedQA to answer a natural language question against SQLite views and return SQL results', 'match a user question to the most relevant view table using OpenAI embeddings and cosine similarity', 'generate a provenance SQL query that traces which base tuples contributed to a given query result', 'load or generate view metadata embeddings from CSV or via the OpenAI embedding model', 'translate a SQL query result table into a natural language English sentence using an LLM', 'read a views catalog file and parse table metadata into a dictionary', 'rewrite a SQL query to add fuzzy matching using embedding-based CLOSE function', 'get an OpenAI text embedding with disk-based caching to avoid redundant API calls', 'perform fuzzy string matching between two strings using cosine similarity on embeddings', 'return a list of JSON-serialized view descriptions from a views catalog dictionary']
```

Usage

```
{'query_views_with_natural_language': 'use ViewBasedQA to answer a natural language question against SQLite views and return SQL results', 'match_views_by_embedding': 'match a user question to the most relevant view table using OpenAI embeddings and cosine similarity', 'generate_provenance_query': 'generate a provenance SQL query that traces which base tuples contributed to a given query result', 'load_viewsmetadata_embeddings': 'load or generate view metadata embeddings from CSV or via the OpenAI embedding model', 'table_result2English': 'translate a SQL query result table into a natural language English sentence using an LLM'}
```

## File: facebookresearch_personal-timeline/src/qa/posttext/src/views_util.py

Prompts

```
['run the PostText CLI tool to answer questions using view-based QA on a dataset directory', 'create a PostText instance with a config dictionary and dataset directory path', 'query the PostText instance with a natural language question to get a view-based answer', 'review the PostText class and its query method for view-based question answering logic', 'refactor the PostText query method to re-enable the commented out RAG-based retrieval QA', 'build a RetrievalBasedQA instance that loads a pickled vectorstore and configures a LangChain RAG chain with a ChatOpenAI LLM', 'create a function that loads a pickled FAISS vectorstore from a file path for use in retrieval-based QA', 'query the RetrievalBasedQA chain with a natural language question and get an answer with source citations', 'review the RetrievalBasedQA class initialization that sets up a ChatOpenAI LLM and a RetrievalQAWithSourcesChain retriever', 'summarize the RetrievalBasedQA class that provides retrieval-augmented generation QA using LangChain and a pickled vectorstore', 'use ViewBasedQA to answer a natural language question against SQLite views and return SQL results', 'match a user question to the most relevant view table using OpenAI embeddings and cosine similarity', 'generate a provenance SQL query that traces which base tuples contributed to a given query result', 'load or generate view metadata embeddings from CSV or via the OpenAI embedding model', 'translate a SQL query result table into a natural language English sentence using an LLM', 'read a views catalog file and parse table metadata into a dictionary', 'rewrite a SQL query to add fuzzy matching using embedding-based CLOSE function', 'get an OpenAI text embedding with disk-based caching to avoid redundant API calls', 'perform fuzzy string matching between two strings using cosine similarity on embeddings', 'return a list of JSON-serialized view descriptions from a views catalog dictionary']
```

Usage

```
{'read_views_catalog': 'read a views catalog file and parse table metadata into a dictionary', 'prep_SQL': 'rewrite a SQL query to add fuzzy matching using embedding-based CLOSE function', 'get_embedding_with_cache': 'get an OpenAI text embedding with disk-based caching to avoid redundant API calls', 'customLIKE': 'perform fuzzy string matching between two strings using cosine similarity on embeddings', 'get_desc': 'return a list of JSON-serialized view descriptions from a views catalog dictionary'}
```

