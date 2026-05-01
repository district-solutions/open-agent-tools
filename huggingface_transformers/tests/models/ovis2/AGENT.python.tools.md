# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/ovis2/test_image_processing_ovis2.py

Prompts

```
['test the Ovis2 image processor properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb', 'test equivalence between PIL and torchvision backends when cropping a single image to patches', 'test equivalence between backends when cropping a batched set of images to patches', 'test the crop_image_to_patches method with min_patches, max_patches, and patch_size parameters on PIL and torchvision backends', 'create an Ovis2 image processor configuration dictionary with resize, normalize, pad, and RGB conversion settings', 'test the Ovis2ModelTest class for forward pass, inputs_embeds, and mixin behaviors', 'run slow integration tests for Ovis2ForConditionalGeneration with single and multi-image inputs', 'test batch generation with Ovis2ForConditionalGeneration using different image resolutions', 'build an Ovis2VisionText2TextModelTester config with dummy pixel values and input ids for unit testing', 'test the AutoProcessor pipeline with Ovis2ForConditionalGeneration using chat template and image inputs', 'test the Ovis2Processor chat template with image and text messages using apply_chat_template', 'test the Ovis2Processor to_json_string method verifies processor config serialization and deserialization', 'test the Ovis2Processor apply_chat_template with tokenize flag returns input_ids and attention_mask', 'test the Ovis2Processor chat template is saved as a separate file and loaded correctly', 'test loading Ovis2Processor via AutoProcessor.from_pretrained and applying chat templates to multimodal messages']
```

Usage

```
{'test_ovis2_image_processor_properties': 'test the Ovis2 image processor properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb', 'test_backends_equivalence_crop_to_patches': 'test equivalence between PIL and torchvision backends when cropping a single image to patches', 'test_backends_equivalence_batched_crop_to_patches': 'test equivalence between backends when cropping a batched set of images to patches', 'test_crop_to_patches': 'test the crop_image_to_patches method with min_patches, max_patches, and patch_size parameters on PIL and torchvision backends', 'prepare_ovis2_image_processor_dict': 'create an Ovis2 image processor configuration dictionary with resize, normalize, pad, and RGB conversion settings'}
```

## File: huggingface_transformers/tests/models/ovis2/test_modeling_ovis2.py

Prompts

```
['test the Ovis2 image processor properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb', 'test equivalence between PIL and torchvision backends when cropping a single image to patches', 'test equivalence between backends when cropping a batched set of images to patches', 'test the crop_image_to_patches method with min_patches, max_patches, and patch_size parameters on PIL and torchvision backends', 'create an Ovis2 image processor configuration dictionary with resize, normalize, pad, and RGB conversion settings', 'test the Ovis2ModelTest class for forward pass, inputs_embeds, and mixin behaviors', 'run slow integration tests for Ovis2ForConditionalGeneration with single and multi-image inputs', 'test batch generation with Ovis2ForConditionalGeneration using different image resolutions', 'build an Ovis2VisionText2TextModelTester config with dummy pixel values and input ids for unit testing', 'test the AutoProcessor pipeline with Ovis2ForConditionalGeneration using chat template and image inputs', 'test the Ovis2Processor chat template with image and text messages using apply_chat_template', 'test the Ovis2Processor to_json_string method verifies processor config serialization and deserialization', 'test the Ovis2Processor apply_chat_template with tokenize flag returns input_ids and attention_mask', 'test the Ovis2Processor chat template is saved as a separate file and loaded correctly', 'test loading Ovis2Processor via AutoProcessor.from_pretrained and applying chat templates to multimodal messages']
```

Usage

```
{'test_ovis2_model_forward_pass': 'test the Ovis2ModelTest class for forward pass, inputs_embeds, and mixin behaviors', 'test_ovis2_integration': 'run slow integration tests for Ovis2ForConditionalGeneration with single and multi-image inputs', 'test_ovis2_batch_generation': 'test batch generation with Ovis2ForConditionalGeneration using different image resolutions', 'build_ovis2_model_tester': 'build an Ovis2VisionText2TextModelTester config with dummy pixel values and input ids for unit testing', 'test_ovis2_processor_pipeline': 'test the AutoProcessor pipeline with Ovis2ForConditionalGeneration using chat template and image inputs'}
```

## File: huggingface_transformers/tests/models/ovis2/test_processor_ovis2.py

Prompts

```
['test the Ovis2 image processor properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb', 'test equivalence between PIL and torchvision backends when cropping a single image to patches', 'test equivalence between backends when cropping a batched set of images to patches', 'test the crop_image_to_patches method with min_patches, max_patches, and patch_size parameters on PIL and torchvision backends', 'create an Ovis2 image processor configuration dictionary with resize, normalize, pad, and RGB conversion settings', 'test the Ovis2ModelTest class for forward pass, inputs_embeds, and mixin behaviors', 'run slow integration tests for Ovis2ForConditionalGeneration with single and multi-image inputs', 'test batch generation with Ovis2ForConditionalGeneration using different image resolutions', 'build an Ovis2VisionText2TextModelTester config with dummy pixel values and input ids for unit testing', 'test the AutoProcessor pipeline with Ovis2ForConditionalGeneration using chat template and image inputs', 'test the Ovis2Processor chat template with image and text messages using apply_chat_template', 'test the Ovis2Processor to_json_string method verifies processor config serialization and deserialization', 'test the Ovis2Processor apply_chat_template with tokenize flag returns input_ids and attention_mask', 'test the Ovis2Processor chat template is saved as a separate file and loaded correctly', 'test loading Ovis2Processor via AutoProcessor.from_pretrained and applying chat templates to multimodal messages']
```

Usage

```
{'test_ovis2_processor_chat_template': 'test the Ovis2Processor chat template with image and text messages using apply_chat_template', 'test_ovis2_processor_json_serialization': 'test the Ovis2Processor to_json_string method verifies processor config serialization and deserialization', 'test_ovis2_processor_chat_template_tokenized': 'test the Ovis2Processor apply_chat_template with tokenize flag returns input_ids and attention_mask', 'test_ovis2_processor_chat_template_save': 'test the Ovis2Processor chat template is saved as a separate file and loaded correctly', 'test_ovis2_processor_auto_processor': 'test loading Ovis2Processor via AutoProcessor.from_pretrained and applying chat templates to multimodal messages'}
```

