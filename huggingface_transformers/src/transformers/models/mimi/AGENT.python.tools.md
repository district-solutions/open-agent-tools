# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mimi/configuration_mimi.py

Prompts

```
['create a MimiConfig instance to initialize the configuration for the Mimi audio model', 'configure Mimi model parameters including upsampling_ratios, num_quantizers, and hidden_size for audio encoding', 'validate MimiConfig architecture constraints such as num_semantic_quantizers being less than num_quantizers', 'compute the encodec_frame_rate property from upsampling_ratios and sampling_rate for the Mimi model', 'compute the frame_size property by multiplying encoder conv strides for the Mimi model', 'convert a Mimi checkpoint from the original format to a PyTorch HuggingFace model', 'run the Mimi checkpoint conversion CLI with checkpoint path and output folder arguments', 'convert a Mimi checkpoint using a custom config file to override default model settings', 'convert and push a Mimi model checkpoint to the HuggingFace hub via repo_id', 'compare parameter counts between two models excluding final_proj layers', 'encode raw audio waveform into discrete codes using the Mimi model', 'decode discrete audio codes back into raw audio waveform values', 'run full encode-then-decode pipeline on raw audio to produce reconstructed audio', 'build streaming encoder with padding cache for sequential audio encoding', 'configure residual vector quantizer layers with semantic and acoustic codebooks']
```

Usage

```
{'create_config_mimi': 'create a MimiConfig instance to initialize the configuration for the Mimi audio model', 'configure_mimi_model': 'configure Mimi model parameters including upsampling_ratios, num_quantizers, and hidden_size for audio encoding', 'validate_mimi_config': 'validate MimiConfig architecture constraints such as num_semantic_quantizers being less than num_quantizers', 'compute_encodec_frame_rate': 'compute the encodec_frame_rate property from upsampling_ratios and sampling_rate for the Mimi model', 'compute_frame_size': 'compute the frame_size property by multiplying encoder conv strides for the Mimi model'}
```

## File: huggingface_transformers/src/transformers/models/mimi/convert_mimi_checkpoint_to_pytorch.py

Prompts

```
['create a MimiConfig instance to initialize the configuration for the Mimi audio model', 'configure Mimi model parameters including upsampling_ratios, num_quantizers, and hidden_size for audio encoding', 'validate MimiConfig architecture constraints such as num_semantic_quantizers being less than num_quantizers', 'compute the encodec_frame_rate property from upsampling_ratios and sampling_rate for the Mimi model', 'compute the frame_size property by multiplying encoder conv strides for the Mimi model', 'convert a Mimi checkpoint from the original format to a PyTorch HuggingFace model', 'run the Mimi checkpoint conversion CLI with checkpoint path and output folder arguments', 'convert a Mimi checkpoint using a custom config file to override default model settings', 'convert and push a Mimi model checkpoint to the HuggingFace hub via repo_id', 'compare parameter counts between two models excluding final_proj layers', 'encode raw audio waveform into discrete codes using the Mimi model', 'decode discrete audio codes back into raw audio waveform values', 'run full encode-then-decode pipeline on raw audio to produce reconstructed audio', 'build streaming encoder with padding cache for sequential audio encoding', 'configure residual vector quantizer layers with semantic and acoustic codebooks']
```

Usage

```
{'convert_mimi_checkpoint': 'convert a Mimi checkpoint from the original format to a PyTorch HuggingFace model', 'run_convert_cli': 'run the Mimi checkpoint conversion CLI with checkpoint path and output folder arguments', 'convert_with_config': 'convert a Mimi checkpoint using a custom config file to override default model settings', 'push_converted_model': 'convert and push a Mimi model checkpoint to the HuggingFace hub via repo_id', 'compare_model_params': 'compare parameter counts between two models excluding final_proj layers'}
```

## File: huggingface_transformers/src/transformers/models/mimi/modeling_mimi.py

Prompts

```
['create a MimiConfig instance to initialize the configuration for the Mimi audio model', 'configure Mimi model parameters including upsampling_ratios, num_quantizers, and hidden_size for audio encoding', 'validate MimiConfig architecture constraints such as num_semantic_quantizers being less than num_quantizers', 'compute the encodec_frame_rate property from upsampling_ratios and sampling_rate for the Mimi model', 'compute the frame_size property by multiplying encoder conv strides for the Mimi model', 'convert a Mimi checkpoint from the original format to a PyTorch HuggingFace model', 'run the Mimi checkpoint conversion CLI with checkpoint path and output folder arguments', 'convert a Mimi checkpoint using a custom config file to override default model settings', 'convert and push a Mimi model checkpoint to the HuggingFace hub via repo_id', 'compare parameter counts between two models excluding final_proj layers', 'encode raw audio waveform into discrete codes using the Mimi model', 'decode discrete audio codes back into raw audio waveform values', 'run full encode-then-decode pipeline on raw audio to produce reconstructed audio', 'build streaming encoder with padding cache for sequential audio encoding', 'configure residual vector quantizer layers with semantic and acoustic codebooks']
```

Usage

```
{'encode_audio_to_codes': 'encode raw audio waveform into discrete codes using the Mimi model', 'decode_codes_to_audio': 'decode discrete audio codes back into raw audio waveform values', 'run_full_encode_decode': 'run full encode-then-decode pipeline on raw audio to produce reconstructed audio', 'build_streaming_encoder': 'build streaming encoder with padding cache for sequential audio encoding', 'configure_quantizer_layers': 'configure residual vector quantizer layers with semantic and acoustic codebooks'}
```

