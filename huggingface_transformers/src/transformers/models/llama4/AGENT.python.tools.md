# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/llama4/convert_llama4_weights_to_hf.py

Prompts

```
['convert Llama4 model weights from original checkpoint format to Hugging Face format', 'build a Llama4 tokenizer with special tokens, chat template, and ByteLevel post-processor', 'create Llama4 model and text config from params.json with vision and MoE settings', 'test the Llama4 weight conversion by loading the converted model and running a generation', 'summarize the regex-based key mapping from original Llama4 checkpoint keys to Hugging Face keys', 'create a Llama4ImageProcessor instance for preprocessing images with configurable max patches and resize behavior', 'build a tensor of supported resolutions for a given max number of chunks and patch size', 'test the get_best_fit function to select optimal canvas resolution from a list of possible resolutions', 'refactor the pad_to_best_fit function to pad images to a target size with configurable background color', 'summarize the find_supported_resolutions function that computes allowed resolutions for image chunking', 'create a Llama4ForCausalLM model for autoregressive next-token prediction with optional KV cache', 'build a Llama4ForConditionalGeneration model that combines vision encoder with language model for image-text inputs', 'run the Llama4VisionModel to encode images into hidden states using patch embedding and rotary positional encodings', 'test the Llama4TextMoe module with its router, top-k expert selection, and shared expert feed-forward network', 'review the Llama4TextAttention class implementing multi-head attention with RoPE, QK norm, and temperature tuning']
```

Usage

```
{'convert_llama4_weights': 'convert Llama4 model weights from original checkpoint format to Hugging Face format', 'build_llama4_tokenizer': 'build a Llama4 tokenizer with special tokens, chat template, and ByteLevel post-processor', 'create_llama4_model_config': 'create Llama4 model and text config from params.json with vision and MoE settings', 'test_llama4_conversion': 'test the Llama4 weight conversion by loading the converted model and running a generation', 'summarize_key_mapping': 'summarize the regex-based key mapping from original Llama4 checkpoint keys to Hugging Face keys'}
```

## File: huggingface_transformers/src/transformers/models/llama4/image_processing_llama4.py

Prompts

```
['convert Llama4 model weights from original checkpoint format to Hugging Face format', 'build a Llama4 tokenizer with special tokens, chat template, and ByteLevel post-processor', 'create Llama4 model and text config from params.json with vision and MoE settings', 'test the Llama4 weight conversion by loading the converted model and running a generation', 'summarize the regex-based key mapping from original Llama4 checkpoint keys to Hugging Face keys', 'create a Llama4ImageProcessor instance for preprocessing images with configurable max patches and resize behavior', 'build a tensor of supported resolutions for a given max number of chunks and patch size', 'test the get_best_fit function to select optimal canvas resolution from a list of possible resolutions', 'refactor the pad_to_best_fit function to pad images to a target size with configurable background color', 'summarize the find_supported_resolutions function that computes allowed resolutions for image chunking', 'create a Llama4ForCausalLM model for autoregressive next-token prediction with optional KV cache', 'build a Llama4ForConditionalGeneration model that combines vision encoder with language model for image-text inputs', 'run the Llama4VisionModel to encode images into hidden states using patch embedding and rotary positional encodings', 'test the Llama4TextMoe module with its router, top-k expert selection, and shared expert feed-forward network', 'review the Llama4TextAttention class implementing multi-head attention with RoPE, QK norm, and temperature tuning']
```

Usage

```
{'create_image_processor_llama4': 'create a Llama4ImageProcessor instance for preprocessing images with configurable max patches and resize behavior', 'build_image_resolutions': 'build a tensor of supported resolutions for a given max number of chunks and patch size', 'test_get_best_fit': 'test the get_best_fit function to select optimal canvas resolution from a list of possible resolutions', 'refactor_pad_to_best_fit': 'refactor the pad_to_best_fit function to pad images to a target size with configurable background color', 'summarize_find_supported_resolutions': 'summarize the find_supported_resolutions function that computes allowed resolutions for image chunking'}
```

## File: huggingface_transformers/src/transformers/models/llama4/modeling_llama4.py

Prompts

```
['convert Llama4 model weights from original checkpoint format to Hugging Face format', 'build a Llama4 tokenizer with special tokens, chat template, and ByteLevel post-processor', 'create Llama4 model and text config from params.json with vision and MoE settings', 'test the Llama4 weight conversion by loading the converted model and running a generation', 'summarize the regex-based key mapping from original Llama4 checkpoint keys to Hugging Face keys', 'create a Llama4ImageProcessor instance for preprocessing images with configurable max patches and resize behavior', 'build a tensor of supported resolutions for a given max number of chunks and patch size', 'test the get_best_fit function to select optimal canvas resolution from a list of possible resolutions', 'refactor the pad_to_best_fit function to pad images to a target size with configurable background color', 'summarize the find_supported_resolutions function that computes allowed resolutions for image chunking', 'create a Llama4ForCausalLM model for autoregressive next-token prediction with optional KV cache', 'build a Llama4ForConditionalGeneration model that combines vision encoder with language model for image-text inputs', 'run the Llama4VisionModel to encode images into hidden states using patch embedding and rotary positional encodings', 'test the Llama4TextMoe module with its router, top-k expert selection, and shared expert feed-forward network', 'review the Llama4TextAttention class implementing multi-head attention with RoPE, QK norm, and temperature tuning']
```

Usage

```
{'create_llama4_causal_lm': 'create a Llama4ForCausalLM model for autoregressive next-token prediction with optional KV cache', 'build_llama4_multimodal': 'build a Llama4ForConditionalGeneration model that combines vision encoder with language model for image-text inputs', 'run_vision_encoder': 'run the Llama4VisionModel to encode images into hidden states using patch embedding and rotary positional encodings', 'test_moe_experts': 'test the Llama4TextMoe module with its router, top-k expert selection, and shared expert feed-forward network', 'review_attention_forward': 'review the Llama4TextAttention class implementing multi-head attention with RoPE, QK norm, and temperature tuning'}
```

