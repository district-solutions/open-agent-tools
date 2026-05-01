# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/minicpmv4_6/test_image_processing_minicpmv4_6.py

Prompts

```
['test the MiniCPMV4_6ImageProcessingTester expected_output_image_shape method to compute NaViT-packed shape for pixel values', 'test the MiniCPMV4_6ImageProcessingTester prepare_image_processor_dict method to return image processor configuration dictionary', 'test the MiniCPMV4_6ImageProcessingTest test_call_pil method to verify PIL image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_call_numpy method to verify numpy array image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_downsample_modes method to compare 4x and 16x downsample mode target sizes', 'test the MiniCPMV4_6Model forward pass with NaViT-packed pixel values and target sizes', 'test MiniCPMV4_6ForConditionalGeneration model generation with vision and text inputs', 'test attention outputs for Qwen3.5 hybrid full and linear attention layers', 'test MiniCPM-V 4.6 integration with image URL and text prompt generation', 'test batched generation with mixed image and text-only messages using AutoProcessor', 'test the MiniCPMV4_6Processor to handle image inputs and verify pixel_values and input_ids are returned', 'test the MiniCPMV4_6Processor to handle video inputs and verify pixel_values_videos and input_ids are returned', 'test the MiniCPMV4_6Processor with text-only input to verify input_ids and attention_mask are returned', 'test the MiniCPMV4_6Processor with a list of text inputs for batch processing', 'test the post_process_image_text_to_text method to decode generated token IDs back into text strings', 'test the MiniCPMV4_6VideoProcessor with PIL image inputs and verify NaViT packed output shape', 'test the MiniCPMV4_6VideoProcessor with numpy array video inputs and verify batched encoding output', 'test the MiniCPMV4_6VideoProcessor with PyTorch tensor video inputs and verify encoded video shape', 'test the MiniCPMV4_6VideoProcessor with nested list inputs and verify dimension zero equals one', 'test the MiniCPMV4_6VideoProcessor frame sampling with VideoMetadata and stack_frames parameters']
```

Usage

```
{'test_MiniCPMV4_6ImageProcessingTester_expected_output_image_shape': 'test the MiniCPMV4_6ImageProcessingTester expected_output_image_shape method to compute NaViT-packed shape for pixel values', 'test_MiniCPMV4_6ImageProcessingTester_prepare_image_processor_dict': 'test the MiniCPMV4_6ImageProcessingTester prepare_image_processor_dict method to return image processor configuration dictionary', 'test_MiniCPMV4_6ImageProcessingTest_test_call_pil': 'test the MiniCPMV4_6ImageProcessingTest test_call_pil method to verify PIL image processing with batched and unbatched inputs', 'test_MiniCPMV4_6ImageProcessingTest_test_call_numpy': 'test the MiniCPMV4_6ImageProcessingTest test_call_numpy method to verify numpy array image processing with batched and unbatched inputs', 'test_MiniCPMV4_6ImageProcessingTest_test_downsample_modes': 'test the MiniCPMV4_6ImageProcessingTest test_downsample_modes method to compare 4x and 16x downsample mode target sizes'}
```

## File: huggingface_transformers/tests/models/minicpmv4_6/test_modeling_minicpmv4_6.py

Prompts

```
['test the MiniCPMV4_6ImageProcessingTester expected_output_image_shape method to compute NaViT-packed shape for pixel values', 'test the MiniCPMV4_6ImageProcessingTester prepare_image_processor_dict method to return image processor configuration dictionary', 'test the MiniCPMV4_6ImageProcessingTest test_call_pil method to verify PIL image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_call_numpy method to verify numpy array image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_downsample_modes method to compare 4x and 16x downsample mode target sizes', 'test the MiniCPMV4_6Model forward pass with NaViT-packed pixel values and target sizes', 'test MiniCPMV4_6ForConditionalGeneration model generation with vision and text inputs', 'test attention outputs for Qwen3.5 hybrid full and linear attention layers', 'test MiniCPM-V 4.6 integration with image URL and text prompt generation', 'test batched generation with mixed image and text-only messages using AutoProcessor', 'test the MiniCPMV4_6Processor to handle image inputs and verify pixel_values and input_ids are returned', 'test the MiniCPMV4_6Processor to handle video inputs and verify pixel_values_videos and input_ids are returned', 'test the MiniCPMV4_6Processor with text-only input to verify input_ids and attention_mask are returned', 'test the MiniCPMV4_6Processor with a list of text inputs for batch processing', 'test the post_process_image_text_to_text method to decode generated token IDs back into text strings', 'test the MiniCPMV4_6VideoProcessor with PIL image inputs and verify NaViT packed output shape', 'test the MiniCPMV4_6VideoProcessor with numpy array video inputs and verify batched encoding output', 'test the MiniCPMV4_6VideoProcessor with PyTorch tensor video inputs and verify encoded video shape', 'test the MiniCPMV4_6VideoProcessor with nested list inputs and verify dimension zero equals one', 'test the MiniCPMV4_6VideoProcessor frame sampling with VideoMetadata and stack_frames parameters']
```

Usage

```
{'test_minicpmv4_6_model_forward': 'test the MiniCPMV4_6Model forward pass with NaViT-packed pixel values and target sizes', 'test_minicpmv4_6_conditional_generation': 'test MiniCPMV4_6ForConditionalGeneration model generation with vision and text inputs', 'test_minicpmv4_6_attention_outputs': 'test attention outputs for Qwen3.5 hybrid full and linear attention layers', 'test_minicpmv4_6_integration_vision_generation': 'test MiniCPM-V 4.6 integration with image URL and text prompt generation', 'test_minicpmv4_6_batch_mixed_generation': 'test batched generation with mixed image and text-only messages using AutoProcessor'}
```

