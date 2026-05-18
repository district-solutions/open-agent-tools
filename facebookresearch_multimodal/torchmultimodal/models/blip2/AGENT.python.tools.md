# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/blip2/blip2.py

Prompts

```
['build a BLIP2 vision-language model with a frozen vision encoder and Q-former for cross-modal alignment', 'run the BLIP2 forward pass with an image tensor to get normalized image embeddings and features', 'run the BLIP2 forward pass with image and text inputs to get prediction scores for next word prediction', 'review the Blip2Output NamedTuple structure containing image embeddings, features, qformer output, text features, and prediction scores', 'refactor the BLIP2 model to toggle freezing of the vision encoder parameters during initialization', 'build a QformerLayer with self-attention and optional cross-attention for query embeddings', 'build a QformerEncoder stacking multiple QformerLayer modules with configurable cross-attention frequency', 'build a QformerEmbedding module combining token, position, and query embeddings with layer norm', 'review the QformerLayer forward method to understand self-attention, cross-attention, and feedforward flow', 'review the QformerEncoder forward method to understand layer iteration and key-value caching', 'build a QformerModel with embedding and encoder layers for multimodal query processing', 'run the QformerModel forward pass with input_ids, attention_mask, and query_embeds tensors', 'create a QformerPredictionHead MLP to compute prediction scores from QformerModel output', 'build a QformerForCLM model wrapper for causal language modeling with a prediction head', 'run the QformerForCLM forward pass to generate next word prediction scores', 'build a causal attention mask tensor for Q-Former generation tasks with padding mask support', 'create a causal mask that allows queries attending each other but not text tokens', 'test the get_causal_mask function with attention_mask tensor and input_shape tuple arguments', 'review the get_causal_mask function for handling prefix sequence length and query-text interaction masking', 'summarize the get_causal_mask function that generates causal attention masks for BLIP-2 Q-Former models']
```

Usage

