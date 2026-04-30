# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/moonshine_streaming/modeling_moonshine_streaming.py

Prompts

```
['create a MoonshineStreamingForConditionalGeneration model for automatic speech recognition', 'run MoonshineStreamingForConditionalGeneration.generate to transcribe raw audio waveform input into text', 'build MoonshineStreamingEncoder with causal convolutions and sliding-window attention for audio feature extraction', 'test MoonshineStreamingDecoder with self-attention, cross-attention, and rotary embeddings for seq2seq generation', 'refactor MoonshineStreamingModel.forward to support encoder-decoder inference with past_key_values caching', 'create a MoonshineStreamingForConditionalGeneration model from a MoonshineStreamingConfig for streaming speech recognition', 'run the MoonshineStreamingEncoder forward pass on raw audio input values with an attention mask', 'test the MoonshineStreamingEncoderEmbedder CMVN, asinh compression, and causal conv1d audio feature extraction pipeline', 'review the MoonshineStreamingDecoder forward method that adds positional embeddings and projects encoder hidden states into cross-attention', 'create a MoonshineStreamingProcessor instance with a feature extractor and tokenizer for audio-text processing', 'call the MoonshineStreamingProcessor with audio input to extract feature inputs for the model', 'call the MoonshineStreamingProcessor with text input to tokenize and encode text for the model', 'call the MoonshineStreamingProcessor with both audio and text to produce features with labels for training', 'pad a batch of input features and labels using the MoonshineStreamingProcessor pad method', 'get the model input names from the MoonshineStreamingProcessor combining feature extractor names and labels']
```

Usage

```
{'create_moonshine_streaming_asr_model': 'create a MoonshineStreamingForConditionalGeneration model for automatic speech recognition', 'run_moonshine_streaming_transcription': 'run MoonshineStreamingForConditionalGeneration.generate to transcribe raw audio waveform input into text', 'build_moonshine_streaming_encoder': 'build MoonshineStreamingEncoder with causal convolutions and sliding-window attention for audio feature extraction', 'test_moonshine_streaming_decoder': 'test MoonshineStreamingDecoder with self-attention, cross-attention, and rotary embeddings for seq2seq generation', 'refactor_moonshine_streaming_forward': 'refactor MoonshineStreamingModel.forward to support encoder-decoder inference with past_key_values caching'}
```

## File: huggingface_transformers/src/transformers/models/moonshine_streaming/modular_moonshine_streaming.py

Prompts

```
['create a MoonshineStreamingForConditionalGeneration model for automatic speech recognition', 'run MoonshineStreamingForConditionalGeneration.generate to transcribe raw audio waveform input into text', 'build MoonshineStreamingEncoder with causal convolutions and sliding-window attention for audio feature extraction', 'test MoonshineStreamingDecoder with self-attention, cross-attention, and rotary embeddings for seq2seq generation', 'refactor MoonshineStreamingModel.forward to support encoder-decoder inference with past_key_values caching', 'create a MoonshineStreamingForConditionalGeneration model from a MoonshineStreamingConfig for streaming speech recognition', 'run the MoonshineStreamingEncoder forward pass on raw audio input values with an attention mask', 'test the MoonshineStreamingEncoderEmbedder CMVN, asinh compression, and causal conv1d audio feature extraction pipeline', 'review the MoonshineStreamingDecoder forward method that adds positional embeddings and projects encoder hidden states into cross-attention', 'create a MoonshineStreamingProcessor instance with a feature extractor and tokenizer for audio-text processing', 'call the MoonshineStreamingProcessor with audio input to extract feature inputs for the model', 'call the MoonshineStreamingProcessor with text input to tokenize and encode text for the model', 'call the MoonshineStreamingProcessor with both audio and text to produce features with labels for training', 'pad a batch of input features and labels using the MoonshineStreamingProcessor pad method', 'get the model input names from the MoonshineStreamingProcessor combining feature extractor names and labels']
```

Usage

```
{'create_moonshine_streaming_model': 'create a MoonshineStreamingForConditionalGeneration model from a MoonshineStreamingConfig for streaming speech recognition', 'build_moonshine_streaming_encoder': 'build a MoonshineStreamingEncoder with causal convolutions and sliding-window self-attention for streaming audio processing', 'run_moonshine_streaming_forward': 'run the MoonshineStreamingEncoder forward pass on raw audio input values with an attention mask', 'test_moonshine_streaming_encoder_embedder': 'test the MoonshineStreamingEncoderEmbedder CMVN, asinh compression, and causal conv1d audio feature extraction pipeline', 'review_moonshine_streaming_decoder': 'review the MoonshineStreamingDecoder forward method that adds positional embeddings and projects encoder hidden states into cross-attention'}
```

## File: huggingface_transformers/src/transformers/models/moonshine_streaming/processing_moonshine_streaming.py

Prompts

```
['create a MoonshineStreamingForConditionalGeneration model for automatic speech recognition', 'run MoonshineStreamingForConditionalGeneration.generate to transcribe raw audio waveform input into text', 'build MoonshineStreamingEncoder with causal convolutions and sliding-window attention for audio feature extraction', 'test MoonshineStreamingDecoder with self-attention, cross-attention, and rotary embeddings for seq2seq generation', 'refactor MoonshineStreamingModel.forward to support encoder-decoder inference with past_key_values caching', 'create a MoonshineStreamingForConditionalGeneration model from a MoonshineStreamingConfig for streaming speech recognition', 'run the MoonshineStreamingEncoder forward pass on raw audio input values with an attention mask', 'test the MoonshineStreamingEncoderEmbedder CMVN, asinh compression, and causal conv1d audio feature extraction pipeline', 'review the MoonshineStreamingDecoder forward method that adds positional embeddings and projects encoder hidden states into cross-attention', 'create a MoonshineStreamingProcessor instance with a feature extractor and tokenizer for audio-text processing', 'call the MoonshineStreamingProcessor with audio input to extract feature inputs for the model', 'call the MoonshineStreamingProcessor with text input to tokenize and encode text for the model', 'call the MoonshineStreamingProcessor with both audio and text to produce features with labels for training', 'pad a batch of input features and labels using the MoonshineStreamingProcessor pad method', 'get the model input names from the MoonshineStreamingProcessor combining feature extractor names and labels']
```

Usage

```
{'create_moonshine_streaming_processor': 'create a MoonshineStreamingProcessor instance with a feature extractor and tokenizer for audio-text processing', 'call_processor_with_audio': 'call the MoonshineStreamingProcessor with audio input to extract feature inputs for the model', 'call_processor_with_text': 'call the MoonshineStreamingProcessor with text input to tokenize and encode text for the model', 'call_processor_with_audio_and_text': 'call the MoonshineStreamingProcessor with both audio and text to produce features with labels for training', 'pad_processor_batch': 'pad a batch of input features and labels using the MoonshineStreamingProcessor pad method', 'get_model_input_names': 'get the model input names from the MoonshineStreamingProcessor combining feature extractor names and labels'}
```

