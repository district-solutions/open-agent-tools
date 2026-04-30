# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/voxtral/convert_voxtral_weights_to_hf.py

Prompts

```
['convert Voxtral model weights from Csm format to Hugging Face Transformers format', 'convert the original Voxtral config dictionary to a VoxtralConfig object with text and audio sub-configs', 'convert a state dict from the original format to Hugging Face format with ROPE permutation for attention weights', 'write the converted Voxtral model checkpoint and saved weights to an output directory', 'create and save a VoxtralProcessor with MistralCommonBackend tokenizer and WhisperFeatureExtractor', 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout', 'apply a chat template to a conversation containing audio and text messages for the Voxtral model', 'apply a transcription request to audio input with optional language detection for the Voxtral model', 'tokenize text input for the Voxtral model and return a BatchFeature with input ids', 'extract and chunk mel spectrogram input features from audio arrays for the Voxtral model', 'process audio files or arrays with language specification and return tokenized transcription output']
```

Usage

```
{'convert_voxtral_weights_to_hf': 'convert Voxtral model weights from Csm format to Hugging Face Transformers format', 'convert_config': 'convert the original Voxtral config dictionary to a VoxtralConfig object with text and audio sub-configs', 'convert_state_dict': 'convert a state dict from the original format to Hugging Face format with ROPE permutation for attention weights', 'write_model': 'write the converted Voxtral model checkpoint and saved weights to an output directory', 'write_processor': 'create and save a VoxtralProcessor with MistralCommonBackend tokenizer and WhisperFeatureExtractor'}
```

## File: huggingface_transformers/src/transformers/models/voxtral/modeling_voxtral.py

Prompts

```
['convert Voxtral model weights from Csm format to Hugging Face Transformers format', 'convert the original Voxtral config dictionary to a VoxtralConfig object with text and audio sub-configs', 'convert a state dict from the original format to Hugging Face format with ROPE permutation for attention weights', 'write the converted Voxtral model checkpoint and saved weights to an output directory', 'create and save a VoxtralProcessor with MistralCommonBackend tokenizer and WhisperFeatureExtractor', 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout', 'apply a chat template to a conversation containing audio and text messages for the Voxtral model', 'apply a transcription request to audio input with optional language detection for the Voxtral model', 'tokenize text input for the Voxtral model and return a BatchFeature with input ids', 'extract and chunk mel spectrogram input features from audio arrays for the Voxtral model', 'process audio files or arrays with language specification and return tokenized transcription output']
```

Usage

```
{'create_voxtral_model': 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build_audio_features': 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run_voxtral_generation': 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure_voxtral_encoder': 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test_voxtral_attention': 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout'}
```

## File: huggingface_transformers/src/transformers/models/voxtral/modular_voxtral.py

Prompts

```
['convert Voxtral model weights from Csm format to Hugging Face Transformers format', 'convert the original Voxtral config dictionary to a VoxtralConfig object with text and audio sub-configs', 'convert a state dict from the original format to Hugging Face format with ROPE permutation for attention weights', 'write the converted Voxtral model checkpoint and saved weights to an output directory', 'create and save a VoxtralProcessor with MistralCommonBackend tokenizer and WhisperFeatureExtractor', 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout', 'apply a chat template to a conversation containing audio and text messages for the Voxtral model', 'apply a transcription request to audio input with optional language detection for the Voxtral model', 'tokenize text input for the Voxtral model and return a BatchFeature with input ids', 'extract and chunk mel spectrogram input features from audio arrays for the Voxtral model', 'process audio files or arrays with language specification and return tokenized transcription output']
```

Usage

```
{'create_voxtral_model': 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build_audio_features': 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run_voxtral_generation': 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure_voxtral_encoder': 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test_voxtral_attention': 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout'}
```

## File: huggingface_transformers/src/transformers/models/voxtral/processing_voxtral.py

Prompts

```
['convert Voxtral model weights from Csm format to Hugging Face Transformers format', 'convert the original Voxtral config dictionary to a VoxtralConfig object with text and audio sub-configs', 'convert a state dict from the original format to Hugging Face format with ROPE permutation for attention weights', 'write the converted Voxtral model checkpoint and saved weights to an output directory', 'create and save a VoxtralProcessor with MistralCommonBackend tokenizer and WhisperFeatureExtractor', 'create a VoxtralForConditionalGeneration model for audio-text multimodal generation', 'build audio embeddings from mel spectrogram input features using get_audio_features', 'run text generation with VoxtralForConditionalGeneration using audio and text inputs', 'configure a VoxtralEncoder with Whisper-based audio processing layers', 'test the VoxtralAttention multi-headed attention mechanism with configurable heads and dropout', 'apply a chat template to a conversation containing audio and text messages for the Voxtral model', 'apply a transcription request to audio input with optional language detection for the Voxtral model', 'tokenize text input for the Voxtral model and return a BatchFeature with input ids', 'extract and chunk mel spectrogram input features from audio arrays for the Voxtral model', 'process audio files or arrays with language specification and return tokenized transcription output']
```

Usage

```
{'apply_chat_template_audio_text': 'apply a chat template to a conversation containing audio and text messages for the Voxtral model', 'apply_transcription_request': 'apply a transcription request to audio input with optional language detection for the Voxtral model', 'tokenize_text_input': 'tokenize text input for the Voxtral model and return a BatchFeature with input ids', 'retrieve_input_features': 'extract and chunk mel spectrogram input features from audio arrays for the Voxtral model', 'process_audio_transcription': 'process audio files or arrays with language specification and return tokenized transcription output'}
```

