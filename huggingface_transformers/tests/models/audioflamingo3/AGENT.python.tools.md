# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/audioflamingo3/test_modeling_audioflamingo3.py

Prompts

```
['run the AudioFlamingo3ForConditionalGeneration model unit tests using the ModelTesterMixin and GenerationTesterMixin', 'test that SDPA attention implementation dispatches correctly to language model and audio tower submodules', 'run the single sample integration test against the nvidia audio-flamingo-3-hf checkpoint', 'run the batched integration test with multiple conversations against the public checkpoint', 'create an AudioFlamingo3ModelTester instance to build tiny configs and synthetic audio inputs for testing', 'test the AudioFlamingo3Processor save and load pretrained models with tokenizer and feature extractor', 'test the AudioFlamingo3Processor tokenizer integration with slow and fast tokenizers produce identical outputs', 'test the AudioFlamingo3Processor chat template formatting with audio and text conversation inputs', 'test the AudioFlamingo3Processor apply_transcription_request helper generates correct input_ids and input_features', 'test the AudioFlamingo3Processor apply_chat_template with audio modalities and pytorch tensors']
```

Usage

```
{'test_AudioFlamingo3ForConditionalGeneration': 'run the AudioFlamingo3ForConditionalGeneration model unit tests using the ModelTesterMixin and GenerationTesterMixin', 'test_sdpa_dispatch_composite_models': 'test that SDPA attention implementation dispatches correctly to language model and audio tower submodules', 'test_fixture_single_matches': 'run the single sample integration test against the nvidia audio-flamingo-3-hf checkpoint', 'test_fixture_batched_matches': 'run the batched integration test with multiple conversations against the public checkpoint', 'create_AudioFlamingo3ModelTester': 'create an AudioFlamingo3ModelTester instance to build tiny configs and synthetic audio inputs for testing'}
```

## File: huggingface_transformers/tests/models/audioflamingo3/test_processing_audioflamingo3.py

Prompts

```
['run the AudioFlamingo3ForConditionalGeneration model unit tests using the ModelTesterMixin and GenerationTesterMixin', 'test that SDPA attention implementation dispatches correctly to language model and audio tower submodules', 'run the single sample integration test against the nvidia audio-flamingo-3-hf checkpoint', 'run the batched integration test with multiple conversations against the public checkpoint', 'create an AudioFlamingo3ModelTester instance to build tiny configs and synthetic audio inputs for testing', 'test the AudioFlamingo3Processor save and load pretrained models with tokenizer and feature extractor', 'test the AudioFlamingo3Processor tokenizer integration with slow and fast tokenizers produce identical outputs', 'test the AudioFlamingo3Processor chat template formatting with audio and text conversation inputs', 'test the AudioFlamingo3Processor apply_transcription_request helper generates correct input_ids and input_features', 'test the AudioFlamingo3Processor apply_chat_template with audio modalities and pytorch tensors']
```

Usage

```
{'test_audioflamingo3_processor_save_load': 'test the AudioFlamingo3Processor save and load pretrained models with tokenizer and feature extractor', 'test_audioflamingo3_tokenizer_integration': 'test the AudioFlamingo3Processor tokenizer integration with slow and fast tokenizers produce identical outputs', 'test_audioflamingo3_chat_template': 'test the AudioFlamingo3Processor chat template formatting with audio and text conversation inputs', 'test_audioflamingo3_transcription_request': 'test the AudioFlamingo3Processor apply_transcription_request helper generates correct input_ids and input_features', 'test_audioflamingo3_apply_chat_template_audio': 'test the AudioFlamingo3Processor apply_chat_template with audio modalities and pytorch tensors'}
```

