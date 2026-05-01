# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/donut/test_image_processing_donut.py

Prompts

```
['test the DonutImageProcessor class has all expected image processing attributes', 'test creating DonutImageProcessor from a config dict with overriding kwargs', 'test preprocessing images with DonutImageProcessor using custom size and return_tensors', 'test calling DonutImageProcessor on PIL images and verifying output shape', 'test calling DonutImageProcessor on numpy arrays and verifying output shape', 'test the DonutSwinModelTester to prepare config and pixel values inputs for model testing', 'test the DonutSwinModel forward pass and verify output hidden state shape matches expected dimensions', 'test the DonutSwinForImageClassification model forward pass and verify logits shape for RGB and grayscale images', 'test the DonutSwin model attention outputs by enabling output attentions and verifying attention tensor shapes', 'test the DonutSwin model hidden states output and reshaped hidden states for all model classes', 'test the DonutProcessor token2json method to convert a token sequence into a structured JSON object']
```

Usage

```
{'test_DonutImageProcessor_properties': 'test the DonutImageProcessor class has all expected image processing attributes', 'test_DonutImageProcessor_from_dict': 'test creating DonutImageProcessor from a config dict with overriding kwargs', 'test_DonutImageProcessor_preprocess': 'test preprocessing images with DonutImageProcessor using custom size and return_tensors', 'test_DonutImageProcessor_call_pil': 'test calling DonutImageProcessor on PIL images and verifying output shape', 'test_DonutImageProcessor_call_numpy': 'test calling DonutImageProcessor on numpy arrays and verifying output shape'}
```

## File: huggingface_transformers/tests/models/donut/test_modeling_donut_swin.py

Prompts

```
['test the DonutImageProcessor class has all expected image processing attributes', 'test creating DonutImageProcessor from a config dict with overriding kwargs', 'test preprocessing images with DonutImageProcessor using custom size and return_tensors', 'test calling DonutImageProcessor on PIL images and verifying output shape', 'test calling DonutImageProcessor on numpy arrays and verifying output shape', 'test the DonutSwinModelTester to prepare config and pixel values inputs for model testing', 'test the DonutSwinModel forward pass and verify output hidden state shape matches expected dimensions', 'test the DonutSwinForImageClassification model forward pass and verify logits shape for RGB and grayscale images', 'test the DonutSwin model attention outputs by enabling output attentions and verifying attention tensor shapes', 'test the DonutSwin model hidden states output and reshaped hidden states for all model classes', 'test the DonutProcessor token2json method to convert a token sequence into a structured JSON object']
```

Usage

```
{'test_DonutSwinModelTester_prepare_config_and_inputs': 'test the DonutSwinModelTester to prepare config and pixel values inputs for model testing', 'test_DonutSwinModelTester_create_and_check_model': 'test the DonutSwinModel forward pass and verify output hidden state shape matches expected dimensions', 'test_DonutSwinModelTester_create_and_check_for_image_classification': 'test the DonutSwinForImageClassification model forward pass and verify logits shape for RGB and grayscale images', 'test_DonutSwinModelTest_test_attention_outputs': 'test the DonutSwin model attention outputs by enabling output attentions and verifying attention tensor shapes', 'test_DonutSwinModelTest_test_hidden_states_output': 'test the DonutSwin model hidden states output and reshaped hidden states for all model classes'}
```

## File: huggingface_transformers/tests/models/donut/test_processing_donut.py

Prompts

```
['test the DonutImageProcessor class has all expected image processing attributes', 'test creating DonutImageProcessor from a config dict with overriding kwargs', 'test preprocessing images with DonutImageProcessor using custom size and return_tensors', 'test calling DonutImageProcessor on PIL images and verifying output shape', 'test calling DonutImageProcessor on numpy arrays and verifying output shape', 'test the DonutSwinModelTester to prepare config and pixel values inputs for model testing', 'test the DonutSwinModel forward pass and verify output hidden state shape matches expected dimensions', 'test the DonutSwinForImageClassification model forward pass and verify logits shape for RGB and grayscale images', 'test the DonutSwin model attention outputs by enabling output attentions and verifying attention tensor shapes', 'test the DonutSwin model hidden states output and reshaped hidden states for all model classes', 'test the DonutProcessor token2json method to convert a token sequence into a structured JSON object']
```

Usage

```
{'test_token2json': 'test the DonutProcessor token2json method to convert a token sequence into a structured JSON object'}
```

