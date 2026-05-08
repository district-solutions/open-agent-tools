# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/blenderbot2/agents/blenderbot2.py

Prompts

```
['build a BlenderBot2 RAG agent with long-term memory and retriever modules for dialogue', 'build a BlenderBot2 FiD agent combining factual knowledge with dialogue generation', 'build a BlenderBot2 FiD agent that uses search engine retrieval for knowledge access', 'review the HistoryCleanUnsafeToken class that filters unsafe tokens from dialogue history', 'review the BlenderBot2RagSequence class that retrieves documents prior to beam generation', 'build a retriever for RAG using retriever_factory with opt and dictionary agent', 'create a BlenderBot2 RAG model with long-term memory and query generation capabilities', 'retrieve documents from search and memory then concatenate with input for encoding', 'access long-term memory to write and retrieve memories using DPR encoders', 'create a LongTermMemory retriever that writes document embeddings and scores queries against stored memories', 'build a QueryGenerator agent from a model file to classify retrieval type and generate search queries', 'build a MemoryDecoder agent from a model file to generate persona memories from dialogue context', 'classify input text to determine whether to retrieve from memory, search, or skip retrieval entirely', 'generate prefixed persona memories from conversational context lines using the MemoryDecoder agent', 'clean a token vector by removing special tokens using a DictionaryAgent and clean_vec utility']
```

Usage

```
{'build_BlenderBot2RagAgent': 'build a BlenderBot2 RAG agent with long-term memory and retriever modules for dialogue', 'build_BlenderBot2FidAgent': 'build a BlenderBot2 FiD agent combining factual knowledge with dialogue generation', 'build_BlenderBot2SearchQueryFiDAgent': 'build a BlenderBot2 FiD agent that uses search engine retrieval for knowledge access', 'review_HistoryCleanUnsafeToken': 'review the HistoryCleanUnsafeToken class that filters unsafe tokens from dialogue history', 'review_BlenderBot2RagSequence': 'review the BlenderBot2RagSequence class that retrieves documents prior to beam generation'}
```

## File: facebookresearch_parlai/projects/blenderbot2/agents/modules.py

Prompts

```
['build a BlenderBot2 RAG agent with long-term memory and retriever modules for dialogue', 'build a BlenderBot2 FiD agent combining factual knowledge with dialogue generation', 'build a BlenderBot2 FiD agent that uses search engine retrieval for knowledge access', 'review the HistoryCleanUnsafeToken class that filters unsafe tokens from dialogue history', 'review the BlenderBot2RagSequence class that retrieves documents prior to beam generation', 'build a retriever for RAG using retriever_factory with opt and dictionary agent', 'create a BlenderBot2 RAG model with long-term memory and query generation capabilities', 'retrieve documents from search and memory then concatenate with input for encoding', 'access long-term memory to write and retrieve memories using DPR encoders', 'create a LongTermMemory retriever that writes document embeddings and scores queries against stored memories', 'build a QueryGenerator agent from a model file to classify retrieval type and generate search queries', 'build a MemoryDecoder agent from a model file to generate persona memories from dialogue context', 'classify input text to determine whether to retrieve from memory, search, or skip retrieval entirely', 'generate prefixed persona memories from conversational context lines using the MemoryDecoder agent', 'clean a token vector by removing special tokens using a DictionaryAgent and clean_vec utility']
```

Usage

```
{'build_retriever_factory': 'build a retriever for RAG using retriever_factory with opt and dictionary agent', 'create_BlenderBot2RagModel': 'create a BlenderBot2 RAG model with long-term memory and query generation capabilities', 'retrieve_and_concat_documents': 'retrieve documents from search and memory then concatenate with input for encoding', 'access_long_term_memory': 'access long-term memory to write and retrieve memories using DPR encoders', 'create_LongTermMemory': 'create a LongTermMemory retriever that writes document embeddings and scores queries against stored memories'}
```

## File: facebookresearch_parlai/projects/blenderbot2/agents/sub_modules.py

Prompts

```
['build a BlenderBot2 RAG agent with long-term memory and retriever modules for dialogue', 'build a BlenderBot2 FiD agent combining factual knowledge with dialogue generation', 'build a BlenderBot2 FiD agent that uses search engine retrieval for knowledge access', 'review the HistoryCleanUnsafeToken class that filters unsafe tokens from dialogue history', 'review the BlenderBot2RagSequence class that retrieves documents prior to beam generation', 'build a retriever for RAG using retriever_factory with opt and dictionary agent', 'create a BlenderBot2 RAG model with long-term memory and query generation capabilities', 'retrieve documents from search and memory then concatenate with input for encoding', 'access long-term memory to write and retrieve memories using DPR encoders', 'create a LongTermMemory retriever that writes document embeddings and scores queries against stored memories', 'build a QueryGenerator agent from a model file to classify retrieval type and generate search queries', 'build a MemoryDecoder agent from a model file to generate persona memories from dialogue context', 'classify input text to determine whether to retrieve from memory, search, or skip retrieval entirely', 'generate prefixed persona memories from conversational context lines using the MemoryDecoder agent', 'clean a token vector by removing special tokens using a DictionaryAgent and clean_vec utility']
```

Usage

```
{'build_query_generator': 'build a QueryGenerator agent from a model file to classify retrieval type and generate search queries', 'build_memory_decoder': 'build a MemoryDecoder agent from a model file to generate persona memories from dialogue context', 'classify_retrieval_QueryGenerator': 'classify input text to determine whether to retrieve from memory, search, or skip retrieval entirely', 'generate_memories_MemoryDecoder': 'generate prefixed persona memories from conversational context lines using the MemoryDecoder agent', 'clean_vec_with_dict': 'clean a token vector by removing special tokens using a DictionaryAgent and clean_vec utility'}
```