## File: huggingface_transformers/tests/models/minicpmv4_6/test_processing_minicpmv4_6.py

Prompts

```
['test the MiniCPMV4_6ImageProcessingTester expected_output_image_shape method to compute NaViT-packed shape for pixel values', 'test the MiniCPMV4_6ImageProcessingTester prepare_image_processor_dict method to return image processor configuration dictionary', 'test the MiniCPMV4_6ImageProcessingTest test_call_pil method to verify PIL image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_call_numpy method to verify numpy array image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_downsample_modes method to compare 4x and 16x downsample mode target sizes', 'test the MiniCPMV4_6Model forward pass with NaViT-packed pixel values and target sizes', 'test MiniCPMV4_6ForConditionalGeneration model generation with vision and text inputs', 'test attention outputs for Qwen3.5 hybrid full and linear attention layers', 'test MiniCPM-V 4.6 integration with image URL and text prompt generation', 'test batched generation with mixed image and text-only messages using AutoProcessor', 'test the MiniCPMV4_6Processor to handle image inputs and verify pixel_values and input_ids are returned', 'test the MiniCPMV4_6Processor to handle video inputs and verify pixel_values_videos and input_ids are returned', 'test the MiniCPMV4_6Processor with text-only input to verify input_ids and attention_mask are returned', 'test the MiniCPMV4_6Processor with a list of text inputs for batch processing', 'test the post_process_image_text_to_text method to decode generated token IDs back into text strings', 'test the MiniCPMV4_6VideoProcessor with PIL image inputs and verify NaViT packed output shape', 'test the MiniCPMV4_6VideoProcessor with numpy array video inputs and verify batched encoding output', 'test the MiniCPMV4_6VideoProcessor with PyTorch tensor video inputs and verify encoded video shape', 'test the MiniCPMV4_6VideoProcessor with nested list inputs and verify dimension zero equals one', 'test the MiniCPMV4_6VideoProcessor frame sampling with VideoMetadata and stack_frames parameters']
```

Usage

```
{'test_image_processing': 'test the MiniCPMV4_6Processor to handle image inputs and verify pixel_values and input_ids are returned', 'test_video_processing': 'test the MiniCPMV4_6Processor to handle video inputs and verify pixel_values_videos and input_ids are returned', 'test_text_only_processing': 'test the MiniCPMV4_6Processor with text-only input to verify input_ids and attention_mask are returned', 'test_batch_text_processing': 'test the MiniCPMV4_6Processor with a list of text inputs for batch processing', 'test_post_process_image_text_to_text': 'test the post_process_image_text_to_text method to decode generated token IDs back into text strings'}
```

## File: huggingface_transformers/tests/models/minicpmv4_6/test_video_processing_minicpmv4_6.py

Prompts

```
['test the MiniCPMV4_6ImageProcessingTester expected_output_image_shape method to compute NaViT-packed shape for pixel values', 'test the MiniCPMV4_6ImageProcessingTester prepare_image_processor_dict method to return image processor configuration dictionary', 'test the MiniCPMV4_6ImageProcessingTest test_call_pil method to verify PIL image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_call_numpy method to verify numpy array image processing with batched and unbatched inputs', 'test the MiniCPMV4_6ImageProcessingTest test_downsample_modes method to compare 4x and 16x downsample mode target sizes', 'test the MiniCPMV4_6Model forward pass with NaViT-packed pixel values and target sizes', 'test MiniCPMV4_6ForConditionalGeneration model generation with vision and text inputs', 'test attention outputs for Qwen3.5 hybrid full and linear attention layers', 'test MiniCPM-V 4.6 integration with image URL and text prompt generation', 'test batched generation with mixed image and text-only messages using AutoProcessor', 'test the MiniCPMV4_6Processor to handle image inputs and verify pixel_values and input_ids are returned', 'test the MiniCPMV4_6Processor to handle video inputs and verify pixel_values_videos and input_ids are returned', 'test the MiniCPMV4_6Processor with text-only input to verify input_ids and attention_mask are returned', 'test the MiniCPMV4_6Processor with a list of text inputs for batch processing', 'test the post_process_image_text_to_text method to decode generated token IDs back into text strings', 'test the MiniCPMV4_6VideoProcessor with PIL image inputs and verify NaViT packed output shape', 'test the MiniCPMV4_6VideoProcessor with numpy array video inputs and verify batched encoding output', 'test the MiniCPMV4_6VideoProcessor with PyTorch tensor video inputs and verify encoded video shape', 'test the MiniCPMV4_6VideoProcessor with nested list inputs and verify dimension zero equals one', 'test the MiniCPMV4_6VideoProcessor frame sampling with VideoMetadata and stack_frames parameters']
```

Usage

```
{'test_video_processor_pil': 'test the MiniCPMV4_6VideoProcessor with PIL image inputs and verify NaViT packed output shape', 'test_video_processor_numpy': 'test the MiniCPMV4_6VideoProcessor with numpy array video inputs and verify batched encoding output', 'test_video_processor_pytorch': 'test the MiniCPMV4_6VideoProcessor with PyTorch tensor video inputs and verify encoded video shape', 'test_video_processor_nested_input': 'test the MiniCPMV4_6VideoProcessor with nested list inputs and verify dimension zero equals one', 'test_video_processor_sample_frames': 'test the MiniCPMV4_6VideoProcessor frame sampling with VideoMetadata and stack_frames parameters'}
```

