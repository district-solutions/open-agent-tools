# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pix2struct/test_modeling_pix2struct.py

Prompts

```
['test the Pix2StructVisionModel class with flattened patches and configuration to verify forward pass shapes', 'test the Pix2StructTextModel class with input ids and attention mask to verify logits output shapes', 'test the Pix2StructForConditionalGeneration model with flattened patches and decoder input ids for forward pass', 'test the Pix2StructForConditionalGeneration model generate method with and without cache for output equivalence', 'test Pix2StructForConditionalGeneration inference on image captioning with a stop sign image', 'test the Pix2StructProcessor with varying max_patches values to verify flattened_patches shape', 'test that image processor defaults are preserved when passed through image_kwargs to the processor', 'test that kwargs like max_patches override default image processor settings', 'test the processor with unstructured kwargs including return_tensors, padding, and max_length', 'test the processor with batched image and text inputs using unstructured kwargs']
```

Usage

```
{'test_Pix2StructVisionModel': 'test the Pix2StructVisionModel class with flattened patches and configuration to verify forward pass shapes', 'test_Pix2StructTextModel': 'test the Pix2StructTextModel class with input ids and attention mask to verify logits output shapes', 'test_Pix2StructModel': 'test the Pix2StructForConditionalGeneration model with flattened patches and decoder input ids for forward pass', 'test_Pix2StructModel_generation': 'test the Pix2StructForConditionalGeneration model generate method with and without cache for output equivalence', 'test_Pix2StructIntegration_inference': 'test Pix2StructForConditionalGeneration inference on image captioning with a stop sign image'}
```

## File: huggingface_transformers/tests/models/pix2struct/test_processing_pix2struct.py

Prompts

```
['test the Pix2StructVisionModel class with flattened patches and configuration to verify forward pass shapes', 'test the Pix2StructTextModel class with input ids and attention mask to verify logits output shapes', 'test the Pix2StructForConditionalGeneration model with flattened patches and decoder input ids for forward pass', 'test the Pix2StructForConditionalGeneration model generate method with and without cache for output equivalence', 'test Pix2StructForConditionalGeneration inference on image captioning with a stop sign image', 'test the Pix2StructProcessor with varying max_patches values to verify flattened_patches shape', 'test that image processor defaults are preserved when passed through image_kwargs to the processor', 'test that kwargs like max_patches override default image processor settings', 'test the processor with unstructured kwargs including return_tensors, padding, and max_length', 'test the processor with batched image and text inputs using unstructured kwargs']
```

Usage

```
{'test_processor_max_patches': 'test the Pix2StructProcessor with varying max_patches values to verify flattened_patches shape', 'test_image_processor_defaults': 'test that image processor defaults are preserved when passed through image_kwargs to the processor', 'test_kwargs_overrides_defaults': 'test that kwargs like max_patches override default image processor settings', 'test_unstructured_kwargs': 'test the processor with unstructured kwargs including return_tensors, padding, and max_length', 'test_unstructured_kwargs_batched': 'test the processor with batched image and text inputs using unstructured kwargs'}
```

