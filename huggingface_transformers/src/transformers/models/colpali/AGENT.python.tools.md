# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/colpali/convert_colpali_weights_to_hf.py

Prompts

```
['convert ColPali model weights from the original repository to HuggingFace format', 'rename state dict keys from original ColPali format to HuggingFace transformers format', 'load original ColPali state dict from safetensors files on the HuggingFace Hub', 'run the CLI script to convert ColPali-v1.2-merged model to HuggingFace format and push to hub', 'run the CLI script to convert ColPali-v1.3-merged model to HuggingFace format and save locally', 'build a ColPaliForRetrieval model that generates multi-vector embeddings from document images for retrieval', 'create multi-vector embeddings from document images and queries using ColPaliForRetrieval forward pass', 'run ColPaliForRetrieval to produce L2-normalized embeddings from pixel values and input_ids for document retrieval', 'review the ColPaliPreTrainedModel base class with weight initialization and attention support flags', 'summarize the ColPaliForRetrievalOutput dataclass containing embeddings, hidden_states, and past_key_values', 'create a ColPaliProcessor instance with custom visual prompt prefix and query prefix for document retrieval', 'process images with ColPaliProcessor to generate input_ids, attention_mask, pixel_values, and labels for model input', 'process text queries with ColPaliProcessor to generate tokenized input_ids and attention_mask with query augmentation suffix', 'score retrieval by computing late-interaction MaxSim scores between multi-vector query and passage embeddings', 'build ColPaliProcessorKwargs with default text padding, image data format, and common tensor return settings', 'create a ColPaliProcessor instance with an image processor and tokenizer for multimodal document retrieval', 'process images with ColPaliProcessor to generate pixel values, input_ids, and labels for document page encoding', 'process text queries with ColPaliProcessor to generate tokenized query inputs with padding and truncation', 'score retrieval by computing late-interaction MaxSim scores between query embeddings and passage embeddings', 'build a string from input prompt by prepending image tokens and bos_token for multimodal sequence formatting']
```

Usage

```
{'convert_colpali_weights_to_hf': 'convert ColPali model weights from the original repository to HuggingFace format', 'rename_state_dict_keys': 'rename state dict keys from original ColPali format to HuggingFace transformers format', 'load_original_state_dict': 'load original ColPali state dict from safetensors files on the HuggingFace Hub', 'convert_colpali_weights_to_hf_cli': 'run the CLI script to convert ColPali-v1.2-merged model to HuggingFace format and push to hub', 'convert_colpali_weights_to_hf_cli_local': 'run the CLI script to convert ColPali-v1.3-merged model to HuggingFace format and save locally'}
```

## File: huggingface_transformers/src/transformers/models/colpali/modeling_colpali.py

Prompts

```
['convert ColPali model weights from the original repository to HuggingFace format', 'rename state dict keys from original ColPali format to HuggingFace transformers format', 'load original ColPali state dict from safetensors files on the HuggingFace Hub', 'run the CLI script to convert ColPali-v1.2-merged model to HuggingFace format and push to hub', 'run the CLI script to convert ColPali-v1.3-merged model to HuggingFace format and save locally', 'build a ColPaliForRetrieval model that generates multi-vector embeddings from document images for retrieval', 'create multi-vector embeddings from document images and queries using ColPaliForRetrieval forward pass', 'run ColPaliForRetrieval to produce L2-normalized embeddings from pixel values and input_ids for document retrieval', 'review the ColPaliPreTrainedModel base class with weight initialization and attention support flags', 'summarize the ColPaliForRetrievalOutput dataclass containing embeddings, hidden_states, and past_key_values', 'create a ColPaliProcessor instance with custom visual prompt prefix and query prefix for document retrieval', 'process images with ColPaliProcessor to generate input_ids, attention_mask, pixel_values, and labels for model input', 'process text queries with ColPaliProcessor to generate tokenized input_ids and attention_mask with query augmentation suffix', 'score retrieval by computing late-interaction MaxSim scores between multi-vector query and passage embeddings', 'build ColPaliProcessorKwargs with default text padding, image data format, and common tensor return settings', 'create a ColPaliProcessor instance with an image processor and tokenizer for multimodal document retrieval', 'process images with ColPaliProcessor to generate pixel values, input_ids, and labels for document page encoding', 'process text queries with ColPaliProcessor to generate tokenized query inputs with padding and truncation', 'score retrieval by computing late-interaction MaxSim scores between query embeddings and passage embeddings', 'build a string from input prompt by prepending image tokens and bos_token for multimodal sequence formatting']
```

Usage

```
{'build_colpali_for_retrieval': 'build a ColPaliForRetrieval model that generates multi-vector embeddings from document images for retrieval', 'create_colpali_embeddings': 'create multi-vector embeddings from document images and queries using ColPaliForRetrieval forward pass', 'run_colpali_document_retrieval': 'run ColPaliForRetrieval to produce L2-normalized embeddings from pixel values and input_ids for document retrieval', 'review_colpali_pretrained_model': 'review the ColPaliPreTrainedModel base class with weight initialization and attention support flags', 'summarize_colpali_output': 'summarize the ColPaliForRetrievalOutput dataclass containing embeddings, hidden_states, and past_key_values'}
```

