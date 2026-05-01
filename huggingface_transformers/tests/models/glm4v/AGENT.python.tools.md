# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/glm4v/test_image_processing_glm4v.py

Prompts

```
['test the Glm4vImageProcessingTester class to prepare image processor configuration dicts and expected output shapes', 'test the Glm4vImageProcessingTest class by running PIL image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running NumPy array image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running PyTorch tensor image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running 4-channel NumPy image processing tests with custom mean and std', 'test the Glm4vModel and Glm4vForConditionalGeneration classes using the ModelTesterMixin and GenerationTesterMixin', 'test the Glm4vConfig class using the ConfigTester to run common configuration tests', 'test that vision position IDs are built correctly for images and videos in Glm4vModel', 'test that inputs_embeds produces the same output as input_ids for Glm4vModel classes', 'test GLM-4.1V-9B-Thinking model integration with image, video, and text inputs using AutoProcessor', 'test the Glm4vProcessor apply_chat_template method with text and image modalities', 'test the Glm4vProcessor video frame sampling with fps and do_sample_frames arguments', 'test the Glm4vProcessor chat template with batched messages and padding', 'test the Glm4vProcessor apply_chat_template returns input_ids and attention_mask in dict', 'test the Glm4vProcessor raises error when sampling frames from a list of images', 'test the Glm4vVideoProcessor with PIL image inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with numpy array inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with PyTorch tensor inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with nested list inputs where each video is a list of arrays', 'test the Glm4vVideoProcessor frame sampling with video metadata and verify batched and single video encoding']
```

Usage

```
{'test_Glm4vImageProcessingTester': 'test the Glm4vImageProcessingTester class to prepare image processor configuration dicts and expected output shapes', 'test_Glm4vImageProcessingTest_call_pil': 'test the Glm4vImageProcessingTest class by running PIL image processing tests with batched and non-batched inputs', 'test_Glm4vImageProcessingTest_call_numpy': 'test the Glm4vImageProcessingTest class by running NumPy array image processing tests with batched and non-batched inputs', 'test_Glm4vImageProcessingTest_call_pytorch': 'test the Glm4vImageProcessingTest class by running PyTorch tensor image processing tests with batched and non-batched inputs', 'test_Glm4vImageProcessingTest_call_numpy_4_channels': 'test the Glm4vImageProcessingTest class by running 4-channel NumPy image processing tests with custom mean and std'}
```

## File: huggingface_transformers/tests/models/glm4v/test_modeling_glm4v.py

Prompts

```
['test the Glm4vImageProcessingTester class to prepare image processor configuration dicts and expected output shapes', 'test the Glm4vImageProcessingTest class by running PIL image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running NumPy array image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running PyTorch tensor image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running 4-channel NumPy image processing tests with custom mean and std', 'test the Glm4vModel and Glm4vForConditionalGeneration classes using the ModelTesterMixin and GenerationTesterMixin', 'test the Glm4vConfig class using the ConfigTester to run common configuration tests', 'test that vision position IDs are built correctly for images and videos in Glm4vModel', 'test that inputs_embeds produces the same output as input_ids for Glm4vModel classes', 'test GLM-4.1V-9B-Thinking model integration with image, video, and text inputs using AutoProcessor', 'test the Glm4vProcessor apply_chat_template method with text and image modalities', 'test the Glm4vProcessor video frame sampling with fps and do_sample_frames arguments', 'test the Glm4vProcessor chat template with batched messages and padding', 'test the Glm4vProcessor apply_chat_template returns input_ids and attention_mask in dict', 'test the Glm4vProcessor raises error when sampling frames from a list of images', 'test the Glm4vVideoProcessor with PIL image inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with numpy array inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with PyTorch tensor inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with nested list inputs where each video is a list of arrays', 'test the Glm4vVideoProcessor frame sampling with video metadata and verify batched and single video encoding']
```

Usage

```
{'test_glm4v_model': 'test the Glm4vModel and Glm4vForConditionalGeneration classes using the ModelTesterMixin and GenerationTesterMixin', 'test_glm4v_config': 'test the Glm4vConfig class using the ConfigTester to run common configuration tests', 'test_vision_position_ids': 'test that vision position IDs are built correctly for images and videos in Glm4vModel', 'test_glm4v_inputs_embeds': 'test that inputs_embeds produces the same output as input_ids for Glm4vModel classes', 'test_glm4v_integration': 'test GLM-4.1V-9B-Thinking model integration with image, video, and text inputs using AutoProcessor'}
```

