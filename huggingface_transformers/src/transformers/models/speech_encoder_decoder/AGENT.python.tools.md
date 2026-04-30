# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/speech_encoder_decoder/configuration_speech_encoder_decoder.py

Prompts

```
['create a SpeechEncoderDecoderConfig from encoder and decoder model configurations', 'create a SpeechEncoderDecoderConfig loaded from a pretrained model directory', 'create a SpeechEncoderDecoderConfig with encoder and decoder sub-configurations', 'access the encoder and decoder configurations from a SpeechEncoderDecoderConfig instance', 'save a SpeechEncoderDecoderConfig and its model to a pretrained directory', 'convert a fairseq wav2vec2-to-mbart checkpoint to a Hugging Face SpeechEncoderDecoder model', 'recursively load fairseq wav2vec2 weights into a Hugging Face Wav2Vec2Model', 'load convolutional layer weights from fairseq into Hugging Face Wav2Vec2FeatureExtractor conv layers', 'load adapter layer weights from fairseq into Hugging Face Wav2Vec2Model adapter modules', 'create a Linear layer from an embedding layer by transposing the weight matrix', 'create a vocabulary dictionary from a fairseq dict file with special tokens for <s>, <pad>, </s>, and <unk>', 'set model weights recursively by navigating nested module attributes and matching tensor shapes', 'build a SpeechEncoderDecoderModel by combining a pretrained speech encoder with a causal language decoder', 'create a SpeechEncoderDecoderModel from pretrained encoder and decoder checkpoint paths', 'run a forward pass of SpeechEncoderDecoderModel with audio inputs and decoder labels to compute loss', 'test the shift_tokens_right function that shifts input ids right and prepends decoder start token', 'review the SpeechEncoderDecoderModel generate method inherited from GenerationMixin for speech-to-text generation']
```

Usage

```
{'create_SpeechEncoderDecoderConfig_from_encoder_decoder_configs': 'create a SpeechEncoderDecoderConfig from encoder and decoder model configurations', 'create_SpeechEncoderDecoderConfig_from_pretrained': 'create a SpeechEncoderDecoderConfig loaded from a pretrained model directory', 'create_SpeechEncoderDecoderConfig_with_encoder_decoder': 'create a SpeechEncoderDecoderConfig with encoder and decoder sub-configurations', 'access_SpeechEncoderDecoderConfig_encoder_decoder': 'access the encoder and decoder configurations from a SpeechEncoderDecoderConfig instance', 'save_SpeechEncoderDecoderConfig_pretrained': 'save a SpeechEncoderDecoderConfig and its model to a pretrained directory'}
```

## File: huggingface_transformers/src/transformers/models/speech_encoder_decoder/convert_mbart_wav2vec2_seq2seq_original_to_pytorch.py

Prompts

```
['create a SpeechEncoderDecoderConfig from encoder and decoder model configurations', 'create a SpeechEncoderDecoderConfig loaded from a pretrained model directory', 'create a SpeechEncoderDecoderConfig with encoder and decoder sub-configurations', 'access the encoder and decoder configurations from a SpeechEncoderDecoderConfig instance', 'save a SpeechEncoderDecoderConfig and its model to a pretrained directory', 'convert a fairseq wav2vec2-to-mbart checkpoint to a Hugging Face SpeechEncoderDecoder model', 'recursively load fairseq wav2vec2 weights into a Hugging Face Wav2Vec2Model', 'load convolutional layer weights from fairseq into Hugging Face Wav2Vec2FeatureExtractor conv layers', 'load adapter layer weights from fairseq into Hugging Face Wav2Vec2Model adapter modules', 'create a Linear layer from an embedding layer by transposing the weight matrix', 'create a vocabulary dictionary from a fairseq dict file with special tokens for <s>, <pad>, </s>, and <unk>', 'set model weights recursively by navigating nested module attributes and matching tensor shapes', 'build a SpeechEncoderDecoderModel by combining a pretrained speech encoder with a causal language decoder', 'create a SpeechEncoderDecoderModel from pretrained encoder and decoder checkpoint paths', 'run a forward pass of SpeechEncoderDecoderModel with audio inputs and decoder labels to compute loss', 'test the shift_tokens_right function that shifts input ids right and prepends decoder start token', 'review the SpeechEncoderDecoderModel generate method inherited from GenerationMixin for speech-to-text generation']
```

Usage

```
{'convert_wav2vec2_checkpoint': 'convert a fairseq wav2vec2-to-mbart checkpoint to a Hugging Face SpeechEncoderDecoder model', 'recursively_load_weights_wav2vec2': 'recursively load fairseq wav2vec2 weights into a Hugging Face Wav2Vec2Model', 'load_conv_layer': 'load convolutional layer weights from fairseq into Hugging Face Wav2Vec2FeatureExtractor conv layers', 'load_adapter': 'load adapter layer weights from fairseq into Hugging Face Wav2Vec2Model adapter modules', 'make_linear_from_emb': 'create a Linear layer from an embedding layer by transposing the weight matrix'}
```

