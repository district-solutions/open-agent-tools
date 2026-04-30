# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/multimodal_audio/qwen2_audio.py

Prompts

```
['quantize a Qwen2-Audio model using GPTQ W4A16 scheme with llmcompressor oneshot', 'preprocess a multimodal audio dataset with chat template and audio tokenization', 'generate audio transcription from a Qwen2-Audio model using processor and model.generate', 'save a quantized Qwen2-Audio model and processor to disk with compression', 'configure GPTQ quantization with W4A16 scheme targeting Linear layers while ignoring lm_head', 'run GPTQ W4A16 quantization on a Whisper large-v3 model using llmcompressor oneshot', 'load a pretrained WhisperForConditionalGeneration model and WhisperProcessor from Hugging Face', 'generate audio transcriptions from a quantized Whisper model using model.generate']
```

Usage

```
{'quantize_qwen2_audio_model': 'quantize a Qwen2-Audio model using GPTQ W4A16 scheme with llmcompressor oneshot', 'preprocess_audio_dataset': 'preprocess a multimodal audio dataset with chat template and audio tokenization', 'generate_audio_transcription': 'generate audio transcription from a Qwen2-Audio model using processor and model.generate', 'save_quantized_model': 'save a quantized Qwen2-Audio model and processor to disk with compression', 'configure_gptq_quantization': 'configure GPTQ quantization with W4A16 scheme targeting Linear layers while ignoring lm_head'}
```

## File: vllm-project_llm-compressor/examples/multimodal_audio/whisper_example.py

Prompts

```
['quantize a Qwen2-Audio model using GPTQ W4A16 scheme with llmcompressor oneshot', 'preprocess a multimodal audio dataset with chat template and audio tokenization', 'generate audio transcription from a Qwen2-Audio model using processor and model.generate', 'save a quantized Qwen2-Audio model and processor to disk with compression', 'configure GPTQ quantization with W4A16 scheme targeting Linear layers while ignoring lm_head', 'run GPTQ W4A16 quantization on a Whisper large-v3 model using llmcompressor oneshot', 'load a pretrained WhisperForConditionalGeneration model and WhisperProcessor from Hugging Face', 'generate audio transcriptions from a quantized Whisper model using model.generate']
```

Usage

```
{'run_whisper_quantization': 'run GPTQ W4A16 quantization on a Whisper large-v3 model using llmcompressor oneshot', 'load_whisper_model': 'load a pretrained WhisperForConditionalGeneration model and WhisperProcessor from Hugging Face', 'preprocess_audio_dataset': 'preprocess an audio transcription dataset with WhisperProcessor for GPTQ calibration', 'generate_transcription': 'generate audio transcriptions from a quantized Whisper model using model.generate', 'save_quantized_model': 'save a quantized Whisper model and processor to disk with compression enabled'}
```

