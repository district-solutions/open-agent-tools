# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/qianfan_ocr/test_modeling_qianfan_ocr.py

Prompts

```
['test the QianfanOCRModelTest class for reverse loading mapping and skip unsupported torch compile tests', 'test the QianfanOCRVisionText2TextModelTester class with get_config, get_vision_config, create_pixel_values, and place_image_tokens methods', 'test the QianfanOCRIntegrationTest model integration forward pass with bfloat16 logits on cuda', 'test the QianfanOCRIntegrationTest model integration text and image generation with max_new_tokens', 'test the QianfanOCRIntegrationTest model integration batched generation with multiple messages and padding', 'test the QianfanOCRProcessor apply_chat_template method with batched image messages and tokenization', 'test the QianfanOCRProcessor model_input_names match the processor output keys for image inputs', 'test the QianfanOCRProcessor _get_num_multimodal_tokens helper returns correct image token and patch counts', 'test the QianfanOCRProcessor handles image modality inputs with dynamic patching and pixel values', 'test the QianfanOCRProcessor apply_chat_template continue_final_message flag preserves assistant text without eos token']
```

Usage

```
{'test_QianfanOCRModelTest': 'test the QianfanOCRModelTest class for reverse loading mapping and skip unsupported torch compile tests', 'test_QianfanOCRVisionText2TextModelTester': 'test the QianfanOCRVisionText2TextModelTester class with get_config, get_vision_config, create_pixel_values, and place_image_tokens methods', 'test_QianfanOCRIntegrationTest_forward': 'test the QianfanOCRIntegrationTest model integration forward pass with bfloat16 logits on cuda', 'test_QianfanOCRIntegrationTest_generate': 'test the QianfanOCRIntegrationTest model integration text and image generation with max_new_tokens', 'test_QianfanOCRIntegrationTest_batched_generate': 'test the QianfanOCRIntegrationTest model integration batched generation with multiple messages and padding'}
```

## File: huggingface_transformers/tests/models/qianfan_ocr/test_processing_qianfan_ocr.py

Prompts

```
['test the QianfanOCRModelTest class for reverse loading mapping and skip unsupported torch compile tests', 'test the QianfanOCRVisionText2TextModelTester class with get_config, get_vision_config, create_pixel_values, and place_image_tokens methods', 'test the QianfanOCRIntegrationTest model integration forward pass with bfloat16 logits on cuda', 'test the QianfanOCRIntegrationTest model integration text and image generation with max_new_tokens', 'test the QianfanOCRIntegrationTest model integration batched generation with multiple messages and padding', 'test the QianfanOCRProcessor apply_chat_template method with batched image messages and tokenization', 'test the QianfanOCRProcessor model_input_names match the processor output keys for image inputs', 'test the QianfanOCRProcessor _get_num_multimodal_tokens helper returns correct image token and patch counts', 'test the QianfanOCRProcessor handles image modality inputs with dynamic patching and pixel values', 'test the QianfanOCRProcessor apply_chat_template continue_final_message flag preserves assistant text without eos token']
```

Usage

```
{'test_QianfanOCRProcessor_chat_template': 'test the QianfanOCRProcessor apply_chat_template method with batched image messages and tokenization', 'test_QianfanOCRProcessor_model_input_names': 'test the QianfanOCRProcessor model_input_names match the processor output keys for image inputs', 'test_QianfanOCRProcessor_num_vision_tokens': 'test the QianfanOCRProcessor _get_num_multimodal_tokens helper returns correct image token and patch counts', 'test_QianfanOCRProcessor_image_processing': 'test the QianfanOCRProcessor handles image modality inputs with dynamic patching and pixel values', 'test_QianfanOCRProcessor_continue_final_message': 'test the QianfanOCRProcessor apply_chat_template continue_final_message flag preserves assistant text without eos token'}
```

