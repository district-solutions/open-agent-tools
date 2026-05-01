# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/parakeet/test_feature_extraction_parakeet.py

Prompts

```
['test the ParakeetFeatureExtractor with a single audio sample and verify torch tensor output shapes', 'test the ParakeetFeatureExtractor with a batch of five audio samples and verify output shapes', 'create a ParakeetFeatureExtractionTester instance to prepare feature extraction configuration and random speech inputs', 'review the ParakeetFeatureExtractionTest class and its torch integration test methods for audio feature extraction', 'summarize the floats_list utility function that generates random float32 lists for test inputs', 'test the ParakeetEncoder model with config and input features to verify output shape', 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions', 'test the ParakeetTokenizer by running the ParakeetTokenizationTest unittest suite for the nvidia/parakeet-ctc-1.1b model', 'load the pretrained ParakeetTokenizer from nvidia/parakeet-ctc-1.1b using from_pretrained and save it locally', 'review the ParakeetTokenizationTest class that extends TokenizerTesterMixin to test the ParakeetTokenizer', 'run the unittest suite for ParakeetTokenizationTest to verify tokenizer encoding and decoding behavior', 'summarize the setUpClass method that loads and saves the ParakeetTokenizer from the nvidia/parakeet-ctc-1.1b pretrained model']
```

Usage

```
{'test_ParakeetFeatureExtractor_torch_integration': 'test the ParakeetFeatureExtractor with a single audio sample and verify torch tensor output shapes', 'test_ParakeetFeatureExtractor_batch_processing': 'test the ParakeetFeatureExtractor with a batch of five audio samples and verify output shapes', 'create_ParakeetFeatureExtractionTester': 'create a ParakeetFeatureExtractionTester instance to prepare feature extraction configuration and random speech inputs', 'review_ParakeetFeatureExtractionTest': 'review the ParakeetFeatureExtractionTest class and its torch integration test methods for audio feature extraction', 'summarize_floats_list': 'summarize the floats_list utility function that generates random float32 lists for test inputs'}
```

## File: huggingface_transformers/tests/models/parakeet/test_modeling_parakeet.py

Prompts

```
['test the ParakeetFeatureExtractor with a single audio sample and verify torch tensor output shapes', 'test the ParakeetFeatureExtractor with a batch of five audio samples and verify output shapes', 'create a ParakeetFeatureExtractionTester instance to prepare feature extraction configuration and random speech inputs', 'review the ParakeetFeatureExtractionTest class and its torch integration test methods for audio feature extraction', 'summarize the floats_list utility function that generates random float32 lists for test inputs', 'test the ParakeetEncoder model with config and input features to verify output shape', 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions', 'test the ParakeetTokenizer by running the ParakeetTokenizationTest unittest suite for the nvidia/parakeet-ctc-1.1b model', 'load the pretrained ParakeetTokenizer from nvidia/parakeet-ctc-1.1b using from_pretrained and save it locally', 'review the ParakeetTokenizationTest class that extends TokenizerTesterMixin to test the ParakeetTokenizer', 'run the unittest suite for ParakeetTokenizationTest to verify tokenizer encoding and decoding behavior', 'summarize the setUpClass method that loads and saves the ParakeetTokenizer from the nvidia/parakeet-ctc-1.1b pretrained model']
```

Usage

```
{'test_ParakeetEncoder_model': 'test the ParakeetEncoder model with config and input features to verify output shape', 'test_ParakeetForCTC_model': 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test_ParakeetForCTC_config': 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test_sdpa_can_dispatch_composite_models': 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test_1b_model_integration': 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions'}
```

## File: huggingface_transformers/tests/models/parakeet/test_tokenization_parakeet.py

Prompts

```
['test the ParakeetFeatureExtractor with a single audio sample and verify torch tensor output shapes', 'test the ParakeetFeatureExtractor with a batch of five audio samples and verify output shapes', 'create a ParakeetFeatureExtractionTester instance to prepare feature extraction configuration and random speech inputs', 'review the ParakeetFeatureExtractionTest class and its torch integration test methods for audio feature extraction', 'summarize the floats_list utility function that generates random float32 lists for test inputs', 'test the ParakeetEncoder model with config and input features to verify output shape', 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions', 'test the ParakeetTokenizer by running the ParakeetTokenizationTest unittest suite for the nvidia/parakeet-ctc-1.1b model', 'load the pretrained ParakeetTokenizer from nvidia/parakeet-ctc-1.1b using from_pretrained and save it locally', 'review the ParakeetTokenizationTest class that extends TokenizerTesterMixin to test the ParakeetTokenizer', 'run the unittest suite for ParakeetTokenizationTest to verify tokenizer encoding and decoding behavior', 'summarize the setUpClass method that loads and saves the ParakeetTokenizer from the nvidia/parakeet-ctc-1.1b pretrained model']
```

Usage

```
{'test_parakeet_tokenizer': 'test the ParakeetTokenizer by running the ParakeetTokenizationTest unittest suite for the nvidia/parakeet-ctc-1.1b model', 'load_parakeet_tokenizer': 'load the pretrained ParakeetTokenizer from nvidia/parakeet-ctc-1.1b using from_pretrained and save it locally', 'review_parakeet_tokenization_test': 'review the ParakeetTokenizationTest class that extends TokenizerTesterMixin to test the ParakeetTokenizer', 'run_parakeet_tokenizer_tests': 'run the unittest suite for ParakeetTokenizationTest to verify tokenizer encoding and decoding behavior', 'summarize_parakeet_tokenizer_setup': 'summarize the setUpClass method that loads and saves the ParakeetTokenizer from the nvidia/parakeet-ctc-1.1b pretrained model'}
```

