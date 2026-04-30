# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/cohere2_vision/test_image_processing_cohere2_vision.py

Prompts

```
['test the Cohere2VisionImageProcessingTester class that prepares image processor configuration and test inputs', 'test the Cohere2VisionProcessingTest class that validates image processing for Cohere2Vision models', 'test the prepare_image_processor_dict method that returns image processor configuration as a dictionary', 'test the prepare_image_inputs method that generates random test images with configurable batch size and resolution', 'test processing PIL images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing numpy array images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing PyTorch tensor images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing 4-channel numpy images through the image processor with custom mean and std values', 'test cropping non-square images into patches and verify row/column ordering by stitching patches back to reconstruct the original image', 'test the get_number_of_image_patches method returns correct patch counts for tall, wide, and asymmetric aspect ratio images', 'test the Cohere2VisionConfig initialization and serialization via ConfigTester', 'test the Cohere2VisionModel forward pass with synthetic pixel values and input ids', 'test the Cohere2VisionForConditionalGeneration text generation with max_new_tokens', 'test the Cohere2VisionForConditionalGeneration forward pass using the real checkpoint with image input', 'test batched image-to-text generation across multiple images and prompts']
```

Usage

```
{'test_image_processing_cohere2_vision_Cohere2VisionImageProcessingTester': 'test the Cohere2VisionImageProcessingTester class that prepares image processor configuration and test inputs', 'test_image_processing_cohere2_vision_Cohere2VisionProcessingTest': 'test the Cohere2VisionProcessingTest class that validates image processing for Cohere2Vision models', 'test_image_processing_cohere2_vision_prepare_image_processor_dict': 'test the prepare_image_processor_dict method that returns image processor configuration as a dictionary', 'test_image_processing_cohere2_vision_prepare_image_inputs': 'test the prepare_image_inputs method that generates random test images with configurable batch size and resolution', 'test_image_processing_cohere2_vision_test_call_pil': 'test processing PIL images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test_image_processing_cohere2_vision_test_call_numpy': 'test processing numpy array images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test_image_processing_cohere2_vision_test_call_pytorch': 'test processing PyTorch tensor images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test_image_processing_cohere2_vision_test_call_numpy_4_channels': 'test processing 4-channel numpy images through the image processor with custom mean and std values', 'test_image_processing_cohere2_vision_test_crop_to_patches_aspect_ratio': 'test cropping non-square images into patches and verify row/column ordering by stitching patches back to reconstruct the original image', 'test_image_processing_cohere2_vision_test_get_number_of_image_patches_aspect_ratio': 'test the get_number_of_image_patches method returns correct patch counts for tall, wide, and asymmetric aspect ratio images'}
```

## File: huggingface_transformers/tests/models/cohere2_vision/test_modeling_cohere2_vision.py

Prompts

```
['test the Cohere2VisionImageProcessingTester class that prepares image processor configuration and test inputs', 'test the Cohere2VisionProcessingTest class that validates image processing for Cohere2Vision models', 'test the prepare_image_processor_dict method that returns image processor configuration as a dictionary', 'test the prepare_image_inputs method that generates random test images with configurable batch size and resolution', 'test processing PIL images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing numpy array images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing PyTorch tensor images through the image processor and verify output tensor shapes for batched and unbatched inputs', 'test processing 4-channel numpy images through the image processor with custom mean and std values', 'test cropping non-square images into patches and verify row/column ordering by stitching patches back to reconstruct the original image', 'test the get_number_of_image_patches method returns correct patch counts for tall, wide, and asymmetric aspect ratio images', 'test the Cohere2VisionConfig initialization and serialization via ConfigTester', 'test the Cohere2VisionModel forward pass with synthetic pixel values and input ids', 'test the Cohere2VisionForConditionalGeneration text generation with max_new_tokens', 'test the Cohere2VisionForConditionalGeneration forward pass using the real checkpoint with image input', 'test batched image-to-text generation across multiple images and prompts']
```

Usage

```
{'test_model_config': 'test the Cohere2VisionConfig initialization and serialization via ConfigTester', 'test_model_forward_pass': 'test the Cohere2VisionModel forward pass with synthetic pixel values and input ids', 'test_model_generation': 'test the Cohere2VisionForConditionalGeneration text generation with max_new_tokens', 'test_model_integration_forward': 'test the Cohere2VisionForConditionalGeneration forward pass using the real checkpoint with image input', 'test_model_batched_generate': 'test batched image-to-text generation across multiple images and prompts'}
```

