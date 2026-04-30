# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pi0/configuration_pi0.py

Prompts

```
['create a PI0Config with default settings for a Pi0 model using PaliGemma and Gemma backbones', 'create a PI0Config initialized from a dictionary with custom vlm_config and dit_config parameters', 'build a PI0ForConditionalGeneration model by passing a PI0Config instance to the constructor', "validate a PI0Config's architecture to ensure DiT hidden size is divisible by 2", 'customize a PI0Config with time sampling parameters including beta alpha, beta beta, scale, and offset', 'create a PI0 model for robot action generation using the PI0ForConditionalGeneration class', 'build flow matching inference to generate robot actions from state and image inputs', 'embed robot state, noise, and timestep into action embeddings for DiT processing', 'run denoising sampling with configurable steps to produce predicted actions from noise', 'test MSE loss computation between predicted velocity and target velocity during training', 'create a PI0Config with PaliGemma VLM backbone and DiT action expert configuration', 'create a PI0Processor that normalizes robot state and action tensors with mean/std and pads to max dimensions', 'build a PI0Model that merges PaliGemma image features with DiT action embeddings using bidirectional blockwise masking', 'run PI0ForConditionalGeneration flow matching inference to denoise random noise into robot action predictions', 'test PI0ForConditionalGeneration training with flow matching loss between predicted and target action velocities', 'call PI0Processor to process images and text into padded pixel values, tokenized input_ids, and normalized actions or state tensors', 'get the number of multimodal tokens for given image sizes using PI0Processor._get_num_multimodal_tokens', 'configure PI0ProcessorKwargs with text padding, max_length, and return_tensors defaults', 'get the model_input_names property from PI0Processor to list all required input keys including pixel_attention_mask']
```

Usage

```
{'create_PI0Config_default': 'create a PI0Config with default settings for a Pi0 model using PaliGemma and Gemma backbones', 'create_PI0Config_from_dict': 'create a PI0Config initialized from a dictionary with custom vlm_config and dit_config parameters', 'build_PI0_model_with_config': 'build a PI0ForConditionalGeneration model by passing a PI0Config instance to the constructor', 'validate_PI0_architecture': "validate a PI0Config's architecture to ensure DiT hidden size is divisible by 2", 'customize_PI0_time_sampling': 'customize a PI0Config with time sampling parameters including beta alpha, beta beta, scale, and offset'}
```

## File: huggingface_transformers/src/transformers/models/pi0/modeling_pi0.py

Prompts

```
['create a PI0Config with default settings for a Pi0 model using PaliGemma and Gemma backbones', 'create a PI0Config initialized from a dictionary with custom vlm_config and dit_config parameters', 'build a PI0ForConditionalGeneration model by passing a PI0Config instance to the constructor', "validate a PI0Config's architecture to ensure DiT hidden size is divisible by 2", 'customize a PI0Config with time sampling parameters including beta alpha, beta beta, scale, and offset', 'create a PI0 model for robot action generation using the PI0ForConditionalGeneration class', 'build flow matching inference to generate robot actions from state and image inputs', 'embed robot state, noise, and timestep into action embeddings for DiT processing', 'run denoising sampling with configurable steps to produce predicted actions from noise', 'test MSE loss computation between predicted velocity and target velocity during training', 'create a PI0Config with PaliGemma VLM backbone and DiT action expert configuration', 'create a PI0Processor that normalizes robot state and action tensors with mean/std and pads to max dimensions', 'build a PI0Model that merges PaliGemma image features with DiT action embeddings using bidirectional blockwise masking', 'run PI0ForConditionalGeneration flow matching inference to denoise random noise into robot action predictions', 'test PI0ForConditionalGeneration training with flow matching loss between predicted and target action velocities', 'call PI0Processor to process images and text into padded pixel values, tokenized input_ids, and normalized actions or state tensors', 'get the number of multimodal tokens for given image sizes using PI0Processor._get_num_multimodal_tokens', 'configure PI0ProcessorKwargs with text padding, max_length, and return_tensors defaults', 'get the model_input_names property from PI0Processor to list all required input keys including pixel_attention_mask']
```

Usage

```
{'create_pi0_model': 'create a PI0 model for robot action generation using the PI0ForConditionalGeneration class', 'build_flow_matching_inference': 'build flow matching inference to generate robot actions from state and image inputs', 'embed_robot_state_and_actions': 'embed robot state, noise, and timestep into action embeddings for DiT processing', 'run_denoising_sampling': 'run denoising sampling with configurable steps to produce predicted actions from noise', 'test_loss_computation': 'test MSE loss computation between predicted velocity and target velocity during training'}
```

## File: huggingface_transformers/src/transformers/models/pi0/modular_pi0.py

