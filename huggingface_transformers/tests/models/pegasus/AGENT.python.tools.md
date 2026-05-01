# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/pegasus/test_modeling_pegasus.py

Prompts

```
['create a PegasusModelTester with custom config parameters like batch_size, seq_length, and vocab_size', 'test the PegasusModelTester prepare_config_and_inputs method returns valid config and inputs dict', 'test decoder model past key values with large inputs using create_and_check_decoder_model_past_large_inputs', 'test PegasusStandaloneDecoderModelTester decoder model past with attention mask support', 'test PegasusXSUMIntegrationTest generate summaries on google/pegasus-xsum checkpoint', 'run the PegasusTokenizationTest class to test Pegasus tokenizer with google/pegasus-xsum model', 'run the BigBirdPegasusTokenizationTest class to test BigBird-Pegasus tokenizer integration', 'test the Pegasus large tokenizer mask token handling with mask_1 and mask_2 special tokens', 'test the BigBird-Pegasus large tokenizer settings including vocab size, pad token, and eos token', 'test the BigBird-Pegasus tokenizer sequence to sequence truncation with padding and max length']
```

Usage

```
{'create_pegasus_model_tester': 'create a PegasusModelTester with custom config parameters like batch_size, seq_length, and vocab_size', 'test_pegasus_encoder_decoder_model': 'test the PegasusModelTester prepare_config_and_inputs method returns valid config and inputs dict', 'test_pegasus_decoder_past_large_inputs': 'test decoder model past key values with large inputs using create_and_check_decoder_model_past_large_inputs', 'test_pegasus_standalone_decoder': 'test PegasusStandaloneDecoderModelTester decoder model past with attention mask support', 'test_pegasus_integration_xsum_summary': 'test PegasusXSUMIntegrationTest generate summaries on google/pegasus-xsum checkpoint'}
```

## File: huggingface_transformers/tests/models/pegasus/test_tokenization_pegasus.py

Prompts

```
['create a PegasusModelTester with custom config parameters like batch_size, seq_length, and vocab_size', 'test the PegasusModelTester prepare_config_and_inputs method returns valid config and inputs dict', 'test decoder model past key values with large inputs using create_and_check_decoder_model_past_large_inputs', 'test PegasusStandaloneDecoderModelTester decoder model past with attention mask support', 'test PegasusXSUMIntegrationTest generate summaries on google/pegasus-xsum checkpoint', 'run the PegasusTokenizationTest class to test Pegasus tokenizer with google/pegasus-xsum model', 'run the BigBirdPegasusTokenizationTest class to test BigBird-Pegasus tokenizer integration', 'test the Pegasus large tokenizer mask token handling with mask_1 and mask_2 special tokens', 'test the BigBird-Pegasus large tokenizer settings including vocab size, pad token, and eos token', 'test the BigBird-Pegasus tokenizer sequence to sequence truncation with padding and max length']
```

Usage

```
{'run_pegasus_tokenization_test': 'run the PegasusTokenizationTest class to test Pegasus tokenizer with google/pegasus-xsum model', 'run_bigbird_pegasus_tokenization_test': 'run the BigBirdPegasusTokenizationTest class to test BigBird-Pegasus tokenizer integration', 'test_large_mask_tokens': 'test the Pegasus large tokenizer mask token handling with mask_1 and mask_2 special tokens', 'test_large_tokenizer_settings': 'test the BigBird-Pegasus large tokenizer settings including vocab size, pad token, and eos token', 'test_large_seq2seq_truncation': 'test the BigBird-Pegasus tokenizer sequence to sequence truncation with padding and max length'}
```

