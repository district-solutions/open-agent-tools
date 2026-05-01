# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/cwm/test_configuration_cwm.py

Prompts

```
['create a CwmConfig instance with default sliding window of 8192 and llama3 rope parameters', 'create a CwmConfig with a custom sliding window size of 4096 tokens', 'create a CwmConfig with custom layer types mixing full and sliding attention layers', 'test that CwmConfig can be serialized to a dictionary and reconstructed from it', 'test that CwmConfig raises validation errors for invalid layer type values or mismatched layer counts', 'test the CwmForCausalLM model by loading facebook/cwm and verifying output logits match expected values', 'test the CWM model sliding window attention with a long sequence exceeding the sliding window size', 'test the CWM model text generation by generating 20 tokens from a chat prompt with thinking enabled', 'review the CwmConfig sliding window and rope_parameters settings used in the CwmModelTester class', 'run the CwmModelTest unit tests for CwmModel and CwmForCausalLM model classes']
```

Usage

```
{'create_cwm_config_with_defaults': 'create a CwmConfig instance with default sliding window of 8192 and llama3 rope parameters', 'create_cwm_config_custom_sliding_window': 'create a CwmConfig with a custom sliding window size of 4096 tokens', 'create_cwm_config_custom_layer_types': 'create a CwmConfig with custom layer types mixing full and sliding attention layers', 'test_cwm_config_serialization': 'test that CwmConfig can be serialized to a dictionary and reconstructed from it', 'test_cwm_config_validation': 'test that CwmConfig raises validation errors for invalid layer type values or mismatched layer counts'}
```

## File: huggingface_transformers/tests/models/cwm/test_modeling_cwm.py

Prompts

```
['create a CwmConfig instance with default sliding window of 8192 and llama3 rope parameters', 'create a CwmConfig with a custom sliding window size of 4096 tokens', 'create a CwmConfig with custom layer types mixing full and sliding attention layers', 'test that CwmConfig can be serialized to a dictionary and reconstructed from it', 'test that CwmConfig raises validation errors for invalid layer type values or mismatched layer counts', 'test the CwmForCausalLM model by loading facebook/cwm and verifying output logits match expected values', 'test the CWM model sliding window attention with a long sequence exceeding the sliding window size', 'test the CWM model text generation by generating 20 tokens from a chat prompt with thinking enabled', 'review the CwmConfig sliding window and rope_parameters settings used in the CwmModelTester class', 'run the CwmModelTest unit tests for CwmModel and CwmForCausalLM model classes']
```

Usage

```
{'test_cwm_model_integration': 'test the CwmForCausalLM model by loading facebook/cwm and verifying output logits match expected values', 'test_cwm_sliding_window': 'test the CWM model sliding window attention with a long sequence exceeding the sliding window size', 'test_cwm_text_generation': 'test the CWM model text generation by generating 20 tokens from a chat prompt with thinking enabled', 'review_cwm_config': 'review the CwmConfig sliding window and rope_parameters settings used in the CwmModelTester class', 'run_cwm_model_tests': 'run the CwmModelTest unit tests for CwmModel and CwmForCausalLM model classes'}
```

