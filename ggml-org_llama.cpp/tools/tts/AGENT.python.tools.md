# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/tools/tts/convert_pt_to_hf.py

Prompts

```
['convert a PyTorch .pt WavTokenizer model to HuggingFace safetensors format', 'flatten a nested PyTorch state_dict into a flat dictionary with renamed keys', 'rename norm.scale.weight and norm.shift.weight to norm.weight and norm.bias for GGUF compatibility', 'generate a HuggingFace config.json with WavTokenizerDec architecture parameters', 'save a flattened state_dict as safetensors with index.json and weight_map metadata', 'run the TTS CLI to convert text to audio via LLM and decoder server endpoints', 'create audio waveform from spectrogram embeddings using STFT overlap-add synthesis', 'build a WAV file from audio data with RIFF header and 16-bit PCM encoding', 'test text preprocessing that normalizes, cleans, and tokenizes input text into word list', 'summarize Hann window generation for STFT/ISTFT audio processing with periodic option']
```

Usage

```
{'convert_pt_model_to_hf': 'convert a PyTorch .pt WavTokenizer model to HuggingFace safetensors format', 'flatten_state_dict_keys': 'flatten a nested PyTorch state_dict into a flat dictionary with renamed keys', 'rename_norm_weights_for_gguf': 'rename norm.scale.weight and norm.shift.weight to norm.weight and norm.bias for GGUF compatibility', 'generate_hf_config_json': 'generate a HuggingFace config.json with WavTokenizerDec architecture parameters', 'save_safetensors_with_index': 'save a flattened state_dict as safetensors with index.json and weight_map metadata'}
```

## File: ggml-org_llama.cpp/tools/tts/tts-outetts.py

Prompts

```
['convert a PyTorch .pt WavTokenizer model to HuggingFace safetensors format', 'flatten a nested PyTorch state_dict into a flat dictionary with renamed keys', 'rename norm.scale.weight and norm.shift.weight to norm.weight and norm.bias for GGUF compatibility', 'generate a HuggingFace config.json with WavTokenizerDec architecture parameters', 'save a flattened state_dict as safetensors with index.json and weight_map metadata', 'run the TTS CLI to convert text to audio via LLM and decoder server endpoints', 'create audio waveform from spectrogram embeddings using STFT overlap-add synthesis', 'build a WAV file from audio data with RIFF header and 16-bit PCM encoding', 'test text preprocessing that normalizes, cleans, and tokenizes input text into word list', 'summarize Hann window generation for STFT/ISTFT audio processing with periodic option']
```

Usage

```
{'run_tts_text_to_audio': 'run the TTS CLI to convert text to audio via LLM and decoder server endpoints', 'create_embd_to_audio': 'create audio waveform from spectrogram embeddings using STFT overlap-add synthesis', 'build_save_wav': 'build a WAV file from audio data with RIFF header and 16-bit PCM encoding', 'test_process_text': 'test text preprocessing that normalizes, cleans, and tokenizes input text into word list', 'summarize_fill_hann_window': 'summarize Hann window generation for STFT/ISTFT audio processing with periodic option'}
```

