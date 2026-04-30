# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/audioflamingo3/convert_audioflamingo3_to_hf.py

Prompts

```
['convert AudioFlamingo3 checkpoint from NVIDIA format to Hugging Face repository layout', 'run the CLI converter with --src_dir, --dst_dir, and optional --push_to_hub arguments', 'write processor with tokenizer and feature extractor from source directory to destination', 'merge and shard model weights from source components into Hugging Face safetensors format', 'push converted processor and model assets to a Hugging Face Hub repository', 'create an AudioFlamingo3ForConditionalGeneration model from a config for audio-to-text conditional generation', 'get audio embeddings from input mel spectrogram features using the audio tower and multi-modal projector', 'generate text outputs from combined audio features and input token ids using the language model', 'build an AudioFlamingo3Encoder with conv1d front-end, transformer layers, avg pooler, and layer norm', 'prepare inputs for autoregressive generation by injecting audio features on the first iteration', 'create an AudioFlamingo3ForConditionalGeneration model for audio-to-text conditional generation', 'run the AudioFlamingo3ForConditionalGeneration forward pass with input_ids and audio features', 'get audio embeddings from log-mel spectrogram input features using AudioFlamingo3ForConditionalGeneration', 'build an AudioFlamingo3Encoder that processes audio features through a Whisper encoder with average pooling', 'run audio transcription generation with AudioFlamingo3ForConditionalGeneration using model.generate', 'create an AudioFlamingo3Processor wrapping a feature extractor and tokenizer for audio-text model inputs', 'call the processor with text and audio arrays to expand sound tokens and extract log-mel features', 'prepare ASR inputs for speech recognition using apply_transcription_request with audio paths and custom prompts', 'decode model output ids and strip assistant transcription prefixes and surrounding quotes', 'generate training labels by masking audio tokens and pad tokens with -100 in the input ids']
```

Usage

