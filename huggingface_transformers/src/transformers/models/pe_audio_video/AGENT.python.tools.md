# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pe_audio_video/configuration_pe_audio_video.py

Prompts

```
['create a PeAudioVideoEncoderConfig instance with custom hidden_size, intermediate_size, and num_hidden_layers', 'build a PeAudioVideoConfig instance combining a modernbert text_config with a pe_audio_video_encoder config', 'test the PeAudioVideoEncoderConfig __post_init__ resolves audio_config and video_config from dict inputs', 'test the PeAudioVideoConfig audio_config property returns a pe_audio config from text and audio_video sub-configs', 'test the PeAudioVideoConfig video_config property returns a pe_video config from text and video sub-configs', 'convert model state dict keys from original Perception-Engine format to HuggingFace Transformers format using regex mapping', 'build a converted PeAudioVideoModel by loading weights from facebook/pe-av-large and saving in HuggingFace format', 'test the model conversion pipeline by saving and reloading the converted PeAudioVideoModel with device_map auto', 'review the permute function that applies weight permutation for rotary embedding support in attention layers', 'summarize the ORIGINAL_TO_CONVERTED_KEY_MAPPING regex patterns that map audio, video, and modality aligner keys', 'build a PeAudioVideoModel that encodes text, audio, and video into contrastive embeddings', 'create a PeAudioVideoEncoder that processes audio and video inputs with a shared transformer encoder', 'run contrastive loss computation between audio, video, and text embedding pairs', 'get joint audio-video embeddings from the PeAudioVideoEncoder with optional individual modality outputs', 'get text-audio-video joint embeddings using the text model and contrastive head', 'run PeAudioVideoEncoder to process combined audio and video inputs through a transformer encoder with masked group normalization', 'create audio-video embeddings by encoding paired audio and video inputs through the audio_video_encoder and projecting to text embedding space', 'test the contrastive loss computation for aligning audio, video, and text modalities in a shared embedding space', 'review PeAudioVideoOutput dataclass that holds embeddings, model outputs, logits, and losses for text-audio-video combinations']
```

Usage

```
{'create_PeAudioVideoEncoderConfig': 'create a PeAudioVideoEncoderConfig instance with custom hidden_size, intermediate_size, and num_hidden_layers', 'build_PeAudioVideoConfig': 'build a PeAudioVideoConfig instance combining a modernbert text_config with a pe_audio_video_encoder config', 'test_PeAudioVideoEncoderConfig_post_init': 'test the PeAudioVideoEncoderConfig __post_init__ resolves audio_config and video_config from dict inputs', 'test_PeAudioVideoConfig_audio_config_property': 'test the PeAudioVideoConfig audio_config property returns a pe_audio config from text and audio_video sub-configs', 'test_PeAudioVideoConfig_video_config_property': 'test the PeAudioVideoConfig video_config property returns a pe_video config from text and video sub-configs'}
```

## File: huggingface_transformers/src/transformers/models/pe_audio_video/convert_pe_audio_video_to_hf.py

Prompts

```
['create a PeAudioVideoEncoderConfig instance with custom hidden_size, intermediate_size, and num_hidden_layers', 'build a PeAudioVideoConfig instance combining a modernbert text_config with a pe_audio_video_encoder config', 'test the PeAudioVideoEncoderConfig __post_init__ resolves audio_config and video_config from dict inputs', 'test the PeAudioVideoConfig audio_config property returns a pe_audio config from text and audio_video sub-configs', 'test the PeAudioVideoConfig video_config property returns a pe_video config from text and video sub-configs', 'convert model state dict keys from original Perception-Engine format to HuggingFace Transformers format using regex mapping', 'build a converted PeAudioVideoModel by loading weights from facebook/pe-av-large and saving in HuggingFace format', 'test the model conversion pipeline by saving and reloading the converted PeAudioVideoModel with device_map auto', 'review the permute function that applies weight permutation for rotary embedding support in attention layers', 'summarize the ORIGINAL_TO_CONVERTED_KEY_MAPPING regex patterns that map audio, video, and modality aligner keys', 'build a PeAudioVideoModel that encodes text, audio, and video into contrastive embeddings', 'create a PeAudioVideoEncoder that processes audio and video inputs with a shared transformer encoder', 'run contrastive loss computation between audio, video, and text embedding pairs', 'get joint audio-video embeddings from the PeAudioVideoEncoder with optional individual modality outputs', 'get text-audio-video joint embeddings using the text model and contrastive head', 'run PeAudioVideoEncoder to process combined audio and video inputs through a transformer encoder with masked group normalization', 'create audio-video embeddings by encoding paired audio and video inputs through the audio_video_encoder and projecting to text embedding space', 'test the contrastive loss computation for aligning audio, video, and text modalities in a shared embedding space', 'review PeAudioVideoOutput dataclass that holds embeddings, model outputs, logits, and losses for text-audio-video combinations']
```

Usage

```
{'convert_model_state_dict_keys': 'convert model state dict keys from original Perception-Engine format to HuggingFace Transformers format using regex mapping', 'build_converted_pe_audio_video_model': 'build a converted PeAudioVideoModel by loading weights from facebook/pe-av-large and saving in HuggingFace format', 'test_model_conversion_and_reload': 'test the model conversion pipeline by saving and reloading the converted PeAudioVideoModel with device_map auto', 'review_permute_function': 'review the permute function that applies weight permutation for rotary embedding support in attention layers', 'summarize_key_mapping': 'summarize the ORIGINAL_TO_CONVERTED_KEY_MAPPING regex patterns that map audio, video, and modality aligner keys'}
```

