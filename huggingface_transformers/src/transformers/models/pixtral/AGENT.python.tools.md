# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pixtral/convert_pixtral_weights_to_hf.py

Prompts

```
['convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'apply rotary position embedding permutation to query and key projection weights', 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate the number of image tokens given an image size and patch size', 'pad a list of processed images to a uniform shape for batching', 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend', 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings']
```

Usage

```
{'convert_pixtral_weights_to_hf': 'convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert_mistral_tokenizer': 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert_mistral_model': 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'convert_dictionary': 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'permute_for_rope': 'apply rotary position embedding permutation to query and key projection weights'}
```

## File: huggingface_transformers/src/transformers/models/pixtral/image_processing_pil_pixtral.py

Prompts

```
['convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'apply rotary position embedding permutation to query and key projection weights', 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate the number of image tokens given an image size and patch size', 'pad a list of processed images to a uniform shape for batching', 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend', 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings']
```

Usage

```
{'create_PixtralImageProcessorPil': 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run_PixtralImageProcessorPil_preprocess': 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build_resize_output_image_size': 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate_num_image_tokens': 'calculate the number of image tokens given an image size and patch size', 'pad_images_for_batching': 'pad a list of processed images to a uniform shape for batching'}
```

## File: huggingface_transformers/src/transformers/models/pixtral/image_processing_pixtral.py

Prompts

```
['convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'apply rotary position embedding permutation to query and key projection weights', 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate the number of image tokens given an image size and patch size', 'pad a list of processed images to a uniform shape for batching', 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend', 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings']
```

Usage

```
{'create_PixtralImageProcessor': 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run_PixtralImageProcessor_preprocess': 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build_resize_output_image_size': 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate_num_image_tokens': 'calculate the number of image tokens given an image size and patch size', 'pad_images_for_batching': 'pad a list of processed images to a uniform shape for batching'}
```

## File: huggingface_transformers/src/transformers/models/pixtral/modeling_pixtral.py

Prompts

```
['convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'apply rotary position embedding permutation to query and key projection weights', 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate the number of image tokens given an image size and patch size', 'pad a list of processed images to a uniform shape for batching', 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend', 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings']
```

Usage

```
{'build_pixtral_vision_model': 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create_pixtral_rotary_embedding': 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply_rotary_position_embedding': 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate_block_attention_mask': 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run_pixtral_attention': 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend'}
```

## File: huggingface_transformers/src/transformers/models/pixtral/processing_pixtral.py

Prompts

```
['convert Pixtral model weights from Mistral format to HuggingFace Transformers format', 'convert a Mistral tokenizer file to a HuggingFace LlamaTokenizer with proper special tokens', 'convert a Mistral Pixtral model checkpoint directory to a HuggingFace LlavaForConditionalGeneration model', 'map old Mistral-style state dict keys to new HuggingFace key names and apply RoPE permutation', 'apply rotary position embedding permutation to query and key projection weights', 'create a PixtralImageProcessorPil instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessorPil preprocess method to resize, normalize, and batch PIL images', 'build the target image dimensions after resizing to longest_edge while aligning to patch_size', 'calculate the number of image tokens given an image size and patch size', 'pad a list of processed images to a uniform shape for batching', 'create a PixtralImageProcessor instance with custom patch_size and normalization parameters', 'run the PixtralImageProcessor preprocess method to resize, normalize, and batch input images', 'build a PixtralVisionModel that processes pixel values through a convolutional patch encoder and transformer', 'create a PixtralRotaryEmbedding module that generates rotary position embeddings for each pixel position grid', 'apply rotary position embedding to query and key tensors using cos and sin position embeddings', 'generate a block causal attention mask for patch embeddings with per-image sequence boundaries', 'run PixtralAttention multi-headed attention with rotary embeddings and configurable attention backend', 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings']
```

Usage

```
{'create_pixtral_processor': 'create a PixtralProcessor instance with image_processor, tokenizer, and special image tokens for multimodal input', 'call_pixtral_processor': 'call PixtralProcessor with images and text to produce batched input_ids, attention_mask, and pixel_values', 'get_num_multimodal_tokens': 'get the number of multimodal tokens for images with given sizes using patch_size and spatial_merge_size', 'check_model_input_names': 'get the combined model input names from tokenizer, image_processor, and image_sizes', 'configure_pixtral_processor_kwargs': 'configure PixtralProcessorKwargs with padding, return_mm_token_type_ids, and return_tensors settings'}
```

