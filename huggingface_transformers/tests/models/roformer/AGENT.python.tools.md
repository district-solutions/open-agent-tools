# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/roformer/test_modeling_roformer.py

Prompts

```
['test the RoFormerModelTester class that prepares configs and inputs for all RoFormer model variants', 'test all seven RoFormer model classes including MaskedLM, CausalLM, SequenceClassification, and TokenClassification', 'run integration tests that load pretrained RoFormer models like junnyu/roformer_chinese_base for inference', 'test the RoFormerSinusoidalPositionalEmbedding class to verify sinusoidal positional embedding weight generation', 'test the apply_rotary_position_embeddings method on query and key layers in RoFormerSelfAttention', 'test the RoFormer tokenizer with Chinese text input and verify tokenization output', 'test the RoFormer fast Rust tokenizer with Chinese text and verify token IDs', 'test saving and reloading RoFormer tokenizer from pretrained model to temporary directory', 'review the RoFormerTokenizationTest class that tests Chinese tokenization with rjieba and tokenizers', 'run tests comparing slow Python and fast Rust RoFormer tokenizer implementations']
```

Usage

```
{'test_RoFormerModelTester': 'test the RoFormerModelTester class that prepares configs and inputs for all RoFormer model variants', 'test_RoFormerModelTest': 'test all seven RoFormer model classes including MaskedLM, CausalLM, SequenceClassification, and TokenClassification', 'run_RoFormerModelIntegrationTest': 'run integration tests that load pretrained RoFormer models like junnyu/roformer_chinese_base for inference', 'test_RoFormerSinusoidalPositionalEmbedding': 'test the RoFormerSinusoidalPositionalEmbedding class to verify sinusoidal positional embedding weight generation', 'test_RoFormerSelfAttentionRotaryPositionEmbedding': 'test the apply_rotary_position_embeddings method on query and key layers in RoFormerSelfAttention'}
```

## File: huggingface_transformers/tests/models/roformer/test_tokenization_roformer.py

Prompts

```
['test the RoFormerModelTester class that prepares configs and inputs for all RoFormer model variants', 'test all seven RoFormer model classes including MaskedLM, CausalLM, SequenceClassification, and TokenClassification', 'run integration tests that load pretrained RoFormer models like junnyu/roformer_chinese_base for inference', 'test the RoFormerSinusoidalPositionalEmbedding class to verify sinusoidal positional embedding weight generation', 'test the apply_rotary_position_embeddings method on query and key layers in RoFormerSelfAttention', 'test the RoFormer tokenizer with Chinese text input and verify tokenization output', 'test the RoFormer fast Rust tokenizer with Chinese text and verify token IDs', 'test saving and reloading RoFormer tokenizer from pretrained model to temporary directory', 'review the RoFormerTokenizationTest class that tests Chinese tokenization with rjieba and tokenizers', 'run tests comparing slow Python and fast Rust RoFormer tokenizer implementations']
```

Usage

```
{'test_roformer_tokenizer_chinese': 'test the RoFormer tokenizer with Chinese text input and verify tokenization output', 'test_roformer_rust_tokenizer': 'test the RoFormer fast Rust tokenizer with Chinese text and verify token IDs', 'test_save_reload_tokenizer': 'test saving and reloading RoFormer tokenizer from pretrained model to temporary directory', 'review_tokenizer_test_class': 'review the RoFormerTokenizationTest class that tests Chinese tokenization with rjieba and tokenizers', 'run_tokenizer_comparison_tests': 'run tests comparing slow Python and fast Rust RoFormer tokenizer implementations'}
```

