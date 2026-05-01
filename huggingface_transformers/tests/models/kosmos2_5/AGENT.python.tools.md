# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/kosmos2_5/test_image_processing_kosmos2_5.py

Prompts

```
['test the Kosmos2_5ImageProcessingTest class verifies PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessingTest class verifies batched PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessor with PIL images validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with numpy array inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with PyTorch tensor inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5Model test class with vision and text model integration', 'test the Kosmos2_5Config configuration class using ConfigTester', 'test the Kosmos2_5VisionModelTester that prepares vision config and flattened patches', 'test the Kosmos2_5TextModelTester that prepares text config and input ids with attention masks', 'test the Kosmos2_5ModelIntegrationTest class with eager, sdpa, and flash attention inference on receipt OCR', 'test that Kosmos2_5ImageProcessor can be loaded from Hub, saved, and reloaded with identical config', 'test that Kosmos2_5Processor returns correct input keys including flattened_patches and attention_mask', 'test that runtime kwargs like max_patches override default image processor settings in Kosmos2_5Processor', 'test that nested structured kwargs like images_kwargs and text_kwargs work with Kosmos2_5Processor', 'test the full Kosmos2_5Processor pipeline with real images and text tokens including batched inputs']
```

Usage

```
{'test_image_processor_backends_equivalence': 'test the Kosmos2_5ImageProcessingTest class verifies PIL and torchvision backends produce equivalent flattened_patches outputs', 'test_image_processor_backends_equivalence_batched': 'test the Kosmos2_5ImageProcessingTest class verifies batched PIL and torchvision backends produce equivalent flattened_patches outputs', 'test_image_processor_call_pil': 'test the Kosmos2_5ImageProcessor with PIL images validates output shape for single and batched inputs across max_patches values', 'test_image_processor_call_numpy': 'test the Kosmos2_5ImageProcessor with numpy array inputs validates output shape for single and batched inputs across max_patches values', 'test_image_processor_call_pytorch': 'test the Kosmos2_5ImageProcessor with PyTorch tensor inputs validates output shape for single and batched inputs across max_patches values'}
```

## File: huggingface_transformers/tests/models/kosmos2_5/test_modeling_kosmos2_5.py

Prompts

```
['test the Kosmos2_5ImageProcessingTest class verifies PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessingTest class verifies batched PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessor with PIL images validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with numpy array inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with PyTorch tensor inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5Model test class with vision and text model integration', 'test the Kosmos2_5Config configuration class using ConfigTester', 'test the Kosmos2_5VisionModelTester that prepares vision config and flattened patches', 'test the Kosmos2_5TextModelTester that prepares text config and input ids with attention masks', 'test the Kosmos2_5ModelIntegrationTest class with eager, sdpa, and flash attention inference on receipt OCR', 'test that Kosmos2_5ImageProcessor can be loaded from Hub, saved, and reloaded with identical config', 'test that Kosmos2_5Processor returns correct input keys including flattened_patches and attention_mask', 'test that runtime kwargs like max_patches override default image processor settings in Kosmos2_5Processor', 'test that nested structured kwargs like images_kwargs and text_kwargs work with Kosmos2_5Processor', 'test the full Kosmos2_5Processor pipeline with real images and text tokens including batched inputs']
```

Usage

```
{'test_Kosmos2_5Model': 'test the Kosmos2_5Model test class with vision and text model integration', 'test_Kosmos2_5Config': 'test the Kosmos2_5Config configuration class using ConfigTester', 'test_Kosmos2_5VisionModel': 'test the Kosmos2_5VisionModelTester that prepares vision config and flattened patches', 'test_Kosmos2_5TextModel': 'test the Kosmos2_5TextModelTester that prepares text config and input ids with attention masks', 'test_Kosmos2_5ModelIntegration': 'test the Kosmos2_5ModelIntegrationTest class with eager, sdpa, and flash attention inference on receipt OCR'}
```

## File: huggingface_transformers/tests/models/kosmos2_5/test_processor_kosmos2_5.py

Prompts

```
['test the Kosmos2_5ImageProcessingTest class verifies PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessingTest class verifies batched PIL and torchvision backends produce equivalent flattened_patches outputs', 'test the Kosmos2_5ImageProcessor with PIL images validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with numpy array inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5ImageProcessor with PyTorch tensor inputs validates output shape for single and batched inputs across max_patches values', 'test the Kosmos2_5Model test class with vision and text model integration', 'test the Kosmos2_5Config configuration class using ConfigTester', 'test the Kosmos2_5VisionModelTester that prepares vision config and flattened patches', 'test the Kosmos2_5TextModelTester that prepares text config and input ids with attention masks', 'test the Kosmos2_5ModelIntegrationTest class with eager, sdpa, and flash attention inference on receipt OCR', 'test that Kosmos2_5ImageProcessor can be loaded from Hub, saved, and reloaded with identical config', 'test that Kosmos2_5Processor returns correct input keys including flattened_patches and attention_mask', 'test that runtime kwargs like max_patches override default image processor settings in Kosmos2_5Processor', 'test that nested structured kwargs like images_kwargs and text_kwargs work with Kosmos2_5Processor', 'test the full Kosmos2_5Processor pipeline with real images and text tokens including batched inputs']
```

Usage

```
{'test_processor_load_save_reload': 'test that Kosmos2_5ImageProcessor can be loaded from Hub, saved, and reloaded with identical config', 'test_processor_model_input_names': 'test that Kosmos2_5Processor returns correct input keys including flattened_patches and attention_mask', 'test_processor_kwargs_override': 'test that runtime kwargs like max_patches override default image processor settings in Kosmos2_5Processor', 'test_processor_structured_kwargs': 'test that nested structured kwargs like images_kwargs and text_kwargs work with Kosmos2_5Processor', 'test_processor_full_pipeline': 'test the full Kosmos2_5Processor pipeline with real images and text tokens including batched inputs'}
```

