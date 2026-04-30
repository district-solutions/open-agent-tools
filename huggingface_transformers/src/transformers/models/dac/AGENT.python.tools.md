# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dac/configuration_dac.py

Prompts

```
['create a DacConfig instance for the descript/dac_16khz model configuration', 'build a DacConfig with custom downsampling_ratios, codebook_size, and sampling_rate parameters', 'review the DacConfig frame_rate property that computes audio frame rate from sampling_rate and upsampling_ratios', 'test the DacConfig __post_init__ method that derives upsampling_ratios, hidden_size, and hop_length', 'summarize the DacConfig class that configures the Descript DAC audio codec model', 'convert a Descript DAC checkpoint to HuggingFace Transformers DacModel format', 'apply weight normalization to all encoder, decoder, and quantizer layers of a DacModel', 'recursively load and map weights from a Descript DAC checkpoint into a HuggingFace DacModel', 'match a checkpoint key against a pattern while validating block count consistency', 'set recursively a weight value into a HuggingFace model pointer with shape validation', 'create a DacModel and encode audio input to get quantized representation and audio codes', 'create a DacModel and decode quantized representation or audio codes back to reconstructed audio values', 'create a DacModel and run a full forward pass to encode audio and reconstruct it end-to-end', 'test the DacResidualVectorQuantizer from_codes method to reconstruct continuous representation from quantized audio codes', 'refactor the DacModel apply_weight_norm method to apply weight normalization to all encoder, decoder, and quantizer layers']
```

Usage

```
{'create_DacConfig': 'create a DacConfig instance for the descript/dac_16khz model configuration', 'build_DacConfig_custom': 'build a DacConfig with custom downsampling_ratios, codebook_size, and sampling_rate parameters', 'review_DacConfig_frame_rate': 'review the DacConfig frame_rate property that computes audio frame rate from sampling_rate and upsampling_ratios', 'test_DacConfig_post_init': 'test the DacConfig __post_init__ method that derives upsampling_ratios, hidden_size, and hop_length', 'summarize_DacConfig': 'summarize the DacConfig class that configures the Descript DAC audio codec model'}
```

## File: huggingface_transformers/src/transformers/models/dac/convert_dac_checkpoint.py

Prompts

```
['create a DacConfig instance for the descript/dac_16khz model configuration', 'build a DacConfig with custom downsampling_ratios, codebook_size, and sampling_rate parameters', 'review the DacConfig frame_rate property that computes audio frame rate from sampling_rate and upsampling_ratios', 'test the DacConfig __post_init__ method that derives upsampling_ratios, hidden_size, and hop_length', 'summarize the DacConfig class that configures the Descript DAC audio codec model', 'convert a Descript DAC checkpoint to HuggingFace Transformers DacModel format', 'apply weight normalization to all encoder, decoder, and quantizer layers of a DacModel', 'recursively load and map weights from a Descript DAC checkpoint into a HuggingFace DacModel', 'match a checkpoint key against a pattern while validating block count consistency', 'set recursively a weight value into a HuggingFace model pointer with shape validation', 'create a DacModel and encode audio input to get quantized representation and audio codes', 'create a DacModel and decode quantized representation or audio codes back to reconstructed audio values', 'create a DacModel and run a full forward pass to encode audio and reconstruct it end-to-end', 'test the DacResidualVectorQuantizer from_codes method to reconstruct continuous representation from quantized audio codes', 'refactor the DacModel apply_weight_norm method to apply weight normalization to all encoder, decoder, and quantizer layers']
```

Usage

```
{'convert_checkpoint': 'convert a Descript DAC checkpoint to HuggingFace Transformers DacModel format', 'apply_weight_norm': 'apply weight normalization to all encoder, decoder, and quantizer layers of a DacModel', 'recursively_load_weights': 'recursively load and map weights from a Descript DAC checkpoint into a HuggingFace DacModel', 'match_pattern': 'match a checkpoint key against a pattern while validating block count consistency', 'set_recursively': 'set recursively a weight value into a HuggingFace model pointer with shape validation'}
```

## File: huggingface_transformers/src/transformers/models/dac/modeling_dac.py

Prompts

```
['create a DacConfig instance for the descript/dac_16khz model configuration', 'build a DacConfig with custom downsampling_ratios, codebook_size, and sampling_rate parameters', 'review the DacConfig frame_rate property that computes audio frame rate from sampling_rate and upsampling_ratios', 'test the DacConfig __post_init__ method that derives upsampling_ratios, hidden_size, and hop_length', 'summarize the DacConfig class that configures the Descript DAC audio codec model', 'convert a Descript DAC checkpoint to HuggingFace Transformers DacModel format', 'apply weight normalization to all encoder, decoder, and quantizer layers of a DacModel', 'recursively load and map weights from a Descript DAC checkpoint into a HuggingFace DacModel', 'match a checkpoint key against a pattern while validating block count consistency', 'set recursively a weight value into a HuggingFace model pointer with shape validation', 'create a DacModel and encode audio input to get quantized representation and audio codes', 'create a DacModel and decode quantized representation or audio codes back to reconstructed audio values', 'create a DacModel and run a full forward pass to encode audio and reconstruct it end-to-end', 'test the DacResidualVectorQuantizer from_codes method to reconstruct continuous representation from quantized audio codes', 'refactor the DacModel apply_weight_norm method to apply weight normalization to all encoder, decoder, and quantizer layers']
```

Usage

```
{'create_DacModel_encode': 'create a DacModel and encode audio input to get quantized representation and audio codes', 'create_DacModel_decode': 'create a DacModel and decode quantized representation or audio codes back to reconstructed audio values', 'create_DacModel_forward': 'create a DacModel and run a full forward pass to encode audio and reconstruct it end-to-end', 'test_DacResidualVectorQuantizer_from_codes': 'test the DacResidualVectorQuantizer from_codes method to reconstruct continuous representation from quantized audio codes', 'refactor_DacModel_apply_weight_norm': 'refactor the DacModel apply_weight_norm method to apply weight normalization to all encoder, decoder, and quantizer layers'}
```