## File: huggingface_transformers/src/transformers/models/pe_audio_video/modeling_pe_audio_video.py

Prompts

```
['create a PeAudioVideoEncoderConfig instance with custom hidden_size, intermediate_size, and num_hidden_layers', 'build a PeAudioVideoConfig instance combining a modernbert text_config with a pe_audio_video_encoder config', 'test the PeAudioVideoEncoderConfig __post_init__ resolves audio_config and video_config from dict inputs', 'test the PeAudioVideoConfig audio_config property returns a pe_audio config from text and audio_video sub-configs', 'test the PeAudioVideoConfig video_config property returns a pe_video config from text and video sub-configs', 'convert model state dict keys from original Perception-Engine format to HuggingFace Transformers format using regex mapping', 'build a converted PeAudioVideoModel by loading weights from facebook/pe-av-large and saving in HuggingFace format', 'test the model conversion pipeline by saving and reloading the converted PeAudioVideoModel with device_map auto', 'review the permute function that applies weight permutation for rotary embedding support in attention layers', 'summarize the ORIGINAL_TO_CONVERTED_KEY_MAPPING regex patterns that map audio, video, and modality aligner keys', 'build a PeAudioVideoModel that encodes text, audio, and video into contrastive embeddings', 'create a PeAudioVideoEncoder that processes audio and video inputs with a shared transformer encoder', 'run contrastive loss computation between audio, video, and text embedding pairs', 'get joint audio-video embeddings from the PeAudioVideoEncoder with optional individual modality outputs', 'get text-audio-video joint embeddings using the text model and contrastive head', 'run PeAudioVideoEncoder to process combined audio and video inputs through a transformer encoder with masked group normalization', 'create audio-video embeddings by encoding paired audio and video inputs through the audio_video_encoder and projecting to text embedding space', 'test the contrastive loss computation for aligning audio, video, and text modalities in a shared embedding space', 'review PeAudioVideoOutput dataclass that holds embeddings, model outputs, logits, and losses for text-audio-video combinations']
```

Usage

```
{'build_pe_audio_video_model': 'build a PeAudioVideoModel that encodes text, audio, and video into contrastive embeddings', 'create_pe_audio_video_encoder': 'create a PeAudioVideoEncoder that processes audio and video inputs with a shared transformer encoder', 'run_contrastive_loss': 'run contrastive loss computation between audio, video, and text embedding pairs', 'get_audio_video_embeds': 'get joint audio-video embeddings from the PeAudioVideoEncoder with optional individual modality outputs', 'get_text_audio_video_embeds': 'get text-audio-video joint embeddings using the text model and contrastive head'}
```

## File: huggingface_transformers/src/transformers/models/pe_audio_video/modular_pe_audio_video.py

Prompts

```
['create a PeAudioVideoEncoderConfig instance with custom hidden_size, intermediate_size, and num_hidden_layers', 'build a PeAudioVideoConfig instance combining a modernbert text_config with a pe_audio_video_encoder config', 'test the PeAudioVideoEncoderConfig __post_init__ resolves audio_config and video_config from dict inputs', 'test the PeAudioVideoConfig audio_config property returns a pe_audio config from text and audio_video sub-configs', 'test the PeAudioVideoConfig video_config property returns a pe_video config from text and video sub-configs', 'convert model state dict keys from original Perception-Engine format to HuggingFace Transformers format using regex mapping', 'build a converted PeAudioVideoModel by loading weights from facebook/pe-av-large and saving in HuggingFace format', 'test the model conversion pipeline by saving and reloading the converted PeAudioVideoModel with device_map auto', 'review the permute function that applies weight permutation for rotary embedding support in attention layers', 'summarize the ORIGINAL_TO_CONVERTED_KEY_MAPPING regex patterns that map audio, video, and modality aligner keys', 'build a PeAudioVideoModel that encodes text, audio, and video into contrastive embeddings', 'create a PeAudioVideoEncoder that processes audio and video inputs with a shared transformer encoder', 'run contrastive loss computation between audio, video, and text embedding pairs', 'get joint audio-video embeddings from the PeAudioVideoEncoder with optional individual modality outputs', 'get text-audio-video joint embeddings using the text model and contrastive head', 'run PeAudioVideoEncoder to process combined audio and video inputs through a transformer encoder with masked group normalization', 'create audio-video embeddings by encoding paired audio and video inputs through the audio_video_encoder and projecting to text embedding space', 'test the contrastive loss computation for aligning audio, video, and text modalities in a shared embedding space', 'review PeAudioVideoOutput dataclass that holds embeddings, model outputs, logits, and losses for text-audio-video combinations']
```

Usage

```
{'build_pe_audio_video_model': 'build a PeAudioVideoModel to encode text, audio, and video inputs into shared embedding space with contrastive learning', 'run_pe_audio_video_encoder': 'run PeAudioVideoEncoder to process combined audio and video inputs through a transformer encoder with masked group normalization', 'create_audio_video_embeddings': 'create audio-video embeddings by encoding paired audio and video inputs through the audio_video_encoder and projecting to text embedding space', 'test_contrastive_loss': 'test the contrastive loss computation for aligning audio, video, and text modalities in a shared embedding space', 'review_pe_audio_video_output': 'review PeAudioVideoOutput dataclass that holds embeddings, model outputs, logits, and losses for text-audio-video combinations'}
```

