# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vibevoice_asr/convert_vibevoice_asr_to_hf.py

Prompts

```
['convert a VibeVoice ASR checkpoint to Hugging Face format using the conversion script', "create a VibeVoiceASR config from an original checkpoint's config.json and tokenizer settings", 'load a sharded safetensors VibeVoice ASR checkpoint into a state dictionary', 'convert original VibeVoice ASR state dict keys to Hugging Face model key naming convention', 'create a VibeVoiceASR processor with feature extractor, tokenizer, and chat template', 'create a VibeVoice ASR model for speech recognition from a pre-trained config', 'run VibeVoice ASR generation to transcribe audio into text using the model forward pass', 'encode audio input into embeddings using VibeVoiceAsrForConditionalGeneration.get_audio_features', 'prepare inputs for autoregressive text generation with VibeVoiceAsrForConditionalGeneration.prepare_inputs_for_generation', 'build a VibeVoiceAsrMultiModalProjector to combine acoustic and semantic latents into shared embeddings', 'create a VibeVoice ASR config with acoustic, semantic, and text sub-configs for the multimodal model', 'initialize a VibeVoice ASR for conditional generation model from a config with acoustic and semantic tokenizers', 'encode audio input values into acoustic and semantic latents via the tokenizers with chunked processing', 'run VibeVoice ASR forward pass replacing audio token placeholders with audio embeddings for text generation', 'build an ASR generation pipeline using get_audio_features, forward pass, and prepare_inputs_for_generation', 'create a VibeVoiceASRProcessor that wraps a feature extractor and tokenizer for audio-text ASR', 'run the VibeVoice ASR processor on text and audio inputs to produce tokenized features and labels', 'build an ASR transcription request from audio samples and optional prompts using apply_transcription_request', 'decode VibeVoice ASR model output as raw, parsed speaker dicts, or transcription-only strings', 'extract speaker dictionaries with timestamps from raw decoded ASR output text']
```

Usage

