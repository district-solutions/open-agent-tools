# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/Contextual-Chunking-RAG/embedding.py

Prompts

```
['generate a vector embedding for any input text using the Jina embeddings model', 'create a LocalJinaEmbedding class instance compatible with LlamaIndex for text and query embeddings', 'get a text embedding as a list via LocalJinaEmbedding for LlamaIndex document indexing', 'get a query embedding as a list via LocalJinaEmbedding for LlamaIndex retrieval queries', 'run the embedding module directly to generate and print the shape of a text embedding', 'generate contextual keywords for each chunk of document content using Llama-3.1-405B', 'generate 1-3 questions for sampled document chunks using Llama-3.1-405B', 'parse LLM keyword output into a list of keyword lists per chunk', 'get a RAG answer from Llama-3.1-405B using chunked content and a user question', 'run a chat completion with Llama-3.1-405B via DeepInfra using a system and user message']
```

Usage

```
{'get_embedding_text': 'generate a vector embedding for any input text using the Jina embeddings model', 'create_local_jina_embedding': 'create a LocalJinaEmbedding class instance compatible with LlamaIndex for text and query embeddings', 'get_text_embedding_llamaindex': 'get a text embedding as a list via LocalJinaEmbedding for LlamaIndex document indexing', 'get_query_embedding_llamaindex': 'get a query embedding as a list via LocalJinaEmbedding for LlamaIndex retrieval queries', 'run_embedding_main': 'run the embedding module directly to generate and print the shape of a text embedding'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/Contextual-Chunking-RAG/helper.py

Prompts

```
['generate a vector embedding for any input text using the Jina embeddings model', 'create a LocalJinaEmbedding class instance compatible with LlamaIndex for text and query embeddings', 'get a text embedding as a list via LocalJinaEmbedding for LlamaIndex document indexing', 'get a query embedding as a list via LocalJinaEmbedding for LlamaIndex retrieval queries', 'run the embedding module directly to generate and print the shape of a text embedding', 'generate contextual keywords for each chunk of document content using Llama-3.1-405B', 'generate 1-3 questions for sampled document chunks using Llama-3.1-405B', 'parse LLM keyword output into a list of keyword lists per chunk', 'get a RAG answer from Llama-3.1-405B using chunked content and a user question', 'run a chat completion with Llama-3.1-405B via DeepInfra using a system and user message']
```

Usage

```
{'generate_contextual_keywords': 'generate contextual keywords for each chunk of document content using Llama-3.1-405B', 'generate_questions_bychunk': 'generate 1-3 questions for sampled document chunks using Llama-3.1-405B', 'parse_keywords': 'parse LLM keyword output into a list of keyword lists per chunk', 'get_llm_answer': 'get a RAG answer from Llama-3.1-405B using chunked content and a user question', 'deepinfra_run': 'run a chat completion with Llama-3.1-405B via DeepInfra using a system and user message'}
```

