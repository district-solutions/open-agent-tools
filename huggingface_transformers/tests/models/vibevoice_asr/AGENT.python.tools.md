# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vibevoice_asr/test_modeling_vibevoice_asr.py

Prompts

```
['test the VibeVoiceAsrModelTester to build a tiny VibeVoice ASR config with acoustic and semantic tokenizer settings', 'test the VibeVoiceAsrModelTester to prepare synthetic input IDs, attention masks, and audio input values for model testing', 'test the VibeVoiceAsrForConditionalGeneration model to verify SDPA and eager attention dispatch for composite audio-text models', 'test the VibeVoiceAsrForConditionalGeneration get_audio_features method to extract acoustic token hidden states from raw audio input', 'test the VibeVoice ASR integration to transcribe a single audio sample using the microsoft/VibeVoice-ASR-HF checkpoint', 'load the VibeVoiceAsrProcessor from a pretrained HuggingFace checkpoint using from_pretrained', 'save a VibeVoiceAsrProcessor with its tokenizer and feature extractor to a local directory', 'transcribe an audio file using apply_transcription_request with a text prompt and audio URL', 'apply a chat template to a conversation containing text and audio content with tokenization', 'decode model generated token IDs into parsed transcripts with timestamps or plain text']
```

Usage

```
{'test_VibeVoiceAsrModelTester_get_config': 'test the VibeVoiceAsrModelTester to build a tiny VibeVoice ASR config with acoustic and semantic tokenizer settings', 'test_VibeVoiceAsrModelTester_prepare_inputs': 'test the VibeVoiceAsrModelTester to prepare synthetic input IDs, attention masks, and audio input values for model testing', 'test_VibeVoiceAsrForConditionalGeneration_sdpa_dispatch': 'test the VibeVoiceAsrForConditionalGeneration model to verify SDPA and eager attention dispatch for composite audio-text models', 'test_VibeVoiceAsrForConditionalGeneration_audio_features': 'test the VibeVoiceAsrForConditionalGeneration get_audio_features method to extract acoustic token hidden states from raw audio input', 'test_VibeVoiceAsrIntegration_single_transcription': 'test the VibeVoice ASR integration to transcribe a single audio sample using the microsoft/VibeVoice-ASR-HF checkpoint'}
```

## File: huggingface_transformers/tests/models/vibevoice_asr/test_processing_vibevoice_asr.py

Prompts

```
['test the VibeVoiceAsrModelTester to build a tiny VibeVoice ASR config with acoustic and semantic tokenizer settings', 'test the VibeVoiceAsrModelTester to prepare synthetic input IDs, attention masks, and audio input values for model testing', 'test the VibeVoiceAsrForConditionalGeneration model to verify SDPA and eager attention dispatch for composite audio-text models', 'test the VibeVoiceAsrForConditionalGeneration get_audio_features method to extract acoustic token hidden states from raw audio input', 'test the VibeVoice ASR integration to transcribe a single audio sample using the microsoft/VibeVoice-ASR-HF checkpoint', 'load the VibeVoiceAsrProcessor from a pretrained HuggingFace checkpoint using from_pretrained', 'save a VibeVoiceAsrProcessor with its tokenizer and feature extractor to a local directory', 'transcribe an audio file using apply_transcription_request with a text prompt and audio URL', 'apply a chat template to a conversation containing text and audio content with tokenization', 'decode model generated token IDs into parsed transcripts with timestamps or plain text']
```

Usage

```
{'load_vibevoice_asr_processor': 'load the VibeVoiceAsrProcessor from a pretrained HuggingFace checkpoint using from_pretrained', 'save_vibevoice_asr_processor': 'save a VibeVoiceAsrProcessor with its tokenizer and feature extractor to a local directory', 'transcribe_audio_with_prompt': 'transcribe an audio file using apply_transcription_request with a text prompt and audio URL', 'apply_chat_template_with_audio': 'apply a chat template to a conversation containing text and audio content with tokenization', 'decode_generated_ids': 'decode model generated token IDs into parsed transcripts with timestamps or plain text'}
```

