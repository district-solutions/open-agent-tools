# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/fast_vlm/configuration_fast_vlm.py

Prompts

```
['create a FastVlmConfig instance with default FastVLM-7B style configuration for conditional generation', 'initialize vision and text sub-configs from dictionaries or use defaults for fast_vlm model architecture', "validate fast_vlm config architecture ensuring vision_feature_select_strategy is 'full' and vision_feature_layer is -1", 'build a FastVlmForConditionalGeneration model from a FastVlmConfig instance for multimodal image-text generation', 'configure fast_vlm projector settings including hidden act, image token index, image seq length, and multimodal projector bias', "convert FastVLM model weights from Apple's format to Hugging Face format and push to hub", 'run the FastVLM weight conversion CLI with custom text model, vision model, and output paths', 'load original FastVLM state dict from Hugging Face Hub safetensors files', 'convert FastVLM state dict keys from original naming to Hugging Face naming convention', 'build FastVLM config combining text and vision models with image token and processor settings', 'create a FastVlmForConditionalGeneration model from a config for vision-language conditional generation', 'build image features from pixel values using the vision tower and multimodal projector', 'run a forward pass through the FastVlmModel with input ids, pixel values, and attention mask', 'generate text from the FastVlmForConditionalGeneration model given image and text inputs', 'prepare inputs for generation with pixel values, past key values, and attention mask', 'build a FastVlmModel with a vision tower and language model for multimodal processing', 'generate text from image and text inputs using FastVlmForConditionalGeneration', 'get image features from pixel values through the vision tower and multimodal projector']
```

Usage

```
{'create_fastvlm_config': 'create a FastVlmConfig instance with default FastVLM-7B style configuration for conditional generation', 'initialize_vision_text_configs': 'initialize vision and text sub-configs from dictionaries or use defaults for fast_vlm model architecture', 'validate_fastvlm_architecture': "validate fast_vlm config architecture ensuring vision_feature_select_strategy is 'full' and vision_feature_layer is -1", 'build_fastvlm_model_from_config': 'build a FastVlmForConditionalGeneration model from a FastVlmConfig instance for multimodal image-text generation', 'configure_fastvlm_projector_settings': 'configure fast_vlm projector settings including hidden act, image token index, image seq length, and multimodal projector bias'}
```

## File: huggingface_transformers/src/transformers/models/fast_vlm/convert_fastvlm_weights_to_hf.py

Prompts

```
['create a FastVlmConfig instance with default FastVLM-7B style configuration for conditional generation', 'initialize vision and text sub-configs from dictionaries or use defaults for fast_vlm model architecture', "validate fast_vlm config architecture ensuring vision_feature_select_strategy is 'full' and vision_feature_layer is -1", 'build a FastVlmForConditionalGeneration model from a FastVlmConfig instance for multimodal image-text generation', 'configure fast_vlm projector settings including hidden act, image token index, image seq length, and multimodal projector bias', "convert FastVLM model weights from Apple's format to Hugging Face format and push to hub", 'run the FastVLM weight conversion CLI with custom text model, vision model, and output paths', 'load original FastVLM state dict from Hugging Face Hub safetensors files', 'convert FastVLM state dict keys from original naming to Hugging Face naming convention', 'build FastVLM config combining text and vision models with image token and processor settings', 'create a FastVlmForConditionalGeneration model from a config for vision-language conditional generation', 'build image features from pixel values using the vision tower and multimodal projector', 'run a forward pass through the FastVlmModel with input ids, pixel values, and attention mask', 'generate text from the FastVlmForConditionalGeneration model given image and text inputs', 'prepare inputs for generation with pixel values, past key values, and attention mask', 'build a FastVlmModel with a vision tower and language model for multimodal processing', 'generate text from image and text inputs using FastVlmForConditionalGeneration', 'get image features from pixel values through the vision tower and multimodal projector']
```

Usage

```
{'convert_fastvlm_weights_to_hf': "convert FastVLM model weights from Apple's format to Hugging Face format and push to hub", 'run_convert_fastvlm_cli': 'run the FastVLM weight conversion CLI with custom text model, vision model, and output paths', 'load_original_state_dict': 'load original FastVLM state dict from Hugging Face Hub safetensors files', 'convert_state_dict_to_hf': 'convert FastVLM state dict keys from original naming to Hugging Face naming convention', 'build_fastvlm_config': 'build FastVLM config combining text and vision models with image token and processor settings'}
```

