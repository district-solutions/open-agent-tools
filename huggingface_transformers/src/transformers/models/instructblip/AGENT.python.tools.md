# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/instructblip/convert_instructblip_original_to_pytorch.py

Prompts

```
['convert an InstructBLIP checkpoint from the original Salesforce LAVIS repository to a HuggingFace PyTorch model', 'create a list of key rename mappings from Salesforce LAVIS state dict keys to HuggingFace InstructBLIP state dict keys', 'build an InstructBlipConfig with vision, text, and QFormer configs for a given model name', 'read separate q and v biases from the original state dict and concatenate them into a single qkv bias tensor', 'run the conversion script via argparse CLI to convert an InstructBLIP model and optionally push to the HuggingFace hub', 'generate text captions from images using InstructBlipForConditionalGeneration with pixel values and prompts', 'create an InstructBlipModel combining vision encoder, Q-Former, and language model for multimodal understanding', 'run a forward pass through InstructBlipForConditionalGeneration to compute loss and logits for training', 'extract image features from pixel values through vision encoder and Q-Former via get_image_features method', 'build an InstructBlipVisionModel with embeddings, transformer encoder layers, and layer normalization for image encoding', 'create an InstructBlipProcessor with image_processor, tokenizer, qformer_tokenizer and optional num_query_tokens', 'call InstructBlipProcessor with images and text to produce batched encoding with qformer input ids and attention masks', 'call InstructBlipProcessor with text only to produce qformer encoding without image tokens', 'call InstructBlipProcessor with images only to produce image encoding without text tokens', 'get the combined model_input_names property listing tokenizer, image_processor and qformer input names']
```

Usage

```
{'convert_instructblip_checkpoint': 'convert an InstructBLIP checkpoint from the original Salesforce LAVIS repository to a HuggingFace PyTorch model', 'create_rename_keys': 'create a list of key rename mappings from Salesforce LAVIS state dict keys to HuggingFace InstructBLIP state dict keys', 'get_blip2_config': 'build an InstructBlipConfig with vision, text, and QFormer configs for a given model name', 'read_in_q_v_bias': 'read separate q and v biases from the original state dict and concatenate them into a single qkv bias tensor', 'run_conversion_cli': 'run the conversion script via argparse CLI to convert an InstructBLIP model and optionally push to the HuggingFace hub'}
```

## File: huggingface_transformers/src/transformers/models/instructblip/modeling_instructblip.py

Prompts

```
['convert an InstructBLIP checkpoint from the original Salesforce LAVIS repository to a HuggingFace PyTorch model', 'create a list of key rename mappings from Salesforce LAVIS state dict keys to HuggingFace InstructBLIP state dict keys', 'build an InstructBlipConfig with vision, text, and QFormer configs for a given model name', 'read separate q and v biases from the original state dict and concatenate them into a single qkv bias tensor', 'run the conversion script via argparse CLI to convert an InstructBLIP model and optionally push to the HuggingFace hub', 'generate text captions from images using InstructBlipForConditionalGeneration with pixel values and prompts', 'create an InstructBlipModel combining vision encoder, Q-Former, and language model for multimodal understanding', 'run a forward pass through InstructBlipForConditionalGeneration to compute loss and logits for training', 'extract image features from pixel values through vision encoder and Q-Former via get_image_features method', 'build an InstructBlipVisionModel with embeddings, transformer encoder layers, and layer normalization for image encoding', 'create an InstructBlipProcessor with image_processor, tokenizer, qformer_tokenizer and optional num_query_tokens', 'call InstructBlipProcessor with images and text to produce batched encoding with qformer input ids and attention masks', 'call InstructBlipProcessor with text only to produce qformer encoding without image tokens', 'call InstructBlipProcessor with images only to produce image encoding without text tokens', 'get the combined model_input_names property listing tokenizer, image_processor and qformer input names']
```

Usage

```
{'generate_image_caption': 'generate text captions from images using InstructBlipForConditionalGeneration with pixel values and prompts', 'create_multimodal_model': 'create an InstructBlipModel combining vision encoder, Q-Former, and language model for multimodal understanding', 'run_forward_pass': 'run a forward pass through InstructBlipForConditionalGeneration to compute loss and logits for training', 'get_image_features': 'extract image features from pixel values through vision encoder and Q-Former via get_image_features method', 'build_vision_encoder': 'build an InstructBlipVisionModel with embeddings, transformer encoder layers, and layer normalization for image encoding'}
```

## File: huggingface_transformers/src/transformers/models/instructblip/processing_instructblip.py

Prompts

```
['convert an InstructBLIP checkpoint from the original Salesforce LAVIS repository to a HuggingFace PyTorch model', 'create a list of key rename mappings from Salesforce LAVIS state dict keys to HuggingFace InstructBLIP state dict keys', 'build an InstructBlipConfig with vision, text, and QFormer configs for a given model name', 'read separate q and v biases from the original state dict and concatenate them into a single qkv bias tensor', 'run the conversion script via argparse CLI to convert an InstructBLIP model and optionally push to the HuggingFace hub', 'generate text captions from images using InstructBlipForConditionalGeneration with pixel values and prompts', 'create an InstructBlipModel combining vision encoder, Q-Former, and language model for multimodal understanding', 'run a forward pass through InstructBlipForConditionalGeneration to compute loss and logits for training', 'extract image features from pixel values through vision encoder and Q-Former via get_image_features method', 'build an InstructBlipVisionModel with embeddings, transformer encoder layers, and layer normalization for image encoding', 'create an InstructBlipProcessor with image_processor, tokenizer, qformer_tokenizer and optional num_query_tokens', 'call InstructBlipProcessor with images and text to produce batched encoding with qformer input ids and attention masks', 'call InstructBlipProcessor with text only to produce qformer encoding without image tokens', 'call InstructBlipProcessor with images only to produce image encoding without text tokens', 'get the combined model_input_names property listing tokenizer, image_processor and qformer input names']
```

Usage

```
{'create_instructblip_processor': 'create an InstructBlipProcessor with image_processor, tokenizer, qformer_tokenizer and optional num_query_tokens', 'call_processor_with_text_and_images': 'call InstructBlipProcessor with images and text to produce batched encoding with qformer input ids and attention masks', 'call_processor_with_text_only': 'call InstructBlipProcessor with text only to produce qformer encoding without image tokens', 'call_processor_with_images_only': 'call InstructBlipProcessor with images only to produce image encoding without text tokens', 'get_model_input_names': 'get the combined model_input_names property listing tokenizer, image_processor and qformer input names'}
```

