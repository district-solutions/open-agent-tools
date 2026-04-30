# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/cohere/test_modeling_cohere.py

Prompts

```
['test CohereModel forward pass with input_ids and attention_mask returning last_hidden_state', 'test CohereConfig initialization and common configuration attributes', 'test CohereModelTester prepare_config_and_inputs and create_and_check_model methods', 'test CohereForCausalLM generation with model_split_percents for CPU offload and batching', 'test CohereForCausalLM 4-bit batched inference with bitsandbytes and multi-GPU device_map', 'test the CohereTokenizationTest class which verifies Cohere tokenizer behavior against expected tokens and decoded text', 'test the encodings from sample data by asserting computed tokens match target token lists for input sentences', 'test the tokenization for tool use by applying the tool use template with conversation and tool definitions', 'test the tokenization for grounded generation by applying the grounded generation template with conversation and documents', 'test the add_prefix_space fast tokenizer behavior by comparing tokenized output with and without prefix space']
```

Usage

```
{'test_cohere_model_forward': 'test CohereModel forward pass with input_ids and attention_mask returning last_hidden_state', 'test_cohere_config': 'test CohereConfig initialization and common configuration attributes', 'test_cohere_model_tester': 'test CohereModelTester prepare_config_and_inputs and create_and_check_model methods', 'test_cohere_generation': 'test CohereForCausalLM generation with model_split_percents for CPU offload and batching', 'test_cohere_integration_4bit': 'test CohereForCausalLM 4-bit batched inference with bitsandbytes and multi-GPU device_map'}
```

## File: huggingface_transformers/tests/models/cohere/test_tokenization_cohere.py

Prompts

```
['test CohereModel forward pass with input_ids and attention_mask returning last_hidden_state', 'test CohereConfig initialization and common configuration attributes', 'test CohereModelTester prepare_config_and_inputs and create_and_check_model methods', 'test CohereForCausalLM generation with model_split_percents for CPU offload and batching', 'test CohereForCausalLM 4-bit batched inference with bitsandbytes and multi-GPU device_map', 'test the CohereTokenizationTest class which verifies Cohere tokenizer behavior against expected tokens and decoded text', 'test the encodings from sample data by asserting computed tokens match target token lists for input sentences', 'test the tokenization for tool use by applying the tool use template with conversation and tool definitions', 'test the tokenization for grounded generation by applying the grounded generation template with conversation and documents', 'test the add_prefix_space fast tokenizer behavior by comparing tokenized output with and without prefix space']
```

Usage

```
{'test_tokenization_cohere': 'test the CohereTokenizationTest class which verifies Cohere tokenizer behavior against expected tokens and decoded text', 'test_encodings_from_sample_data': 'test the encodings from sample data by asserting computed tokens match target token lists for input sentences', 'test_tokenization_for_tool_use': 'test the tokenization for tool use by applying the tool use template with conversation and tool definitions', 'test_tokenization_for_grounded_generation': 'test the tokenization for grounded generation by applying the grounded generation template with conversation and documents', 'test_add_prefix_space_fast': 'test the add_prefix_space fast tokenizer behavior by comparing tokenized output with and without prefix space'}
```

