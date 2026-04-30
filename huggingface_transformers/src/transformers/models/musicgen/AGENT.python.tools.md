# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/musicgen/configuration_musicgen.py

Prompts

```
['create a MusicgenDecoderConfig instance with custom vocab_size, hidden_size, and num_codebooks parameters', 'validate the MusicgenDecoderConfig audio_channels is mono or stereo', 'create a MusicgenConfig with text_encoder, audio_encoder, and decoder sub-configurations', 'initialize a MusicgenConfig by passing text_encoder, audio_encoder, and decoder as dictionaries with model_type keys', 'get the sampling_rate property from a MusicgenConfig instance via its audio_encoder', 'convert a MusicGen checkpoint from fairseq to Hugging Face Transformers format', 'rename a fairseq MusicGen state dict to Hugging Face module names and split encoder-dec projection', 'build a MusicgenDecoderConfig from a checkpoint name like small, medium, or large', 'rename Fairseq MusicGen parameter keys to match Hugging Face Transformers naming conventions', 'run the CLI script to convert a MusicGen checkpoint and save it to a local directory', 'generate audio from text prompts using MusicgenForConditionalGeneration.generate with text input', 'generate audio conditioned on an audio prompt using MusicgenForConditionalGeneration.generate with input_values', 'build a delayed pattern mask for multi-codebook offset in MusicgenForCausalLM generation', 'create a MusicgenForConditionalGeneration model from pretrained text encoder, audio encoder, and decoder', 'get null inputs for unconditional audio generation without text or audio prompts', 'create a MusicgenProcessor instance with a feature extractor and tokenizer for audio processing', 'build decoder prompt ids for MusicGen by specifying task, language, and timestamp settings', 'test the MusicgenProcessor __call__ method to process audio input with feature extraction and tokenization', 'summarize the MusicgenProcessor batch_decode method that strips padding from audio outputs or decodes token ids', 'review the MusicgenProcessor _decode_audio method that removes padding from audio values and returns numpy arrays']
```

Usage

```
{'create_musicgendecoderconfig': 'create a MusicgenDecoderConfig instance with custom vocab_size, hidden_size, and num_codebooks parameters', 'validate_musicgendecoderconfig': 'validate the MusicgenDecoderConfig audio_channels is mono or stereo', 'create_musicgenconfig': 'create a MusicgenConfig with text_encoder, audio_encoder, and decoder sub-configurations', 'initialize_musicgenconfig_from_dict': 'initialize a MusicgenConfig by passing text_encoder, audio_encoder, and decoder as dictionaries with model_type keys', 'get_sampling_rate': 'get the sampling_rate property from a MusicgenConfig instance via its audio_encoder'}
```

## File: huggingface_transformers/src/transformers/models/musicgen/convert_musicgen_transformers.py

Prompts

```
['create a MusicgenDecoderConfig instance with custom vocab_size, hidden_size, and num_codebooks parameters', 'validate the MusicgenDecoderConfig audio_channels is mono or stereo', 'create a MusicgenConfig with text_encoder, audio_encoder, and decoder sub-configurations', 'initialize a MusicgenConfig by passing text_encoder, audio_encoder, and decoder as dictionaries with model_type keys', 'get the sampling_rate property from a MusicgenConfig instance via its audio_encoder', 'convert a MusicGen checkpoint from fairseq to Hugging Face Transformers format', 'rename a fairseq MusicGen state dict to Hugging Face module names and split encoder-dec projection', 'build a MusicgenDecoderConfig from a checkpoint name like small, medium, or large', 'rename Fairseq MusicGen parameter keys to match Hugging Face Transformers naming conventions', 'run the CLI script to convert a MusicGen checkpoint and save it to a local directory', 'generate audio from text prompts using MusicgenForConditionalGeneration.generate with text input', 'generate audio conditioned on an audio prompt using MusicgenForConditionalGeneration.generate with input_values', 'build a delayed pattern mask for multi-codebook offset in MusicgenForCausalLM generation', 'create a MusicgenForConditionalGeneration model from pretrained text encoder, audio encoder, and decoder', 'get null inputs for unconditional audio generation without text or audio prompts', 'create a MusicgenProcessor instance with a feature extractor and tokenizer for audio processing', 'build decoder prompt ids for MusicGen by specifying task, language, and timestamp settings', 'test the MusicgenProcessor __call__ method to process audio input with feature extraction and tokenization', 'summarize the MusicgenProcessor batch_decode method that strips padding from audio outputs or decodes token ids', 'review the MusicgenProcessor _decode_audio method that removes padding from audio values and returns numpy arrays']
```

Usage

```
{'convert_musicgen_checkpoint': 'convert a MusicGen checkpoint from fairseq to Hugging Face Transformers format', 'rename_state_dict': 'rename a fairseq MusicGen state dict to Hugging Face module names and split encoder-dec projection', 'decoder_config_from_checkpoint': 'build a MusicgenDecoderConfig from a checkpoint name like small, medium, or large', 'rename_keys': 'rename Fairseq MusicGen parameter keys to match Hugging Face Transformers naming conventions', 'run_cli_convert': 'run the CLI script to convert a MusicGen checkpoint and save it to a local directory'}
```

