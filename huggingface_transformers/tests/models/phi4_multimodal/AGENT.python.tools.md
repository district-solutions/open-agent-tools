# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/phi4_multimodal/test_feature_extraction_phi4_multimodal.py

Prompts

```
['create a Phi4MultimodalFeatureExtractor instance with custom audio processing parameters', 'test saving and loading a Phi4MultimodalFeatureExtractor from a pretrained directory', 'test serializing and deserializing a Phi4MultimodalFeatureExtractor via JSON file', 'test overriding feature_size when loading a Phi4MultimodalFeatureExtractor from pretrained', 'test batched and unbatched audio input processing with numpy and torch tensors', 'test the Phi4MultimodalImageProcessingTest class verifies image processor attributes like do_resize, size, and normalize', 'test the Phi4MultimodalImageProcessor with PIL image inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with numpy array inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with PyTorch tensor inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor casting to different dtypes and devices including float16 and bfloat16', 'test the Phi4MultimodalModelTester class that generates mock configs and tensor inputs for unit testing', 'test the Phi4MultimodalModelTest class mixing ModelTesterMixin and GenerationTesterMixin for regression tests', 'test the Phi4MultimodalIntegrationTest class with slow integration tests against real model checkpoints', 'create a Phi4MultimodalConfig instance from Phi4MultimodalModelTester.get_config with vision and audio sub-configs', 'create mock tensor inputs including input_ids, image_pixel_values, and audio_input_features for Phi4MultimodalModelTester']
```

Usage

```
{'create_feature_extractor_phi4_multimodal': 'create a Phi4MultimodalFeatureExtractor instance with custom audio processing parameters', 'test_feat_extract_save_pretrained': 'test saving and loading a Phi4MultimodalFeatureExtractor from a pretrained directory', 'test_feat_extract_to_json_file': 'test serializing and deserializing a Phi4MultimodalFeatureExtractor via JSON file', 'test_feat_extract_from_pretrained_kwargs': 'test overriding feature_size when loading a Phi4MultimodalFeatureExtractor from pretrained', 'test_feature_extractor_call': 'test batched and unbatched audio input processing with numpy and torch tensors'}
```

## File: huggingface_transformers/tests/models/phi4_multimodal/test_image_processing_phi4_multimodal.py

Prompts

```
['create a Phi4MultimodalFeatureExtractor instance with custom audio processing parameters', 'test saving and loading a Phi4MultimodalFeatureExtractor from a pretrained directory', 'test serializing and deserializing a Phi4MultimodalFeatureExtractor via JSON file', 'test overriding feature_size when loading a Phi4MultimodalFeatureExtractor from pretrained', 'test batched and unbatched audio input processing with numpy and torch tensors', 'test the Phi4MultimodalImageProcessingTest class verifies image processor attributes like do_resize, size, and normalize', 'test the Phi4MultimodalImageProcessor with PIL image inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with numpy array inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with PyTorch tensor inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor casting to different dtypes and devices including float16 and bfloat16', 'test the Phi4MultimodalModelTester class that generates mock configs and tensor inputs for unit testing', 'test the Phi4MultimodalModelTest class mixing ModelTesterMixin and GenerationTesterMixin for regression tests', 'test the Phi4MultimodalIntegrationTest class with slow integration tests against real model checkpoints', 'create a Phi4MultimodalConfig instance from Phi4MultimodalModelTester.get_config with vision and audio sub-configs', 'create mock tensor inputs including input_ids, image_pixel_values, and audio_input_features for Phi4MultimodalModelTester']
```

Usage

```
{'test_image_processing_properties': 'test the Phi4MultimodalImageProcessingTest class verifies image processor attributes like do_resize, size, and normalize', 'test_call_pil': 'test the Phi4MultimodalImageProcessor with PIL image inputs and verify encoded output shapes for batched and unbatched cases', 'test_call_numpy': 'test the Phi4MultimodalImageProcessor with numpy array inputs and verify encoded output shapes for batched and unbatched cases', 'test_call_pytorch': 'test the Phi4MultimodalImageProcessor with PyTorch tensor inputs and verify encoded output shapes for batched and unbatched cases', 'test_cast_dtype_device': 'test the Phi4MultimodalImageProcessor casting to different dtypes and devices including float16 and bfloat16'}
```

## File: huggingface_transformers/tests/models/phi4_multimodal/test_modeling_phi4_multimodal.py

Prompts

```
['create a Phi4MultimodalFeatureExtractor instance with custom audio processing parameters', 'test saving and loading a Phi4MultimodalFeatureExtractor from a pretrained directory', 'test serializing and deserializing a Phi4MultimodalFeatureExtractor via JSON file', 'test overriding feature_size when loading a Phi4MultimodalFeatureExtractor from pretrained', 'test batched and unbatched audio input processing with numpy and torch tensors', 'test the Phi4MultimodalImageProcessingTest class verifies image processor attributes like do_resize, size, and normalize', 'test the Phi4MultimodalImageProcessor with PIL image inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with numpy array inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor with PyTorch tensor inputs and verify encoded output shapes for batched and unbatched cases', 'test the Phi4MultimodalImageProcessor casting to different dtypes and devices including float16 and bfloat16', 'test the Phi4MultimodalModelTester class that generates mock configs and tensor inputs for unit testing', 'test the Phi4MultimodalModelTest class mixing ModelTesterMixin and GenerationTesterMixin for regression tests', 'test the Phi4MultimodalIntegrationTest class with slow integration tests against real model checkpoints', 'create a Phi4MultimodalConfig instance from Phi4MultimodalModelTester.get_config with vision and audio sub-configs', 'create mock tensor inputs including input_ids, image_pixel_values, and audio_input_features for Phi4MultimodalModelTester']
```

Usage

```
{'test_Phi4MultimodalModelTester': 'test the Phi4MultimodalModelTester class that generates mock configs and tensor inputs for unit testing', 'test_Phi4MultimodalModelTest': 'test the Phi4MultimodalModelTest class mixing ModelTesterMixin and GenerationTesterMixin for regression tests', 'test_Phi4MultimodalIntegrationTest': 'test the Phi4MultimodalIntegrationTest class with slow integration tests against real model checkpoints', 'create_Phi4MultimodalModelTester_get_config': 'create a Phi4MultimodalConfig instance from Phi4MultimodalModelTester.get_config with vision and audio sub-configs', 'create_Phi4MultimodalModelTester_prepare_config_and_inputs': 'create mock tensor inputs including input_ids, image_pixel_values, and audio_input_features for Phi4MultimodalModelTester'}
```