```
{'build_blip2_model': 'build a BLIP2 vision-language model with a frozen vision encoder and Q-former for cross-modal alignment', 'run_blip2_forward_image_only': 'run the BLIP2 forward pass with an image tensor to get normalized image embeddings and features', 'run_blip2_forward_image_text': 'run the BLIP2 forward pass with image and text inputs to get prediction scores for next word prediction', 'review_blip2output_namedtuple': 'review the Blip2Output NamedTuple structure containing image embeddings, features, qformer output, text features, and prediction scores', 'refactor_blip2_freeze_vision_encoder': 'refactor the BLIP2 model to toggle freezing of the vision encoder parameters during initialization'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/blip2/qformer_layers.py

Prompts

```
['build a BLIP2 vision-language model with a frozen vision encoder and Q-former for cross-modal alignment', 'run the BLIP2 forward pass with an image tensor to get normalized image embeddings and features', 'run the BLIP2 forward pass with image and text inputs to get prediction scores for next word prediction', 'review the Blip2Output NamedTuple structure containing image embeddings, features, qformer output, text features, and prediction scores', 'refactor the BLIP2 model to toggle freezing of the vision encoder parameters during initialization', 'build a QformerLayer with self-attention and optional cross-attention for query embeddings', 'build a QformerEncoder stacking multiple QformerLayer modules with configurable cross-attention frequency', 'build a QformerEmbedding module combining token, position, and query embeddings with layer norm', 'review the QformerLayer forward method to understand self-attention, cross-attention, and feedforward flow', 'review the QformerEncoder forward method to understand layer iteration and key-value caching', 'build a QformerModel with embedding and encoder layers for multimodal query processing', 'run the QformerModel forward pass with input_ids, attention_mask, and query_embeds tensors', 'create a QformerPredictionHead MLP to compute prediction scores from QformerModel output', 'build a QformerForCLM model wrapper for causal language modeling with a prediction head', 'run the QformerForCLM forward pass to generate next word prediction scores', 'build a causal attention mask tensor for Q-Former generation tasks with padding mask support', 'create a causal mask that allows queries attending each other but not text tokens', 'test the get_causal_mask function with attention_mask tensor and input_shape tuple arguments', 'review the get_causal_mask function for handling prefix sequence length and query-text interaction masking', 'summarize the get_causal_mask function that generates causal attention masks for BLIP-2 Q-Former models']
```

Usage

```
{'build_QformerLayer': 'build a QformerLayer with self-attention and optional cross-attention for query embeddings', 'build_QformerEncoder': 'build a QformerEncoder stacking multiple QformerLayer modules with configurable cross-attention frequency', 'build_QformerEmbedding': 'build a QformerEmbedding module combining token, position, and query embeddings with layer norm', 'review_QformerLayer_forward': 'review the QformerLayer forward method to understand self-attention, cross-attention, and feedforward flow', 'review_QformerEncoder_forward': 'review the QformerEncoder forward method to understand layer iteration and key-value caching'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/blip2/qformer_model.py

Prompts

```
['build a BLIP2 vision-language model with a frozen vision encoder and Q-former for cross-modal alignment', 'run the BLIP2 forward pass with an image tensor to get normalized image embeddings and features', 'run the BLIP2 forward pass with image and text inputs to get prediction scores for next word prediction', 'review the Blip2Output NamedTuple structure containing image embeddings, features, qformer output, text features, and prediction scores', 'refactor the BLIP2 model to toggle freezing of the vision encoder parameters during initialization', 'build a QformerLayer with self-attention and optional cross-attention for query embeddings', 'build a QformerEncoder stacking multiple QformerLayer modules with configurable cross-attention frequency', 'build a QformerEmbedding module combining token, position, and query embeddings with layer norm', 'review the QformerLayer forward method to understand self-attention, cross-attention, and feedforward flow', 'review the QformerEncoder forward method to understand layer iteration and key-value caching', 'build a QformerModel with embedding and encoder layers for multimodal query processing', 'run the QformerModel forward pass with input_ids, attention_mask, and query_embeds tensors', 'create a QformerPredictionHead MLP to compute prediction scores from QformerModel output', 'build a QformerForCLM model wrapper for causal language modeling with a prediction head', 'run the QformerForCLM forward pass to generate next word prediction scores', 'build a causal attention mask tensor for Q-Former generation tasks with padding mask support', 'create a causal mask that allows queries attending each other but not text tokens', 'test the get_causal_mask function with attention_mask tensor and input_shape tuple arguments', 'review the get_causal_mask function for handling prefix sequence length and query-text interaction masking', 'summarize the get_causal_mask function that generates causal attention masks for BLIP-2 Q-Former models']
```

Usage

```
{'build_QformerModel': 'build a QformerModel with embedding and encoder layers for multimodal query processing', 'run_QformerModel_forward': 'run the QformerModel forward pass with input_ids, attention_mask, and query_embeds tensors', 'create_QformerPredictionHead': 'create a QformerPredictionHead MLP to compute prediction scores from QformerModel output', 'build_QformerForCLM': 'build a QformerForCLM model wrapper for causal language modeling with a prediction head', 'run_QformerForCLM_forward': 'run the QformerForCLM forward pass to generate next word prediction scores'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/blip2/qformer_utils.py

Prompts

```
['build a BLIP2 vision-language model with a frozen vision encoder and Q-former for cross-modal alignment', 'run the BLIP2 forward pass with an image tensor to get normalized image embeddings and features', 'run the BLIP2 forward pass with image and text inputs to get prediction scores for next word prediction', 'review the Blip2Output NamedTuple structure containing image embeddings, features, qformer output, text features, and prediction scores', 'refactor the BLIP2 model to toggle freezing of the vision encoder parameters during initialization', 'build a QformerLayer with self-attention and optional cross-attention for query embeddings', 'build a QformerEncoder stacking multiple QformerLayer modules with configurable cross-attention frequency', 'build a QformerEmbedding module combining token, position, and query embeddings with layer norm', 'review the QformerLayer forward method to understand self-attention, cross-attention, and feedforward flow', 'review the QformerEncoder forward method to understand layer iteration and key-value caching', 'build a QformerModel with embedding and encoder layers for multimodal query processing', 'run the QformerModel forward pass with input_ids, attention_mask, and query_embeds tensors', 'create a QformerPredictionHead MLP to compute prediction scores from QformerModel output', 'build a QformerForCLM model wrapper for causal language modeling with a prediction head', 'run the QformerForCLM forward pass to generate next word prediction scores', 'build a causal attention mask tensor for Q-Former generation tasks with padding mask support', 'create a causal mask that allows queries attending each other but not text tokens', 'test the get_causal_mask function with attention_mask tensor and input_shape tuple arguments', 'review the get_causal_mask function for handling prefix sequence length and query-text interaction masking', 'summarize the get_causal_mask function that generates causal attention masks for BLIP-2 Q-Former models']
```

Usage

```
{'build_causal_mask_for_qformer': 'build a causal attention mask tensor for Q-Former generation tasks with padding mask support', 'create_causal_mask_with_query': 'create a causal mask that allows queries attending each other but not text tokens', 'test_get_causal_mask': 'test the get_causal_mask function with attention_mask tensor and input_shape tuple arguments', 'review_get_causal_mask': 'review the get_causal_mask function for handling prefix sequence length and query-text interaction masking', 'summarize_get_causal_mask': 'summarize the get_causal_mask function that generates causal attention masks for BLIP-2 Q-Former models'}
```

