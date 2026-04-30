# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bark/convert_suno_to_hf.py

Prompts

```
['convert a Suno Bark checkpoint to Hugging Face format for text, coarse, or fine model types', 'load a Bark model component (text, coarse, or fine) from a checkpoint and map Suno layer names to Hugging Face names', 'assemble a complete BarkModel from pretrained semantic, coarse, and fine components with Encodec codec', 'download a Suno Bark checkpoint file from the Hugging Face Hub into a local cache directory', 'verify that the converted Hugging Face Bark model produces outputs matching the original Suno Bark model', 'create a BarkSemanticGenerationConfig for controlling semantic model generation with custom eos_token_id and max_new_tokens', 'create a BarkCoarseGenerationConfig for controlling coarse acoustics model generation with custom codebooks and sliding_window_len', 'create a BarkFineGenerationConfig for controlling fine acoustics model generation with custom temperature and codebooks', 'create a BarkGenerationConfig that composes semantic, coarse, and fine sub-model generation configurations', 'build a BarkGenerationConfig from existing BarkSemanticGenerationConfig, BarkCoarseGenerationConfig, and BarkFineGenerationConfig instances', 'generate audio waveform from text input using the full BarkModel pipeline with speaker history prompts', 'generate semantic text tokens from tokenized input using BarkSemanticModel autoregressive generation', 'generate coarse acoustics tokens from semantic output using BarkCoarseModel with sliding window and alternating codebooks', 'generate fine acoustics tokens from coarse output using BarkFineModel non-causal iterative codebook prediction', 'decode quantized audio codes into audio array using BarkModel codec_decode with Encodec quantizer and decoder', 'create a BarkProcessor from a pretrained model name or path with optional speaker embeddings', 'save a BarkProcessor and its speaker embeddings to a local directory for reuse', 'load a voice preset dictionary of semantic, coarse, and fine prompt embeddings by name', 'encode text with Bark tokenizer and attach a voice preset as history prompt', 'list available voice preset names from loaded speaker embeddings']
```

Usage

```
{'convert_suno_bark_checkpoint': 'convert a Suno Bark checkpoint to Hugging Face format for text, coarse, or fine model types', 'load_bark_model_component': 'load a Bark model component (text, coarse, or fine) from a checkpoint and map Suno layer names to Hugging Face names', 'load_whole_bark_model': 'assemble a complete BarkModel from pretrained semantic, coarse, and fine components with Encodec codec', 'download_bark_checkpoint': 'download a Suno Bark checkpoint file from the Hugging Face Hub into a local cache directory', 'verify_bark_conversion': 'verify that the converted Hugging Face Bark model produces outputs matching the original Suno Bark model'}
```

## File: huggingface_transformers/src/transformers/models/bark/generation_configuration_bark.py

Prompts

```
['convert a Suno Bark checkpoint to Hugging Face format for text, coarse, or fine model types', 'load a Bark model component (text, coarse, or fine) from a checkpoint and map Suno layer names to Hugging Face names', 'assemble a complete BarkModel from pretrained semantic, coarse, and fine components with Encodec codec', 'download a Suno Bark checkpoint file from the Hugging Face Hub into a local cache directory', 'verify that the converted Hugging Face Bark model produces outputs matching the original Suno Bark model', 'create a BarkSemanticGenerationConfig for controlling semantic model generation with custom eos_token_id and max_new_tokens', 'create a BarkCoarseGenerationConfig for controlling coarse acoustics model generation with custom codebooks and sliding_window_len', 'create a BarkFineGenerationConfig for controlling fine acoustics model generation with custom temperature and codebooks', 'create a BarkGenerationConfig that composes semantic, coarse, and fine sub-model generation configurations', 'build a BarkGenerationConfig from existing BarkSemanticGenerationConfig, BarkCoarseGenerationConfig, and BarkFineGenerationConfig instances', 'generate audio waveform from text input using the full BarkModel pipeline with speaker history prompts', 'generate semantic text tokens from tokenized input using BarkSemanticModel autoregressive generation', 'generate coarse acoustics tokens from semantic output using BarkCoarseModel with sliding window and alternating codebooks', 'generate fine acoustics tokens from coarse output using BarkFineModel non-causal iterative codebook prediction', 'decode quantized audio codes into audio array using BarkModel codec_decode with Encodec quantizer and decoder', 'create a BarkProcessor from a pretrained model name or path with optional speaker embeddings', 'save a BarkProcessor and its speaker embeddings to a local directory for reuse', 'load a voice preset dictionary of semantic, coarse, and fine prompt embeddings by name', 'encode text with Bark tokenizer and attach a voice preset as history prompt', 'list available voice preset names from loaded speaker embeddings']
```

Usage

```
{'create_bark_semantic_generation_config': 'create a BarkSemanticGenerationConfig for controlling semantic model generation with custom eos_token_id and max_new_tokens', 'create_bark_coarse_generation_config': 'create a BarkCoarseGenerationConfig for controlling coarse acoustics model generation with custom codebooks and sliding_window_len', 'create_bark_fine_generation_config': 'create a BarkFineGenerationConfig for controlling fine acoustics model generation with custom temperature and codebooks', 'create_bark_generation_config': 'create a BarkGenerationConfig that composes semantic, coarse, and fine sub-model generation configurations', 'build_bark_generation_config_from_sub_models': 'build a BarkGenerationConfig from existing BarkSemanticGenerationConfig, BarkCoarseGenerationConfig, and BarkFineGenerationConfig instances'}
```