## File: huggingface_transformers/src/transformers/models/speech_encoder_decoder/convert_speech_to_text_wav2vec2_seq2seq_original_to_pytorch.py

Prompts

```
['create a SpeechEncoderDecoderConfig from encoder and decoder model configurations', 'create a SpeechEncoderDecoderConfig loaded from a pretrained model directory', 'create a SpeechEncoderDecoderConfig with encoder and decoder sub-configurations', 'access the encoder and decoder configurations from a SpeechEncoderDecoderConfig instance', 'save a SpeechEncoderDecoderConfig and its model to a pretrained directory', 'convert a fairseq wav2vec2-to-mbart checkpoint to a Hugging Face SpeechEncoderDecoder model', 'recursively load fairseq wav2vec2 weights into a Hugging Face Wav2Vec2Model', 'load convolutional layer weights from fairseq into Hugging Face Wav2Vec2FeatureExtractor conv layers', 'load adapter layer weights from fairseq into Hugging Face Wav2Vec2Model adapter modules', 'create a Linear layer from an embedding layer by transposing the weight matrix', 'create a vocabulary dictionary from a fairseq dict file with special tokens for <s>, <pad>, </s>, and <unk>', 'set model weights recursively by navigating nested module attributes and matching tensor shapes', 'build a SpeechEncoderDecoderModel by combining a pretrained speech encoder with a causal language decoder', 'create a SpeechEncoderDecoderModel from pretrained encoder and decoder checkpoint paths', 'run a forward pass of SpeechEncoderDecoderModel with audio inputs and decoder labels to compute loss', 'test the shift_tokens_right function that shifts input ids right and prepends decoder start token', 'review the SpeechEncoderDecoderModel generate method inherited from GenerationMixin for speech-to-text generation']
```

Usage

```
{'convert_wav2vec2_checkpoint': 'convert a fairseq wav2vec2 checkpoint to a HuggingFace SpeechEncoderDecoderModel with wav2vec2 encoder and speech2text2 decoder', 'recursively_load_weights_wav2vec2': 'recursively load fairseq wav2vec2 model weights into a HuggingFace Wav2Vec2Model with proper key mapping', 'create_vocab_dict': 'create a vocabulary dictionary from a fairseq dict file with special tokens for <s>, <pad>, </s>, and <unk>', 'load_conv_layer': 'load convolutional layer weights from fairseq feature extractor into HuggingFace Wav2Vec2 conv layers', 'set_recursively': 'set model weights recursively by navigating nested module attributes and matching tensor shapes'}
```

## File: huggingface_transformers/src/transformers/models/speech_encoder_decoder/modeling_speech_encoder_decoder.py

Prompts

```
['create a SpeechEncoderDecoderConfig from encoder and decoder model configurations', 'create a SpeechEncoderDecoderConfig loaded from a pretrained model directory', 'create a SpeechEncoderDecoderConfig with encoder and decoder sub-configurations', 'access the encoder and decoder configurations from a SpeechEncoderDecoderConfig instance', 'save a SpeechEncoderDecoderConfig and its model to a pretrained directory', 'convert a fairseq wav2vec2-to-mbart checkpoint to a Hugging Face SpeechEncoderDecoder model', 'recursively load fairseq wav2vec2 weights into a Hugging Face Wav2Vec2Model', 'load convolutional layer weights from fairseq into Hugging Face Wav2Vec2FeatureExtractor conv layers', 'load adapter layer weights from fairseq into Hugging Face Wav2Vec2Model adapter modules', 'create a Linear layer from an embedding layer by transposing the weight matrix', 'create a vocabulary dictionary from a fairseq dict file with special tokens for <s>, <pad>, </s>, and <unk>', 'set model weights recursively by navigating nested module attributes and matching tensor shapes', 'build a SpeechEncoderDecoderModel by combining a pretrained speech encoder with a causal language decoder', 'create a SpeechEncoderDecoderModel from pretrained encoder and decoder checkpoint paths', 'run a forward pass of SpeechEncoderDecoderModel with audio inputs and decoder labels to compute loss', 'test the shift_tokens_right function that shifts input ids right and prepends decoder start token', 'review the SpeechEncoderDecoderModel generate method inherited from GenerationMixin for speech-to-text generation']
```

Usage

```
{'build_speech_encoder_decoder_model': 'build a SpeechEncoderDecoderModel by combining a pretrained speech encoder with a causal language decoder', 'create_speech_encoder_decoder_from_pretrained': 'create a SpeechEncoderDecoderModel from pretrained encoder and decoder checkpoint paths', 'run_speech_encoder_decoder_forward': 'run a forward pass of SpeechEncoderDecoderModel with audio inputs and decoder labels to compute loss', 'test_shift_tokens_right': 'test the shift_tokens_right function that shifts input ids right and prepends decoder start token', 'review_speech_encoder_decoder_generate': 'review the SpeechEncoderDecoderModel generate method inherited from GenerationMixin for speech-to-text generation'}
```

