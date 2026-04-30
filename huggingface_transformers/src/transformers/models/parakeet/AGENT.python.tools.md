# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/parakeet/convert_nemo_to_hf.py

Prompts

```
['convert a NeMo Parakeet model checkpoint to HuggingFace format with encoder or CTC architecture', 'extract a .nemo tar archive and locate model weights, config, and tokenizer files', 'write a ParakeetProcessor with feature extractor and tokenizer from NeMo config', 'convert a NeMo encoder configuration dictionary to HuggingFace ParakeetEncoderConfig', 'load a NeMo state dict and remap keys to HuggingFace Parakeet model naming convention', 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run the ParakeetEncoder forward pass on audio input features to get hidden states', 'build a ParakeetEncoder with multi-head attention, relative positional encoding, and convolution modules', 'test the ParakeetForCTC forward pass with labels to compute CTC loss', 'generate ASR transcription from audio using ParakeetForCTC greedy decoding', 'run the ParakeetEncoder model on audio input features to extract hidden state representations', 'build a ParakeetEncoderBlock layer with conformer-style feed-forward, attention, and convolution modules', 'test the ParakeetEncoderAttention module with relative positional encoding and global content bias', 'create a ParakeetProcessor instance wrapping a feature extractor and tokenizer for speech recognition', 'process raw audio input and corresponding text tokens into model-ready input features with attention masks and labels', 'process raw audio input without text into feature extractor output tensors with padding and attention masks', "validate that provided audio sampling rate matches the processor's expected 16000 Hz sampling rate", 'get the list of model input names including feature extractor outputs and labels for the ParakeetProcessor']
```

Usage

```
{'convert_nemo_to_hf_model': 'convert a NeMo Parakeet model checkpoint to HuggingFace format with encoder or CTC architecture', 'extract_nemo_archive': 'extract a .nemo tar archive and locate model weights, config, and tokenizer files', 'write_processor': 'write a ParakeetProcessor with feature extractor and tokenizer from NeMo config', 'convert_encoder_config': 'convert a NeMo encoder configuration dictionary to HuggingFace ParakeetEncoderConfig', 'load_and_convert_state_dict': 'load a NeMo state dict and remap keys to HuggingFace Parakeet model naming convention'}
```

## File: huggingface_transformers/src/transformers/models/parakeet/modeling_parakeet.py

Prompts

```
['convert a NeMo Parakeet model checkpoint to HuggingFace format with encoder or CTC architecture', 'extract a .nemo tar archive and locate model weights, config, and tokenizer files', 'write a ParakeetProcessor with feature extractor and tokenizer from NeMo config', 'convert a NeMo encoder configuration dictionary to HuggingFace ParakeetEncoderConfig', 'load a NeMo state dict and remap keys to HuggingFace Parakeet model naming convention', 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run the ParakeetEncoder forward pass on audio input features to get hidden states', 'build a ParakeetEncoder with multi-head attention, relative positional encoding, and convolution modules', 'test the ParakeetForCTC forward pass with labels to compute CTC loss', 'generate ASR transcription from audio using ParakeetForCTC greedy decoding', 'run the ParakeetEncoder model on audio input features to extract hidden state representations', 'build a ParakeetEncoderBlock layer with conformer-style feed-forward, attention, and convolution modules', 'test the ParakeetEncoderAttention module with relative positional encoding and global content bias', 'create a ParakeetProcessor instance wrapping a feature extractor and tokenizer for speech recognition', 'process raw audio input and corresponding text tokens into model-ready input features with attention masks and labels', 'process raw audio input without text into feature extractor output tensors with padding and attention masks', "validate that provided audio sampling rate matches the processor's expected 16000 Hz sampling rate", 'get the list of model input names including feature extractor outputs and labels for the ParakeetProcessor']
```

Usage

```
{'create_parakeet_for_ctc_model': 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run_parakeet_encoder_forward': 'run the ParakeetEncoder forward pass on audio input features to get hidden states', 'build_parakeet_encoder_with_attention': 'build a ParakeetEncoder with multi-head attention, relative positional encoding, and convolution modules', 'test_parakeet_ctc_loss_computation': 'test the ParakeetForCTC forward pass with labels to compute CTC loss', 'generate_parakeet_transcription': 'generate ASR transcription from audio using ParakeetForCTC greedy decoding'}
```