## File: huggingface_transformers/src/transformers/models/colpali/modular_colpali.py

Prompts

```
['convert ColPali model weights from the original repository to HuggingFace format', 'rename state dict keys from original ColPali format to HuggingFace transformers format', 'load original ColPali state dict from safetensors files on the HuggingFace Hub', 'run the CLI script to convert ColPali-v1.2-merged model to HuggingFace format and push to hub', 'run the CLI script to convert ColPali-v1.3-merged model to HuggingFace format and save locally', 'build a ColPaliForRetrieval model that generates multi-vector embeddings from document images for retrieval', 'create multi-vector embeddings from document images and queries using ColPaliForRetrieval forward pass', 'run ColPaliForRetrieval to produce L2-normalized embeddings from pixel values and input_ids for document retrieval', 'review the ColPaliPreTrainedModel base class with weight initialization and attention support flags', 'summarize the ColPaliForRetrievalOutput dataclass containing embeddings, hidden_states, and past_key_values', 'create a ColPaliProcessor instance with custom visual prompt prefix and query prefix for document retrieval', 'process images with ColPaliProcessor to generate input_ids, attention_mask, pixel_values, and labels for model input', 'process text queries with ColPaliProcessor to generate tokenized input_ids and attention_mask with query augmentation suffix', 'score retrieval by computing late-interaction MaxSim scores between multi-vector query and passage embeddings', 'build ColPaliProcessorKwargs with default text padding, image data format, and common tensor return settings', 'create a ColPaliProcessor instance with an image processor and tokenizer for multimodal document retrieval', 'process images with ColPaliProcessor to generate pixel values, input_ids, and labels for document page encoding', 'process text queries with ColPaliProcessor to generate tokenized query inputs with padding and truncation', 'score retrieval by computing late-interaction MaxSim scores between query embeddings and passage embeddings', 'build a string from input prompt by prepending image tokens and bos_token for multimodal sequence formatting']
```

Usage

```
{'create_ColPaliProcessor': 'create a ColPaliProcessor instance with custom visual prompt prefix and query prefix for document retrieval', 'process_images_ColPaliProcessor': 'process images with ColPaliProcessor to generate input_ids, attention_mask, pixel_values, and labels for model input', 'process_queries_ColPaliProcessor': 'process text queries with ColPaliProcessor to generate tokenized input_ids and attention_mask with query augmentation suffix', 'score_retrieval_ColPaliProcessor': 'score retrieval by computing late-interaction MaxSim scores between multi-vector query and passage embeddings', 'build_ColPaliProcessorKwargs': 'build ColPaliProcessorKwargs with default text padding, image data format, and common tensor return settings'}
```

## File: huggingface_transformers/src/transformers/models/colpali/processing_colpali.py

Prompts

```
['convert ColPali model weights from the original repository to HuggingFace format', 'rename state dict keys from original ColPali format to HuggingFace transformers format', 'load original ColPali state dict from safetensors files on the HuggingFace Hub', 'run the CLI script to convert ColPali-v1.2-merged model to HuggingFace format and push to hub', 'run the CLI script to convert ColPali-v1.3-merged model to HuggingFace format and save locally', 'build a ColPaliForRetrieval model that generates multi-vector embeddings from document images for retrieval', 'create multi-vector embeddings from document images and queries using ColPaliForRetrieval forward pass', 'run ColPaliForRetrieval to produce L2-normalized embeddings from pixel values and input_ids for document retrieval', 'review the ColPaliPreTrainedModel base class with weight initialization and attention support flags', 'summarize the ColPaliForRetrievalOutput dataclass containing embeddings, hidden_states, and past_key_values', 'create a ColPaliProcessor instance with custom visual prompt prefix and query prefix for document retrieval', 'process images with ColPaliProcessor to generate input_ids, attention_mask, pixel_values, and labels for model input', 'process text queries with ColPaliProcessor to generate tokenized input_ids and attention_mask with query augmentation suffix', 'score retrieval by computing late-interaction MaxSim scores between multi-vector query and passage embeddings', 'build ColPaliProcessorKwargs with default text padding, image data format, and common tensor return settings', 'create a ColPaliProcessor instance with an image processor and tokenizer for multimodal document retrieval', 'process images with ColPaliProcessor to generate pixel values, input_ids, and labels for document page encoding', 'process text queries with ColPaliProcessor to generate tokenized query inputs with padding and truncation', 'score retrieval by computing late-interaction MaxSim scores between query embeddings and passage embeddings', 'build a string from input prompt by prepending image tokens and bos_token for multimodal sequence formatting']
```

Usage

```
{'create_colpali_processor': 'create a ColPaliProcessor instance with an image processor and tokenizer for multimodal document retrieval', 'process_images_colpali': 'process images with ColPaliProcessor to generate pixel values, input_ids, and labels for document page encoding', 'process_queries_colpali': 'process text queries with ColPaliProcessor to generate tokenized query inputs with padding and truncation', 'score_retrieval_colpali': 'score retrieval by computing late-interaction MaxSim scores between query embeddings and passage embeddings', 'build_string_from_input': 'build a string from input prompt by prepending image tokens and bos_token for multimodal sequence formatting'}
```