Prompts

```
['create a PI0Config with default settings for a Pi0 model using PaliGemma and Gemma backbones', 'create a PI0Config initialized from a dictionary with custom vlm_config and dit_config parameters', 'build a PI0ForConditionalGeneration model by passing a PI0Config instance to the constructor', "validate a PI0Config's architecture to ensure DiT hidden size is divisible by 2", 'customize a PI0Config with time sampling parameters including beta alpha, beta beta, scale, and offset', 'create a PI0 model for robot action generation using the PI0ForConditionalGeneration class', 'build flow matching inference to generate robot actions from state and image inputs', 'embed robot state, noise, and timestep into action embeddings for DiT processing', 'run denoising sampling with configurable steps to produce predicted actions from noise', 'test MSE loss computation between predicted velocity and target velocity during training', 'create a PI0Config with PaliGemma VLM backbone and DiT action expert configuration', 'create a PI0Processor that normalizes robot state and action tensors with mean/std and pads to max dimensions', 'build a PI0Model that merges PaliGemma image features with DiT action embeddings using bidirectional blockwise masking', 'run PI0ForConditionalGeneration flow matching inference to denoise random noise into robot action predictions', 'test PI0ForConditionalGeneration training with flow matching loss between predicted and target action velocities', 'call PI0Processor to process images and text into padded pixel values, tokenized input_ids, and normalized actions or state tensors', 'get the number of multimodal tokens for given image sizes using PI0Processor._get_num_multimodal_tokens', 'configure PI0ProcessorKwargs with text padding, max_length, and return_tensors defaults', 'get the model_input_names property from PI0Processor to list all required input keys including pixel_attention_mask']
```

Usage

```
{'create_PI0Config': 'create a PI0Config with PaliGemma VLM backbone and DiT action expert configuration', 'create_PI0Processor': 'create a PI0Processor that normalizes robot state and action tensors with mean/std and pads to max dimensions', 'build_PI0Model': 'build a PI0Model that merges PaliGemma image features with DiT action embeddings using bidirectional blockwise masking', 'run_PI0_flow_matching': 'run PI0ForConditionalGeneration flow matching inference to denoise random noise into robot action predictions', 'test_PI0_training': 'test PI0ForConditionalGeneration training with flow matching loss between predicted and target action velocities'}
```

## File: huggingface_transformers/src/transformers/models/pi0/processing_pi0.py

Prompts

```
['create a PI0Config with default settings for a Pi0 model using PaliGemma and Gemma backbones', 'create a PI0Config initialized from a dictionary with custom vlm_config and dit_config parameters', 'build a PI0ForConditionalGeneration model by passing a PI0Config instance to the constructor', "validate a PI0Config's architecture to ensure DiT hidden size is divisible by 2", 'customize a PI0Config with time sampling parameters including beta alpha, beta beta, scale, and offset', 'create a PI0 model for robot action generation using the PI0ForConditionalGeneration class', 'build flow matching inference to generate robot actions from state and image inputs', 'embed robot state, noise, and timestep into action embeddings for DiT processing', 'run denoising sampling with configurable steps to produce predicted actions from noise', 'test MSE loss computation between predicted velocity and target velocity during training', 'create a PI0Config with PaliGemma VLM backbone and DiT action expert configuration', 'create a PI0Processor that normalizes robot state and action tensors with mean/std and pads to max dimensions', 'build a PI0Model that merges PaliGemma image features with DiT action embeddings using bidirectional blockwise masking', 'run PI0ForConditionalGeneration flow matching inference to denoise random noise into robot action predictions', 'test PI0ForConditionalGeneration training with flow matching loss between predicted and target action velocities', 'call PI0Processor to process images and text into padded pixel values, tokenized input_ids, and normalized actions or state tensors', 'get the number of multimodal tokens for given image sizes using PI0Processor._get_num_multimodal_tokens', 'configure PI0ProcessorKwargs with text padding, max_length, and return_tensors defaults', 'get the model_input_names property from PI0Processor to list all required input keys including pixel_attention_mask']
```

Usage

```
{'create_PI0Processor': 'create a PI0Processor with an image processor, tokenizer, and state/action normalization parameters', 'call_PI0Processor': 'call PI0Processor to process images and text into padded pixel values, tokenized input_ids, and normalized actions or state tensors', 'get_num_multimodal_tokens': 'get the number of multimodal tokens for given image sizes using PI0Processor._get_num_multimodal_tokens', 'configure_PI0ProcessorKwargs': 'configure PI0ProcessorKwargs with text padding, max_length, and return_tensors defaults', 'get_model_input_names': 'get the model_input_names property from PI0Processor to list all required input keys including pixel_attention_mask'}
```

