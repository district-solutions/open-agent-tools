# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/instructblipvideo/test_modeling_instructblipvideo.py

Prompts

```
['test the InstructBlipVideoVisionModel class and its forward pass with pixel values', 'test the InstructBlipVideoQFormerModelTester class and QFormer config generation', 'test the InstructBlipVideoForConditionalGeneration model with vision, qformer, and text inputs', 'test SDPA and eager attention implementation dispatch on composite InstructBlipVideo model sub-configs', 'test loading InstructBlipVideoForConditionalGeneration and InstructBlipVideoVisionModel from pretrained weights', 'test the InstructBlipVideoProcessor class is correctly assigned to processor_class attribute', 'test _setup_tokenizer returns a tokenizer from hf-internal-testing/tiny-random-GPT2Model', 'test _setup_qformer_tokenizer returns a qformer tokenizer from hf-internal-testing/tiny-random-bert', 'test prepare_processor_dict returns a dict with num_query_tokens set to 1', 'test processor_with_multiple_inputs is skipped because InstructBlipVideoProcessor takes images instead of videos', 'test the InstructBlipVideoVideoVideoProcessor class properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb attributes', 'test InstructBlipVideoVideoProcessor.from_dict method with default kwargs and overridden size parameter', 'create an InstructBlipVideoVideoProcessingTester instance with configurable batch_size, num_frames, num_channels, resolution range, and preprocessing options', 'build an InstructBlipVideoVideoProcessor from a configuration dictionary containing do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb settings', 'prepare test video inputs with configurable batch_size, num_frames, num_channels, min/max resolution, and equal_resolution flag']
```

Usage

```
{'test_instructblip_video_vision_model': 'test the InstructBlipVideoVisionModel class and its forward pass with pixel values', 'test_instructblip_video_qformer_model': 'test the InstructBlipVideoQFormerModelTester class and QFormer config generation', 'test_instructblip_video_conditional_generation': 'test the InstructBlipVideoForConditionalGeneration model with vision, qformer, and text inputs', 'test_instructblip_video_sdpa_dispatch': 'test SDPA and eager attention implementation dispatch on composite InstructBlipVideo model sub-configs', 'test_instructblip_video_from_pretrained': 'test loading InstructBlipVideoForConditionalGeneration and InstructBlipVideoVisionModel from pretrained weights'}
```

## File: huggingface_transformers/tests/models/instructblipvideo/test_processing_instructblipvideo.py

Prompts

```
['test the InstructBlipVideoVisionModel class and its forward pass with pixel values', 'test the InstructBlipVideoQFormerModelTester class and QFormer config generation', 'test the InstructBlipVideoForConditionalGeneration model with vision, qformer, and text inputs', 'test SDPA and eager attention implementation dispatch on composite InstructBlipVideo model sub-configs', 'test loading InstructBlipVideoForConditionalGeneration and InstructBlipVideoVisionModel from pretrained weights', 'test the InstructBlipVideoProcessor class is correctly assigned to processor_class attribute', 'test _setup_tokenizer returns a tokenizer from hf-internal-testing/tiny-random-GPT2Model', 'test _setup_qformer_tokenizer returns a qformer tokenizer from hf-internal-testing/tiny-random-bert', 'test prepare_processor_dict returns a dict with num_query_tokens set to 1', 'test processor_with_multiple_inputs is skipped because InstructBlipVideoProcessor takes images instead of videos', 'test the InstructBlipVideoVideoVideoProcessor class properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb attributes', 'test InstructBlipVideoVideoProcessor.from_dict method with default kwargs and overridden size parameter', 'create an InstructBlipVideoVideoProcessingTester instance with configurable batch_size, num_frames, num_channels, resolution range, and preprocessing options', 'build an InstructBlipVideoVideoProcessor from a configuration dictionary containing do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb settings', 'prepare test video inputs with configurable batch_size, num_frames, num_channels, min/max resolution, and equal_resolution flag']
```

Usage

```
{'test_processor_class': 'test the InstructBlipVideoProcessor class is correctly assigned to processor_class attribute', 'test_setup_tokenizer': 'test _setup_tokenizer returns a tokenizer from hf-internal-testing/tiny-random-GPT2Model', 'test_setup_qformer_tokenizer': 'test _setup_qformer_tokenizer returns a qformer tokenizer from hf-internal-testing/tiny-random-bert', 'test_prepare_processor_dict': 'test prepare_processor_dict returns a dict with num_query_tokens set to 1', 'test_processor_with_multiple_inputs': 'test processor_with_multiple_inputs is skipped because InstructBlipVideoProcessor takes images instead of videos'}
```

## File: huggingface_transformers/tests/models/instructblipvideo/test_video_processing_instructblipvideo.py

Prompts

```
['test the InstructBlipVideoVisionModel class and its forward pass with pixel values', 'test the InstructBlipVideoQFormerModelTester class and QFormer config generation', 'test the InstructBlipVideoForConditionalGeneration model with vision, qformer, and text inputs', 'test SDPA and eager attention implementation dispatch on composite InstructBlipVideo model sub-configs', 'test loading InstructBlipVideoForConditionalGeneration and InstructBlipVideoVisionModel from pretrained weights', 'test the InstructBlipVideoProcessor class is correctly assigned to processor_class attribute', 'test _setup_tokenizer returns a tokenizer from hf-internal-testing/tiny-random-GPT2Model', 'test _setup_qformer_tokenizer returns a qformer tokenizer from hf-internal-testing/tiny-random-bert', 'test prepare_processor_dict returns a dict with num_query_tokens set to 1', 'test processor_with_multiple_inputs is skipped because InstructBlipVideoProcessor takes images instead of videos', 'test the InstructBlipVideoVideoVideoProcessor class properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb attributes', 'test InstructBlipVideoVideoProcessor.from_dict method with default kwargs and overridden size parameter', 'create an InstructBlipVideoVideoProcessingTester instance with configurable batch_size, num_frames, num_channels, resolution range, and preprocessing options', 'build an InstructBlipVideoVideoProcessor from a configuration dictionary containing do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb settings', 'prepare test video inputs with configurable batch_size, num_frames, num_channels, min/max resolution, and equal_resolution flag']
```

Usage

```
{'test_instructblip_video_processor_properties': 'test the InstructBlipVideoVideoVideoProcessor class properties including do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb attributes', 'test_video_processor_from_dict_with_kwargs': 'test InstructBlipVideoVideoProcessor.from_dict method with default kwargs and overridden size parameter', 'create_video_processor_tester': 'create an InstructBlipVideoVideoProcessingTester instance with configurable batch_size, num_frames, num_channels, resolution range, and preprocessing options', 'build_video_processor_from_config_dict': 'build an InstructBlipVideoVideoProcessor from a configuration dictionary containing do_resize, size, do_normalize, image_mean, image_std, and do_convert_rgb settings', 'prepare_video_inputs_for_testing': 'prepare test video inputs with configurable batch_size, num_frames, num_channels, min/max resolution, and equal_resolution flag'}
```