## File: huggingface_transformers/tests/models/glm4v/test_processor_glm4v.py

Prompts

```
['test the Glm4vImageProcessingTester class to prepare image processor configuration dicts and expected output shapes', 'test the Glm4vImageProcessingTest class by running PIL image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running NumPy array image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running PyTorch tensor image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running 4-channel NumPy image processing tests with custom mean and std', 'test the Glm4vModel and Glm4vForConditionalGeneration classes using the ModelTesterMixin and GenerationTesterMixin', 'test the Glm4vConfig class using the ConfigTester to run common configuration tests', 'test that vision position IDs are built correctly for images and videos in Glm4vModel', 'test that inputs_embeds produces the same output as input_ids for Glm4vModel classes', 'test GLM-4.1V-9B-Thinking model integration with image, video, and text inputs using AutoProcessor', 'test the Glm4vProcessor apply_chat_template method with text and image modalities', 'test the Glm4vProcessor video frame sampling with fps and do_sample_frames arguments', 'test the Glm4vProcessor chat template with batched messages and padding', 'test the Glm4vProcessor apply_chat_template returns input_ids and attention_mask in dict', 'test the Glm4vProcessor raises error when sampling frames from a list of images', 'test the Glm4vVideoProcessor with PIL image inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with numpy array inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with PyTorch tensor inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with nested list inputs where each video is a list of arrays', 'test the Glm4vVideoProcessor frame sampling with video metadata and verify batched and single video encoding']
```

Usage

```
{'test_glm4v_processor_chat_template': 'test the Glm4vProcessor apply_chat_template method with text and image modalities', 'test_glm4v_processor_video_frame_sampling': 'test the Glm4vProcessor video frame sampling with fps and do_sample_frames arguments', 'test_glm4v_processor_batch_processing': 'test the Glm4vProcessor chat template with batched messages and padding', 'test_glm4v_processor_return_dict': 'test the Glm4vProcessor apply_chat_template returns input_ids and attention_mask in dict', 'test_glm4v_processor_video_input_validation': 'test the Glm4vProcessor raises error when sampling frames from a list of images'}
```

## File: huggingface_transformers/tests/models/glm4v/test_video_processing_glm4v.py

Prompts

```
['test the Glm4vImageProcessingTester class to prepare image processor configuration dicts and expected output shapes', 'test the Glm4vImageProcessingTest class by running PIL image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running NumPy array image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running PyTorch tensor image processing tests with batched and non-batched inputs', 'test the Glm4vImageProcessingTest class by running 4-channel NumPy image processing tests with custom mean and std', 'test the Glm4vModel and Glm4vForConditionalGeneration classes using the ModelTesterMixin and GenerationTesterMixin', 'test the Glm4vConfig class using the ConfigTester to run common configuration tests', 'test that vision position IDs are built correctly for images and videos in Glm4vModel', 'test that inputs_embeds produces the same output as input_ids for Glm4vModel classes', 'test GLM-4.1V-9B-Thinking model integration with image, video, and text inputs using AutoProcessor', 'test the Glm4vProcessor apply_chat_template method with text and image modalities', 'test the Glm4vProcessor video frame sampling with fps and do_sample_frames arguments', 'test the Glm4vProcessor chat template with batched messages and padding', 'test the Glm4vProcessor apply_chat_template returns input_ids and attention_mask in dict', 'test the Glm4vProcessor raises error when sampling frames from a list of images', 'test the Glm4vVideoProcessor with PIL image inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with numpy array inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with PyTorch tensor inputs and verify encoded video output shape', 'test the Glm4vVideoProcessor with nested list inputs where each video is a list of arrays', 'test the Glm4vVideoProcessor frame sampling with video metadata and verify batched and single video encoding']
```

Usage

```
{'test_glm4v_video_processor_pil': 'test the Glm4vVideoProcessor with PIL image inputs and verify encoded video output shape', 'test_glm4v_video_processor_numpy': 'test the Glm4vVideoProcessor with numpy array inputs and verify encoded video output shape', 'test_glm4v_video_processor_pytorch': 'test the Glm4vVideoProcessor with PyTorch tensor inputs and verify encoded video output shape', 'test_glm4v_video_processor_nested_input': 'test the Glm4vVideoProcessor with nested list inputs where each video is a list of arrays', 'test_glm4v_video_processor_sample_frames': 'test the Glm4vVideoProcessor frame sampling with video metadata and verify batched and single video encoding'}
```

