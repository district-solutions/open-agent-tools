# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/qwen3_vl/test_modeling_qwen3_vl.py

Prompts

```
['test the Qwen3VLModel get_rope_index method builds correct 3D vision position ids for images and videos', 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with image inputs and pixel values', 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with video inputs and pixel values', 'test the Qwen3VLTextModel class handles 3D vision position ids with use_cache true and false', 'test the Qwen3VLModel raises ValueError when image token count mismatches pixel values or image_grid_thw', 'test the Qwen3VLVideoProcessor.from_dict method to construct a processor from a configuration dictionary with optional size overrides', 'test the Qwen3VLVideoProcessor with PIL image inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with numpy array inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with PyTorch tensor inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with nested list inputs where each video is a list of numpy arrays and verify correct encoding']
```

Usage

```
{'test_Qwen3VL_vision_position_ids': 'test the Qwen3VLModel get_rope_index method builds correct 3D vision position ids for images and videos', 'test_Qwen3VL_image_forward': 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with image inputs and pixel values', 'test_Qwen3VL_video_forward': 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with video inputs and pixel values', 'test_Qwen3VLText_3d_position_ids': 'test the Qwen3VLTextModel class handles 3D vision position ids with use_cache true and false', 'test_Qwen3VL_mismatching_num_image_tokens': 'test the Qwen3VLModel raises ValueError when image token count mismatches pixel values or image_grid_thw'}
```

## File: huggingface_transformers/tests/models/qwen3_vl/test_video_processing_qwen3_vl.py

Prompts

```
['test the Qwen3VLModel get_rope_index method builds correct 3D vision position ids for images and videos', 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with image inputs and pixel values', 'test the Qwen3VLModel and Qwen3VLForConditionalGeneration classes forward pass with video inputs and pixel values', 'test the Qwen3VLTextModel class handles 3D vision position ids with use_cache true and false', 'test the Qwen3VLModel raises ValueError when image token count mismatches pixel values or image_grid_thw', 'test the Qwen3VLVideoProcessor.from_dict method to construct a processor from a configuration dictionary with optional size overrides', 'test the Qwen3VLVideoProcessor with PIL image inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with numpy array inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with PyTorch tensor inputs and verify encoded output shapes match expected dimensions', 'test the Qwen3VLVideoProcessor with nested list inputs where each video is a list of numpy arrays and verify correct encoding']
```

Usage

```
{'test_video_processor_from_dict_with_kwargs': 'test the Qwen3VLVideoProcessor.from_dict method to construct a processor from a configuration dictionary with optional size overrides', 'test_call_pil': 'test the Qwen3VLVideoProcessor with PIL image inputs and verify encoded output shapes match expected dimensions', 'test_call_numpy': 'test the Qwen3VLVideoProcessor with numpy array inputs and verify encoded output shapes match expected dimensions', 'test_call_pytorch': 'test the Qwen3VLVideoProcessor with PyTorch tensor inputs and verify encoded output shapes match expected dimensions', 'test_nested_input': 'test the Qwen3VLVideoProcessor with nested list inputs where each video is a list of numpy arrays and verify correct encoding'}
```

