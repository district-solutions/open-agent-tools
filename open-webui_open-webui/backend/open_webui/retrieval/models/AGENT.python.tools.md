# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/retrieval/models/base_reranker.py

Prompts

```
['review the BaseReranker abstract class and its predict method signature', 'test the BaseReranker abstract class to verify predict is abstract and must be implemented by subclasses', 'summarize the BaseReranker abstract base class used for sentence pair reranking', 'refactor the BaseReranker abstract class to support additional reranking parameters', 'review the BaseReranker.predict abstract method that takes sentence pairs and returns relevance scores', 'create a ColBERT reranker instance with a model name and optional docker environment flag', 'calculate similarity scores between query embeddings and document embeddings using ColBERT max pooling', 'run ColBERT predict to score documents against a query and return normalized relevance scores', 'embed a query string into ColBERT vector space using queryFromText with batch size 32', 'embed multiple documents into ColBERT vector space using docFromText with batch size 32', 'create an ExternalReranker instance with an API key and URL for external reranking service', 'test the ExternalReranker.predict method with query-document sentence pairs', 'review the ExternalReranker class that extends BaseReranker for external API-based reranking', 'build an ExternalReranker with a custom timeout and model name for reranking requests', 'summarize how ExternalReranker.predict sends documents to an external API and returns relevance scores']
```

Usage

```
{'review_BaseReranker': 'review the BaseReranker abstract class and its predict method signature', 'test_BaseReranker': 'test the BaseReranker abstract class to verify predict is abstract and must be implemented by subclasses', 'summarize_BaseReranker': 'summarize the BaseReranker abstract base class used for sentence pair reranking', 'refactor_BaseReranker': 'refactor the BaseReranker abstract class to support additional reranking parameters', 'review_BaseReranker_predict': 'review the BaseReranker.predict abstract method that takes sentence pairs and returns relevance scores'}
```

## File: open-webui_open-webui/backend/open_webui/retrieval/models/colbert.py

Prompts

```
['review the BaseReranker abstract class and its predict method signature', 'test the BaseReranker abstract class to verify predict is abstract and must be implemented by subclasses', 'summarize the BaseReranker abstract base class used for sentence pair reranking', 'refactor the BaseReranker abstract class to support additional reranking parameters', 'review the BaseReranker.predict abstract method that takes sentence pairs and returns relevance scores', 'create a ColBERT reranker instance with a model name and optional docker environment flag', 'calculate similarity scores between query embeddings and document embeddings using ColBERT max pooling', 'run ColBERT predict to score documents against a query and return normalized relevance scores', 'embed a query string into ColBERT vector space using queryFromText with batch size 32', 'embed multiple documents into ColBERT vector space using docFromText with batch size 32', 'create an ExternalReranker instance with an API key and URL for external reranking service', 'test the ExternalReranker.predict method with query-document sentence pairs', 'review the ExternalReranker class that extends BaseReranker for external API-based reranking', 'build an ExternalReranker with a custom timeout and model name for reranking requests', 'summarize how ExternalReranker.predict sends documents to an external API and returns relevance scores']
```

Usage

```
{'create_colbert_reranker': 'create a ColBERT reranker instance with a model name and optional docker environment flag', 'calculate_similarity_scores': 'calculate similarity scores between query embeddings and document embeddings using ColBERT max pooling', 'run_colbert_predict': 'run ColBERT predict to score documents against a query and return normalized relevance scores', 'embed_query_with_colbert': 'embed a query string into ColBERT vector space using queryFromText with batch size 32', 'embed_documents_with_colbert': 'embed multiple documents into ColBERT vector space using docFromText with batch size 32'}
```

## File: open-webui_open-webui/backend/open_webui/retrieval/models/external.py

Prompts

```
['review the BaseReranker abstract class and its predict method signature', 'test the BaseReranker abstract class to verify predict is abstract and must be implemented by subclasses', 'summarize the BaseReranker abstract base class used for sentence pair reranking', 'refactor the BaseReranker abstract class to support additional reranking parameters', 'review the BaseReranker.predict abstract method that takes sentence pairs and returns relevance scores', 'create a ColBERT reranker instance with a model name and optional docker environment flag', 'calculate similarity scores between query embeddings and document embeddings using ColBERT max pooling', 'run ColBERT predict to score documents against a query and return normalized relevance scores', 'embed a query string into ColBERT vector space using queryFromText with batch size 32', 'embed multiple documents into ColBERT vector space using docFromText with batch size 32', 'create an ExternalReranker instance with an API key and URL for external reranking service', 'test the ExternalReranker.predict method with query-document sentence pairs', 'review the ExternalReranker class that extends BaseReranker for external API-based reranking', 'build an ExternalReranker with a custom timeout and model name for reranking requests', 'summarize how ExternalReranker.predict sends documents to an external API and returns relevance scores']
```

Usage

```
{'create_external_reranker': 'create an ExternalReranker instance with an API key and URL for external reranking service', 'test_external_reranker_predict': 'test the ExternalReranker.predict method with query-document sentence pairs', 'review_external_reranker_class': 'review the ExternalReranker class that extends BaseReranker for external API-based reranking', 'build_external_reranker_with_timeout': 'build an ExternalReranker with a custom timeout and model name for reranking requests', 'summarize_external_reranker_predict': 'summarize how ExternalReranker.predict sends documents to an external API and returns relevance scores'}
```

