# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/granite_speech/test_modeling_granite_speech.py

Prompts

```
['test the GraniteSpeechForConditionalGeneration model forward pass using FP16 precision and verify logits are not NaN', 'test the GraniteSpeechForConditionalGeneration model forward pass using torch autocast with FP16 on CUDA device', 'test the GraniteSpeechForConditionalGeneration model with inputs_embeds instead of input_ids and without input_features', 'test that GraniteSpeech composite model can dispatch to SDPA attention implementation when saving and reloading', 'run a single sample integration test that loads granite-speech-3.3-2b and generates transcription output from audio input', 'test that GraniteSpeechProcessor can save and reload from pretrained checkpoint correctly', 'test that GraniteSpeechProcessor raises TypeError when text input is None or wrong type', 'test that GraniteSpeechProcessor raises TypeError when audio input is a string or wrong type', 'test that GraniteSpeechProcessor fills audio tokens correctly for same-length and varying-length feature tensors', 'test that GraniteSpeechProcessor places input features on the specified CPU or CUDA device']
```

Usage

```
{'test_granite_speech_model_fp16_forward': 'test the GraniteSpeechForConditionalGeneration model forward pass using FP16 precision and verify logits are not NaN', 'test_granite_speech_model_fp16_autocast': 'test the GraniteSpeechForConditionalGeneration model forward pass using torch autocast with FP16 on CUDA device', 'test_granite_speech_inputs_embeds': 'test the GraniteSpeechForConditionalGeneration model with inputs_embeds instead of input_ids and without input_features', 'test_granite_speech_sdpa_dispatch': 'test that GraniteSpeech composite model can dispatch to SDPA attention implementation when saving and reloading', 'test_granite_speech_integration_single': 'run a single sample integration test that loads granite-speech-3.3-2b and generates transcription output from audio input'}
```

## File: huggingface_transformers/tests/models/granite_speech/test_processing_granite_speech.py

Prompts

```
['test the GraniteSpeechForConditionalGeneration model forward pass using FP16 precision and verify logits are not NaN', 'test the GraniteSpeechForConditionalGeneration model forward pass using torch autocast with FP16 on CUDA device', 'test the GraniteSpeechForConditionalGeneration model with inputs_embeds instead of input_ids and without input_features', 'test that GraniteSpeech composite model can dispatch to SDPA attention implementation when saving and reloading', 'run a single sample integration test that loads granite-speech-3.3-2b and generates transcription output from audio input', 'test that GraniteSpeechProcessor can save and reload from pretrained checkpoint correctly', 'test that GraniteSpeechProcessor raises TypeError when text input is None or wrong type', 'test that GraniteSpeechProcessor raises TypeError when audio input is a string or wrong type', 'test that GraniteSpeechProcessor fills audio tokens correctly for same-length and varying-length feature tensors', 'test that GraniteSpeechProcessor places input features on the specified CPU or CUDA device']
```

Usage

```
{'test_granite_speech_processor_save_load': 'test that GraniteSpeechProcessor can save and reload from pretrained checkpoint correctly', 'test_granite_speech_processor_text_validation': 'test that GraniteSpeechProcessor raises TypeError when text input is None or wrong type', 'test_granite_speech_processor_audio_validation': 'test that GraniteSpeechProcessor raises TypeError when audio input is a string or wrong type', 'test_granite_speech_processor_audio_token_filling': 'test that GraniteSpeechProcessor fills audio tokens correctly for same-length and varying-length feature tensors', 'test_granite_speech_processor_device_placement': 'test that GraniteSpeechProcessor places input features on the specified CPU or CUDA device'}
```

