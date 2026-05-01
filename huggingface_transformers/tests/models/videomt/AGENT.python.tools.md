# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/videomt/test_modeling_videomt.py

Prompts

```
['test the VideomtForUniversalSegmentation model with config and pixel value inputs for correctness', 'test the VideomtConfig class by creating config instances and verifying common configuration attributes', 'run instance segmentation inference on a preloaded VideoMT model with video frame inputs', 'run semantic segmentation inference on a preloaded VideoMT model and validate output shapes', 'run panoptic segmentation inference on a preloaded VideoMT model and verify segment info results', 'test the VideomtVideoProcessor class properties like do_resize, size, and model_input_names', 'test the VideomtVideoProcessor.from_dict method with override kwargs for size parameter', 'test post_process_semantic_segmentation to produce per-frame segmentation maps from Videomt model outputs', 'test post_process_instance_segmentation to produce per-frame instance masks and segment info from model outputs', 'test post_process_panoptic_segmentation to produce per-frame panoptic masks and segment info from model outputs']
```

Usage

```
{'test_VideomtForUniversalSegmentation_model': 'test the VideomtForUniversalSegmentation model with config and pixel value inputs for correctness', 'test_VideomtConfig': 'test the VideomtConfig class by creating config instances and verifying common configuration attributes', 'test_instance_segmentation_inference': 'run instance segmentation inference on a preloaded VideoMT model with video frame inputs', 'test_semantic_segmentation_inference': 'run semantic segmentation inference on a preloaded VideoMT model and validate output shapes', 'test_panoptic_segmentation_inference': 'run panoptic segmentation inference on a preloaded VideoMT model and verify segment info results'}
```

## File: huggingface_transformers/tests/models/videomt/test_video_processing_videomt.py

Prompts

```
['test the VideomtForUniversalSegmentation model with config and pixel value inputs for correctness', 'test the VideomtConfig class by creating config instances and verifying common configuration attributes', 'run instance segmentation inference on a preloaded VideoMT model with video frame inputs', 'run semantic segmentation inference on a preloaded VideoMT model and validate output shapes', 'run panoptic segmentation inference on a preloaded VideoMT model and verify segment info results', 'test the VideomtVideoProcessor class properties like do_resize, size, and model_input_names', 'test the VideomtVideoProcessor.from_dict method with override kwargs for size parameter', 'test post_process_semantic_segmentation to produce per-frame segmentation maps from Videomt model outputs', 'test post_process_instance_segmentation to produce per-frame instance masks and segment info from model outputs', 'test post_process_panoptic_segmentation to produce per-frame panoptic masks and segment info from model outputs']
```

Usage

```
{'test_videomt_video_processor_properties': 'test the VideomtVideoProcessor class properties like do_resize, size, and model_input_names', 'test_videomt_from_dict_with_kwargs': 'test the VideomtVideoProcessor.from_dict method with override kwargs for size parameter', 'test_post_process_semantic_segmentation': 'test post_process_semantic_segmentation to produce per-frame segmentation maps from Videomt model outputs', 'test_post_process_instance_segmentation': 'test post_process_instance_segmentation to produce per-frame instance masks and segment info from model outputs', 'test_post_process_panoptic_segmentation': 'test post_process_panoptic_segmentation to produce per-frame panoptic masks and segment info from model outputs'}
```

