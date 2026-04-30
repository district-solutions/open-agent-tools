# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/granite_speech_plus/modeling_granite_speech_plus.py

Prompts

```
['build a GraniteSpeechPlusForConditionalGeneration model from config with encoder, projector, and language model', 'run get_audio_features to extract and project audio embeddings from input features tensor', 'generate text output from audio and text inputs using GraniteSpeechPlusForConditionalGeneration with LoRA adapter support', 'merge audio features into LLM text embeddings using get_merged_audio_embeddings with masked scatter', 'encode raw audio features through the GraniteSpeechPlusCTCEncoder conformer-based encoder with intermediate layer concatenation', 'build a GraniteSpeechPlusEncoderConfig with cat_hidden_layers to select intermediate encoder layers for concatenation', 'build a GraniteSpeechPlusConfig that validates cat_hidden_layers indices and projector encoder_hidden_size alignment', 'run the GraniteSpeechPlusCTCEncoder forward pass to concatenate selected intermediate hidden states with the final output', 'create a GraniteSpeechPlusForConditionalGeneration model from a GraniteSpeechPlusConfig for audio conditional generation', 'review the GraniteSpeechPlusConfig post_init validation logic for cat_hidden_layers bounds and projector dimension checks']
```

Usage

```
{'build_conditional_generation_model': 'build a GraniteSpeechPlusForConditionalGeneration model from config with encoder, projector, and language model', 'run_audio_feature_extraction': 'run get_audio_features to extract and project audio embeddings from input features tensor', 'generate_multimodal_output': 'generate text output from audio and text inputs using GraniteSpeechPlusForConditionalGeneration with LoRA adapter support', 'merge_audio_embeddings': 'merge audio features into LLM text embeddings using get_merged_audio_embeddings with masked scatter', 'encode_audio_with_ctc_encoder': 'encode raw audio features through the GraniteSpeechPlusCTCEncoder conformer-based encoder with intermediate layer concatenation'}
```

## File: huggingface_transformers/src/transformers/models/granite_speech_plus/modular_granite_speech_plus.py

Prompts

```
['build a GraniteSpeechPlusForConditionalGeneration model from config with encoder, projector, and language model', 'run get_audio_features to extract and project audio embeddings from input features tensor', 'generate text output from audio and text inputs using GraniteSpeechPlusForConditionalGeneration with LoRA adapter support', 'merge audio features into LLM text embeddings using get_merged_audio_embeddings with masked scatter', 'encode raw audio features through the GraniteSpeechPlusCTCEncoder conformer-based encoder with intermediate layer concatenation', 'build a GraniteSpeechPlusEncoderConfig with cat_hidden_layers to select intermediate encoder layers for concatenation', 'build a GraniteSpeechPlusConfig that validates cat_hidden_layers indices and projector encoder_hidden_size alignment', 'run the GraniteSpeechPlusCTCEncoder forward pass to concatenate selected intermediate hidden states with the final output', 'create a GraniteSpeechPlusForConditionalGeneration model from a GraniteSpeechPlusConfig for audio conditional generation', 'review the GraniteSpeechPlusConfig post_init validation logic for cat_hidden_layers bounds and projector dimension checks']
```

Usage

```
{'build_encoder_config': 'build a GraniteSpeechPlusEncoderConfig with cat_hidden_layers to select intermediate encoder layers for concatenation', 'build_model_config': 'build a GraniteSpeechPlusConfig that validates cat_hidden_layers indices and projector encoder_hidden_size alignment', 'run_ctc_encoder_forward': 'run the GraniteSpeechPlusCTCEncoder forward pass to concatenate selected intermediate hidden states with the final output', 'create_conditional_generation_model': 'create a GraniteSpeechPlusForConditionalGeneration model from a GraniteSpeechPlusConfig for audio conditional generation', 'review_encoder_config_validation': 'review the GraniteSpeechPlusConfig post_init validation logic for cat_hidden_layers bounds and projector dimension checks'}
```

