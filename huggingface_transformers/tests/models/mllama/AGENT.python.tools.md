# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mllama/test_image_processing_mllama.py

Prompts

```
['test the MllamaImageProcessingTester class properties for image processor configuration attributes', 'test the image processor with numpy array inputs in batched and unbatched modes', 'test the image processor with PIL image inputs in batched and unbatched modes', 'test the image tiling logic for different aspect ratios and tile grid configurations', 'test that explicit None attributes are preserved through save and load cycles', 'test the MllamaForCausalLM model class with text-only inputs and fp16 forward pass', 'test the MllamaForConditionalGeneration model class with vision-text inputs and cross-attention layers', 'build MllamaConfig with text and vision configs, image token index, and cross-attention layer indices', 'build MllamaTextConfig with vocab size, hidden size, attention heads, and rope parameters for text-only testing', 'test the MllamaForConditionalGeneration integration with 4-bit quantized model generation and image inputs', 'test the MllamaProcessorTest class to verify MllamaProcessor chat template and image processing behavior', 'test the apply_chat_template method with interleaved image and text messages for MllamaProcessor', 'test processing interleaved images and text prompts with cross attention mask generation', 'test error handling when image token count mismatches provided images in MllamaProcessor', 'test that special multimodal vision tokens are not truncated when max_length is set']
```

Usage

```
{'test_mllama_image_processing_properties': 'test the MllamaImageProcessingTester class properties for image processor configuration attributes', 'test_call_numpy_inputs': 'test the image processor with numpy array inputs in batched and unbatched modes', 'test_call_pil_inputs': 'test the image processor with PIL image inputs in batched and unbatched modes', 'test_image_correctly_tiled': 'test the image tiling logic for different aspect ratios and tile grid configurations', 'test_fast_image_processor_explicit_none_preserved': 'test that explicit None attributes are preserved through save and load cycles'}
```

## File: huggingface_transformers/tests/models/mllama/test_modeling_mllama.py

Prompts

```
['test the MllamaImageProcessingTester class properties for image processor configuration attributes', 'test the image processor with numpy array inputs in batched and unbatched modes', 'test the image processor with PIL image inputs in batched and unbatched modes', 'test the image tiling logic for different aspect ratios and tile grid configurations', 'test that explicit None attributes are preserved through save and load cycles', 'test the MllamaForCausalLM model class with text-only inputs and fp16 forward pass', 'test the MllamaForConditionalGeneration model class with vision-text inputs and cross-attention layers', 'build MllamaConfig with text and vision configs, image token index, and cross-attention layer indices', 'build MllamaTextConfig with vocab size, hidden size, attention heads, and rope parameters for text-only testing', 'test the MllamaForConditionalGeneration integration with 4-bit quantized model generation and image inputs', 'test the MllamaProcessorTest class to verify MllamaProcessor chat template and image processing behavior', 'test the apply_chat_template method with interleaved image and text messages for MllamaProcessor', 'test processing interleaved images and text prompts with cross attention mask generation', 'test error handling when image token count mismatches provided images in MllamaProcessor', 'test that special multimodal vision tokens are not truncated when max_length is set']
```

Usage

```
{'test_MllamaForCausalLMModelTest': 'test the MllamaForCausalLM model class with text-only inputs and fp16 forward pass', 'test_MllamaForConditionalGenerationModelTest': 'test the MllamaForConditionalGeneration model class with vision-text inputs and cross-attention layers', 'test_MllamaVisionText2TextModelTester_prepare_config': 'build MllamaConfig with text and vision configs, image token index, and cross-attention layer indices', 'test_MllamaText2TextModelTester_prepare_config': 'build MllamaTextConfig with vocab size, hidden size, attention heads, and rope parameters for text-only testing', 'test_MllamaForConditionalGenerationIntegrationTest': 'test the MllamaForConditionalGeneration integration with 4-bit quantized model generation and image inputs'}
```

## File: huggingface_transformers/tests/models/mllama/test_processing_mllama.py

Prompts

```
['test the MllamaImageProcessingTester class properties for image processor configuration attributes', 'test the image processor with numpy array inputs in batched and unbatched modes', 'test the image processor with PIL image inputs in batched and unbatched modes', 'test the image tiling logic for different aspect ratios and tile grid configurations', 'test that explicit None attributes are preserved through save and load cycles', 'test the MllamaForCausalLM model class with text-only inputs and fp16 forward pass', 'test the MllamaForConditionalGeneration model class with vision-text inputs and cross-attention layers', 'build MllamaConfig with text and vision configs, image token index, and cross-attention layer indices', 'build MllamaTextConfig with vocab size, hidden size, attention heads, and rope parameters for text-only testing', 'test the MllamaForConditionalGeneration integration with 4-bit quantized model generation and image inputs', 'test the MllamaProcessorTest class to verify MllamaProcessor chat template and image processing behavior', 'test the apply_chat_template method with interleaved image and text messages for MllamaProcessor', 'test processing interleaved images and text prompts with cross attention mask generation', 'test error handling when image token count mismatches provided images in MllamaProcessor', 'test that special multimodal vision tokens are not truncated when max_length is set']
```

Usage

```
{'test_MllamaProcessorTest_class': 'test the MllamaProcessorTest class to verify MllamaProcessor chat template and image processing behavior', 'test_apply_chat_template': 'test the apply_chat_template method with interleaved image and text messages for MllamaProcessor', 'test_process_interleaved_images_prompts_image_splitting': 'test processing interleaved images and text prompts with cross attention mask generation', 'test_process_interleaved_images_prompts_image_error': 'test error handling when image token count mismatches provided images in MllamaProcessor', 'test_special_mm_token_truncation': 'test that special multimodal vision tokens are not truncated when max_length is set'}
```