## File: huggingface_transformers/src/transformers/models/bark/modeling_bark.py

Prompts

```
['convert a Suno Bark checkpoint to Hugging Face format for text, coarse, or fine model types', 'load a Bark model component (text, coarse, or fine) from a checkpoint and map Suno layer names to Hugging Face names', 'assemble a complete BarkModel from pretrained semantic, coarse, and fine components with Encodec codec', 'download a Suno Bark checkpoint file from the Hugging Face Hub into a local cache directory', 'verify that the converted Hugging Face Bark model produces outputs matching the original Suno Bark model', 'create a BarkSemanticGenerationConfig for controlling semantic model generation with custom eos_token_id and max_new_tokens', 'create a BarkCoarseGenerationConfig for controlling coarse acoustics model generation with custom codebooks and sliding_window_len', 'create a BarkFineGenerationConfig for controlling fine acoustics model generation with custom temperature and codebooks', 'create a BarkGenerationConfig that composes semantic, coarse, and fine sub-model generation configurations', 'build a BarkGenerationConfig from existing BarkSemanticGenerationConfig, BarkCoarseGenerationConfig, and BarkFineGenerationConfig instances', 'generate audio waveform from text input using the full BarkModel pipeline with speaker history prompts', 'generate semantic text tokens from tokenized input using BarkSemanticModel autoregressive generation', 'generate coarse acoustics tokens from semantic output using BarkCoarseModel with sliding window and alternating codebooks', 'generate fine acoustics tokens from coarse output using BarkFineModel non-causal iterative codebook prediction', 'decode quantized audio codes into audio array using BarkModel codec_decode with Encodec quantizer and decoder', 'create a BarkProcessor from a pretrained model name or path with optional speaker embeddings', 'save a BarkProcessor and its speaker embeddings to a local directory for reuse', 'load a voice preset dictionary of semantic, coarse, and fine prompt embeddings by name', 'encode text with Bark tokenizer and attach a voice preset as history prompt', 'list available voice preset names from loaded speaker embeddings']
```

Usage

```
{'generate_audio_from_text': 'generate audio waveform from text input using the full BarkModel pipeline with speaker history prompts', 'generate_semantic_tokens': 'generate semantic text tokens from tokenized input using BarkSemanticModel autoregressive generation', 'generate_coarse_acoustics': 'generate coarse acoustics tokens from semantic output using BarkCoarseModel with sliding window and alternating codebooks', 'generate_fine_acoustics': 'generate fine acoustics tokens from coarse output using BarkFineModel non-causal iterative codebook prediction', 'decode_audio_codes': 'decode quantized audio codes into audio array using BarkModel codec_decode with Encodec quantizer and decoder'}
```

## File: huggingface_transformers/src/transformers/models/bark/processing_bark.py

Prompts

```
['convert a Suno Bark checkpoint to Hugging Face format for text, coarse, or fine model types', 'load a Bark model component (text, coarse, or fine) from a checkpoint and map Suno layer names to Hugging Face names', 'assemble a complete BarkModel from pretrained semantic, coarse, and fine components with Encodec codec', 'download a Suno Bark checkpoint file from the Hugging Face Hub into a local cache directory', 'verify that the converted Hugging Face Bark model produces outputs matching the original Suno Bark model', 'create a BarkSemanticGenerationConfig for controlling semantic model generation with custom eos_token_id and max_new_tokens', 'create a BarkCoarseGenerationConfig for controlling coarse acoustics model generation with custom codebooks and sliding_window_len', 'create a BarkFineGenerationConfig for controlling fine acoustics model generation with custom temperature and codebooks', 'create a BarkGenerationConfig that composes semantic, coarse, and fine sub-model generation configurations', 'build a BarkGenerationConfig from existing BarkSemanticGenerationConfig, BarkCoarseGenerationConfig, and BarkFineGenerationConfig instances', 'generate audio waveform from text input using the full BarkModel pipeline with speaker history prompts', 'generate semantic text tokens from tokenized input using BarkSemanticModel autoregressive generation', 'generate coarse acoustics tokens from semantic output using BarkCoarseModel with sliding window and alternating codebooks', 'generate fine acoustics tokens from coarse output using BarkFineModel non-causal iterative codebook prediction', 'decode quantized audio codes into audio array using BarkModel codec_decode with Encodec quantizer and decoder', 'create a BarkProcessor from a pretrained model name or path with optional speaker embeddings', 'save a BarkProcessor and its speaker embeddings to a local directory for reuse', 'load a voice preset dictionary of semantic, coarse, and fine prompt embeddings by name', 'encode text with Bark tokenizer and attach a voice preset as history prompt', 'list available voice preset names from loaded speaker embeddings']
```

Usage

```
{'create_bark_processor_from_pretrained': 'create a BarkProcessor from a pretrained model name or path with optional speaker embeddings', 'save_bark_processor_pretrained': 'save a BarkProcessor and its speaker embeddings to a local directory for reuse', 'load_voice_preset_from_embeddings': 'load a voice preset dictionary of semantic, coarse, and fine prompt embeddings by name', 'encode_text_with_voice_preset': 'encode text with Bark tokenizer and attach a voice preset as history prompt', 'list_available_voice_presets': 'list available voice preset names from loaded speaker embeddings'}
```

