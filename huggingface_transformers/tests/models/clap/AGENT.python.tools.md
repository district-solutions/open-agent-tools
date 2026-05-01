# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/clap/test_feature_extraction_clap.py

Prompts

```
['test the ClapFeatureExtractor call method with batched and unbatched numpy and list inputs', 'test the ClapFeatureExtractor pad method converts float64 inputs to float32 output', 'test ClapFeatureExtractor integration with short audio input using repeat, repeatpad, and pad padding modes', 'test ClapFeatureExtractor integration with short audio input using random truncation and various padding modes', 'test ClapFeatureExtractor integration with long concatenated audio input using repeat, repeatpad, and pad padding modes', 'test the ClapAudioModelTester to prepare configs and inputs for CLAP audio model unit tests', 'test the ClapTextModelTester to prepare configs and inputs for CLAP text model unit tests', 'test the ClapModelTester to prepare configs and inputs for the joint CLAP model tests', 'run the ClapAudioModelTest suite to verify ClapAudioModel and ClapAudioModelWithProjection forward passes', 'run the ClapModelIntegrationTest suite to verify pretrained CLAP models against expected audio embedding means', 'test that ClapProcessor saves and loads pretrained tokenizer and feature extractor correctly', 'test ClapProcessor save and load with additional tokenizer and feature extractor kwargs', 'test that ClapProcessor extracts audio features matching the standalone feature extractor output', 'test that ClapProcessor tokenizes text matching the standalone RobertaTokenizer output', 'test that ClapProcessor batch_decode returns the same results as the standalone tokenizer']
```

Usage

```
{'test_clap_feature_extractor_call': 'test the ClapFeatureExtractor call method with batched and unbatched numpy and list inputs', 'test_clap_feature_extractor_double_precision_pad': 'test the ClapFeatureExtractor pad method converts float64 inputs to float32 output', 'test_clap_integration_fusion_short_input': 'test ClapFeatureExtractor integration with short audio input using repeat, repeatpad, and pad padding modes', 'test_clap_integration_rand_trunc_short_input': 'test ClapFeatureExtractor integration with short audio input using random truncation and various padding modes', 'test_clap_integration_fusion_long_input': 'test ClapFeatureExtractor integration with long concatenated audio input using repeat, repeatpad, and pad padding modes'}
```

## File: huggingface_transformers/tests/models/clap/test_modeling_clap.py

Prompts

```
['test the ClapFeatureExtractor call method with batched and unbatched numpy and list inputs', 'test the ClapFeatureExtractor pad method converts float64 inputs to float32 output', 'test ClapFeatureExtractor integration with short audio input using repeat, repeatpad, and pad padding modes', 'test ClapFeatureExtractor integration with short audio input using random truncation and various padding modes', 'test ClapFeatureExtractor integration with long concatenated audio input using repeat, repeatpad, and pad padding modes', 'test the ClapAudioModelTester to prepare configs and inputs for CLAP audio model unit tests', 'test the ClapTextModelTester to prepare configs and inputs for CLAP text model unit tests', 'test the ClapModelTester to prepare configs and inputs for the joint CLAP model tests', 'run the ClapAudioModelTest suite to verify ClapAudioModel and ClapAudioModelWithProjection forward passes', 'run the ClapModelIntegrationTest suite to verify pretrained CLAP models against expected audio embedding means', 'test that ClapProcessor saves and loads pretrained tokenizer and feature extractor correctly', 'test ClapProcessor save and load with additional tokenizer and feature extractor kwargs', 'test that ClapProcessor extracts audio features matching the standalone feature extractor output', 'test that ClapProcessor tokenizes text matching the standalone RobertaTokenizer output', 'test that ClapProcessor batch_decode returns the same results as the standalone tokenizer']
```

Usage

```
{'test_ClapAudioModelTester': 'test the ClapAudioModelTester to prepare configs and inputs for CLAP audio model unit tests', 'test_ClapTextModelTester': 'test the ClapTextModelTester to prepare configs and inputs for CLAP text model unit tests', 'test_ClapModelTester': 'test the ClapModelTester to prepare configs and inputs for the joint CLAP model tests', 'run_ClapAudioModelTest': 'run the ClapAudioModelTest suite to verify ClapAudioModel and ClapAudioModelWithProjection forward passes', 'run_ClapModelIntegrationTest': 'run the ClapModelIntegrationTest suite to verify pretrained CLAP models against expected audio embedding means'}
```

## File: huggingface_transformers/tests/models/clap/test_processing_clap.py

Prompts

```
['test the ClapFeatureExtractor call method with batched and unbatched numpy and list inputs', 'test the ClapFeatureExtractor pad method converts float64 inputs to float32 output', 'test ClapFeatureExtractor integration with short audio input using repeat, repeatpad, and pad padding modes', 'test ClapFeatureExtractor integration with short audio input using random truncation and various padding modes', 'test ClapFeatureExtractor integration with long concatenated audio input using repeat, repeatpad, and pad padding modes', 'test the ClapAudioModelTester to prepare configs and inputs for CLAP audio model unit tests', 'test the ClapTextModelTester to prepare configs and inputs for CLAP text model unit tests', 'test the ClapModelTester to prepare configs and inputs for the joint CLAP model tests', 'run the ClapAudioModelTest suite to verify ClapAudioModel and ClapAudioModelWithProjection forward passes', 'run the ClapModelIntegrationTest suite to verify pretrained CLAP models against expected audio embedding means', 'test that ClapProcessor saves and loads pretrained tokenizer and feature extractor correctly', 'test ClapProcessor save and load with additional tokenizer and feature extractor kwargs', 'test that ClapProcessor extracts audio features matching the standalone feature extractor output', 'test that ClapProcessor tokenizes text matching the standalone RobertaTokenizer output', 'test that ClapProcessor batch_decode returns the same results as the standalone tokenizer']
```

Usage

```
{'test_clap_processor_save_load': 'test that ClapProcessor saves and loads pretrained tokenizer and feature extractor correctly', 'test_clap_processor_additional_kwargs': 'test ClapProcessor save and load with additional tokenizer and feature extractor kwargs', 'test_clap_processor_audio_extraction': 'test that ClapProcessor extracts audio features matching the standalone feature extractor output', 'test_clap_processor_tokenization': 'test that ClapProcessor tokenizes text matching the standalone RobertaTokenizer output', 'test_clap_processor_batch_decode': 'test that ClapProcessor batch_decode returns the same results as the standalone tokenizer'}
```

