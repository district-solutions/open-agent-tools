# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/paddleocr_vl/test_image_processing_paddleocr_vl.py

Prompts

```
['test the PaddleOCRVL image processor with PIL images for single and batched inputs', 'test the PaddleOCRVL image processor with numpy array inputs for single and batched processing', 'test the smart_resize function to verify it selects the best resolution for given dimensions', 'test the get_number_of_image_patches method to calculate patch counts for different image sizes', 'test that all image processing backends produce equivalent pixel values and grid tensors', 'test the PaddleOCRVLVisionText2TextModelTester class that prepares config and inputs for PaddleOCRVL model unit tests', 'test the PaddleOCRVLModelTest class that validates PaddleOCRVLForConditionalGeneration forward pass, generation, and pipeline behavior', 'test that PaddleOCRVLForConditionalGeneration raises ValueError when image features and image tokens do not match', 'test the PaddleOCRVLIntegrationTest class that verifies end-to-end OCR generation with the PaddlePaddle/PaddleOCR-VL model', 'test PaddleOCRVLForConditionalGeneration with flash_attention_2 implementation for OCR generation on GPU']
```

Usage

```
{'test_paddleocr_vl_image_processing_pil': 'test the PaddleOCRVL image processor with PIL images for single and batched inputs', 'test_paddleocr_vl_image_processing_numpy': 'test the PaddleOCRVL image processor with numpy array inputs for single and batched processing', 'test_paddleocr_vl_smart_resize': 'test the smart_resize function to verify it selects the best resolution for given dimensions', 'test_paddleocr_vl_get_num_patches': 'test the get_number_of_image_patches method to calculate patch counts for different image sizes', 'test_paddleocr_vl_backends_equivalence': 'test that all image processing backends produce equivalent pixel values and grid tensors'}
```

## File: huggingface_transformers/tests/models/paddleocr_vl/test_modeling_paddleocr_vl.py

Prompts

```
['test the PaddleOCRVL image processor with PIL images for single and batched inputs', 'test the PaddleOCRVL image processor with numpy array inputs for single and batched processing', 'test the smart_resize function to verify it selects the best resolution for given dimensions', 'test the get_number_of_image_patches method to calculate patch counts for different image sizes', 'test that all image processing backends produce equivalent pixel values and grid tensors', 'test the PaddleOCRVLVisionText2TextModelTester class that prepares config and inputs for PaddleOCRVL model unit tests', 'test the PaddleOCRVLModelTest class that validates PaddleOCRVLForConditionalGeneration forward pass, generation, and pipeline behavior', 'test that PaddleOCRVLForConditionalGeneration raises ValueError when image features and image tokens do not match', 'test the PaddleOCRVLIntegrationTest class that verifies end-to-end OCR generation with the PaddlePaddle/PaddleOCR-VL model', 'test PaddleOCRVLForConditionalGeneration with flash_attention_2 implementation for OCR generation on GPU']
```

Usage

```
{'test_PaddleOCRVLVisionText2TextModelTester': 'test the PaddleOCRVLVisionText2TextModelTester class that prepares config and inputs for PaddleOCRVL model unit tests', 'test_PaddleOCRVLModelTest': 'test the PaddleOCRVLModelTest class that validates PaddleOCRVLForConditionalGeneration forward pass, generation, and pipeline behavior', 'test_mismatching_num_image_tokens': 'test that PaddleOCRVLForConditionalGeneration raises ValueError when image features and image tokens do not match', 'test_PaddleOCRVLIntegrationTest': 'test the PaddleOCRVLIntegrationTest class that verifies end-to-end OCR generation with the PaddlePaddle/PaddleOCR-VL model', 'test_small_model_integration_test_flashatt2': 'test PaddleOCRVLForConditionalGeneration with flash_attention_2 implementation for OCR generation on GPU'}
```

