# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/encodec/configuration_encodec.py

Prompts

```
['create an EncodecConfig instance with custom target_bandwidths and sampling_rate for audio encoding', 'build an EncodecConfig and call validate_architecture to verify norm_type is weight_norm or time_group_norm', 'test the EncodecConfig properties chunk_length, chunk_stride, hop_length, codebook_nbits, frame_rate, and num_quantizers', 'review the EncodecConfig __post_init__ method that defaults codebook_dim to hidden_size when None', 'summarize the EncodecConfig class and its architecture parameters for the facebook/encodec_24khz model', 'convert a Facebook EnCodec 24kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 48kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 32kHz checkpoint to Hugging Face PyTorch format', 'convert an EnCodec checkpoint to PyTorch and push to Hugging Face hub', 'convert an EnCodec checkpoint using a custom config.json path', 'create an EncodecFeatureExtractor instance with default mono audio settings at 24000 Hz sampling rate', 'create an EncodecFeatureExtractor configured for stereo audio with feature_size 2 and custom chunk length', 'featurize raw mono audio waveform data into padded input values with padding mask for model ingestion', 'featurize a batch of stereo audio sequences with truncation and return PyTorch tensors', 'compute the chunk stride from chunk length and overlap parameters for streaming audio processing', 'encode audio waveform into discrete codes using EncodecModel.encode with specified bandwidth', 'decode discrete audio codes back to waveform using EncodecModel.decode with scales and padding mask', 'encode and decode audio through EncodecModel forward pass for full codec pipeline', 'quantize audio embeddings using EncodecResidualVectorQuantizer with configurable number of quantizers', 'overlap-add decoded audio frames with linear fade-in/fade-out using EncodecModel._linear_overlap_add']
```

Usage

```
{'create_config_encodec': 'create an EncodecConfig instance with custom target_bandwidths and sampling_rate for audio encoding', 'build_config_validate': 'build an EncodecConfig and call validate_architecture to verify norm_type is weight_norm or time_group_norm', 'test_config_properties': 'test the EncodecConfig properties chunk_length, chunk_stride, hop_length, codebook_nbits, frame_rate, and num_quantizers', 'review_config_post_init': 'review the EncodecConfig __post_init__ method that defaults codebook_dim to hidden_size when None', 'summarize_config_class': 'summarize the EncodecConfig class and its architecture parameters for the facebook/encodec_24khz model'}
```

## File: huggingface_transformers/src/transformers/models/encodec/convert_encodec_checkpoint_to_pytorch.py

Prompts

```
['create an EncodecConfig instance with custom target_bandwidths and sampling_rate for audio encoding', 'build an EncodecConfig and call validate_architecture to verify norm_type is weight_norm or time_group_norm', 'test the EncodecConfig properties chunk_length, chunk_stride, hop_length, codebook_nbits, frame_rate, and num_quantizers', 'review the EncodecConfig __post_init__ method that defaults codebook_dim to hidden_size when None', 'summarize the EncodecConfig class and its architecture parameters for the facebook/encodec_24khz model', 'convert a Facebook EnCodec 24kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 48kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 32kHz checkpoint to Hugging Face PyTorch format', 'convert an EnCodec checkpoint to PyTorch and push to Hugging Face hub', 'convert an EnCodec checkpoint using a custom config.json path', 'create an EncodecFeatureExtractor instance with default mono audio settings at 24000 Hz sampling rate', 'create an EncodecFeatureExtractor configured for stereo audio with feature_size 2 and custom chunk length', 'featurize raw mono audio waveform data into padded input values with padding mask for model ingestion', 'featurize a batch of stereo audio sequences with truncation and return PyTorch tensors', 'compute the chunk stride from chunk length and overlap parameters for streaming audio processing', 'encode audio waveform into discrete codes using EncodecModel.encode with specified bandwidth', 'decode discrete audio codes back to waveform using EncodecModel.decode with scales and padding mask', 'encode and decode audio through EncodecModel forward pass for full codec pipeline', 'quantize audio embeddings using EncodecResidualVectorQuantizer with configurable number of quantizers', 'overlap-add decoded audio frames with linear fade-in/fade-out using EncodecModel._linear_overlap_add']
```

Usage

```
{'convert_encodec_24khz_checkpoint': 'convert a Facebook EnCodec 24kHz checkpoint to Hugging Face PyTorch format', 'convert_encodec_48khz_checkpoint': 'convert a Facebook EnCodec 48kHz checkpoint to Hugging Face PyTorch format', 'convert_encodec_32khz_checkpoint': 'convert a Facebook EnCodec 32kHz checkpoint to Hugging Face PyTorch format', 'convert_encodec_checkpoint_push_hub': 'convert an EnCodec checkpoint to PyTorch and push to Hugging Face hub', 'convert_encodec_checkpoint_custom_config': 'convert an EnCodec checkpoint using a custom config.json path'}
```

