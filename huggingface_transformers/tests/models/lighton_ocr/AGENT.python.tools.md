# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/lighton_ocr/test_modeling_lighton_ocr.py

Prompts

```
['test the LightOnOcrForConditionalGeneration model with vision-text inputs and verify forward pass outputs', 'test the vision projection layer transforms vision embeddings to text hidden space with correct output dimensions', 'test the model can be created and initialized with different spatial_merge_size values of 1, 2, and 4', 'test that model outputs are deterministic and consistent across repeated forward passes with identical inputs', 'test the LightOnOCR model performs OCR on a receipt image and produces output with at least 95% similarity to expected text']
```

Usage

```
{'test_modeling_lighton_ocr': 'test the LightOnOcrForConditionalGeneration model with vision-text inputs and verify forward pass outputs', 'test_vision_projection': 'test the vision projection layer transforms vision embeddings to text hidden space with correct output dimensions', 'test_spatial_merge_size': 'test the model can be created and initialized with different spatial_merge_size values of 1, 2, and 4', 'test_model_outputs_equivalence': 'test that model outputs are deterministic and consistent across repeated forward passes with identical inputs', 'test_lightonocr_ocr_integration': 'test the LightOnOCR model performs OCR on a receipt image and produces output with at least 95% similarity to expected text'}
```

