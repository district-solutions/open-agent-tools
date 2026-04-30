# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/kosmos2/test_modeling_kosmos2.py

Prompts

```
['create a Kosmos2VisionModelTester with custom patch size, image size, and hidden size for vision model unit tests', 'create a Kosmos2TextModelTester with custom vocab size, seq length, and hidden size for text model unit tests', 'create a Kosmos2ModelTester combining vision and text testers to prepare full model inputs including image_embeds_position_mask', 'test the Kosmos2ModelTest class covering model forward pass, config validation, hidden states output, and generation from inputs_embeds', 'run the Kosmos2ModelIntegrationTest slow tests to verify pretrained kosmos-2 model image captioning and entity grounding on real images', 'test the Kosmos2Processor class handles text, images, and bounding box inputs correctly', 'test the Kosmos2Processor with grounding phrases, bounding boxes, and batched image inputs', 'test loading, saving, and reloading the CLIPImageProcessor from a temporary directory', 'test that max_length and padding kwargs override the default tokenizer settings', 'test passing nested structured kwargs for image processor size customization']
```

Usage

```
{'create_Kosmos2VisionModelTester': 'create a Kosmos2VisionModelTester with custom patch size, image size, and hidden size for vision model unit tests', 'create_Kosmos2TextModelTester': 'create a Kosmos2TextModelTester with custom vocab size, seq length, and hidden size for text model unit tests', 'create_Kosmos2ModelTester': 'create a Kosmos2ModelTester combining vision and text testers to prepare full model inputs including image_embeds_position_mask', 'test_Kosmos2ModelTest': 'test the Kosmos2ModelTest class covering model forward pass, config validation, hidden states output, and generation from inputs_embeds', 'run_Kosmos2ModelIntegrationTest': 'run the Kosmos2ModelIntegrationTest slow tests to verify pretrained kosmos-2 model image captioning and entity grounding on real images'}
```

## File: huggingface_transformers/tests/models/kosmos2/test_processing_kosmos2.py

Prompts

```
['create a Kosmos2VisionModelTester with custom patch size, image size, and hidden size for vision model unit tests', 'create a Kosmos2TextModelTester with custom vocab size, seq length, and hidden size for text model unit tests', 'create a Kosmos2ModelTester combining vision and text testers to prepare full model inputs including image_embeds_position_mask', 'test the Kosmos2ModelTest class covering model forward pass, config validation, hidden states output, and generation from inputs_embeds', 'run the Kosmos2ModelIntegrationTest slow tests to verify pretrained kosmos-2 model image captioning and entity grounding on real images', 'test the Kosmos2Processor class handles text, images, and bounding box inputs correctly', 'test the Kosmos2Processor with grounding phrases, bounding boxes, and batched image inputs', 'test loading, saving, and reloading the CLIPImageProcessor from a temporary directory', 'test that max_length and padding kwargs override the default tokenizer settings', 'test passing nested structured kwargs for image processor size customization']
```

Usage

```
{'test_Kosmos2Processor': 'test the Kosmos2Processor class handles text, images, and bounding box inputs correctly', 'test_full_processor': 'test the Kosmos2Processor with grounding phrases, bounding boxes, and batched image inputs', 'test_image_processor_load_save_reload': 'test loading, saving, and reloading the CLIPImageProcessor from a temporary directory', 'test_kwargs_overrides_default_tokenizer_kwargs': 'test that max_length and padding kwargs override the default tokenizer settings', 'test_structured_kwargs_nested': 'test passing nested structured kwargs for image processor size customization'}
```

