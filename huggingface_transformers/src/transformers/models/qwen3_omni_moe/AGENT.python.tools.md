# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/qwen3_omni_moe/configuration_qwen3_omni_moe.py

Prompts

```
['create a Qwen3OmniMoeConfig instance with default thinker, talker, and code2wav sub-configurations', 'create a Qwen3OmniMoeThinkerConfig with audio, vision, and text sub-configurations for multimodal input', 'create a Qwen3OmniMoeTalkerConfig with code predictor and text decoder sub-configurations for speech generation', 'create a Qwen3OmniMoeTextConfig with MoE parameters including 128 experts and 8 experts per token', 'create a Qwen3OmniMoeAudioEncoderConfig with 128 mel bins and 1280 d_model for audio processing', 'generate a text response from Qwen3OmniMoeForConditionalGeneration given multimodal inputs', 'generate text and audio output using Qwen3OmniMoeForConditionalGeneration.generate with return_audio enabled', 'encode images using Qwen3OmniMoeVisionEncoder to extract visual features for the LLM', 'encode audio inputs using Qwen3OmniMoeAudioEncoder to extract audio features for the LLM', 'decode audio codes to waveform using Qwen3OmniMoeCode2Wav with chunked inference', 'create a Qwen3OmniMoeForConditionalGeneration model with multimodal audio, image, video, and text support', 'generate text and audio output from a Qwen3OmniMoeForConditionalGeneration model using the generate method', 'build a Qwen3OmniMoeProcessor to tokenize text and process audio, image, video, and multimodal inputs', 'configure a Qwen3OmniMoeConfig with thinker, talker, and code2wav sub-configurations for the omni model', 'run Qwen3OmniMoeCode2Wav vocoder to convert codec token sequences into waveform audio output', 'create a BatchFeature from text, images, videos, and audio inputs by calling the processor with multimodal special tokens', 'test replacing multimodal special tokens like audio, image, and video tokens with placeholder sequences in text templates', 'summarize how post_process_multimodal_output decodes generated model outputs into text strings or audio numpy arrays based on generation_mode', 'review the get_chunked_index method that splits monotonically increasing token indices into chunks by token value ranges']
```

Usage

