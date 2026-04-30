# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/biogpt/test_modeling_biogpt.py

Prompts

```
['test the BioGptModel forward pass with input_ids and attention mask to verify output shapes', 'test the BioGptModel past key values caching produces matching outputs without recomputation', 'test the BioGptForCausalLM gradient checkpointing enables correct forward and backward passes', 'test the BioGptForTokenClassification model outputs logits with the correct batch and label shape', 'test the BioGptForSequenceClassification model for single label and multi label classification tasks', 'test the BioGptTokenizer full tokenization pipeline with vocab and merges files', 'test the BioGptTokenizer sequence builders for encoding sentences and pairs with special tokens', 'create a BioGptTokenizer instance from vocab and merges files for subword tokenization', "test tokenizing the input text 'lower' into BPE tokens ['low', 'er</w>']", 'test converting BPE tokens to their corresponding integer IDs']
```

Usage

```
{'test_biogpt_model_forward': 'test the BioGptModel forward pass with input_ids and attention mask to verify output shapes', 'test_biogpt_past_key_values': 'test the BioGptModel past key values caching produces matching outputs without recomputation', 'test_biogpt_gradient_checkpointing': 'test the BioGptForCausalLM gradient checkpointing enables correct forward and backward passes', 'test_biogpt_token_classification': 'test the BioGptForTokenClassification model outputs logits with the correct batch and label shape', 'test_biogpt_sequence_classification': 'test the BioGptForSequenceClassification model for single label and multi label classification tasks'}
```

## File: huggingface_transformers/tests/models/biogpt/test_tokenization_biogpt.py

Prompts

```
['test the BioGptModel forward pass with input_ids and attention mask to verify output shapes', 'test the BioGptModel past key values caching produces matching outputs without recomputation', 'test the BioGptForCausalLM gradient checkpointing enables correct forward and backward passes', 'test the BioGptForTokenClassification model outputs logits with the correct batch and label shape', 'test the BioGptForSequenceClassification model for single label and multi label classification tasks', 'test the BioGptTokenizer full tokenization pipeline with vocab and merges files', 'test the BioGptTokenizer sequence builders for encoding sentences and pairs with special tokens', 'create a BioGptTokenizer instance from vocab and merges files for subword tokenization', "test tokenizing the input text 'lower' into BPE tokens ['low', 'er</w>']", 'test converting BPE tokens to their corresponding integer IDs']
```

Usage

```
{'test_full_tokenizer': 'test the BioGptTokenizer full tokenization pipeline with vocab and merges files', 'test_sequence_builders': 'test the BioGptTokenizer sequence builders for encoding sentences and pairs with special tokens', 'create_BioGptTokenizer': 'create a BioGptTokenizer instance from vocab and merges files for subword tokenization', 'test_tokenize_input': "test tokenizing the input text 'lower' into BPE tokens ['low', 'er</w>']", 'test_convert_tokens_to_ids': 'test converting BPE tokens to their corresponding integer IDs'}
```

