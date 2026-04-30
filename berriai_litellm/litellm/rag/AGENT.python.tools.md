# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/rag/main.py

Prompts

```
['ingest a document into a vector store with configurable chunking, embedding, and provider', 'query a RAG pipeline with vector store retrieval, optional reranking, and LLM completion', 'run async document ingestion into a vector store with file URL or base64-encoded content', 'run async RAG query with vector store search, reranking, and model completion', 'get the provider-specific RAG ingestion class from the registry for openai, bedrock, gemini, s3_vectors, or vertex_ai', 'extract the query string from the last user message in a list of chat messages', 'build a context message from a list of search result chunks for RAG prompt assembly', 'add vector store search results and optional rerank results to an LLM model response', 'extract text documents from a vector store search response dictionary', 'get original search result chunks corresponding to the top reranked results', 'get the RAG ingestion class for the openai provider', 'get the RAG ingestion class for the bedrock provider', 'get the RAG ingestion class for the vertex_ai provider', 'get the RAG transformation class for the vertex_ai provider', 'get the RAG transformation class for the openai provider']
```

Usage

```
{'ingest_document': 'ingest a document into a vector store with configurable chunking, embedding, and provider', 'query_rag_pipeline': 'query a RAG pipeline with vector store retrieval, optional reranking, and LLM completion', 'run_async_ingest': 'run async document ingestion into a vector store with file URL or base64-encoded content', 'run_async_query': 'run async RAG query with vector store search, reranking, and model completion', 'get_ingestion_class': 'get the provider-specific RAG ingestion class from the registry for openai, bedrock, gemini, s3_vectors, or vertex_ai'}
```

## File: berriai_litellm/litellm/rag/rag_query.py

Prompts

```
['ingest a document into a vector store with configurable chunking, embedding, and provider', 'query a RAG pipeline with vector store retrieval, optional reranking, and LLM completion', 'run async document ingestion into a vector store with file URL or base64-encoded content', 'run async RAG query with vector store search, reranking, and model completion', 'get the provider-specific RAG ingestion class from the registry for openai, bedrock, gemini, s3_vectors, or vertex_ai', 'extract the query string from the last user message in a list of chat messages', 'build a context message from a list of search result chunks for RAG prompt assembly', 'add vector store search results and optional rerank results to an LLM model response', 'extract text documents from a vector store search response dictionary', 'get original search result chunks corresponding to the top reranked results', 'get the RAG ingestion class for the openai provider', 'get the RAG ingestion class for the bedrock provider', 'get the RAG ingestion class for the vertex_ai provider', 'get the RAG transformation class for the vertex_ai provider', 'get the RAG transformation class for the openai provider']
```

Usage

```
{'extract_query_from_messages': 'extract the query string from the last user message in a list of chat messages', 'build_context_message': 'build a context message from a list of search result chunks for RAG prompt assembly', 'add_search_results_to_response': 'add vector store search results and optional rerank results to an LLM model response', 'extract_documents_from_search': 'extract text documents from a vector store search response dictionary', 'get_top_chunks_from_rerank': 'get original search result chunks corresponding to the top reranked results'}
```

## File: berriai_litellm/litellm/rag/utils.py

Prompts

```
['ingest a document into a vector store with configurable chunking, embedding, and provider', 'query a RAG pipeline with vector store retrieval, optional reranking, and LLM completion', 'run async document ingestion into a vector store with file URL or base64-encoded content', 'run async RAG query with vector store search, reranking, and model completion', 'get the provider-specific RAG ingestion class from the registry for openai, bedrock, gemini, s3_vectors, or vertex_ai', 'extract the query string from the last user message in a list of chat messages', 'build a context message from a list of search result chunks for RAG prompt assembly', 'add vector store search results and optional rerank results to an LLM model response', 'extract text documents from a vector store search response dictionary', 'get original search result chunks corresponding to the top reranked results', 'get the RAG ingestion class for the openai provider', 'get the RAG ingestion class for the bedrock provider', 'get the RAG ingestion class for the vertex_ai provider', 'get the RAG transformation class for the vertex_ai provider', 'get the RAG transformation class for the openai provider']
```

Usage

```
{'get_rag_ingestion_class_openai': 'get the RAG ingestion class for the openai provider', 'get_rag_ingestion_class_bedrock': 'get the RAG ingestion class for the bedrock provider', 'get_rag_ingestion_class_vertex_ai': 'get the RAG ingestion class for the vertex_ai provider', 'get_rag_transformation_class_vertex_ai': 'get the RAG transformation class for the vertex_ai provider', 'get_rag_transformation_class_openai': 'get the RAG transformation class for the openai provider'}
```