## File: huggingface_transformers/src/transformers/models/encodec/feature_extraction_encodec.py

Prompts

```
['create an EncodecConfig instance with custom target_bandwidths and sampling_rate for audio encoding', 'build an EncodecConfig and call validate_architecture to verify norm_type is weight_norm or time_group_norm', 'test the EncodecConfig properties chunk_length, chunk_stride, hop_length, codebook_nbits, frame_rate, and num_quantizers', 'review the EncodecConfig __post_init__ method that defaults codebook_dim to hidden_size when None', 'summarize the EncodecConfig class and its architecture parameters for the facebook/encodec_24khz model', 'convert a Facebook EnCodec 24kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 48kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 32kHz checkpoint to Hugging Face PyTorch format', 'convert an EnCodec checkpoint to PyTorch and push to Hugging Face hub', 'convert an EnCodec checkpoint using a custom config.json path', 'create an EncodecFeatureExtractor instance with default mono audio settings at 24000 Hz sampling rate', 'create an EncodecFeatureExtractor configured for stereo audio with feature_size 2 and custom chunk length', 'featurize raw mono audio waveform data into padded input values with padding mask for model ingestion', 'featurize a batch of stereo audio sequences with truncation and return PyTorch tensors', 'compute the chunk stride from chunk length and overlap parameters for streaming audio processing', 'encode audio waveform into discrete codes using EncodecModel.encode with specified bandwidth', 'decode discrete audio codes back to waveform using EncodecModel.decode with scales and padding mask', 'encode and decode audio through EncodecModel forward pass for full codec pipeline', 'quantize audio embeddings using EncodecResidualVectorQuantizer with configurable number of quantizers', 'overlap-add decoded audio frames with linear fade-in/fade-out using EncodecModel._linear_overlap_add']
```

Usage

```
{'create_encodec_feature_extractor': 'create an EncodecFeatureExtractor instance with default mono audio settings at 24000 Hz sampling rate', 'create_stereo_encodec_extractor': 'create an EncodecFeatureExtractor configured for stereo audio with feature_size 2 and custom chunk length', 'featurize_raw_audio': 'featurize raw mono audio waveform data into padded input values with padding mask for model ingestion', 'featurize_batch_audio': 'featurize a batch of stereo audio sequences with truncation and return PyTorch tensors', 'compute_chunk_stride': 'compute the chunk stride from chunk length and overlap parameters for streaming audio processing'}
```

## File: huggingface_transformers/src/transformers/models/encodec/modeling_encodec.py

Prompts

```
['create an EncodecConfig instance with custom target_bandwidths and sampling_rate for audio encoding', 'build an EncodecConfig and call validate_architecture to verify norm_type is weight_norm or time_group_norm', 'test the EncodecConfig properties chunk_length, chunk_stride, hop_length, codebook_nbits, frame_rate, and num_quantizers', 'review the EncodecConfig __post_init__ method that defaults codebook_dim to hidden_size when None', 'summarize the EncodecConfig class and its architecture parameters for the facebook/encodec_24khz model', 'convert a Facebook EnCodec 24kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 48kHz checkpoint to Hugging Face PyTorch format', 'convert a Facebook EnCodec 32kHz checkpoint to Hugging Face PyTorch format', 'convert an EnCodec checkpoint to PyTorch and push to Hugging Face hub', 'convert an EnCodec checkpoint using a custom config.json path', 'create an EncodecFeatureExtractor instance with default mono audio settings at 24000 Hz sampling rate', 'create an EncodecFeatureExtractor configured for stereo audio with feature_size 2 and custom chunk length', 'featurize raw mono audio waveform data into padded input values with padding mask for model ingestion', 'featurize a batch of stereo audio sequences with truncation and return PyTorch tensors', 'compute the chunk stride from chunk length and overlap parameters for streaming audio processing', 'encode audio waveform into discrete codes using EncodecModel.encode with specified bandwidth', 'decode discrete audio codes back to waveform using EncodecModel.decode with scales and padding mask', 'encode and decode audio through EncodecModel forward pass for full codec pipeline', 'quantize audio embeddings using EncodecResidualVectorQuantizer with configurable number of quantizers', 'overlap-add decoded audio frames with linear fade-in/fade-out using EncodecModel._linear_overlap_add']
```

Usage

```
{'encode_audio_waveform': 'encode audio waveform into discrete codes using EncodecModel.encode with specified bandwidth', 'decode_audio_codes': 'decode discrete audio codes back to waveform using EncodecModel.decode with scales and padding mask', 'encode_decode_audio': 'encode and decode audio through EncodecModel forward pass for full codec pipeline', 'quantize_audio_embeddings': 'quantize audio embeddings using EncodecResidualVectorQuantizer with configurable number of quantizers', 'overlap_add_frames': 'overlap-add decoded audio frames with linear fade-in/fade-out using EncodecModel._linear_overlap_add'}
```

