# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/retrieval/vector/async_client.py

Prompts

```
['build an async vector database client that wraps a sync client using asyncio.to_thread', 'create a function that searches a vector collection by embedding vectors with optional filters and limit', 'insert a list of vector items into a named vector database collection asynchronously', 'query items from a vector collection by filter criteria with an optional result limit', 'delete a named vector database collection or remove specific items by id or filter', 'build a vector database client instance by specifying the vector type string such as milvus or qdrant', 'create a factory class that returns vector database clients based on the configured VECTOR_DB type', 'review the Vector.get_vector static method that dispatches to the correct vector database client implementation', 'test the Vector.get_vector method with supported vector types like milvus, qdrant, chroma, and pinecone', 'summarize the vector factory module that instantiates and exposes a global VECTOR_DB_CLIENT singleton', 'create a vector database backend class that inherits from VectorDBBase and implements all abstract methods', 'build a VectorItem model with id, text, vector, and metadata fields for storing vector data', 'test the VectorDBBase search method to find similar vectors in a collection with optional filtering', 'refactor the VectorDBBase upsert method to insert or update vector items in a collection', 'review the VectorDBBase query method to retrieve vectors from a collection using metadata filters', 'filter the metadata dictionary to exclude keys like content, pages, tables, paragraphs, sections, and figures', 'process the metadata dictionary by removing excluded keys and converting non-serializable values to strings', 'filter metadata dictionary to remove large fields and convert datetime objects to strings', 'filter metadata dictionary to remove large fields and convert list or dict values to string representations', 'review the filter_metadata function that removes excluded keys from a metadata dictionary']
```

Usage

```
{'build_async_vector_db_client': 'build an async vector database client that wraps a sync client using asyncio.to_thread', 'create_vector_search': 'create a function that searches a vector collection by embedding vectors with optional filters and limit', 'insert_vector_items': 'insert a list of vector items into a named vector database collection asynchronously', 'query_vector_collection': 'query items from a vector collection by filter criteria with an optional result limit', 'delete_vector_collection': 'delete a named vector database collection or remove specific items by id or filter'}
```

## File: open-webui_open-webui/backend/open_webui/retrieval/vector/factory.py

Prompts

```
['build an async vector database client that wraps a sync client using asyncio.to_thread', 'create a function that searches a vector collection by embedding vectors with optional filters and limit', 'insert a list of vector items into a named vector database collection asynchronously', 'query items from a vector collection by filter criteria with an optional result limit', 'delete a named vector database collection or remove specific items by id or filter', 'build a vector database client instance by specifying the vector type string such as milvus or qdrant', 'create a factory class that returns vector database clients based on the configured VECTOR_DB type', 'review the Vector.get_vector static method that dispatches to the correct vector database client implementation', 'test the Vector.get_vector method with supported vector types like milvus, qdrant, chroma, and pinecone', 'summarize the vector factory module that instantiates and exposes a global VECTOR_DB_CLIENT singleton', 'create a vector database backend class that inherits from VectorDBBase and implements all abstract methods', 'build a VectorItem model with id, text, vector, and metadata fields for storing vector data', 'test the VectorDBBase search method to find similar vectors in a collection with optional filtering', 'refactor the VectorDBBase upsert method to insert or update vector items in a collection', 'review the VectorDBBase query method to retrieve vectors from a collection using metadata filters', 'filter the metadata dictionary to exclude keys like content, pages, tables, paragraphs, sections, and figures', 'process the metadata dictionary by removing excluded keys and converting non-serializable values to strings', 'filter metadata dictionary to remove large fields and convert datetime objects to strings', 'filter metadata dictionary to remove large fields and convert list or dict values to string representations', 'review the filter_metadata function that removes excluded keys from a metadata dictionary']
```

Usage

```
{'build_get_vector_instance': 'build a vector database client instance by specifying the vector type string such as milvus or qdrant', 'create_vector_client_factory': 'create a factory class that returns vector database clients based on the configured VECTOR_DB type', 'review_Vector_get_vector': 'review the Vector.get_vector static method that dispatches to the correct vector database client implementation', 'test_Vector_get_vector': 'test the Vector.get_vector method with supported vector types like milvus, qdrant, chroma, and pinecone', 'summarize_vector_factory': 'summarize the vector factory module that instantiates and exposes a global VECTOR_DB_CLIENT singleton'}
```

## File: open-webui_open-webui/backend/open_webui/retrieval/vector/main.py

