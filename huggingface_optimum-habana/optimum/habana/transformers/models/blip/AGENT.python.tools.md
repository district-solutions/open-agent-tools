# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/blip/modeling_blip.py

Prompts

```
['generate image captions using BlipForConditionalGeneration with Habana Gaudi HPU graph acceleration', 'generate visual question answering responses using BlipForQuestionAnswering with Habana Gaudi HPU graph acceleration', 'wrap the BLIP vision model in an HPU graph for optimized inference on Habana accelerators', 'wrap the BLIP text decoder in an HPU graph for optimized text generation on Habana accelerators', 'wrap the BLIP text encoder in an HPU graph for optimized question encoding on Habana accelerators', 'run the gaudi BlipTextSelfAttention forward pass with token_idx support for Habana Gaudi acceleration', 'run the gaudi BlipTextLayer forward pass with self-attention, cross-attention, and feed-forward chunking', 'run the gaudi BlipTextEncoder forward pass through all hidden layers with optional gradient checkpointing', 'run the gaudi BlipTextModel forward pass to get sequence and pooled outputs with cross-attention support', 'run the gaudi BlipTextLMHeadModel forward pass for next-token prediction with cross-entropy loss']
```

Usage

```
{'generate_blip_caption_hpu': 'generate image captions using BlipForConditionalGeneration with Habana Gaudi HPU graph acceleration', 'generate_blip_vqa_hpu': 'generate visual question answering responses using BlipForQuestionAnswering with Habana Gaudi HPU graph acceleration', 'wrap_blip_vision_model_hpu_graph': 'wrap the BLIP vision model in an HPU graph for optimized inference on Habana accelerators', 'wrap_blip_text_decoder_hpu_graph': 'wrap the BLIP text decoder in an HPU graph for optimized text generation on Habana accelerators', 'wrap_blip_text_encoder_hpu_graph': 'wrap the BLIP text encoder in an HPU graph for optimized question encoding on Habana accelerators'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/models/blip/modeling_blip_text.py

Prompts

```
['generate image captions using BlipForConditionalGeneration with Habana Gaudi HPU graph acceleration', 'generate visual question answering responses using BlipForQuestionAnswering with Habana Gaudi HPU graph acceleration', 'wrap the BLIP vision model in an HPU graph for optimized inference on Habana accelerators', 'wrap the BLIP text decoder in an HPU graph for optimized text generation on Habana accelerators', 'wrap the BLIP text encoder in an HPU graph for optimized question encoding on Habana accelerators', 'run the gaudi BlipTextSelfAttention forward pass with token_idx support for Habana Gaudi acceleration', 'run the gaudi BlipTextLayer forward pass with self-attention, cross-attention, and feed-forward chunking', 'run the gaudi BlipTextEncoder forward pass through all hidden layers with optional gradient checkpointing', 'run the gaudi BlipTextModel forward pass to get sequence and pooled outputs with cross-attention support', 'run the gaudi BlipTextLMHeadModel forward pass for next-token prediction with cross-entropy loss']
```

Usage

```
{'run_blip_text_self_attention': 'run the gaudi BlipTextSelfAttention forward pass with token_idx support for Habana Gaudi acceleration', 'run_blip_text_layer_forward': 'run the gaudi BlipTextLayer forward pass with self-attention, cross-attention, and feed-forward chunking', 'run_blip_text_encoder_forward': 'run the gaudi BlipTextEncoder forward pass through all hidden layers with optional gradient checkpointing', 'run_blip_text_model_forward': 'run the gaudi BlipTextModel forward pass to get sequence and pooled outputs with cross-attention support', 'run_blip_text_lm_head_forward': 'run the gaudi BlipTextLMHeadModel forward pass for next-token prediction with cross-entropy loss'}
```

