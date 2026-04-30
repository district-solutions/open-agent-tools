# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/kyutai_speech_to_text/test_modeling_kyutai_speech_to_text.py

Prompts

```
['test the KyutaiSpeechToTextModel and KyutaiSpeechToTextForConditionalGeneration model classes with config and input tensors', 'test the KyutaiSpeechToTextForConditionalGeneration model generate method with audio input values and padding masks', 'test bf16 and fp16 dtype conversion with codec_model kept in fp32 for KyutaiSpeechToTextForConditionalGeneration', 'test generation output tokens against expected values using LibriSpeech audio samples with KyutaiSpeechToTextProcessor', 'test batched generation output tokens against expected values for multiple audio samples with KyutaiSpeechToTextForConditionalGeneration']
```

Usage

```
{'test_model_kyutai_speech_to_text': 'test the KyutaiSpeechToTextModel and KyutaiSpeechToTextForConditionalGeneration model classes with config and input tensors', 'test_generation_kyutai_speech_to_text': 'test the KyutaiSpeechToTextForConditionalGeneration model generate method with audio input values and padding masks', 'test_bf16_fp32_conversion': 'test bf16 and fp16 dtype conversion with codec_model kept in fp32 for KyutaiSpeechToTextForConditionalGeneration', 'test_integration_generation': 'test generation output tokens against expected values using LibriSpeech audio samples with KyutaiSpeechToTextProcessor', 'test_generation_batched': 'test batched generation output tokens against expected values for multiple audio samples with KyutaiSpeechToTextForConditionalGeneration'}
```

