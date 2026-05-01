# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/cpmant/test_modeling_cpmant.py

Prompts

```
['test the CpmAntModel forward pass and verify hidden_states shape matches expected dimensions', 'test the CpmAntForCausalLM forward pass and verify logits shape includes prompt_types times prompt_length', 'create a CpmAntConfig with vocab_size, hidden_size, num_hidden_layers, and position bias parameters', 'test CpmAntForCausalLM text generation with single and batch inputs using tokenizer and model.generate', 'test CpmAntModel and CpmAntForCausalLM inference on Chinese text and verify output logits match expected slices', 'test the CPMAntTokenizationTest class to verify CpmAntTokenizer tokenization with rjieba', 'test the pre_tokenization method to tokenize Chinese text and convert tokens to IDs', 'review the CpmAntTokenizer usage for tokenizing Chinese text with rjieba segmentation', 'test loading CpmAntTokenizer from pretrained openbmb/cpm-ant-10b model checkpoint', 'test the tokenizer decode method to reconstruct text from token IDs']
```

Usage

```
{'test_cpmant_model': 'test the CpmAntModel forward pass and verify hidden_states shape matches expected dimensions', 'test_cpmant_lm_head_model': 'test the CpmAntForCausalLM forward pass and verify logits shape includes prompt_types times prompt_length', 'create_cpmant_config': 'create a CpmAntConfig with vocab_size, hidden_size, num_hidden_layers, and position bias parameters', 'test_cpmant_generation': 'test CpmAntForCausalLM text generation with single and batch inputs using tokenizer and model.generate', 'test_cpmant_inference': 'test CpmAntModel and CpmAntForCausalLM inference on Chinese text and verify output logits match expected slices'}
```

## File: huggingface_transformers/tests/models/cpmant/test_tokenization_cpmant.py

Prompts

```
['test the CpmAntModel forward pass and verify hidden_states shape matches expected dimensions', 'test the CpmAntForCausalLM forward pass and verify logits shape includes prompt_types times prompt_length', 'create a CpmAntConfig with vocab_size, hidden_size, num_hidden_layers, and position bias parameters', 'test CpmAntForCausalLM text generation with single and batch inputs using tokenizer and model.generate', 'test CpmAntModel and CpmAntForCausalLM inference on Chinese text and verify output logits match expected slices', 'test the CPMAntTokenizationTest class to verify CpmAntTokenizer tokenization with rjieba', 'test the pre_tokenization method to tokenize Chinese text and convert tokens to IDs', 'review the CpmAntTokenizer usage for tokenizing Chinese text with rjieba segmentation', 'test loading CpmAntTokenizer from pretrained openbmb/cpm-ant-10b model checkpoint', 'test the tokenizer decode method to reconstruct text from token IDs']
```

Usage

```
{'test_CPMAntTokenizationTest': 'test the CPMAntTokenizationTest class to verify CpmAntTokenizer tokenization with rjieba', 'test_pre_tokenization': 'test the pre_tokenization method to tokenize Chinese text and convert tokens to IDs', 'review_CpmAntTokenizer': 'review the CpmAntTokenizer usage for tokenizing Chinese text with rjieba segmentation', 'test_CpmAntTokenizer_from_pretrained': 'test loading CpmAntTokenizer from pretrained openbmb/cpm-ant-10b model checkpoint', 'test_tokenizer_decode': 'test the tokenizer decode method to reconstruct text from token IDs'}
```