```
{'convert_audioflamingo3_to_hf': 'convert AudioFlamingo3 checkpoint from NVIDIA format to Hugging Face repository layout', 'run_convert_cli': 'run the CLI converter with --src_dir, --dst_dir, and optional --push_to_hub arguments', 'write_processor': 'write processor with tokenizer and feature extractor from source directory to destination', 'merge_and_shard_weights': 'merge and shard model weights from source components into Hugging Face safetensors format', 'push_to_hub': 'push converted processor and model assets to a Hugging Face Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/audioflamingo3/modeling_audioflamingo3.py

Prompts

```
['convert AudioFlamingo3 checkpoint from NVIDIA format to Hugging Face repository layout', 'run the CLI converter with --src_dir, --dst_dir, and optional --push_to_hub arguments', 'write processor with tokenizer and feature extractor from source directory to destination', 'merge and shard model weights from source components into Hugging Face safetensors format', 'push converted processor and model assets to a Hugging Face Hub repository', 'create an AudioFlamingo3ForConditionalGeneration model from a config for audio-to-text conditional generation', 'get audio embeddings from input mel spectrogram features using the audio tower and multi-modal projector', 'generate text outputs from combined audio features and input token ids using the language model', 'build an AudioFlamingo3Encoder with conv1d front-end, transformer layers, avg pooler, and layer norm', 'prepare inputs for autoregressive generation by injecting audio features on the first iteration', 'create an AudioFlamingo3ForConditionalGeneration model for audio-to-text conditional generation', 'run the AudioFlamingo3ForConditionalGeneration forward pass with input_ids and audio features', 'get audio embeddings from log-mel spectrogram input features using AudioFlamingo3ForConditionalGeneration', 'build an AudioFlamingo3Encoder that processes audio features through a Whisper encoder with average pooling', 'run audio transcription generation with AudioFlamingo3ForConditionalGeneration using model.generate', 'create an AudioFlamingo3Processor wrapping a feature extractor and tokenizer for audio-text model inputs', 'call the processor with text and audio arrays to expand sound tokens and extract log-mel features', 'prepare ASR inputs for speech recognition using apply_transcription_request with audio paths and custom prompts', 'decode model output ids and strip assistant transcription prefixes and surrounding quotes', 'generate training labels by masking audio tokens and pad tokens with -100 in the input ids']
```

Usage

```
{'create_audio_flamingo3_model': 'create an AudioFlamingo3ForConditionalGeneration model from a config for audio-to-text conditional generation', 'get_audio_features_from_waveform': 'get audio embeddings from input mel spectrogram features using the audio tower and multi-modal projector', 'generate_text_from_audio_and_text': 'generate text outputs from combined audio features and input token ids using the language model', 'build_audio_encoder_with_convolutions': 'build an AudioFlamingo3Encoder with conv1d front-end, transformer layers, avg pooler, and layer norm', 'prepare_inputs_for_autoregressive_generation': 'prepare inputs for autoregressive generation by injecting audio features on the first iteration'}
```

## File: huggingface_transformers/src/transformers/models/audioflamingo3/modular_audioflamingo3.py

Prompts

```
['convert AudioFlamingo3 checkpoint from NVIDIA format to Hugging Face repository layout', 'run the CLI converter with --src_dir, --dst_dir, and optional --push_to_hub arguments', 'write processor with tokenizer and feature extractor from source directory to destination', 'merge and shard model weights from source components into Hugging Face safetensors format', 'push converted processor and model assets to a Hugging Face Hub repository', 'create an AudioFlamingo3ForConditionalGeneration model from a config for audio-to-text conditional generation', 'get audio embeddings from input mel spectrogram features using the audio tower and multi-modal projector', 'generate text outputs from combined audio features and input token ids using the language model', 'build an AudioFlamingo3Encoder with conv1d front-end, transformer layers, avg pooler, and layer norm', 'prepare inputs for autoregressive generation by injecting audio features on the first iteration', 'create an AudioFlamingo3ForConditionalGeneration model for audio-to-text conditional generation', 'run the AudioFlamingo3ForConditionalGeneration forward pass with input_ids and audio features', 'get audio embeddings from log-mel spectrogram input features using AudioFlamingo3ForConditionalGeneration', 'build an AudioFlamingo3Encoder that processes audio features through a Whisper encoder with average pooling', 'run audio transcription generation with AudioFlamingo3ForConditionalGeneration using model.generate', 'create an AudioFlamingo3Processor wrapping a feature extractor and tokenizer for audio-text model inputs', 'call the processor with text and audio arrays to expand sound tokens and extract log-mel features', 'prepare ASR inputs for speech recognition using apply_transcription_request with audio paths and custom prompts', 'decode model output ids and strip assistant transcription prefixes and surrounding quotes', 'generate training labels by masking audio tokens and pad tokens with -100 in the input ids']
```

Usage

```
{'create_audioflamingo3_model': 'create an AudioFlamingo3ForConditionalGeneration model for audio-to-text conditional generation', 'run_audioflamingo3_forward': 'run the AudioFlamingo3ForConditionalGeneration forward pass with input_ids and audio features', 'get_audio_features': 'get audio embeddings from log-mel spectrogram input features using AudioFlamingo3ForConditionalGeneration', 'build_audio_encoder': 'build an AudioFlamingo3Encoder that processes audio features through a Whisper encoder with average pooling', 'run_audioflamingo3_generate': 'run audio transcription generation with AudioFlamingo3ForConditionalGeneration using model.generate'}
```

## File: huggingface_transformers/src/transformers/models/audioflamingo3/processing_audioflamingo3.py

Prompts

```
['convert AudioFlamingo3 checkpoint from NVIDIA format to Hugging Face repository layout', 'run the CLI converter with --src_dir, --dst_dir, and optional --push_to_hub arguments', 'write processor with tokenizer and feature extractor from source directory to destination', 'merge and shard model weights from source components into Hugging Face safetensors format', 'push converted processor and model assets to a Hugging Face Hub repository', 'create an AudioFlamingo3ForConditionalGeneration model from a config for audio-to-text conditional generation', 'get audio embeddings from input mel spectrogram features using the audio tower and multi-modal projector', 'generate text outputs from combined audio features and input token ids using the language model', 'build an AudioFlamingo3Encoder with conv1d front-end, transformer layers, avg pooler, and layer norm', 'prepare inputs for autoregressive generation by injecting audio features on the first iteration', 'create an AudioFlamingo3ForConditionalGeneration model for audio-to-text conditional generation', 'run the AudioFlamingo3ForConditionalGeneration forward pass with input_ids and audio features', 'get audio embeddings from log-mel spectrogram input features using AudioFlamingo3ForConditionalGeneration', 'build an AudioFlamingo3Encoder that processes audio features through a Whisper encoder with average pooling', 'run audio transcription generation with AudioFlamingo3ForConditionalGeneration using model.generate', 'create an AudioFlamingo3Processor wrapping a feature extractor and tokenizer for audio-text model inputs', 'call the processor with text and audio arrays to expand sound tokens and extract log-mel features', 'prepare ASR inputs for speech recognition using apply_transcription_request with audio paths and custom prompts', 'decode model output ids and strip assistant transcription prefixes and surrounding quotes', 'generate training labels by masking audio tokens and pad tokens with -100 in the input ids']
```

Usage

```
{'create_AudioFlamingo3Processor': 'create an AudioFlamingo3Processor wrapping a feature extractor and tokenizer for audio-text model inputs', 'process_audio_text_with_call': 'call the processor with text and audio arrays to expand sound tokens and extract log-mel features', 'prepare_transcription_with_apply_transcription_request': 'prepare ASR inputs for speech recognition using apply_transcription_request with audio paths and custom prompts', 'decode_outputs_with_strip_prefix': 'decode model output ids and strip assistant transcription prefixes and surrounding quotes', 'generate_training_labels_with_output_labels': 'generate training labels by masking audio tokens and pad tokens with -100 in the input ids'}
```