```
{'convert_vibevoice_checkpoint': 'convert a VibeVoice ASR checkpoint to Hugging Face format using the conversion script', 'create_config_from_checkpoint': "create a VibeVoiceASR config from an original checkpoint's config.json and tokenizer settings", 'load_original_checkpoint': 'load a sharded safetensors VibeVoice ASR checkpoint into a state dictionary', 'convert_state_dict': 'convert original VibeVoice ASR state dict keys to Hugging Face model key naming convention', 'create_processor': 'create a VibeVoiceASR processor with feature extractor, tokenizer, and chat template'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_asr/modeling_vibevoice_asr.py

Prompts

```
['convert a VibeVoice ASR checkpoint to Hugging Face format using the conversion script', "create a VibeVoiceASR config from an original checkpoint's config.json and tokenizer settings", 'load a sharded safetensors VibeVoice ASR checkpoint into a state dictionary', 'convert original VibeVoice ASR state dict keys to Hugging Face model key naming convention', 'create a VibeVoiceASR processor with feature extractor, tokenizer, and chat template', 'create a VibeVoice ASR model for speech recognition from a pre-trained config', 'run VibeVoice ASR generation to transcribe audio into text using the model forward pass', 'encode audio input into embeddings using VibeVoiceAsrForConditionalGeneration.get_audio_features', 'prepare inputs for autoregressive text generation with VibeVoiceAsrForConditionalGeneration.prepare_inputs_for_generation', 'build a VibeVoiceAsrMultiModalProjector to combine acoustic and semantic latents into shared embeddings', 'create a VibeVoice ASR config with acoustic, semantic, and text sub-configs for the multimodal model', 'initialize a VibeVoice ASR for conditional generation model from a config with acoustic and semantic tokenizers', 'encode audio input values into acoustic and semantic latents via the tokenizers with chunked processing', 'run VibeVoice ASR forward pass replacing audio token placeholders with audio embeddings for text generation', 'build an ASR generation pipeline using get_audio_features, forward pass, and prepare_inputs_for_generation', 'create a VibeVoiceASRProcessor that wraps a feature extractor and tokenizer for audio-text ASR', 'run the VibeVoice ASR processor on text and audio inputs to produce tokenized features and labels', 'build an ASR transcription request from audio samples and optional prompts using apply_transcription_request', 'decode VibeVoice ASR model output as raw, parsed speaker dicts, or transcription-only strings', 'extract speaker dictionaries with timestamps from raw decoded ASR output text']
```

Usage

```
{'create_vibevoice_asr_model': 'create a VibeVoice ASR model for speech recognition from a pre-trained config', 'run_vibevoice_asr_generation': 'run VibeVoice ASR generation to transcribe audio into text using the model forward pass', 'encode_audio_features': 'encode audio input into embeddings using VibeVoiceAsrForConditionalGeneration.get_audio_features', 'prepare_generation_inputs': 'prepare inputs for autoregressive text generation with VibeVoiceAsrForConditionalGeneration.prepare_inputs_for_generation', 'build_multi_modal_projector': 'build a VibeVoiceAsrMultiModalProjector to combine acoustic and semantic latents into shared embeddings'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_asr/modular_vibevoice_asr.py

Prompts

```
['convert a VibeVoice ASR checkpoint to Hugging Face format using the conversion script', "create a VibeVoiceASR config from an original checkpoint's config.json and tokenizer settings", 'load a sharded safetensors VibeVoice ASR checkpoint into a state dictionary', 'convert original VibeVoice ASR state dict keys to Hugging Face model key naming convention', 'create a VibeVoiceASR processor with feature extractor, tokenizer, and chat template', 'create a VibeVoice ASR model for speech recognition from a pre-trained config', 'run VibeVoice ASR generation to transcribe audio into text using the model forward pass', 'encode audio input into embeddings using VibeVoiceAsrForConditionalGeneration.get_audio_features', 'prepare inputs for autoregressive text generation with VibeVoiceAsrForConditionalGeneration.prepare_inputs_for_generation', 'build a VibeVoiceAsrMultiModalProjector to combine acoustic and semantic latents into shared embeddings', 'create a VibeVoice ASR config with acoustic, semantic, and text sub-configs for the multimodal model', 'initialize a VibeVoice ASR for conditional generation model from a config with acoustic and semantic tokenizers', 'encode audio input values into acoustic and semantic latents via the tokenizers with chunked processing', 'run VibeVoice ASR forward pass replacing audio token placeholders with audio embeddings for text generation', 'build an ASR generation pipeline using get_audio_features, forward pass, and prepare_inputs_for_generation', 'create a VibeVoiceASRProcessor that wraps a feature extractor and tokenizer for audio-text ASR', 'run the VibeVoice ASR processor on text and audio inputs to produce tokenized features and labels', 'build an ASR transcription request from audio samples and optional prompts using apply_transcription_request', 'decode VibeVoice ASR model output as raw, parsed speaker dicts, or transcription-only strings', 'extract speaker dictionaries with timestamps from raw decoded ASR output text']
```

Usage

```
{'create_vibevoice_asr_config': 'create a VibeVoice ASR config with acoustic, semantic, and text sub-configs for the multimodal model', 'initialize_vibevoice_asr_model': 'initialize a VibeVoice ASR for conditional generation model from a config with acoustic and semantic tokenizers', 'encode_audio_to_embeddings': 'encode audio input values into acoustic and semantic latents via the tokenizers with chunked processing', 'run_vibevoice_asr_inference': 'run VibeVoice ASR forward pass replacing audio token placeholders with audio embeddings for text generation', 'build_asr_generation_pipeline': 'build an ASR generation pipeline using get_audio_features, forward pass, and prepare_inputs_for_generation'}
```

## File: huggingface_transformers/src/transformers/models/vibevoice_asr/processing_vibevoice_asr.py

Prompts

```
['convert a VibeVoice ASR checkpoint to Hugging Face format using the conversion script', "create a VibeVoiceASR config from an original checkpoint's config.json and tokenizer settings", 'load a sharded safetensors VibeVoice ASR checkpoint into a state dictionary', 'convert original VibeVoice ASR state dict keys to Hugging Face model key naming convention', 'create a VibeVoiceASR processor with feature extractor, tokenizer, and chat template', 'create a VibeVoice ASR model for speech recognition from a pre-trained config', 'run VibeVoice ASR generation to transcribe audio into text using the model forward pass', 'encode audio input into embeddings using VibeVoiceAsrForConditionalGeneration.get_audio_features', 'prepare inputs for autoregressive text generation with VibeVoiceAsrForConditionalGeneration.prepare_inputs_for_generation', 'build a VibeVoiceAsrMultiModalProjector to combine acoustic and semantic latents into shared embeddings', 'create a VibeVoice ASR config with acoustic, semantic, and text sub-configs for the multimodal model', 'initialize a VibeVoice ASR for conditional generation model from a config with acoustic and semantic tokenizers', 'encode audio input values into acoustic and semantic latents via the tokenizers with chunked processing', 'run VibeVoice ASR forward pass replacing audio token placeholders with audio embeddings for text generation', 'build an ASR generation pipeline using get_audio_features, forward pass, and prepare_inputs_for_generation', 'create a VibeVoiceASRProcessor that wraps a feature extractor and tokenizer for audio-text ASR', 'run the VibeVoice ASR processor on text and audio inputs to produce tokenized features and labels', 'build an ASR transcription request from audio samples and optional prompts using apply_transcription_request', 'decode VibeVoice ASR model output as raw, parsed speaker dicts, or transcription-only strings', 'extract speaker dictionaries with timestamps from raw decoded ASR output text']
```

Usage

```
{'create_vibevoice_asr_processor': 'create a VibeVoiceASRProcessor that wraps a feature extractor and tokenizer for audio-text ASR', 'run_vibevoice_asr_processing': 'run the VibeVoice ASR processor on text and audio inputs to produce tokenized features and labels', 'build_transcription_request': 'build an ASR transcription request from audio samples and optional prompts using apply_transcription_request', 'decode_asr_output': 'decode VibeVoice ASR model output as raw, parsed speaker dicts, or transcription-only strings', 'extract_speaker_dict': 'extract speaker dictionaries with timestamps from raw decoded ASR output text'}
```