Prompts

```
['build an async vector database client that wraps a sync client using asyncio.to_thread', 'create a function that searches a vector collection by embedding vectors with optional filters and limit', 'insert a list of vector items into a named vector database collection asynchronously', 'query items from a vector collection by filter criteria with an optional result limit', 'delete a named vector database collection or remove specific items by id or filter', 'build a vector database client instance by specifying the vector type string such as milvus or qdrant', 'create a factory class that returns vector database clients based on the configured VECTOR_DB type', 'review the Vector.get_vector static method that dispatches to the correct vector database client implementation', 'test the Vector.get_vector method with supported vector types like milvus, qdrant, chroma, and pinecone', 'summarize the vector factory module that instantiates and exposes a global VECTOR_DB_CLIENT singleton', 'create a vector database backend class that inherits from VectorDBBase and implements all abstract methods', 'build a VectorItem model with id, text, vector, and metadata fields for storing vector data', 'test the VectorDBBase search method to find similar vectors in a collection with optional filtering', 'refactor the VectorDBBase upsert method to insert or update vector items in a collection', 'review the VectorDBBase query method to retrieve vectors from a collection using metadata filters', 'filter the metadata dictionary to exclude keys like content, pages, tables, paragraphs, sections, and figures', 'process the metadata dictionary by removing excluded keys and converting non-serializable values to strings', 'filter metadata dictionary to remove large fields and convert datetime objects to strings', 'filter metadata dictionary to remove large fields and convert list or dict values to string representations', 'review the filter_metadata function that removes excluded keys from a metadata dictionary']
```

Usage

```
{'create_VectorDBBase': 'create a vector database backend class that inherits from VectorDBBase and implements all abstract methods', 'build_VectorItem_model': 'build a VectorItem model with id, text, vector, and metadata fields for storing vector data', 'test_VectorDBBase_search': 'test the VectorDBBase search method to find similar vectors in a collection with optional filtering', 'refactor_VectorDBBase_upsert': 'refactor the VectorDBBase upsert method to insert or update vector items in a collection', 'review_VectorDBBase_query': 'review the VectorDBBase query method to retrieve vectors from a collection using metadata filters'}
```

## File: open-webui_open-webui/backend/open_webui/retrieval/vector/utils.py

Prompts

```
['build an async vector database client that wraps a sync client using asyncio.to_thread', 'create a function that searches a vector collection by embedding vectors with optional filters and limit', 'insert a list of vector items into a named vector database collection asynchronously', 'query items from a vector collection by filter criteria with an optional result limit', 'delete a named vector database collection or remove specific items by id or filter', 'build a vector database client instance by specifying the vector type string such as milvus or qdrant', 'create a factory class that returns vector database clients based on the configured VECTOR_DB type', 'review the Vector.get_vector static method that dispatches to the correct vector database client implementation', 'test the Vector.get_vector method with supported vector types like milvus, qdrant, chroma, and pinecone', 'summarize the vector factory module that instantiates and exposes a global VECTOR_DB_CLIENT singleton', 'create a vector database backend class that inherits from VectorDBBase and implements all abstract methods', 'build a VectorItem model with id, text, vector, and metadata fields for storing vector data', 'test the VectorDBBase search method to find similar vectors in a collection with optional filtering', 'refactor the VectorDBBase upsert method to insert or update vector items in a collection', 'review the VectorDBBase query method to retrieve vectors from a collection using metadata filters', 'filter the metadata dictionary to exclude keys like content, pages, tables, paragraphs, sections, and figures', 'process the metadata dictionary by removing excluded keys and converting non-serializable values to strings', 'filter metadata dictionary to remove large fields and convert datetime objects to strings', 'filter metadata dictionary to remove large fields and convert list or dict values to string representations', 'review the filter_metadata function that removes excluded keys from a metadata dictionary']
```

Usage

```
{'filter_metadata': 'filter the metadata dictionary to exclude keys like content, pages, tables, paragraphs, sections, and figures', 'process_metadata': 'process the metadata dictionary by removing excluded keys and converting non-serializable values to strings', 'filter_metadata_datetime': 'filter metadata dictionary to remove large fields and convert datetime objects to strings', 'filter_metadata_lists_dicts': 'filter metadata dictionary to remove large fields and convert list or dict values to string representations', 'review_filter_metadata': 'review the filter_metadata function that removes excluded keys from a metadata dictionary'}
```

