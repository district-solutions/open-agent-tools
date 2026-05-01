# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/video_llava/test_modeling_video_llava.py

Prompts

```
['test the VideoLlavaForConditionalGeneration model with mixed image and video inputs', 'test the VideoLlavaForConditionalGeneration model with video-only inputs and no images', 'test the VideoLlavaForConditionalGeneration model with image-only inputs and no videos', 'test that batched and single row VideoLLaVA model outputs are numerically equivalent', 'run integration test with quantized VideoLLaVA model to generate text from video inputs', 'create a VideoLlavaVideoProcessingTester and call prepare_video_processor_dict to get processor config', 'use VideoLlavaVideoProcessingTester to prepare synthetic video inputs for testing the processor', 'run test_video_processor_properties to verify VideoLlavaVideoProcessor has all expected attributes', 'call expected_output_video_shape on the tester to get the expected output tensor dimensions', 'review the VideoLlavaVideoProcessingTester class to understand resize, crop, and normalize configuration options']
```

Usage

```
{'test_mixed_input': 'test the VideoLlavaForConditionalGeneration model with mixed image and video inputs', 'test_video_only_input': 'test the VideoLlavaForConditionalGeneration model with video-only inputs and no images', 'test_image_only_input': 'test the VideoLlavaForConditionalGeneration model with image-only inputs and no videos', 'test_batching_equivalence': 'test that batched and single row VideoLLaVA model outputs are numerically equivalent', 'run_integration_test': 'run integration test with quantized VideoLLaVA model to generate text from video inputs'}
```

## File: huggingface_transformers/tests/models/video_llava/test_video_processing_video_llava.py

Prompts

```
['test the VideoLlavaForConditionalGeneration model with mixed image and video inputs', 'test the VideoLlavaForConditionalGeneration model with video-only inputs and no images', 'test the VideoLlavaForConditionalGeneration model with image-only inputs and no videos', 'test that batched and single row VideoLLaVA model outputs are numerically equivalent', 'run integration test with quantized VideoLLaVA model to generate text from video inputs', 'create a VideoLlavaVideoProcessingTester and call prepare_video_processor_dict to get processor config', 'use VideoLlavaVideoProcessingTester to prepare synthetic video inputs for testing the processor', 'run test_video_processor_properties to verify VideoLlavaVideoProcessor has all expected attributes', 'call expected_output_video_shape on the tester to get the expected output tensor dimensions', 'review the VideoLlavaVideoProcessingTester class to understand resize, crop, and normalize configuration options']
```

Usage

```
{'create_video_processor_dict': 'create a VideoLlavaVideoProcessingTester and call prepare_video_processor_dict to get processor config', 'prepare_video_inputs': 'use VideoLlavaVideoProcessingTester to prepare synthetic video inputs for testing the processor', 'test_video_processor_properties': 'run test_video_processor_properties to verify VideoLlavaVideoProcessor has all expected attributes', 'expected_output_video_shape': 'call expected_output_video_shape on the tester to get the expected output tensor dimensions', 'review_VideoLlavaVideoProcessingTester': 'review the VideoLlavaVideoProcessingTester class to understand resize, crop, and normalize configuration options'}
```

