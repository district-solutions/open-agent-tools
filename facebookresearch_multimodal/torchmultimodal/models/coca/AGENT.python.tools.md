# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/coca/coca_model.py

Prompts

```
['build a CoCa model using coca_vit with custom vision, text, and fusion transformer hyperparameters', 'create a CoCa ViT-B/32 pretrained model configuration with 12-layer vision encoder and 512-dim text decoder', 'create a CoCa ViT-L/14 pretrained model configuration with 24-layer vision encoder and 768-dim text decoder', 'run CoCa pretraining with contrastive and captioning losses using coca_for_pretraining factory function', 'build a CoCa model with downstream task heads using CoCaModelWithHeads and a custom pooler function', 'build a CoCaMultimodalDecoder with transformer layers, cross-attention, and causal masking for text-image generation', 'create a CoCaMultimodalDecoder with an output projection layer to map hidden states to a custom output dimension', 'run a forward pass through CoCaMultimodalDecoder with text and image embedding tensors to get output embeddings', 'review how CoCaMultimodalDecoder registers a causal attention mask buffer for autoregressive text decoding', 'refactor CoCaMultimodalDecoder to configure cross-attention between text embeddings and image embeddings via the transformer decoder', 'create a CoCaTextDecoder with vocab size, embedding dim, and transformer layer count', 'create a CoCaTextEmbeddings module with token, positional, and optional CLS embeddings', 'run the CoCaTextDecoder forward pass on input token IDs to get pooled and token outputs', 'run the CoCaTextEmbeddings forward pass on input token IDs to get embedded tensors', 'review the CoCaTextDecoder build_mask method that constructs causal attention masks with padding']
```

Usage

```
{'build_coca_vit_model': 'build a CoCa model using coca_vit with custom vision, text, and fusion transformer hyperparameters', 'create_coca_vit_b_32': 'create a CoCa ViT-B/32 pretrained model configuration with 12-layer vision encoder and 512-dim text decoder', 'create_coca_vit_l_14': 'create a CoCa ViT-L/14 pretrained model configuration with 24-layer vision encoder and 768-dim text decoder', 'run_coca_for_pretraining': 'run CoCa pretraining with contrastive and captioning losses using coca_for_pretraining factory function', 'build_coca_model_with_heads': 'build a CoCa model with downstream task heads using CoCaModelWithHeads and a custom pooler function'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/coca/multimodal_decoder.py

Prompts

```
['build a CoCa model using coca_vit with custom vision, text, and fusion transformer hyperparameters', 'create a CoCa ViT-B/32 pretrained model configuration with 12-layer vision encoder and 512-dim text decoder', 'create a CoCa ViT-L/14 pretrained model configuration with 24-layer vision encoder and 768-dim text decoder', 'run CoCa pretraining with contrastive and captioning losses using coca_for_pretraining factory function', 'build a CoCa model with downstream task heads using CoCaModelWithHeads and a custom pooler function', 'build a CoCaMultimodalDecoder with transformer layers, cross-attention, and causal masking for text-image generation', 'create a CoCaMultimodalDecoder with an output projection layer to map hidden states to a custom output dimension', 'run a forward pass through CoCaMultimodalDecoder with text and image embedding tensors to get output embeddings', 'review how CoCaMultimodalDecoder registers a causal attention mask buffer for autoregressive text decoding', 'refactor CoCaMultimodalDecoder to configure cross-attention between text embeddings and image embeddings via the transformer decoder', 'create a CoCaTextDecoder with vocab size, embedding dim, and transformer layer count', 'create a CoCaTextEmbeddings module with token, positional, and optional CLS embeddings', 'run the CoCaTextDecoder forward pass on input token IDs to get pooled and token outputs', 'run the CoCaTextEmbeddings forward pass on input token IDs to get embedded tensors', 'review the CoCaTextDecoder build_mask method that constructs causal attention masks with padding']
```

Usage

```
{'build_coca_multimodal_decoder': 'build a CoCaMultimodalDecoder with transformer layers, cross-attention, and causal masking for text-image generation', 'create_decoder_with_output_projection': 'create a CoCaMultimodalDecoder with an output projection layer to map hidden states to a custom output dimension', 'run_forward_pass': 'run a forward pass through CoCaMultimodalDecoder with text and image embedding tensors to get output embeddings', 'review_causal_mask_registration': 'review how CoCaMultimodalDecoder registers a causal attention mask buffer for autoregressive text decoding', 'refactor_cross_attention_config': 'refactor CoCaMultimodalDecoder to configure cross-attention between text embeddings and image embeddings via the transformer decoder'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/coca/text_decoder.py

Prompts

```
['build a CoCa model using coca_vit with custom vision, text, and fusion transformer hyperparameters', 'create a CoCa ViT-B/32 pretrained model configuration with 12-layer vision encoder and 512-dim text decoder', 'create a CoCa ViT-L/14 pretrained model configuration with 24-layer vision encoder and 768-dim text decoder', 'run CoCa pretraining with contrastive and captioning losses using coca_for_pretraining factory function', 'build a CoCa model with downstream task heads using CoCaModelWithHeads and a custom pooler function', 'build a CoCaMultimodalDecoder with transformer layers, cross-attention, and causal masking for text-image generation', 'create a CoCaMultimodalDecoder with an output projection layer to map hidden states to a custom output dimension', 'run a forward pass through CoCaMultimodalDecoder with text and image embedding tensors to get output embeddings', 'review how CoCaMultimodalDecoder registers a causal attention mask buffer for autoregressive text decoding', 'refactor CoCaMultimodalDecoder to configure cross-attention between text embeddings and image embeddings via the transformer decoder', 'create a CoCaTextDecoder with vocab size, embedding dim, and transformer layer count', 'create a CoCaTextEmbeddings module with token, positional, and optional CLS embeddings', 'run the CoCaTextDecoder forward pass on input token IDs to get pooled and token outputs', 'run the CoCaTextEmbeddings forward pass on input token IDs to get embedded tensors', 'review the CoCaTextDecoder build_mask method that constructs causal attention masks with padding']
```

Usage

```
{'create_CoCaTextDecoder': 'create a CoCaTextDecoder with vocab size, embedding dim, and transformer layer count', 'create_CoCaTextEmbeddings': 'create a CoCaTextEmbeddings module with token, positional, and optional CLS embeddings', 'run_CoCaTextDecoder_forward': 'run the CoCaTextDecoder forward pass on input token IDs to get pooled and token outputs', 'run_CoCaTextEmbeddings_forward': 'run the CoCaTextEmbeddings forward pass on input token IDs to get embedded tensors', 'review_CoCaTextDecoder_build_mask': 'review the CoCaTextDecoder build_mask method that constructs causal attention masks with padding'}
```

