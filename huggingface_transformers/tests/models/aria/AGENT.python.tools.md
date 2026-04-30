# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/aria/test_image_processing_aria.py

Prompts

```
['test the AriaImageProcessingTester class that prepares image processor configurations and test inputs', 'test the AriaImageProcessingTest class that validates Aria image processing with numpy, PIL, and PyTorch inputs', 'test that AriaImageProcessor has properties like do_convert_rgb, max_image_size, min_image_size, do_normalize, image_mean, image_std, and split_image', 'test AriaImageProcessor with batched and unbatched numpy array inputs returning correct pixel value shapes', 'test AriaImageProcessor with batched and unbatched PIL image inputs returning correct pixel value shapes', 'test AriaImageProcessor with batched and unbatched PyTorch tensor inputs returning correct pixel value shapes', 'test the _pad_for_patching method that pads odd-sized images to target dimensions', 'test the get_number_of_image_patches method that calculates patch counts based on image dimensions and split_image settings', 'test the AriaVisionText2TextModelTester class for preparing model configs and inputs with vision and text modalities', 'test the AriaForConditionalGenerationModelTest class for model inference and generation using ModelTesterMixin and GenerationTesterMixin', 'test the AriaForConditionalGenerationIntegrationTest class for end-to-end generation with 4-bit quantized models and processors', 'test batched multi-image generation with AriaForConditionalGeneration using chat templates and padded inputs', 'test the Aria tokenizer integration by comparing slow and fast tokenizers on a multi-modal prompt with image tokens']
```

Usage

```
{'test_AriaImageProcessingTester': 'test the AriaImageProcessingTester class that prepares image processor configurations and test inputs', 'test_AriaImageProcessingTest': 'test the AriaImageProcessingTest class that validates Aria image processing with numpy, PIL, and PyTorch inputs', 'test_image_processor_properties': 'test that AriaImageProcessor has properties like do_convert_rgb, max_image_size, min_image_size, do_normalize, image_mean, image_std, and split_image', 'test_call_numpy': 'test AriaImageProcessor with batched and unbatched numpy array inputs returning correct pixel value shapes', 'test_call_pil': 'test AriaImageProcessor with batched and unbatched PIL image inputs returning correct pixel value shapes', 'test_call_pytorch': 'test AriaImageProcessor with batched and unbatched PyTorch tensor inputs returning correct pixel value shapes', 'test_pad_for_patching': 'test the _pad_for_patching method that pads odd-sized images to target dimensions', 'test_get_num_patches_without_images': 'test the get_number_of_image_patches method that calculates patch counts based on image dimensions and split_image settings'}
```

## File: huggingface_transformers/tests/models/aria/test_modeling_aria.py

Prompts

```
['test the AriaImageProcessingTester class that prepares image processor configurations and test inputs', 'test the AriaImageProcessingTest class that validates Aria image processing with numpy, PIL, and PyTorch inputs', 'test that AriaImageProcessor has properties like do_convert_rgb, max_image_size, min_image_size, do_normalize, image_mean, image_std, and split_image', 'test AriaImageProcessor with batched and unbatched numpy array inputs returning correct pixel value shapes', 'test AriaImageProcessor with batched and unbatched PIL image inputs returning correct pixel value shapes', 'test AriaImageProcessor with batched and unbatched PyTorch tensor inputs returning correct pixel value shapes', 'test the _pad_for_patching method that pads odd-sized images to target dimensions', 'test the get_number_of_image_patches method that calculates patch counts based on image dimensions and split_image settings', 'test the AriaVisionText2TextModelTester class for preparing model configs and inputs with vision and text modalities', 'test the AriaForConditionalGenerationModelTest class for model inference and generation using ModelTesterMixin and GenerationTesterMixin', 'test the AriaForConditionalGenerationIntegrationTest class for end-to-end generation with 4-bit quantized models and processors', 'test batched multi-image generation with AriaForConditionalGeneration using chat templates and padded inputs', 'test the Aria tokenizer integration by comparing slow and fast tokenizers on a multi-modal prompt with image tokens']
```

Usage

```
{'test_aria_model_training': 'test the AriaVisionText2TextModelTester class for preparing model configs and inputs with vision and text modalities', 'test_aria_generation': 'test the AriaForConditionalGenerationModelTest class for model inference and generation using ModelTesterMixin and GenerationTesterMixin', 'test_aria_integration_generation': 'test the AriaForConditionalGenerationIntegrationTest class for end-to-end generation with 4-bit quantized models and processors', 'test_aria_batched_generation': 'test batched multi-image generation with AriaForConditionalGeneration using chat templates and padded inputs', 'test_aria_tokenizer': 'test the Aria tokenizer integration by comparing slow and fast tokenizers on a multi-modal prompt with image tokens'}
```

