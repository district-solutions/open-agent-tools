# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pp_ocrv5_server_det/test_image_processing_pp_ocrv5_server_det.py

Prompts

```
['test the PPOCRV5ServerDet image processor with PyTorch tensor inputs and verify output shape', 'test the PPOCRV5ServerDet image processor with NumPy array inputs and verify output shape', 'test the PPOCRV5ServerDet image processor with PIL image inputs and verify output shape', 'build a configuration dictionary for the PPOCRV5ServerDet image processor with normalization and resize settings', 'compute the expected resized height and width for an image based on limit side length and 32-pixel alignment', 'test the PPOCRV5ServerDetForObjectDetection model forward pass with pixel values and verify output shape', 'test the PPOCRV5ServerDetModel and PPOCRV5ServerDetForObjectDetection hidden states output with output_hidden_states flag', 'test the PPOCRV5ServerDetConfig serialization, deserialization, and common properties', 'run inference on PPOCRV5ServerDet models with float32, float16, and bfloat16 dtypes', 'test pretrained PP-OCRv5 server det model inference with object detection post-processing on a real image']
```

Usage

```
{'test_PPOCRV5ServerDet_pytorch': 'test the PPOCRV5ServerDet image processor with PyTorch tensor inputs and verify output shape', 'test_PPOCRV5ServerDet_numpy': 'test the PPOCRV5ServerDet image processor with NumPy array inputs and verify output shape', 'test_PPOCRV5ServerDet_pil': 'test the PPOCRV5ServerDet image processor with PIL image inputs and verify output shape', 'prepare_image_processor_dict': 'build a configuration dictionary for the PPOCRV5ServerDet image processor with normalization and resize settings', 'get_expected_value': 'compute the expected resized height and width for an image based on limit side length and 32-pixel alignment'}
```

## File: huggingface_transformers/tests/models/pp_ocrv5_server_det/test_modeling_pp_ocrv5_server_det.py

Prompts

```
['test the PPOCRV5ServerDet image processor with PyTorch tensor inputs and verify output shape', 'test the PPOCRV5ServerDet image processor with NumPy array inputs and verify output shape', 'test the PPOCRV5ServerDet image processor with PIL image inputs and verify output shape', 'build a configuration dictionary for the PPOCRV5ServerDet image processor with normalization and resize settings', 'compute the expected resized height and width for an image based on limit side length and 32-pixel alignment', 'test the PPOCRV5ServerDetForObjectDetection model forward pass with pixel values and verify output shape', 'test the PPOCRV5ServerDetModel and PPOCRV5ServerDetForObjectDetection hidden states output with output_hidden_states flag', 'test the PPOCRV5ServerDetConfig serialization, deserialization, and common properties', 'run inference on PPOCRV5ServerDet models with float32, float16, and bfloat16 dtypes', 'test pretrained PP-OCRv5 server det model inference with object detection post-processing on a real image']
```

Usage

```
{'test_pp_ocrv5_server_det_object_detection': 'test the PPOCRV5ServerDetForObjectDetection model forward pass with pixel values and verify output shape', 'test_hidden_states_output': 'test the PPOCRV5ServerDetModel and PPOCRV5ServerDetForObjectDetection hidden states output with output_hidden_states flag', 'test_pp_ocrv5_server_det_config': 'test the PPOCRV5ServerDetConfig serialization, deserialization, and common properties', 'test_inference_with_different_dtypes': 'run inference on PPOCRV5ServerDet models with float32, float16, and bfloat16 dtypes', 'test_inference_object_detection_head': 'test pretrained PP-OCRv5 server det model inference with object detection post-processing on a real image'}
```

