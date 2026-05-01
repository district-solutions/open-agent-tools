# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/wav2vec2_bert/test_modeling_wav2vec2_bert.py

Prompts

```
['test the Wav2Vec2BertModel with random input features and attention mask to verify output shape', 'test the Wav2Vec2BertForCTC model for CTC loss computation and training with padded inputs', 'test the Wav2Vec2BertForSequenceClassification model for masked and unmasked sequence classification loss', 'test the Wav2Vec2BertForXVector model with frozen base model and classification head training', 'test the _compute_mask_indices function to generate time masking indices for self-supervised pretraining', 'test that Wav2Vec2BertProcessor produces the same output as the standalone feature extractor', 'test that processor input keys match the model_input_names property', 'create a Wav2Vec2Bert feature extractor with 80-dim features and 16kHz sampling rate', 'create a Wav2Vec2Bert tokenizer from a custom vocabulary file with special tokens', 'run the Wav2Vec2BertProcessor test suite to validate audio and text processing']
```

Usage

```
{'test_Wav2Vec2BertModel': 'test the Wav2Vec2BertModel with random input features and attention mask to verify output shape', 'test_Wav2Vec2BertForCTC': 'test the Wav2Vec2BertForCTC model for CTC loss computation and training with padded inputs', 'test_Wav2Vec2BertForSequenceClassification': 'test the Wav2Vec2BertForSequenceClassification model for masked and unmasked sequence classification loss', 'test_Wav2Vec2BertForXVector': 'test the Wav2Vec2BertForXVector model with frozen base model and classification head training', 'test_compute_mask_indices': 'test the _compute_mask_indices function to generate time masking indices for self-supervised pretraining'}
```

## File: huggingface_transformers/tests/models/wav2vec2_bert/test_processing_wav2vec2_bert.py

Prompts

```
['test the Wav2Vec2BertModel with random input features and attention mask to verify output shape', 'test the Wav2Vec2BertForCTC model for CTC loss computation and training with padded inputs', 'test the Wav2Vec2BertForSequenceClassification model for masked and unmasked sequence classification loss', 'test the Wav2Vec2BertForXVector model with frozen base model and classification head training', 'test the _compute_mask_indices function to generate time masking indices for self-supervised pretraining', 'test that Wav2Vec2BertProcessor produces the same output as the standalone feature extractor', 'test that processor input keys match the model_input_names property', 'create a Wav2Vec2Bert feature extractor with 80-dim features and 16kHz sampling rate', 'create a Wav2Vec2Bert tokenizer from a custom vocabulary file with special tokens', 'run the Wav2Vec2BertProcessor test suite to validate audio and text processing']
```

Usage

```
{'test_processor_feature_extractor': 'test that Wav2Vec2BertProcessor produces the same output as the standalone feature extractor', 'test_model_input_names': 'test that processor input keys match the model_input_names property', 'setup_feature_extractor': 'create a Wav2Vec2Bert feature extractor with 80-dim features and 16kHz sampling rate', 'setup_tokenizer': 'create a Wav2Vec2Bert tokenizer from a custom vocabulary file with special tokens', 'run_processor_tests': 'run the Wav2Vec2BertProcessor test suite to validate audio and text processing'}
```

