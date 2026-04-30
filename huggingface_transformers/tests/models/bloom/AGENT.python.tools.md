# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/bloom/test_modeling_bloom.py

Prompts

```
['test the BloomModel past key-value caching by verifying outputs match with and without cached states', 'test the BloomModel attention mask handling with past key-values across masked and unmasked sequences', 'test the BloomForCausalLM loss and logits shape for a causal language modeling head', 'test the BloomModel weight initialization standard deviation and mean for projection layers', 'test text generation with the bigscience bloom-560m model using greedy decoding and batch inputs', 'test the bloom tokenizer by encoding sample sentences and verifying token IDs match expected values', 'test the bloom tokenizer padding behavior with max_length parameter and verify ValueError when pad_token is None', 'test the bloom tokenizer by encoding multilingual text from the facebook xnli dataset and verifying roundtrip decoding', 'test saving and loading the bloom tokenizer from pretrained bigscience tokenizer model', 'review the BloomTokenizationTest class to understand tokenizer test patterns including encoding, padding, and dataset integration tests']
```

Usage

```
{'test_bloom_past_key_values': 'test the BloomModel past key-value caching by verifying outputs match with and without cached states', 'test_bloom_attention_mask_past': 'test the BloomModel attention mask handling with past key-values across masked and unmasked sequences', 'test_bloom_lm_head_model': 'test the BloomForCausalLM loss and logits shape for a causal language modeling head', 'test_bloom_weight_initialization': 'test the BloomModel weight initialization standard deviation and mean for projection layers', 'test_bloom_integration_generation': 'test text generation with the bigscience bloom-560m model using greedy decoding and batch inputs'}
```

## File: huggingface_transformers/tests/models/bloom/test_tokenization_bloom.py

Prompts

```
['test the BloomModel past key-value caching by verifying outputs match with and without cached states', 'test the BloomModel attention mask handling with past key-values across masked and unmasked sequences', 'test the BloomForCausalLM loss and logits shape for a causal language modeling head', 'test the BloomModel weight initialization standard deviation and mean for projection layers', 'test text generation with the bigscience bloom-560m model using greedy decoding and batch inputs', 'test the bloom tokenizer by encoding sample sentences and verifying token IDs match expected values', 'test the bloom tokenizer padding behavior with max_length parameter and verify ValueError when pad_token is None', 'test the bloom tokenizer by encoding multilingual text from the facebook xnli dataset and verifying roundtrip decoding', 'test saving and loading the bloom tokenizer from pretrained bigscience tokenizer model', 'review the BloomTokenizationTest class to understand tokenizer test patterns including encoding, padding, and dataset integration tests']
```

Usage

```
{'test_bloom_tokenizer_encodings': 'test the bloom tokenizer by encoding sample sentences and verifying token IDs match expected values', 'test_bloom_tokenizer_padding': 'test the bloom tokenizer padding behavior with max_length parameter and verify ValueError when pad_token is None', 'test_bloom_tokenizer_xnli': 'test the bloom tokenizer by encoding multilingual text from the facebook xnli dataset and verifying roundtrip decoding', 'test_bloom_tokenizer_save_load': 'test saving and loading the bloom tokenizer from pretrained bigscience tokenizer model', 'review_bloom_tokenization_test': 'review the BloomTokenizationTest class to understand tokenizer test patterns including encoding, padding, and dataset integration tests'}
```

