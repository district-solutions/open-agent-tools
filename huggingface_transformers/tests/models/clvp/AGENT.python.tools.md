# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/clvp/test_feature_extraction_clvp.py

Prompts

```
['test the ClvpFeatureExtractionTest.test_call method to verify batched and single speech input encoding', 'test the ClvpFeatureExtractionTest.test_feat_extract_from_and_save_pretrained method to verify save and load of feature extractor', 'test the ClvpFeatureExtractionTest.test_integration method to validate CLVP feature extraction against expected output values', 'test the ClvpFeatureExtractionTest.test_double_precision_pad method to verify float32 dtype handling for padded inputs', 'test the ClvpFeatureExtractionTest.test_feat_extract_to_json_file method to verify JSON round-trip serialization of feature extractor', 'run the ClvpEncoderTest suite to verify encoder model config and output shapes', 'run the ClvpDecoderTest suite to verify decoder causal LM generation and training', 'run the ClvpModelForConditionalGenerationTest suite to verify the full conditional generation model', 'run the ClvpIntegrationTest suite to verify conditional encoder, decoder, and full model integration', 'test that ClvpConfig, ClvpEncoderConfig, and ClvpDecoderConfig can be saved and loaded from disk', 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'test_clvp_feature_extraction_call': 'test the ClvpFeatureExtractionTest.test_call method to verify batched and single speech input encoding', 'test_clvp_save_pretrained': 'test the ClvpFeatureExtractionTest.test_feat_extract_from_and_save_pretrained method to verify save and load of feature extractor', 'test_clvp_integration': 'test the ClvpFeatureExtractionTest.test_integration method to validate CLVP feature extraction against expected output values', 'test_clvp_double_precision_pad': 'test the ClvpFeatureExtractionTest.test_double_precision_pad method to verify float32 dtype handling for padded inputs', 'test_clvp_json_serialization': 'test the ClvpFeatureExtractionTest.test_feat_extract_to_json_file method to verify JSON round-trip serialization of feature extractor'}
```

## File: huggingface_transformers/tests/models/clvp/test_modeling_clvp.py

Prompts

```
['test the ClvpFeatureExtractionTest.test_call method to verify batched and single speech input encoding', 'test the ClvpFeatureExtractionTest.test_feat_extract_from_and_save_pretrained method to verify save and load of feature extractor', 'test the ClvpFeatureExtractionTest.test_integration method to validate CLVP feature extraction against expected output values', 'test the ClvpFeatureExtractionTest.test_double_precision_pad method to verify float32 dtype handling for padded inputs', 'test the ClvpFeatureExtractionTest.test_feat_extract_to_json_file method to verify JSON round-trip serialization of feature extractor', 'run the ClvpEncoderTest suite to verify encoder model config and output shapes', 'run the ClvpDecoderTest suite to verify decoder causal LM generation and training', 'run the ClvpModelForConditionalGenerationTest suite to verify the full conditional generation model', 'run the ClvpIntegrationTest suite to verify conditional encoder, decoder, and full model integration', 'test that ClvpConfig, ClvpEncoderConfig, and ClvpDecoderConfig can be saved and loaded from disk', 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'run_clvp_encoder_tests': 'run the ClvpEncoderTest suite to verify encoder model config and output shapes', 'run_clvp_decoder_tests': 'run the ClvpDecoderTest suite to verify decoder causal LM generation and training', 'run_clvp_conditional_generation_tests': 'run the ClvpModelForConditionalGenerationTest suite to verify the full conditional generation model', 'run_clvp_integration_tests': 'run the ClvpIntegrationTest suite to verify conditional encoder, decoder, and full model integration', 'test_clvp_config_loading': 'test that ClvpConfig, ClvpEncoderConfig, and ClvpDecoderConfig can be saved and loaded from disk'}
```

## File: huggingface_transformers/tests/models/clvp/test_processing_clvp.py

Prompts

```
['test the ClvpFeatureExtractionTest.test_call method to verify batched and single speech input encoding', 'test the ClvpFeatureExtractionTest.test_feat_extract_from_and_save_pretrained method to verify save and load of feature extractor', 'test the ClvpFeatureExtractionTest.test_integration method to validate CLVP feature extraction against expected output values', 'test the ClvpFeatureExtractionTest.test_double_precision_pad method to verify float32 dtype handling for padded inputs', 'test the ClvpFeatureExtractionTest.test_feat_extract_to_json_file method to verify JSON round-trip serialization of feature extractor', 'run the ClvpEncoderTest suite to verify encoder model config and output shapes', 'run the ClvpDecoderTest suite to verify decoder causal LM generation and training', 'run the ClvpModelForConditionalGenerationTest suite to verify the full conditional generation model', 'run the ClvpIntegrationTest suite to verify conditional encoder, decoder, and full model integration', 'test that ClvpConfig, ClvpEncoderConfig, and ClvpDecoderConfig can be saved and loaded from disk', 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'test_clvp_processor_save_load': 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test_clvp_processor_feature_extraction': 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test_clvp_processor_tokenization': 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test_clvp_processor_batch_decode': 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test_clvp_processor_save_load_kwargs': 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate'}
```

## File: huggingface_transformers/tests/models/clvp/test_tokenization_clvp.py

Prompts

```
['test the ClvpFeatureExtractionTest.test_call method to verify batched and single speech input encoding', 'test the ClvpFeatureExtractionTest.test_feat_extract_from_and_save_pretrained method to verify save and load of feature extractor', 'test the ClvpFeatureExtractionTest.test_integration method to validate CLVP feature extraction against expected output values', 'test the ClvpFeatureExtractionTest.test_double_precision_pad method to verify float32 dtype handling for padded inputs', 'test the ClvpFeatureExtractionTest.test_feat_extract_to_json_file method to verify JSON round-trip serialization of feature extractor', 'run the ClvpEncoderTest suite to verify encoder model config and output shapes', 'run the ClvpDecoderTest suite to verify decoder causal LM generation and training', 'run the ClvpModelForConditionalGenerationTest suite to verify the full conditional generation model', 'run the ClvpIntegrationTest suite to verify conditional encoder, decoder, and full model integration', 'test that ClvpConfig, ClvpEncoderConfig, and ClvpDecoderConfig can be saved and loaded from disk', 'test ClvpProcessor save_pretrained and from_pretrained with default tokenizer and feature extractor', 'test ClvpProcessor processes raw speech audio input and produces feature extractor output', 'test ClvpProcessor encodes text input identically to ClvpTokenizer directly', 'test ClvpProcessor batch_decode produces same output as ClvpTokenizer batch_decode', 'test ClvpProcessor from_pretrained with additional kwargs like pad_token and sampling_rate', 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled']
```

Usage

```
{'test_tokenization_clvp_full_tokenizer': 'test the ClvpTokenizer full tokenizer with vocab and merges files to verify BPE tokenization output', 'test_tokenization_clvp_special_tokens': 'test the ClvpTokenizer add_special_tokens method with custom cls_token and boxes input', 'test_tokenization_clvp_padding': 'test the ClvpTokenizer padding behavior with pad_token set and max_length truncation', 'test_tokenization_clvp_token_type_ids': 'test the ClvpTokenizer token_type_ids generation for sequence classification tagging', 'test_tokenization_clvp_special_tokens_mask': 'test the ClvpTokenizer special_tokens_mask with input pairs and bos_token enabled'}
```

