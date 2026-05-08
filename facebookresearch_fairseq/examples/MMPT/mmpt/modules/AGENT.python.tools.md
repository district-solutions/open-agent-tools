# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/MMPT/mmpt/modules/mm.py

Prompts

```
['build a VideoTokenMLP module that projects video features into the model hidden size using a two-layer MLP', 'create an MMBertEmbeddings module that fuses text and video embeddings with position and token type embeddings', 'test the MMBertEmbeddings forward pass with input_ids and optional video embeddings to produce multimodal embeddings', 'review the AlignHead module that maps pooled output to binary sequence relationship logits for alignment tasks', 'refactor the VideoTokenMLP forward method to add residual connections or change activation functions', 'create a VectorRetriever with flatl2 index type for FAISS-based video vector retrieval', 'add hidden state vectors and video IDs to a VectorRetriever FAISS index', 'search a VectorRetriever FAISS index with query hidden states and an original distance threshold', 'save a VectorRetriever FAISS index to disk and load it back from a directory', 'search a MMVectorRetriever to retrieve video from text or text from video using FAISS', 'build a VideoVectorPool to average video clips as video representations using pooled video and text embeddings', 'build a DistributedVectorPool to sync retrieval results across multiple GPUs and nodes', 'build a DistributedVideoVectorPool to average video clips with multi-GPU synchronization support', 'review the VectorPool build_retriver method to configure centroids and database type for retrieval', 'review the DistributedVectorPool save and load methods for persisting hidden states and video IDs across ranks']
```

Usage

```
{'build_VideoTokenMLP': 'build a VideoTokenMLP module that projects video features into the model hidden size using a two-layer MLP', 'create_MMBertEmbeddings': 'create an MMBertEmbeddings module that fuses text and video embeddings with position and token type embeddings', 'test_MMBertEmbeddings_forward': 'test the MMBertEmbeddings forward pass with input_ids and optional video embeddings to produce multimodal embeddings', 'review_AlignHead': 'review the AlignHead module that maps pooled output to binary sequence relationship logits for alignment tasks', 'refactor_VideoTokenMLP_forward': 'refactor the VideoTokenMLP forward method to add residual connections or change activation functions'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/modules/retri.py

Prompts

```
['build a VideoTokenMLP module that projects video features into the model hidden size using a two-layer MLP', 'create an MMBertEmbeddings module that fuses text and video embeddings with position and token type embeddings', 'test the MMBertEmbeddings forward pass with input_ids and optional video embeddings to produce multimodal embeddings', 'review the AlignHead module that maps pooled output to binary sequence relationship logits for alignment tasks', 'refactor the VideoTokenMLP forward method to add residual connections or change activation functions', 'create a VectorRetriever with flatl2 index type for FAISS-based video vector retrieval', 'add hidden state vectors and video IDs to a VectorRetriever FAISS index', 'search a VectorRetriever FAISS index with query hidden states and an original distance threshold', 'save a VectorRetriever FAISS index to disk and load it back from a directory', 'search a MMVectorRetriever to retrieve video from text or text from video using FAISS', 'build a VideoVectorPool to average video clips as video representations using pooled video and text embeddings', 'build a DistributedVectorPool to sync retrieval results across multiple GPUs and nodes', 'build a DistributedVideoVectorPool to average video clips with multi-GPU synchronization support', 'review the VectorPool build_retriver method to configure centroids and database type for retrieval', 'review the DistributedVectorPool save and load methods for persisting hidden states and video IDs across ranks']
```

Usage

```
{'create_VectorRetriever_flatl2': 'create a VectorRetriever with flatl2 index type for FAISS-based video vector retrieval', 'add_vectors_to_VectorRetriever': 'add hidden state vectors and video IDs to a VectorRetriever FAISS index', 'search_VectorRetriever': 'search a VectorRetriever FAISS index with query hidden states and an original distance threshold', 'save_and_load_VectorRetriever': 'save a VectorRetriever FAISS index to disk and load it back from a directory', 'search_MMVectorRetriever_cross_modality': 'search a MMVectorRetriever to retrieve video from text or text from video using FAISS'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/modules/vectorpool.py

Prompts

```
['build a VideoTokenMLP module that projects video features into the model hidden size using a two-layer MLP', 'create an MMBertEmbeddings module that fuses text and video embeddings with position and token type embeddings', 'test the MMBertEmbeddings forward pass with input_ids and optional video embeddings to produce multimodal embeddings', 'review the AlignHead module that maps pooled output to binary sequence relationship logits for alignment tasks', 'refactor the VideoTokenMLP forward method to add residual connections or change activation functions', 'create a VectorRetriever with flatl2 index type for FAISS-based video vector retrieval', 'add hidden state vectors and video IDs to a VectorRetriever FAISS index', 'search a VectorRetriever FAISS index with query hidden states and an original distance threshold', 'save a VectorRetriever FAISS index to disk and load it back from a directory', 'search a MMVectorRetriever to retrieve video from text or text from video using FAISS', 'build a VideoVectorPool to average video clips as video representations using pooled video and text embeddings', 'build a DistributedVectorPool to sync retrieval results across multiple GPUs and nodes', 'build a DistributedVideoVectorPool to average video clips with multi-GPU synchronization support', 'review the VectorPool build_retriver method to configure centroids and database type for retrieval', 'review the DistributedVectorPool save and load methods for persisting hidden states and video IDs across ranks']
```

Usage

```
{'build_VideoVectorPool': 'build a VideoVectorPool to average video clips as video representations using pooled video and text embeddings', 'build_DistributedVectorPool': 'build a DistributedVectorPool to sync retrieval results across multiple GPUs and nodes', 'build_DistributedVideoVectorPool': 'build a DistributedVideoVectorPool to average video clips with multi-GPU synchronization support', 'review_VectorPool_build_retriver': 'review the VectorPool build_retriver method to configure centroids and database type for retrieval', 'review_DistributedVectorPool_save_load': 'review the DistributedVectorPool save and load methods for persisting hidden states and video IDs across ranks'}
```

