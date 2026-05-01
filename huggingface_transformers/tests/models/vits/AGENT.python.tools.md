# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vits/test_modeling_vits.py

Prompts

```
['test the VitsModel forward pass with input_ids and attention_mask to verify waveform output shape', 'test VitsModel with DataParallel across multiple GPUs ensuring consistent sequence lengths', 'test saving and loading VitsModel to and from a directory with matching outputs', 'test that VitsModel returns equivalent outputs for tuple and dict input formats', 'test VitsModel integration with VitsTokenizer using a pretrained facebook/mms-tts-eng model', 'test the VitsTokenizer save and load roundtrip to verify encoding and vocab are preserved', 'test the VitsTokenizer text normalization that lowercases text and removes punctuation', 'test the VitsTokenizer Romanian normalization that converts ț to ţ characters', 'test the VitsTokenizer integration with facebook/mms-tts-eng model using padded normalized sequences', 'review the VitsTokenizerTest class that extends TokenizerTesterMixin for HuggingFace tokenizer testing']
```

Usage

```
{'test_vits_model_forward': 'test the VitsModel forward pass with input_ids and attention_mask to verify waveform output shape', 'test_vits_multi_gpu': 'test VitsModel with DataParallel across multiple GPUs ensuring consistent sequence lengths', 'test_vits_save_load': 'test saving and loading VitsModel to and from a directory with matching outputs', 'test_vits_outputs_equivalence': 'test that VitsModel returns equivalent outputs for tuple and dict input formats', 'test_vits_integration': 'test VitsModel integration with VitsTokenizer using a pretrained facebook/mms-tts-eng model'}
```

## File: huggingface_transformers/tests/models/vits/test_tokenization_vits.py

Prompts

```
['test the VitsModel forward pass with input_ids and attention_mask to verify waveform output shape', 'test VitsModel with DataParallel across multiple GPUs ensuring consistent sequence lengths', 'test saving and loading VitsModel to and from a directory with matching outputs', 'test that VitsModel returns equivalent outputs for tuple and dict input formats', 'test VitsModel integration with VitsTokenizer using a pretrained facebook/mms-tts-eng model', 'test the VitsTokenizer save and load roundtrip to verify encoding and vocab are preserved', 'test the VitsTokenizer text normalization that lowercases text and removes punctuation', 'test the VitsTokenizer Romanian normalization that converts ț to ţ characters', 'test the VitsTokenizer integration with facebook/mms-tts-eng model using padded normalized sequences', 'review the VitsTokenizerTest class that extends TokenizerTesterMixin for HuggingFace tokenizer testing']
```

Usage

```
{'test_VitsTokenizer_save_and_load': 'test the VitsTokenizer save and load roundtrip to verify encoding and vocab are preserved', 'test_VitsTokenizer_normalization': 'test the VitsTokenizer text normalization that lowercases text and removes punctuation', 'test_VitsTokenizer_ron_normalization': 'test the VitsTokenizer Romanian normalization that converts ț to ţ characters', 'test_VitsTokenizer_integration': 'test the VitsTokenizer integration with facebook/mms-tts-eng model using padded normalized sequences', 'review_VitsTokenizerTest_class': 'review the VitsTokenizerTest class that extends TokenizerTesterMixin for HuggingFace tokenizer testing'}
```