## File: huggingface_transformers/src/transformers/models/musicgen/modeling_musicgen.py

Prompts

```
['create a MusicgenDecoderConfig instance with custom vocab_size, hidden_size, and num_codebooks parameters', 'validate the MusicgenDecoderConfig audio_channels is mono or stereo', 'create a MusicgenConfig with text_encoder, audio_encoder, and decoder sub-configurations', 'initialize a MusicgenConfig by passing text_encoder, audio_encoder, and decoder as dictionaries with model_type keys', 'get the sampling_rate property from a MusicgenConfig instance via its audio_encoder', 'convert a MusicGen checkpoint from fairseq to Hugging Face Transformers format', 'rename a fairseq MusicGen state dict to Hugging Face module names and split encoder-dec projection', 'build a MusicgenDecoderConfig from a checkpoint name like small, medium, or large', 'rename Fairseq MusicGen parameter keys to match Hugging Face Transformers naming conventions', 'run the CLI script to convert a MusicGen checkpoint and save it to a local directory', 'generate audio from text prompts using MusicgenForConditionalGeneration.generate with text input', 'generate audio conditioned on an audio prompt using MusicgenForConditionalGeneration.generate with input_values', 'build a delayed pattern mask for multi-codebook offset in MusicgenForCausalLM generation', 'create a MusicgenForConditionalGeneration model from pretrained text encoder, audio encoder, and decoder', 'get null inputs for unconditional audio generation without text or audio prompts', 'create a MusicgenProcessor instance with a feature extractor and tokenizer for audio processing', 'build decoder prompt ids for MusicGen by specifying task, language, and timestamp settings', 'test the MusicgenProcessor __call__ method to process audio input with feature extraction and tokenization', 'summarize the MusicgenProcessor batch_decode method that strips padding from audio outputs or decodes token ids', 'review the MusicgenProcessor _decode_audio method that removes padding from audio values and returns numpy arrays']
```

Usage

```
{'generate_audio_from_text': 'generate audio from text prompts using MusicgenForConditionalGeneration.generate with text input', 'generate_audio_from_audio_prompt': 'generate audio conditioned on an audio prompt using MusicgenForConditionalGeneration.generate with input_values', 'build_delay_pattern_mask': 'build a delayed pattern mask for multi-codebook offset in MusicgenForCausalLM generation', 'create_conditional_generation_model': 'create a MusicgenForConditionalGeneration model from pretrained text encoder, audio encoder, and decoder', 'get_unconditional_inputs': 'get null inputs for unconditional audio generation without text or audio prompts'}
```

## File: huggingface_transformers/src/transformers/models/musicgen/processing_musicgen.py

Prompts

```
['create a MusicgenDecoderConfig instance with custom vocab_size, hidden_size, and num_codebooks parameters', 'validate the MusicgenDecoderConfig audio_channels is mono or stereo', 'create a MusicgenConfig with text_encoder, audio_encoder, and decoder sub-configurations', 'initialize a MusicgenConfig by passing text_encoder, audio_encoder, and decoder as dictionaries with model_type keys', 'get the sampling_rate property from a MusicgenConfig instance via its audio_encoder', 'convert a MusicGen checkpoint from fairseq to Hugging Face Transformers format', 'rename a fairseq MusicGen state dict to Hugging Face module names and split encoder-dec projection', 'build a MusicgenDecoderConfig from a checkpoint name like small, medium, or large', 'rename Fairseq MusicGen parameter keys to match Hugging Face Transformers naming conventions', 'run the CLI script to convert a MusicGen checkpoint and save it to a local directory', 'generate audio from text prompts using MusicgenForConditionalGeneration.generate with text input', 'generate audio conditioned on an audio prompt using MusicgenForConditionalGeneration.generate with input_values', 'build a delayed pattern mask for multi-codebook offset in MusicgenForCausalLM generation', 'create a MusicgenForConditionalGeneration model from pretrained text encoder, audio encoder, and decoder', 'get null inputs for unconditional audio generation without text or audio prompts', 'create a MusicgenProcessor instance with a feature extractor and tokenizer for audio processing', 'build decoder prompt ids for MusicGen by specifying task, language, and timestamp settings', 'test the MusicgenProcessor __call__ method to process audio input with feature extraction and tokenization', 'summarize the MusicgenProcessor batch_decode method that strips padding from audio outputs or decodes token ids', 'review the MusicgenProcessor _decode_audio method that removes padding from audio values and returns numpy arrays']
```

Usage

```
{'create_MusicgenProcessor': 'create a MusicgenProcessor instance with a feature extractor and tokenizer for audio processing', 'build_decoder_prompt_ids': 'build decoder prompt ids for MusicGen by specifying task, language, and timestamp settings', 'test_call_audio_processor': 'test the MusicgenProcessor __call__ method to process audio input with feature extraction and tokenization', 'summarize_batch_decode': 'summarize the MusicgenProcessor batch_decode method that strips padding from audio outputs or decodes token ids', 'review_decode_audio': 'review the MusicgenProcessor _decode_audio method that removes padding from audio values and returns numpy arrays'}
```

