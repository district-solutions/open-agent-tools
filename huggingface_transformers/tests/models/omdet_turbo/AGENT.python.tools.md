# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/omdet_turbo/test_modeling_omdet_turbo.py

Prompts

```
['test the OmDetTurboModelTester prepare_config_and_inputs method to generate model config and input tensors', 'test the OmDetTurboForObjectDetection model forward pass and verify output tensor shapes', 'test that OmDetTurbo model produces consistent outputs across different batch sizes', 'test OmDetTurbo inference with pretrained model and verify class and coordinate logits', 'test OmDetTurbo batched inference with multiple images and text labels', 'test the OmDetTurboProcessor post_process_grounded_object_detection method to convert raw model outputs into bounding boxes with text labels', 'create an OmDetTurboProcessor instance for image and text tokenization with grounding support', 'generate fake OmDetTurboObjectDetectionOutput tensors for testing decoder logits and class structures', 'test the processor handles tasks_input_ids, classes_input_ids, pixel_values, and pixel_mask input keys', 'test post_process_grounded_object_detection returns correct box shapes, scores, and text labels per image']
```

Usage

```
{'test_OmDetTurboModelTester_prepare_config_and_inputs': 'test the OmDetTurboModelTester prepare_config_and_inputs method to generate model config and input tensors', 'test_OmDetTurboModelTest_object_detection_head': 'test the OmDetTurboForObjectDetection model forward pass and verify output tensor shapes', 'test_OmDetTurboModelTest_batching_equivalence': 'test that OmDetTurbo model produces consistent outputs across different batch sizes', 'test_OmDetTurboModelIntegrationTests_inference': 'test OmDetTurbo inference with pretrained model and verify class and coordinate logits', 'test_OmDetTurboModelIntegrationTests_batched_inference': 'test OmDetTurbo batched inference with multiple images and text labels'}
```

## File: huggingface_transformers/tests/models/omdet_turbo/test_processing_omdet_turbo.py

Prompts

```
['test the OmDetTurboModelTester prepare_config_and_inputs method to generate model config and input tensors', 'test the OmDetTurboForObjectDetection model forward pass and verify output tensor shapes', 'test that OmDetTurbo model produces consistent outputs across different batch sizes', 'test OmDetTurbo inference with pretrained model and verify class and coordinate logits', 'test OmDetTurbo batched inference with multiple images and text labels', 'test the OmDetTurboProcessor post_process_grounded_object_detection method to convert raw model outputs into bounding boxes with text labels', 'create an OmDetTurboProcessor instance for image and text tokenization with grounding support', 'generate fake OmDetTurboObjectDetectionOutput tensors for testing decoder logits and class structures', 'test the processor handles tasks_input_ids, classes_input_ids, pixel_values, and pixel_mask input keys', 'test post_process_grounded_object_detection returns correct box shapes, scores, and text labels per image']
```

Usage

```
{'test_post_process_grounded_object_detection': 'test the OmDetTurboProcessor post_process_grounded_object_detection method to convert raw model outputs into bounding boxes with text labels', 'create_omdet_turbo_processor': 'create an OmDetTurboProcessor instance for image and text tokenization with grounding support', 'generate_fake_model_outputs': 'generate fake OmDetTurboObjectDetectionOutput tensors for testing decoder logits and class structures', 'test_processor_input_keys': 'test the processor handles tasks_input_ids, classes_input_ids, pixel_values, and pixel_mask input keys', 'test_post_process_scores_and_boxes': 'test post_process_grounded_object_detection returns correct box shapes, scores, and text labels per image'}
```