```
{'create_Qwen3OmniMoeConfig': 'create a Qwen3OmniMoeConfig instance with default thinker, talker, and code2wav sub-configurations', 'create_Qwen3OmniMoeThinkerConfig': 'create a Qwen3OmniMoeThinkerConfig with audio, vision, and text sub-configurations for multimodal input', 'create_Qwen3OmniMoeTalkerConfig': 'create a Qwen3OmniMoeTalkerConfig with code predictor and text decoder sub-configurations for speech generation', 'create_Qwen3OmniMoeTextConfig': 'create a Qwen3OmniMoeTextConfig with MoE parameters including 128 experts and 8 experts per token', 'create_Qwen3OmniMoeAudioEncoderConfig': 'create a Qwen3OmniMoeAudioEncoderConfig with 128 mel bins and 1280 d_model for audio processing'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_omni_moe/modeling_qwen3_omni_moe.py

Prompts

```
['create a Qwen3OmniMoeConfig instance with default thinker, talker, and code2wav sub-configurations', 'create a Qwen3OmniMoeThinkerConfig with audio, vision, and text sub-configurations for multimodal input', 'create a Qwen3OmniMoeTalkerConfig with code predictor and text decoder sub-configurations for speech generation', 'create a Qwen3OmniMoeTextConfig with MoE parameters including 128 experts and 8 experts per token', 'create a Qwen3OmniMoeAudioEncoderConfig with 128 mel bins and 1280 d_model for audio processing', 'generate a text response from Qwen3OmniMoeForConditionalGeneration given multimodal inputs', 'generate text and audio output using Qwen3OmniMoeForConditionalGeneration.generate with return_audio enabled', 'encode images using Qwen3OmniMoeVisionEncoder to extract visual features for the LLM', 'encode audio inputs using Qwen3OmniMoeAudioEncoder to extract audio features for the LLM', 'decode audio codes to waveform using Qwen3OmniMoeCode2Wav with chunked inference', 'create a Qwen3OmniMoeForConditionalGeneration model with multimodal audio, image, video, and text support', 'generate text and audio output from a Qwen3OmniMoeForConditionalGeneration model using the generate method', 'build a Qwen3OmniMoeProcessor to tokenize text and process audio, image, video, and multimodal inputs', 'configure a Qwen3OmniMoeConfig with thinker, talker, and code2wav sub-configurations for the omni model', 'run Qwen3OmniMoeCode2Wav vocoder to convert codec token sequences into waveform audio output', 'create a BatchFeature from text, images, videos, and audio inputs by calling the processor with multimodal special tokens', 'test replacing multimodal special tokens like audio, image, and video tokens with placeholder sequences in text templates', 'summarize how post_process_multimodal_output decodes generated model outputs into text strings or audio numpy arrays based on generation_mode', 'review the get_chunked_index method that splits monotonically increasing token indices into chunks by token value ranges']
```

Usage

```
{'generate_multimodal_response': 'generate a text response from Qwen3OmniMoeForConditionalGeneration given multimodal inputs', 'generate_text_with_audio_output': 'generate text and audio output using Qwen3OmniMoeForConditionalGeneration.generate with return_audio enabled', 'encode_images_with_vision_encoder': 'encode images using Qwen3OmniMoeVisionEncoder to extract visual features for the LLM', 'encode_audio_with_audio_encoder': 'encode audio inputs using Qwen3OmniMoeAudioEncoder to extract audio features for the LLM', 'decode_codes_to_waveform': 'decode audio codes to waveform using Qwen3OmniMoeCode2Wav with chunked inference'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_omni_moe/modular_qwen3_omni_moe.py

Prompts

```
['create a Qwen3OmniMoeConfig instance with default thinker, talker, and code2wav sub-configurations', 'create a Qwen3OmniMoeThinkerConfig with audio, vision, and text sub-configurations for multimodal input', 'create a Qwen3OmniMoeTalkerConfig with code predictor and text decoder sub-configurations for speech generation', 'create a Qwen3OmniMoeTextConfig with MoE parameters including 128 experts and 8 experts per token', 'create a Qwen3OmniMoeAudioEncoderConfig with 128 mel bins and 1280 d_model for audio processing', 'generate a text response from Qwen3OmniMoeForConditionalGeneration given multimodal inputs', 'generate text and audio output using Qwen3OmniMoeForConditionalGeneration.generate with return_audio enabled', 'encode images using Qwen3OmniMoeVisionEncoder to extract visual features for the LLM', 'encode audio inputs using Qwen3OmniMoeAudioEncoder to extract audio features for the LLM', 'decode audio codes to waveform using Qwen3OmniMoeCode2Wav with chunked inference', 'create a Qwen3OmniMoeForConditionalGeneration model with multimodal audio, image, video, and text support', 'generate text and audio output from a Qwen3OmniMoeForConditionalGeneration model using the generate method', 'build a Qwen3OmniMoeProcessor to tokenize text and process audio, image, video, and multimodal inputs', 'configure a Qwen3OmniMoeConfig with thinker, talker, and code2wav sub-configurations for the omni model', 'run Qwen3OmniMoeCode2Wav vocoder to convert codec token sequences into waveform audio output', 'create a BatchFeature from text, images, videos, and audio inputs by calling the processor with multimodal special tokens', 'test replacing multimodal special tokens like audio, image, and video tokens with placeholder sequences in text templates', 'summarize how post_process_multimodal_output decodes generated model outputs into text strings or audio numpy arrays based on generation_mode', 'review the get_chunked_index method that splits monotonically increasing token indices into chunks by token value ranges']
```

Usage

```
{'create_qwen3_omni_moe_model': 'create a Qwen3OmniMoeForConditionalGeneration model with multimodal audio, image, video, and text support', 'generate_qwen3_omni_moe_output': 'generate text and audio output from a Qwen3OmniMoeForConditionalGeneration model using the generate method', 'build_qwen3_omni_moe_processor': 'build a Qwen3OmniMoeProcessor to tokenize text and process audio, image, video, and multimodal inputs', 'configure_qwen3_omni_moe': 'configure a Qwen3OmniMoeConfig with thinker, talker, and code2wav sub-configurations for the omni model', 'run_qwen3_omni_moe_code2wav': 'run Qwen3OmniMoeCode2Wav vocoder to convert codec token sequences into waveform audio output'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_omni_moe/processing_qwen3_omni_moe.py

Prompts

```
['create a Qwen3OmniMoeConfig instance with default thinker, talker, and code2wav sub-configurations', 'create a Qwen3OmniMoeThinkerConfig with audio, vision, and text sub-configurations for multimodal input', 'create a Qwen3OmniMoeTalkerConfig with code predictor and text decoder sub-configurations for speech generation', 'create a Qwen3OmniMoeTextConfig with MoE parameters including 128 experts and 8 experts per token', 'create a Qwen3OmniMoeAudioEncoderConfig with 128 mel bins and 1280 d_model for audio processing', 'generate a text response from Qwen3OmniMoeForConditionalGeneration given multimodal inputs', 'generate text and audio output using Qwen3OmniMoeForConditionalGeneration.generate with return_audio enabled', 'encode images using Qwen3OmniMoeVisionEncoder to extract visual features for the LLM', 'encode audio inputs using Qwen3OmniMoeAudioEncoder to extract audio features for the LLM', 'decode audio codes to waveform using Qwen3OmniMoeCode2Wav with chunked inference', 'create a Qwen3OmniMoeForConditionalGeneration model with multimodal audio, image, video, and text support', 'generate text and audio output from a Qwen3OmniMoeForConditionalGeneration model using the generate method', 'build a Qwen3OmniMoeProcessor to tokenize text and process audio, image, video, and multimodal inputs', 'configure a Qwen3OmniMoeConfig with thinker, talker, and code2wav sub-configurations for the omni model', 'run Qwen3OmniMoeCode2Wav vocoder to convert codec token sequences into waveform audio output', 'create a BatchFeature from text, images, videos, and audio inputs by calling the processor with multimodal special tokens', 'test replacing multimodal special tokens like audio, image, and video tokens with placeholder sequences in text templates', 'summarize how post_process_multimodal_output decodes generated model outputs into text strings or audio numpy arrays based on generation_mode', 'review the get_chunked_index method that splits monotonically increasing token indices into chunks by token value ranges']
```

Usage

```
{'build_qwen3_omni_moe_processor': 'build a Qwen3OmniMoeProcessor instance with image, video, audio feature extractors and a tokenizer for multimodal input processing', 'create_multimodal_input_batch': 'create a BatchFeature from text, images, videos, and audio inputs by calling the processor with multimodal special tokens', 'test_replace_multimodal_special_tokens': 'test replacing multimodal special tokens like audio, image, and video tokens with placeholder sequences in text templates', 'summarize_post_process_multimodal_output': 'summarize how post_process_multimodal_output decodes generated model outputs into text strings or audio numpy arrays based on generation_mode', 'review_get_chunked_index': 'review the get_chunked_index method that splits monotonically increasing token indices into chunks by token value ranges'}
```

