# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xcodec/configuration_xcodec.py

Prompts

```
['create an XcodecConfig instance with default acoustic and semantic model configurations', 'create an XcodecConfig with custom target bandwidths, codebook size, and sample rate parameters', 'create an XcodecConfig initialized from a dictionary of acoustic and semantic model config kwargs', 'read XcodecConfig computed properties like frame_rate, hop_length, codebook_nbits, and hidden_size', 'build an XcodecModel from an XcodecConfig instance with random weights', 'convert xcodec model weights from original checkpoint to huggingface transformers format using checkpoint and config paths', 'run the xcodec weight conversion CLI tool with checkpoint path, config path, and optional output folder or hub upload', 'build a huggingface xcodec model from original checkpoint weights and yaml config for inference', 'summarize the convert_checkpoint function that transforms xcodec original weights to hf-compatible state dict', 'review the safe_load function that loads tensor objects from a checkpoint while skipping BytesIO entries', 'encode mono audio input into discrete codes at a specified bandwidth', 'decode discrete audio codes back into reconstructed audio waveform values', 'run a full encode-decode forward pass on input audio to get codes and reconstructed audio', 'quantize embeddings using residual vector quantization with configurable bandwidth', 'apply weight normalization to acoustic encoder and decoder layers']
```

Usage

```
{'create_xcodec_config': 'create an XcodecConfig instance with default acoustic and semantic model configurations', 'create_xcodec_config_custom': 'create an XcodecConfig with custom target bandwidths, codebook size, and sample rate parameters', 'create_xcodec_config_from_dict': 'create an XcodecConfig initialized from a dictionary of acoustic and semantic model config kwargs', 'read_xcodec_config_properties': 'read XcodecConfig computed properties like frame_rate, hop_length, codebook_nbits, and hidden_size', 'build_xcodec_model_from_config': 'build an XcodecModel from an XcodecConfig instance with random weights'}
```

## File: huggingface_transformers/src/transformers/models/xcodec/convert_xcodec_weights_to_hf.py

Prompts

```
['create an XcodecConfig instance with default acoustic and semantic model configurations', 'create an XcodecConfig with custom target bandwidths, codebook size, and sample rate parameters', 'create an XcodecConfig initialized from a dictionary of acoustic and semantic model config kwargs', 'read XcodecConfig computed properties like frame_rate, hop_length, codebook_nbits, and hidden_size', 'build an XcodecModel from an XcodecConfig instance with random weights', 'convert xcodec model weights from original checkpoint to huggingface transformers format using checkpoint and config paths', 'run the xcodec weight conversion CLI tool with checkpoint path, config path, and optional output folder or hub upload', 'build a huggingface xcodec model from original checkpoint weights and yaml config for inference', 'summarize the convert_checkpoint function that transforms xcodec original weights to hf-compatible state dict', 'review the safe_load function that loads tensor objects from a checkpoint while skipping BytesIO entries', 'encode mono audio input into discrete codes at a specified bandwidth', 'decode discrete audio codes back into reconstructed audio waveform values', 'run a full encode-decode forward pass on input audio to get codes and reconstructed audio', 'quantize embeddings using residual vector quantization with configurable bandwidth', 'apply weight normalization to acoustic encoder and decoder layers']
```

Usage

```
{'convert_xcodec_weights': 'convert xcodec model weights from original checkpoint to huggingface transformers format using checkpoint and config paths', 'run_xcodec_conversion_cli': 'run the xcodec weight conversion CLI tool with checkpoint path, config path, and optional output folder or hub upload', 'build_xcodec_hf_model': 'build a huggingface xcodec model from original checkpoint weights and yaml config for inference', 'summarize_convert_checkpoint': 'summarize the convert_checkpoint function that transforms xcodec original weights to hf-compatible state dict', 'review_safe_load': 'review the safe_load function that loads tensor objects from a checkpoint while skipping BytesIO entries'}
```

## File: huggingface_transformers/src/transformers/models/xcodec/modeling_xcodec.py

Prompts

```
['create an XcodecConfig instance with default acoustic and semantic model configurations', 'create an XcodecConfig with custom target bandwidths, codebook size, and sample rate parameters', 'create an XcodecConfig initialized from a dictionary of acoustic and semantic model config kwargs', 'read XcodecConfig computed properties like frame_rate, hop_length, codebook_nbits, and hidden_size', 'build an XcodecModel from an XcodecConfig instance with random weights', 'convert xcodec model weights from original checkpoint to huggingface transformers format using checkpoint and config paths', 'run the xcodec weight conversion CLI tool with checkpoint path, config path, and optional output folder or hub upload', 'build a huggingface xcodec model from original checkpoint weights and yaml config for inference', 'summarize the convert_checkpoint function that transforms xcodec original weights to hf-compatible state dict', 'review the safe_load function that loads tensor objects from a checkpoint while skipping BytesIO entries', 'encode mono audio input into discrete codes at a specified bandwidth', 'decode discrete audio codes back into reconstructed audio waveform values', 'run a full encode-decode forward pass on input audio to get codes and reconstructed audio', 'quantize embeddings using residual vector quantization with configurable bandwidth', 'apply weight normalization to acoustic encoder and decoder layers']
```

Usage

```
{'encode_audio_input': 'encode mono audio input into discrete codes at a specified bandwidth', 'decode_audio_codes': 'decode discrete audio codes back into reconstructed audio waveform values', 'run_forward_pass': 'run a full encode-decode forward pass on input audio to get codes and reconstructed audio', 'quantize_embeddings_rvq': 'quantize embeddings using residual vector quantization with configurable bandwidth', 'apply_weight_norm': 'apply weight normalization to acoustic encoder and decoder layers'}
```

