# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/emu3/test_modeling_emu3.py

Prompts

```
['test the Emu3ForCausalLM model using Emu3Text2TextModelTester with custom config and input tensors', 'test the Emu3ForConditionalGeneration model using Emu3Vision2TextModelTester with pixel values and image sizes', 'run the Emu3IntegrationTest to verify model generation with BitsAndBytesConfig 4-bit quantization', 'test batched image-text generation with Emu3ForConditionalGeneration using multiple images and prompts', 'test image generation with Emu3ForConditionalGeneration using prefix_allowed_tokens_fn and decode_image_tokens', 'test Emu3Processor with return_for_image_generation to produce input_ids, attention_mask, and image_sizes without providing images', 'test Emu3Processor postprocess to unnormalize pixel values and verify reconstruction accuracy', 'test Emu3Processor._get_num_multimodal_tokens to compute num_image_tokens and num_image_patches for varying image sizes', 'setup an Emu3 tokenizer with extra special tokens for image, boi, eoi, image_wrapper, and eof tokens', 'prepare an Emu3 chat template that renders all images first then text with generation markers for assistant responses']
```

Usage

```
{'test_emu3_text2text_model': 'test the Emu3ForCausalLM model using Emu3Text2TextModelTester with custom config and input tensors', 'test_emu3_vision2text_model': 'test the Emu3ForConditionalGeneration model using Emu3Vision2TextModelTester with pixel values and image sizes', 'run_emu3_integration_test': 'run the Emu3IntegrationTest to verify model generation with BitsAndBytesConfig 4-bit quantization', 'test_emu3_batched_generation': 'test batched image-text generation with Emu3ForConditionalGeneration using multiple images and prompts', 'test_emu3_image_generation': 'test image generation with Emu3ForConditionalGeneration using prefix_allowed_tokens_fn and decode_image_tokens'}
```

## File: huggingface_transformers/tests/models/emu3/test_processing_emu3.py

Prompts

```
['test the Emu3ForCausalLM model using Emu3Text2TextModelTester with custom config and input tensors', 'test the Emu3ForConditionalGeneration model using Emu3Vision2TextModelTester with pixel values and image sizes', 'run the Emu3IntegrationTest to verify model generation with BitsAndBytesConfig 4-bit quantization', 'test batched image-text generation with Emu3ForConditionalGeneration using multiple images and prompts', 'test image generation with Emu3ForConditionalGeneration using prefix_allowed_tokens_fn and decode_image_tokens', 'test Emu3Processor with return_for_image_generation to produce input_ids, attention_mask, and image_sizes without providing images', 'test Emu3Processor postprocess to unnormalize pixel values and verify reconstruction accuracy', 'test Emu3Processor._get_num_multimodal_tokens to compute num_image_tokens and num_image_patches for varying image sizes', 'setup an Emu3 tokenizer with extra special tokens for image, boi, eoi, image_wrapper, and eof tokens', 'prepare an Emu3 chat template that renders all images first then text with generation markers for assistant responses']
```

Usage

```
{'test_processor_for_generation': 'test Emu3Processor with return_for_image_generation to produce input_ids, attention_mask, and image_sizes without providing images', 'test_processor_postprocess': 'test Emu3Processor postprocess to unnormalize pixel values and verify reconstruction accuracy', 'test_get_num_vision_tokens': 'test Emu3Processor._get_num_multimodal_tokens to compute num_image_tokens and num_image_patches for varying image sizes', 'setup_emu3_tokenizer': 'setup an Emu3 tokenizer with extra special tokens for image, boi, eoi, image_wrapper, and eof tokens', 'prepare_emu3_chat_template': 'prepare an Emu3 chat template that renders all images first then text with generation markers for assistant responses'}
```

