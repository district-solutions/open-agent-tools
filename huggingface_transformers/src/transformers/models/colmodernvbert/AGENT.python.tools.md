# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/colmodernvbert/configuration_colmodernvbert.py

Prompts

```
['create a ColModernVBertConfig instance with default embedding_dim and initializer_range for retrieval modeling', 'build a ColModernVBertConfig from a dictionary containing vlm_config model_type and parameters', 'initialize vlm_config with ModernVBertConfig defaults when vlm_config is None', 'get the text configuration from the nested vlm_config via get_text_config method', 'create a ColModernVBertForRetrieval model using a ColModernVBertConfig instance', 'create a ColModernVBertForRetrieval model for multi-vector document retrieval from images and text', 'build an embedding projection layer that maps VLM hidden states to a configurable embedding dimension', 'run the model forward pass to produce L2-normalized multi-vector embeddings from input text and pixel values', 'test the ColBERT-style late interaction embedding pipeline with attention mask masking', 'review the ColModernVBertForRetrievalOutput dataclass containing embeddings, loss, and hidden states', 'create a ColModernVBertConfig with a ModernVBert VLM backbone and configurable embedding dimension', 'build a ColModernVBertProcessor that wraps a VLM processor for images and text queries', 'process document images with a visual prompt prefix and optional suffix labels', 'encode text queries with a prefix and augmentation suffix tokens for retrieval', 'score retrieval using ColBERT-style late interaction MaxSim between query and passage embeddings', 'create a ColModernVBertProcessor with an image processor and tokenizer for multimodal document understanding', 'build image inputs with visual prompt prefix using ColModernVBertProcessor.process_images for document page encoding', 'build text queries with query prefix and augmentation suffix using ColModernVBertProcessor.process_queries for retrieval', 'run late-interaction MaxSim scoring between query and passage embeddings using ColModernVBertProcessor.score_retrieval', 'test multimodal tokenization with image tokens, row-col patches, and global image tags using ColModernVBertProcessor.__call__']
```

Usage

```
{'create_ColModernVBertConfig': 'create a ColModernVBertConfig instance with default embedding_dim and initializer_range for retrieval modeling', 'build_ColModernVBertConfig_from_dict': 'build a ColModernVBertConfig from a dictionary containing vlm_config model_type and parameters', 'initialize_vlm_config_default': 'initialize vlm_config with ModernVBertConfig defaults when vlm_config is None', 'get_text_config': 'get the text configuration from the nested vlm_config via get_text_config method', 'create_ColModernVBertForRetrieval': 'create a ColModernVBertForRetrieval model using a ColModernVBertConfig instance'}
```

## File: huggingface_transformers/src/transformers/models/colmodernvbert/modeling_colmodernvbert.py

Prompts

```
['create a ColModernVBertConfig instance with default embedding_dim and initializer_range for retrieval modeling', 'build a ColModernVBertConfig from a dictionary containing vlm_config model_type and parameters', 'initialize vlm_config with ModernVBertConfig defaults when vlm_config is None', 'get the text configuration from the nested vlm_config via get_text_config method', 'create a ColModernVBertForRetrieval model using a ColModernVBertConfig instance', 'create a ColModernVBertForRetrieval model for multi-vector document retrieval from images and text', 'build an embedding projection layer that maps VLM hidden states to a configurable embedding dimension', 'run the model forward pass to produce L2-normalized multi-vector embeddings from input text and pixel values', 'test the ColBERT-style late interaction embedding pipeline with attention mask masking', 'review the ColModernVBertForRetrievalOutput dataclass containing embeddings, loss, and hidden states', 'create a ColModernVBertConfig with a ModernVBert VLM backbone and configurable embedding dimension', 'build a ColModernVBertProcessor that wraps a VLM processor for images and text queries', 'process document images with a visual prompt prefix and optional suffix labels', 'encode text queries with a prefix and augmentation suffix tokens for retrieval', 'score retrieval using ColBERT-style late interaction MaxSim between query and passage embeddings', 'create a ColModernVBertProcessor with an image processor and tokenizer for multimodal document understanding', 'build image inputs with visual prompt prefix using ColModernVBertProcessor.process_images for document page encoding', 'build text queries with query prefix and augmentation suffix using ColModernVBertProcessor.process_queries for retrieval', 'run late-interaction MaxSim scoring between query and passage embeddings using ColModernVBertProcessor.score_retrieval', 'test multimodal tokenization with image tokens, row-col patches, and global image tags using ColModernVBertProcessor.__call__']
```

Usage

```
{'create_colmodernvbert_retrieval_model': 'create a ColModernVBertForRetrieval model for multi-vector document retrieval from images and text', 'build_embedding_projector': 'build an embedding projection layer that maps VLM hidden states to a configurable embedding dimension', 'run_model_forward_pass': 'run the model forward pass to produce L2-normalized multi-vector embeddings from input text and pixel values', 'test_colbert_late_interaction': 'test the ColBERT-style late interaction embedding pipeline with attention mask masking', 'review_colmodernvbert_output_class': 'review the ColModernVBertForRetrievalOutput dataclass containing embeddings, loss, and hidden states'}
```

