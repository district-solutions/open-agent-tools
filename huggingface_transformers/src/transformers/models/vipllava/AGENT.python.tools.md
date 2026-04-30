# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vipllava/convert_vipllava_weights_to_hf.py

Prompts

```
['convert ViPLLaVA model weights from the original format to HuggingFace Transformers format', 'run the CLI tool to convert ViPLLaVA weights with text model, vision model, output path, and state dict arguments', 'convert a state dict by remapping keys to match HuggingFace model naming conventions', 'resize token embeddings and initialize new token weights using multivariate normal sampling', 'build a LlavaProcessor with a modified tokenizer that includes an image token and pad token', 'build a VipLlavaModel with a config for vision-language multimodal inference', 'create a VipLlavaForConditionalGeneration model for vision-language next-token prediction', 'test the get_image_features method to extract projected image hidden states from a vision tower', 'run the forward method on VipLlavaForConditionalGeneration to compute logits and loss for training', 'review the prepare_inputs_for_generation method to handle pixel values across generation iterations', 'create a VipLlavaMultiModalProjector module to project vision features into text embedding space', 'build a VipLlavaModel that obtains image hidden states from the vision tower and applies multimodal projection', 'run VipLlavaModel forward to merge image features with text embeddings and generate language model outputs', 'generate text from images using VipLlavaForConditionalGeneration forward pass with labels and logits', 'extract image features from pixel values using VipLlavaForConditionalGeneration get_image_features method']
```

Usage

```
{'convert_vipllava_weights_to_hf': 'convert ViPLLaVA model weights from the original format to HuggingFace Transformers format', 'run_convert_cli': 'run the CLI tool to convert ViPLLaVA weights with text model, vision model, output path, and state dict arguments', 'convert_state_dict_to_hf': 'convert a state dict by remapping keys to match HuggingFace model naming conventions', 'resize_token_embeddings_with_sampling': 'resize token embeddings and initialize new token weights using multivariate normal sampling', 'build_vipllava_processor': 'build a LlavaProcessor with a modified tokenizer that includes an image token and pad token'}
```

## File: huggingface_transformers/src/transformers/models/vipllava/modeling_vipllava.py

Prompts

```
['convert ViPLLaVA model weights from the original format to HuggingFace Transformers format', 'run the CLI tool to convert ViPLLaVA weights with text model, vision model, output path, and state dict arguments', 'convert a state dict by remapping keys to match HuggingFace model naming conventions', 'resize token embeddings and initialize new token weights using multivariate normal sampling', 'build a LlavaProcessor with a modified tokenizer that includes an image token and pad token', 'build a VipLlavaModel with a config for vision-language multimodal inference', 'create a VipLlavaForConditionalGeneration model for vision-language next-token prediction', 'test the get_image_features method to extract projected image hidden states from a vision tower', 'run the forward method on VipLlavaForConditionalGeneration to compute logits and loss for training', 'review the prepare_inputs_for_generation method to handle pixel values across generation iterations', 'create a VipLlavaMultiModalProjector module to project vision features into text embedding space', 'build a VipLlavaModel that obtains image hidden states from the vision tower and applies multimodal projection', 'run VipLlavaModel forward to merge image features with text embeddings and generate language model outputs', 'generate text from images using VipLlavaForConditionalGeneration forward pass with labels and logits', 'extract image features from pixel values using VipLlavaForConditionalGeneration get_image_features method']
```

Usage

```
{'build_vipllava_model': 'build a VipLlavaModel with a config for vision-language multimodal inference', 'create_vipllava_conditional_generation': 'create a VipLlavaForConditionalGeneration model for vision-language next-token prediction', 'test_get_image_features': 'test the get_image_features method to extract projected image hidden states from a vision tower', 'run_forward_generation': 'run the forward method on VipLlavaForConditionalGeneration to compute logits and loss for training', 'review_prepare_inputs_generation': 'review the prepare_inputs_for_generation method to handle pixel values across generation iterations'}
```

## File: huggingface_transformers/src/transformers/models/vipllava/modular_vipllava.py

Prompts

```
['convert ViPLLaVA model weights from the original format to HuggingFace Transformers format', 'run the CLI tool to convert ViPLLaVA weights with text model, vision model, output path, and state dict arguments', 'convert a state dict by remapping keys to match HuggingFace model naming conventions', 'resize token embeddings and initialize new token weights using multivariate normal sampling', 'build a LlavaProcessor with a modified tokenizer that includes an image token and pad token', 'build a VipLlavaModel with a config for vision-language multimodal inference', 'create a VipLlavaForConditionalGeneration model for vision-language next-token prediction', 'test the get_image_features method to extract projected image hidden states from a vision tower', 'run the forward method on VipLlavaForConditionalGeneration to compute logits and loss for training', 'review the prepare_inputs_for_generation method to handle pixel values across generation iterations', 'create a VipLlavaMultiModalProjector module to project vision features into text embedding space', 'build a VipLlavaModel that obtains image hidden states from the vision tower and applies multimodal projection', 'run VipLlavaModel forward to merge image features with text embeddings and generate language model outputs', 'generate text from images using VipLlavaForConditionalGeneration forward pass with labels and logits', 'extract image features from pixel values using VipLlavaForConditionalGeneration get_image_features method']
```

Usage

```
{'create_VipLlavaMultiModalProjector': 'create a VipLlavaMultiModalProjector module to project vision features into text embedding space', 'build_VipLlavaModel': 'build a VipLlavaModel that obtains image hidden states from the vision tower and applies multimodal projection', 'run_VipLlavaModel_forward': 'run VipLlavaModel forward to merge image features with text embeddings and generate language model outputs', 'generate_VipLlavaForConditionalGeneration': 'generate text from images using VipLlavaForConditionalGeneration forward pass with labels and logits', 'extract_VipLlavaForConditionalGeneration_get_image_features': 'extract image features from pixel values using VipLlavaForConditionalGeneration get_image_features method'}
```