## File: huggingface_transformers/src/transformers/models/parakeet/modular_parakeet.py

Prompts

```
['convert a NeMo Parakeet model checkpoint to HuggingFace format with encoder or CTC architecture', 'extract a .nemo tar archive and locate model weights, config, and tokenizer files', 'write a ParakeetProcessor with feature extractor and tokenizer from NeMo config', 'convert a NeMo encoder configuration dictionary to HuggingFace ParakeetEncoderConfig', 'load a NeMo state dict and remap keys to HuggingFace Parakeet model naming convention', 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run the ParakeetEncoder forward pass on audio input features to get hidden states', 'build a ParakeetEncoder with multi-head attention, relative positional encoding, and convolution modules', 'test the ParakeetForCTC forward pass with labels to compute CTC loss', 'generate ASR transcription from audio using ParakeetForCTC greedy decoding', 'run the ParakeetEncoder model on audio input features to extract hidden state representations', 'build a ParakeetEncoderBlock layer with conformer-style feed-forward, attention, and convolution modules', 'test the ParakeetEncoderAttention module with relative positional encoding and global content bias', 'create a ParakeetProcessor instance wrapping a feature extractor and tokenizer for speech recognition', 'process raw audio input and corresponding text tokens into model-ready input features with attention masks and labels', 'process raw audio input without text into feature extractor output tensors with padding and attention masks', "validate that provided audio sampling rate matches the processor's expected 16000 Hz sampling rate", 'get the list of model input names including feature extractor outputs and labels for the ParakeetProcessor']
```

Usage

```
{'create_parakeet_for_ctc_model': 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run_parakeet_encoder_inference': 'run the ParakeetEncoder model on audio input features to extract hidden state representations', 'generate_parakeet_transcription': 'generate ASR transcriptions from audio input features using greedy decoding in ParakeetForCTC', 'build_parakeet_encoder_layer': 'build a ParakeetEncoderBlock layer with conformer-style feed-forward, attention, and convolution modules', 'test_parakeet_attention_with_relative_encoding': 'test the ParakeetEncoderAttention module with relative positional encoding and global content bias'}
```

## File: huggingface_transformers/src/transformers/models/parakeet/processing_parakeet.py

Prompts

```
['convert a NeMo Parakeet model checkpoint to HuggingFace format with encoder or CTC architecture', 'extract a .nemo tar archive and locate model weights, config, and tokenizer files', 'write a ParakeetProcessor with feature extractor and tokenizer from NeMo config', 'convert a NeMo encoder configuration dictionary to HuggingFace ParakeetEncoderConfig', 'load a NeMo state dict and remap keys to HuggingFace Parakeet model naming convention', 'create a ParakeetForCTC model for automatic speech recognition with CTC loss', 'run the ParakeetEncoder forward pass on audio input features to get hidden states', 'build a ParakeetEncoder with multi-head attention, relative positional encoding, and convolution modules', 'test the ParakeetForCTC forward pass with labels to compute CTC loss', 'generate ASR transcription from audio using ParakeetForCTC greedy decoding', 'run the ParakeetEncoder model on audio input features to extract hidden state representations', 'build a ParakeetEncoderBlock layer with conformer-style feed-forward, attention, and convolution modules', 'test the ParakeetEncoderAttention module with relative positional encoding and global content bias', 'create a ParakeetProcessor instance wrapping a feature extractor and tokenizer for speech recognition', 'process raw audio input and corresponding text tokens into model-ready input features with attention masks and labels', 'process raw audio input without text into feature extractor output tensors with padding and attention masks', "validate that provided audio sampling rate matches the processor's expected 16000 Hz sampling rate", 'get the list of model input names including feature extractor outputs and labels for the ParakeetProcessor']
```

Usage

```
{'create_parakeet_processor': 'create a ParakeetProcessor instance wrapping a feature extractor and tokenizer for speech recognition', 'process_audio_with_text': 'process raw audio input and corresponding text tokens into model-ready input features with attention masks and labels', 'process_audio_only': 'process raw audio input without text into feature extractor output tensors with padding and attention masks', 'validate_sampling_rate': "validate that provided audio sampling rate matches the processor's expected 16000 Hz sampling rate", 'get_model_input_names': 'get the list of model input names including feature extractor outputs and labels for the ParakeetProcessor'}
```

