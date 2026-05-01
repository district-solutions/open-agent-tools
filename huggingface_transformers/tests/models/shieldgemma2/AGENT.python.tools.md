# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/shieldgemma2/test_modeling_shieldgemma2.py

Prompts

```
['test ShieldGemma2ForImageClassification integration by loading model with 4-bit quantization and running inference on an image', 'test ShieldGemma2Processor loads and processes images into pytorch tensors with left padding', 'test ShieldGemma2ForImageClassification loaded with BitsAndBytesConfig 4-bit quantization', 'test ShieldGemma2ForImageClassification output returns probabilities with expected shape', 'test tearDown cleanup releases torch device memory and runs garbage collection', 'test that ShieldGemma2Processor saves policy_definitions with 3 entries in processor_config.json', 'test ShieldGemma2Processor processing images against default policies like dangerous and violence', 'test ShieldGemma2Processor processing images against custom policies like cbrne and intellectual property', 'test ShieldGemma2Processor handling multiple images in a single batch input', 'test ShieldGemma2Processor handles text inputs with and without associated vision inputs']
```

Usage

```
{'test_shieldgemma2_integration': 'test ShieldGemma2ForImageClassification integration by loading model with 4-bit quantization and running inference on an image', 'test_shieldgemma2_processor': 'test ShieldGemma2Processor loads and processes images into pytorch tensors with left padding', 'test_shieldgemma2_quantization': 'test ShieldGemma2ForImageClassification loaded with BitsAndBytesConfig 4-bit quantization', 'test_shieldgemma2_output_probabilities': 'test ShieldGemma2ForImageClassification output returns probabilities with expected shape', 'test_shieldgemma2_cleanup': 'test tearDown cleanup releases torch device memory and runs garbage collection'}
```

## File: huggingface_transformers/tests/models/shieldgemma2/test_processing_shieldgemma2.py

Prompts

```
['test ShieldGemma2ForImageClassification integration by loading model with 4-bit quantization and running inference on an image', 'test ShieldGemma2Processor loads and processes images into pytorch tensors with left padding', 'test ShieldGemma2ForImageClassification loaded with BitsAndBytesConfig 4-bit quantization', 'test ShieldGemma2ForImageClassification output returns probabilities with expected shape', 'test tearDown cleanup releases torch device memory and runs garbage collection', 'test that ShieldGemma2Processor saves policy_definitions with 3 entries in processor_config.json', 'test ShieldGemma2Processor processing images against default policies like dangerous and violence', 'test ShieldGemma2Processor processing images against custom policies like cbrne and intellectual property', 'test ShieldGemma2Processor handling multiple images in a single batch input', 'test ShieldGemma2Processor handles text inputs with and without associated vision inputs']
```

Usage

```
{'test_policy_definitions_saved_in_config': 'test that ShieldGemma2Processor saves policy_definitions with 3 entries in processor_config.json', 'test_with_default_policies': 'test ShieldGemma2Processor processing images against default policies like dangerous and violence', 'test_with_custom_policies': 'test ShieldGemma2Processor processing images against custom policies like cbrne and intellectual property', 'test_with_multiple_images': 'test ShieldGemma2Processor handling multiple images in a single batch input', 'test_processor_text_has_no_visual': 'test ShieldGemma2Processor handles text inputs with and without associated vision inputs'}
```

