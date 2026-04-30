# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/ernie4_5_vl_moe/test_processing_ernie4_5_vl_moe.py

Prompts

```
['test the Ernie4_5_VLMoeProcessorTest class that validates the Ernie4_5_VLMoeProcessor functionality including image, video, and tokenizer integration', 'create an Ernie4_5_VLMoeProcessor from pretrained model with custom patch_size and image edge dimensions, then save and reload it', 'test the _get_num_multimodal_tokens helper method that computes image patch counts for varying image sizes', 'test apply_chat_template with text-only, image, and video modalities verifying tokenization, padding, truncation, and return_dict outputs', 'test video frame sampling via apply_chat_template with num_frames, fps, and list-of-frames inputs validating output tensor sizes', 'test the Ernie4_5_VLMoeVideoProcessor.from_dict method to construct a processor from a config dict with optional kwargs overriding size', 'test the Ernie4_5_VLMoeVideoProcessor call with PIL image inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor call with numpy array inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor call with pytorch tensor inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor with nested list inputs where each video is a list of numpy arrays']
```

Usage

```
{'test_Ernie4_5_VLMoeProcessorTest': 'test the Ernie4_5_VLMoeProcessorTest class that validates the Ernie4_5_VLMoeProcessor functionality including image, video, and tokenizer integration', 'create_processor_load_pretrained': 'create an Ernie4_5_VLMoeProcessor from pretrained model with custom patch_size and image edge dimensions, then save and reload it', 'test_get_num_multimodal_tokens': 'test the _get_num_multimodal_tokens helper method that computes image patch counts for varying image sizes', 'test_apply_chat_template': 'test apply_chat_template with text-only, image, and video modalities verifying tokenization, padding, truncation, and return_dict outputs', 'test_video_frame_sampling': 'test video frame sampling via apply_chat_template with num_frames, fps, and list-of-frames inputs validating output tensor sizes'}
```

## File: huggingface_transformers/tests/models/ernie4_5_vl_moe/test_video_processing_ernie4_5_vl_moe.py

Prompts

```
['test the Ernie4_5_VLMoeProcessorTest class that validates the Ernie4_5_VLMoeProcessor functionality including image, video, and tokenizer integration', 'create an Ernie4_5_VLMoeProcessor from pretrained model with custom patch_size and image edge dimensions, then save and reload it', 'test the _get_num_multimodal_tokens helper method that computes image patch counts for varying image sizes', 'test apply_chat_template with text-only, image, and video modalities verifying tokenization, padding, truncation, and return_dict outputs', 'test video frame sampling via apply_chat_template with num_frames, fps, and list-of-frames inputs validating output tensor sizes', 'test the Ernie4_5_VLMoeVideoProcessor.from_dict method to construct a processor from a config dict with optional kwargs overriding size', 'test the Ernie4_5_VLMoeVideoProcessor call with PIL image inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor call with numpy array inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor call with pytorch tensor inputs and video metadata, verifying encoded output shape', 'test the Ernie4_5_VLMoeVideoProcessor with nested list inputs where each video is a list of numpy arrays']
```

Usage

```
{'test_video_processor_from_dict_with_kwargs': 'test the Ernie4_5_VLMoeVideoProcessor.from_dict method to construct a processor from a config dict with optional kwargs overriding size', 'test_call_pil_video_processor': 'test the Ernie4_5_VLMoeVideoProcessor call with PIL image inputs and video metadata, verifying encoded output shape', 'test_call_numpy_video_processor': 'test the Ernie4_5_VLMoeVideoProcessor call with numpy array inputs and video metadata, verifying encoded output shape', 'test_call_pytorch_video_processor': 'test the Ernie4_5_VLMoeVideoProcessor call with pytorch tensor inputs and video metadata, verifying encoded output shape', 'test_nested_input_video_processor': 'test the Ernie4_5_VLMoeVideoProcessor with nested list inputs where each video is a list of numpy arrays'}
```

