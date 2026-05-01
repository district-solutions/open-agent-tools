# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/blip/test_image_processing_blip.py

Prompts

```
['test the BlipImageProcessingTest class to verify image processor properties like do_resize and do_normalize', 'test the BlipImageProcessingTestFourChannels class to verify four channel image processor properties', 'create a BlipImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration', 'use BlipImageProcessingTester prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'call expected_output_image_shape on BlipImageProcessingTester to get the expected channel height and width tuple', 'test the BlipVisionModel forward pass with pixel values and verify output shapes', 'test the BlipTextModel forward pass with input ids and attention mask', 'test the BlipModel multimodal features extraction combining image and text inputs', 'test visual question answering inference using BlipForQuestionAnswering with an image and question', 'test image captioning inference using BlipForConditionalGeneration to generate captions from images', 'test the BlipTextModel forward pass with input_ids and attention_mask inputs', 'create a BlipTextConfig with vocabulary size, hidden size, and number of transformer layers', 'build a BlipTextModel instance from a BlipTextConfig and run inference with input tensors', 'test loading a pretrained BlipTextModel from the Salesforce/blip-vqa-base model hub', 'test BlipTextConfig serialization and deserialization with common configuration attributes']
```

Usage

```
{'test_blip_image_processor_properties': 'test the BlipImageProcessingTest class to verify image processor properties like do_resize and do_normalize', 'test_blip_four_channel_processing': 'test the BlipImageProcessingTestFourChannels class to verify four channel image processor properties', 'prepare_blip_processor_dict': 'create a BlipImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration', 'prepare_blip_image_inputs': 'use BlipImageProcessingTester prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'check_blip_output_shape': 'call expected_output_image_shape on BlipImageProcessingTester to get the expected channel height and width tuple'}
```

## File: huggingface_transformers/tests/models/blip/test_modeling_blip.py

Prompts

```
['test the BlipImageProcessingTest class to verify image processor properties like do_resize and do_normalize', 'test the BlipImageProcessingTestFourChannels class to verify four channel image processor properties', 'create a BlipImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration', 'use BlipImageProcessingTester prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'call expected_output_image_shape on BlipImageProcessingTester to get the expected channel height and width tuple', 'test the BlipVisionModel forward pass with pixel values and verify output shapes', 'test the BlipTextModel forward pass with input ids and attention mask', 'test the BlipModel multimodal features extraction combining image and text inputs', 'test visual question answering inference using BlipForQuestionAnswering with an image and question', 'test image captioning inference using BlipForConditionalGeneration to generate captions from images', 'test the BlipTextModel forward pass with input_ids and attention_mask inputs', 'create a BlipTextConfig with vocabulary size, hidden size, and number of transformer layers', 'build a BlipTextModel instance from a BlipTextConfig and run inference with input tensors', 'test loading a pretrained BlipTextModel from the Salesforce/blip-vqa-base model hub', 'test BlipTextConfig serialization and deserialization with common configuration attributes']
```

Usage

```
{'test_blip_vision_model': 'test the BlipVisionModel forward pass with pixel values and verify output shapes', 'test_blip_text_model': 'test the BlipTextModel forward pass with input ids and attention mask', 'test_blip_model_multimodal': 'test the BlipModel multimodal features extraction combining image and text inputs', 'test_blip_vqa_inference': 'test visual question answering inference using BlipForQuestionAnswering with an image and question', 'test_blip_image_captioning': 'test image captioning inference using BlipForConditionalGeneration to generate captions from images'}
```

## File: huggingface_transformers/tests/models/blip/test_modeling_blip_text.py

Prompts

```
['test the BlipImageProcessingTest class to verify image processor properties like do_resize and do_normalize', 'test the BlipImageProcessingTestFourChannels class to verify four channel image processor properties', 'create a BlipImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration', 'use BlipImageProcessingTester prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'call expected_output_image_shape on BlipImageProcessingTester to get the expected channel height and width tuple', 'test the BlipVisionModel forward pass with pixel values and verify output shapes', 'test the BlipTextModel forward pass with input ids and attention mask', 'test the BlipModel multimodal features extraction combining image and text inputs', 'test visual question answering inference using BlipForQuestionAnswering with an image and question', 'test image captioning inference using BlipForConditionalGeneration to generate captions from images', 'test the BlipTextModel forward pass with input_ids and attention_mask inputs', 'create a BlipTextConfig with vocabulary size, hidden size, and number of transformer layers', 'build a BlipTextModel instance from a BlipTextConfig and run inference with input tensors', 'test loading a pretrained BlipTextModel from the Salesforce/blip-vqa-base model hub', 'test BlipTextConfig serialization and deserialization with common configuration attributes']
```

Usage

```
{'test_model_blip_text': 'test the BlipTextModel forward pass with input_ids and attention_mask inputs', 'create_blip_text_config': 'create a BlipTextConfig with vocabulary size, hidden size, and number of transformer layers', 'build_blip_text_model': 'build a BlipTextModel instance from a BlipTextConfig and run inference with input tensors', 'test_model_from_pretrained': 'test loading a pretrained BlipTextModel from the Salesforce/blip-vqa-base model hub', 'test_config_common': 'test BlipTextConfig serialization and deserialization with common configuration attributes'}
```

