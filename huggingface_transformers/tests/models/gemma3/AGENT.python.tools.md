# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/gemma3/test_image_processing_gemma3.py

Prompts

```
['test the Gemma3ImageProcessingTest class verifies image processor properties like do_resize, size, do_normalize, and pan_and_scan attributes', 'test the pan and scan image processing path with wide images that produce base image plus multiple crops', 'test the Gemma3 image processor with PIL Image inputs for both single and batched scenarios', 'test the Gemma3 image processor with NumPy array inputs for both single and batched scenarios', 'test the Gemma3 image processor with PyTorch tensor inputs for both single and batched scenarios', 'test generation beyond sliding window with hybrid cache and attention mask slicing for Gemma3 text model', 'test RoPE scaling frequency properties for linear, dynamic NTK, and yarn scaling types on Gemma3', 'test bidirectional attention mask on image tokens ensuring images attend to themselves but not future images', 'test flash attention 2, 3, and 4 configuration loading and forward pass for Gemma3 vision-language model', 'test Gemma3 4b bf16 multimodal image captioning generation with real checkpoint on GPU accelerator', 'test the Gemma3ProcessorTest class which tests the Gemma3Processor functionality', 'test the _get_num_multimodal_tokens helper method used internally in vLLM for computing vision token counts', 'test the processor with pan_and_scan enabled to crop and process images into base plus multiple crops', 'test the processor handles text with single, multiple, and no image tokens with nested image inputs', 'test that special multimodal tokens are not truncated when truncation is enabled with a small max_length']
```

Usage

```
{'test_image_processor_properties': 'test the Gemma3ImageProcessingTest class verifies image processor properties like do_resize, size, do_normalize, and pan_and_scan attributes', 'test_pan_and_scan': 'test the pan and scan image processing path with wide images that produce base image plus multiple crops', 'test_call_pil': 'test the Gemma3 image processor with PIL Image inputs for both single and batched scenarios', 'test_call_numpy': 'test the Gemma3 image processor with NumPy array inputs for both single and batched scenarios', 'test_call_pytorch': 'test the Gemma3 image processor with PyTorch tensor inputs for both single and batched scenarios'}
```

## File: huggingface_transformers/tests/models/gemma3/test_modeling_gemma3.py

Prompts

```
['test the Gemma3ImageProcessingTest class verifies image processor properties like do_resize, size, do_normalize, and pan_and_scan attributes', 'test the pan and scan image processing path with wide images that produce base image plus multiple crops', 'test the Gemma3 image processor with PIL Image inputs for both single and batched scenarios', 'test the Gemma3 image processor with NumPy array inputs for both single and batched scenarios', 'test the Gemma3 image processor with PyTorch tensor inputs for both single and batched scenarios', 'test generation beyond sliding window with hybrid cache and attention mask slicing for Gemma3 text model', 'test RoPE scaling frequency properties for linear, dynamic NTK, and yarn scaling types on Gemma3', 'test bidirectional attention mask on image tokens ensuring images attend to themselves but not future images', 'test flash attention 2, 3, and 4 configuration loading and forward pass for Gemma3 vision-language model', 'test Gemma3 4b bf16 multimodal image captioning generation with real checkpoint on GPU accelerator', 'test the Gemma3ProcessorTest class which tests the Gemma3Processor functionality', 'test the _get_num_multimodal_tokens helper method used internally in vLLM for computing vision token counts', 'test the processor with pan_and_scan enabled to crop and process images into base plus multiple crops', 'test the processor handles text with single, multiple, and no image tokens with nested image inputs', 'test that special multimodal tokens are not truncated when truncation is enabled with a small max_length']
```

Usage

```
{'test_generation_beyond_sliding_window': 'test generation beyond sliding window with hybrid cache and attention mask slicing for Gemma3 text model', 'test_model_rope_scaling_frequencies': 'test RoPE scaling frequency properties for linear, dynamic NTK, and yarn scaling types on Gemma3', 'test_bidirectional_image_attention': 'test bidirectional attention mask on image tokens ensuring images attend to themselves but not future images', 'test_flash_attn_from_config': 'test flash attention 2, 3, and 4 configuration loading and forward pass for Gemma3 vision-language model', 'test_model_4b_bf16': 'test Gemma3 4b bf16 multimodal image captioning generation with real checkpoint on GPU accelerator'}
```

## File: huggingface_transformers/tests/models/gemma3/test_processing_gemma3.py

Prompts

```
['test the Gemma3ImageProcessingTest class verifies image processor properties like do_resize, size, do_normalize, and pan_and_scan attributes', 'test the pan and scan image processing path with wide images that produce base image plus multiple crops', 'test the Gemma3 image processor with PIL Image inputs for both single and batched scenarios', 'test the Gemma3 image processor with NumPy array inputs for both single and batched scenarios', 'test the Gemma3 image processor with PyTorch tensor inputs for both single and batched scenarios', 'test generation beyond sliding window with hybrid cache and attention mask slicing for Gemma3 text model', 'test RoPE scaling frequency properties for linear, dynamic NTK, and yarn scaling types on Gemma3', 'test bidirectional attention mask on image tokens ensuring images attend to themselves but not future images', 'test flash attention 2, 3, and 4 configuration loading and forward pass for Gemma3 vision-language model', 'test Gemma3 4b bf16 multimodal image captioning generation with real checkpoint on GPU accelerator', 'test the Gemma3ProcessorTest class which tests the Gemma3Processor functionality', 'test the _get_num_multimodal_tokens helper method used internally in vLLM for computing vision token counts', 'test the processor with pan_and_scan enabled to crop and process images into base plus multiple crops', 'test the processor handles text with single, multiple, and no image tokens with nested image inputs', 'test that special multimodal tokens are not truncated when truncation is enabled with a small max_length']
```

Usage

```
{'test_Gemma3ProcessorTest': 'test the Gemma3ProcessorTest class which tests the Gemma3Processor functionality', 'test_Gemma3ProcessorTest_get_num_vision_tokens': 'test the _get_num_multimodal_tokens helper method used internally in vLLM for computing vision token counts', 'test_Gemma3ProcessorTest_pan_and_scan': 'test the processor with pan_and_scan enabled to crop and process images into base plus multiple crops', 'test_Gemma3ProcessorTest_text_with_image_tokens': 'test the processor handles text with single, multiple, and no image tokens with nested image inputs', 'test_Gemma3ProcessorTest_special_mm_token_truncation': 'test that special multimodal tokens are not truncated when truncation is enabled with a small max_length'}
```

