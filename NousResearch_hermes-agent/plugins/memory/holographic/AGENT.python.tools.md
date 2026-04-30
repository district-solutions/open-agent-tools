# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/plugins/memory/holographic/holographic.py

Prompts

```
['create a deterministic phase vector atom from a word string using SHA-256 hashing', 'build a bag-of-words holographic representation by bundling atom vectors for each token in text', 'test circular convolution binding and correlation unbinding of two phase vectors', 'summarize structured fact encoding that binds content and entities to role vectors', 'run phase cosine similarity comparison between two holographic vectors', 'run hybrid FTS5+Jaccard+HRR search on the memory store with a text query, category filter, and trust threshold', 'probe the memory store for facts about an entity using HRR algebraic unbinding and compositional vector queries', 'run related-entity discovery on the memory store to find facts sharing structural connections with a given entity', 'run multi-entity compositional reasoning to find facts where all given entities play structural roles simultaneously', 'run contradiction detection on the memory store to find fact pairs with high entity overlap but low content similarity', 'create a MemoryStore instance with a custom SQLite database path and default trust score', 'add a fact with content, category, and tags to the MemoryStore and return its fact_id', 'search facts by full-text query with optional category filter and minimum trust score', 'record helpful or unhelpful feedback on a fact and adjust its trust score', 'recompute all HRR vectors and category memory banks from existing fact content']
```

Usage

```
{'create_encode_atom': 'create a deterministic phase vector atom from a word string using SHA-256 hashing', 'build_encode_text': 'build a bag-of-words holographic representation by bundling atom vectors for each token in text', 'test_bind_unbind': 'test circular convolution binding and correlation unbinding of two phase vectors', 'summarize_encode_fact': 'summarize structured fact encoding that binds content and entities to role vectors', 'run_similarity_check': 'run phase cosine similarity comparison between two holographic vectors'}
```

## File: NousResearch_hermes-agent/plugins/memory/holographic/retrieval.py

Prompts

```
['create a deterministic phase vector atom from a word string using SHA-256 hashing', 'build a bag-of-words holographic representation by bundling atom vectors for each token in text', 'test circular convolution binding and correlation unbinding of two phase vectors', 'summarize structured fact encoding that binds content and entities to role vectors', 'run phase cosine similarity comparison between two holographic vectors', 'run hybrid FTS5+Jaccard+HRR search on the memory store with a text query, category filter, and trust threshold', 'probe the memory store for facts about an entity using HRR algebraic unbinding and compositional vector queries', 'run related-entity discovery on the memory store to find facts sharing structural connections with a given entity', 'run multi-entity compositional reasoning to find facts where all given entities play structural roles simultaneously', 'run contradiction detection on the memory store to find fact pairs with high entity overlap but low content similarity', 'create a MemoryStore instance with a custom SQLite database path and default trust score', 'add a fact with content, category, and tags to the MemoryStore and return its fact_id', 'search facts by full-text query with optional category filter and minimum trust score', 'record helpful or unhelpful feedback on a fact and adjust its trust score', 'recompute all HRR vectors and category memory banks from existing fact content']
```

Usage

```
{'run_fact_retriever_search': 'run hybrid FTS5+Jaccard+HRR search on the memory store with a text query, category filter, and trust threshold', 'probe_fact_retriever_entity': 'probe the memory store for facts about an entity using HRR algebraic unbinding and compositional vector queries', 'run_fact_retriever_related': 'run related-entity discovery on the memory store to find facts sharing structural connections with a given entity', 'run_fact_retriever_reason': 'run multi-entity compositional reasoning to find facts where all given entities play structural roles simultaneously', 'run_fact_retriever_contradict': 'run contradiction detection on the memory store to find fact pairs with high entity overlap but low content similarity'}
```

## File: NousResearch_hermes-agent/plugins/memory/holographic/store.py

Prompts

```
['create a deterministic phase vector atom from a word string using SHA-256 hashing', 'build a bag-of-words holographic representation by bundling atom vectors for each token in text', 'test circular convolution binding and correlation unbinding of two phase vectors', 'summarize structured fact encoding that binds content and entities to role vectors', 'run phase cosine similarity comparison between two holographic vectors', 'run hybrid FTS5+Jaccard+HRR search on the memory store with a text query, category filter, and trust threshold', 'probe the memory store for facts about an entity using HRR algebraic unbinding and compositional vector queries', 'run related-entity discovery on the memory store to find facts sharing structural connections with a given entity', 'run multi-entity compositional reasoning to find facts where all given entities play structural roles simultaneously', 'run contradiction detection on the memory store to find fact pairs with high entity overlap but low content similarity', 'create a MemoryStore instance with a custom SQLite database path and default trust score', 'add a fact with content, category, and tags to the MemoryStore and return its fact_id', 'search facts by full-text query with optional category filter and minimum trust score', 'record helpful or unhelpful feedback on a fact and adjust its trust score', 'recompute all HRR vectors and category memory banks from existing fact content']
```

Usage

```
{'create_memory_store': 'create a MemoryStore instance with a custom SQLite database path and default trust score', 'add_fact_to_memory': 'add a fact with content, category, and tags to the MemoryStore and return its fact_id', 'search_facts_by_query': 'search facts by full-text query with optional category filter and minimum trust score', 'record_fact_feedback': 'record helpful or unhelpful feedback on a fact and adjust its trust score', 'rebuild_all_hrr_vectors': 'recompute all HRR vectors and category memory banks from existing fact content'}
```