## File: huggingface_transformers/src/transformers/models/fast_vlm/modeling_fast_vlm.py

Prompts

```
['create a FastVlmConfig instance with default FastVLM-7B style configuration for conditional generation', 'initialize vision and text sub-configs from dictionaries or use defaults for fast_vlm model architecture', "validate fast_vlm config architecture ensuring vision_feature_select_strategy is 'full' and vision_feature_layer is -1", 'build a FastVlmForConditionalGeneration model from a FastVlmConfig instance for multimodal image-text generation', 'configure fast_vlm projector settings including hidden act, image token index, image seq length, and multimodal projector bias', "convert FastVLM model weights from Apple's format to Hugging Face format and push to hub", 'run the FastVLM weight conversion CLI with custom text model, vision model, and output paths', 'load original FastVLM state dict from Hugging Face Hub safetensors files', 'convert FastVLM state dict keys from original naming to Hugging Face naming convention', 'build FastVLM config combining text and vision models with image token and processor settings', 'create a FastVlmForConditionalGeneration model from a config for vision-language conditional generation', 'build image features from pixel values using the vision tower and multimodal projector', 'run a forward pass through the FastVlmModel with input ids, pixel values, and attention mask', 'generate text from the FastVlmForConditionalGeneration model given image and text inputs', 'prepare inputs for generation with pixel values, past key values, and attention mask', 'build a FastVlmModel with a vision tower and language model for multimodal processing', 'generate text from image and text inputs using FastVlmForConditionalGeneration', 'get image features from pixel values through the vision tower and multimodal projector']
```

Usage

```
{'create_fastvlm_model': 'create a FastVlmForConditionalGeneration model from a config for vision-language conditional generation', 'build_image_features': 'build image features from pixel values using the vision tower and multimodal projector', 'run_forward_pass': 'run a forward pass through the FastVlmModel with input ids, pixel values, and attention mask', 'generate_text': 'generate text from the FastVlmForConditionalGeneration model given image and text inputs', 'prepare_generation_inputs': 'prepare inputs for generation with pixel values, past key values, and attention mask'}
```

## File: huggingface_transformers/src/transformers/models/fast_vlm/modular_fast_vlm.py

Prompts

```
['create a FastVlmConfig instance with default FastVLM-7B style configuration for conditional generation', 'initialize vision and text sub-configs from dictionaries or use defaults for fast_vlm model architecture', "validate fast_vlm config architecture ensuring vision_feature_select_strategy is 'full' and vision_feature_layer is -1", 'build a FastVlmForConditionalGeneration model from a FastVlmConfig instance for multimodal image-text generation', 'configure fast_vlm projector settings including hidden act, image token index, image seq length, and multimodal projector bias', "convert FastVLM model weights from Apple's format to Hugging Face format and push to hub", 'run the FastVLM weight conversion CLI with custom text model, vision model, and output paths', 'load original FastVLM state dict from Hugging Face Hub safetensors files', 'convert FastVLM state dict keys from original naming to Hugging Face naming convention', 'build FastVLM config combining text and vision models with image token and processor settings', 'create a FastVlmForConditionalGeneration model from a config for vision-language conditional generation', 'build image features from pixel values using the vision tower and multimodal projector', 'run a forward pass through the FastVlmModel with input ids, pixel values, and attention mask', 'generate text from the FastVlmForConditionalGeneration model given image and text inputs', 'prepare inputs for generation with pixel values, past key values, and attention mask', 'build a FastVlmModel with a vision tower and language model for multimodal processing', 'generate text from image and text inputs using FastVlmForConditionalGeneration', 'get image features from pixel values through the vision tower and multimodal projector']
```

Usage

```
{'create_fastvlm_config': 'create a FastVlmConfig instance with vision and text backbone configurations for a FastVLM model', 'build_fastvlm_model': 'build a FastVlmModel with a vision tower and language model for multimodal processing', 'generate_fastvlm_output': 'generate text from image and text inputs using FastVlmForConditionalGeneration', 'get_image_features': 'get image features from pixel values through the vision tower and multimodal projector', 'validate_fastvlm_architecture': 'validate that a FastVlmConfig uses only supported vision feature strategies and layers'}
```