## File: huggingface_transformers/src/transformers/models/colmodernvbert/modular_colmodernvbert.py

Prompts

```
['create a ColModernVBertConfig instance with default embedding_dim and initializer_range for retrieval modeling', 'build a ColModernVBertConfig from a dictionary containing vlm_config model_type and parameters', 'initialize vlm_config with ModernVBertConfig defaults when vlm_config is None', 'get the text configuration from the nested vlm_config via get_text_config method', 'create a ColModernVBertForRetrieval model using a ColModernVBertConfig instance', 'create a ColModernVBertForRetrieval model for multi-vector document retrieval from images and text', 'build an embedding projection layer that maps VLM hidden states to a configurable embedding dimension', 'run the model forward pass to produce L2-normalized multi-vector embeddings from input text and pixel values', 'test the ColBERT-style late interaction embedding pipeline with attention mask masking', 'review the ColModernVBertForRetrievalOutput dataclass containing embeddings, loss, and hidden states', 'create a ColModernVBertConfig with a ModernVBert VLM backbone and configurable embedding dimension', 'build a ColModernVBertProcessor that wraps a VLM processor for images and text queries', 'process document images with a visual prompt prefix and optional suffix labels', 'encode text queries with a prefix and augmentation suffix tokens for retrieval', 'score retrieval using ColBERT-style late interaction MaxSim between query and passage embeddings', 'create a ColModernVBertProcessor with an image processor and tokenizer for multimodal document understanding', 'build image inputs with visual prompt prefix using ColModernVBertProcessor.process_images for document page encoding', 'build text queries with query prefix and augmentation suffix using ColModernVBertProcessor.process_queries for retrieval', 'run late-interaction MaxSim scoring between query and passage embeddings using ColModernVBertProcessor.score_retrieval', 'test multimodal tokenization with image tokens, row-col patches, and global image tags using ColModernVBertProcessor.__call__']
```

Usage

```
{'create_colmodernvbert_config': 'create a ColModernVBertConfig with a ModernVBert VLM backbone and configurable embedding dimension', 'build_colmodernvbert_processor': 'build a ColModernVBertProcessor that wraps a VLM processor for images and text queries', 'process_document_images': 'process document images with a visual prompt prefix and optional suffix labels', 'encode_text_queries': 'encode text queries with a prefix and augmentation suffix tokens for retrieval', 'score_retrieval_embeddings': 'score retrieval using ColBERT-style late interaction MaxSim between query and passage embeddings'}
```

## File: huggingface_transformers/src/transformers/models/colmodernvbert/processing_colmodernvbert.py

Prompts

```
['create a ColModernVBertConfig instance with default embedding_dim and initializer_range for retrieval modeling', 'build a ColModernVBertConfig from a dictionary containing vlm_config model_type and parameters', 'initialize vlm_config with ModernVBertConfig defaults when vlm_config is None', 'get the text configuration from the nested vlm_config via get_text_config method', 'create a ColModernVBertForRetrieval model using a ColModernVBertConfig instance', 'create a ColModernVBertForRetrieval model for multi-vector document retrieval from images and text', 'build an embedding projection layer that maps VLM hidden states to a configurable embedding dimension', 'run the model forward pass to produce L2-normalized multi-vector embeddings from input text and pixel values', 'test the ColBERT-style late interaction embedding pipeline with attention mask masking', 'review the ColModernVBertForRetrievalOutput dataclass containing embeddings, loss, and hidden states', 'create a ColModernVBertConfig with a ModernVBert VLM backbone and configurable embedding dimension', 'build a ColModernVBertProcessor that wraps a VLM processor for images and text queries', 'process document images with a visual prompt prefix and optional suffix labels', 'encode text queries with a prefix and augmentation suffix tokens for retrieval', 'score retrieval using ColBERT-style late interaction MaxSim between query and passage embeddings', 'create a ColModernVBertProcessor with an image processor and tokenizer for multimodal document understanding', 'build image inputs with visual prompt prefix using ColModernVBertProcessor.process_images for document page encoding', 'build text queries with query prefix and augmentation suffix using ColModernVBertProcessor.process_queries for retrieval', 'run late-interaction MaxSim scoring between query and passage embeddings using ColModernVBertProcessor.score_retrieval', 'test multimodal tokenization with image tokens, row-col patches, and global image tags using ColModernVBertProcessor.__call__']
```

Usage

```
{'create_colmodernvbert_processor': 'create a ColModernVBertProcessor with an image processor and tokenizer for multimodal document understanding', 'build_image_processor': 'build image inputs with visual prompt prefix using ColModernVBertProcessor.process_images for document page encoding', 'build_query_processor': 'build text queries with query prefix and augmentation suffix using ColModernVBertProcessor.process_queries for retrieval', 'run_retrieval_scoring': 'run late-interaction MaxSim scoring between query and passage embeddings using ColModernVBertProcessor.score_retrieval', 'test_multimodal_tokenization': 'test multimodal tokenization with image tokens, row-col patches, and global image tags using ColModernVBertProcessor.__call__'}
```

