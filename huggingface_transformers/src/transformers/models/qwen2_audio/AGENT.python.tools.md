# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/qwen2_audio/modeling_qwen2_audio.py

Prompts

```
['create a Qwen2AudioForConditionalGeneration model for audio-text multimodal tasks', 'run audio caption generation using Qwen2AudioForConditionalGeneration with audio input and text prompt', 'build a Qwen2AudioEncoder to extract audio features from mel spectrogram input features', 'merge audio features with text token embeddings in Qwen2AudioForConditionalGeneration for multimodal processing', 'test the Qwen2AudioAttention multi-headed attention mechanism with query, key, and value projections', 'create a Qwen2AudioProcessor combining a feature extractor and tokenizer for audio-text multimodal processing', 'run the Qwen2AudioProcessor to tokenize text with embedded audio tokens and extract audio features into a BatchFeature', 'build expanded audio token sequences by replacing <|AUDIO|> placeholders with bos/eos-wrapped token chains based on audio lengths', 'test the Qwen2AudioProcessor.__call__ method with text containing audio tokens and corresponding numpy audio arrays', 'review the Qwen2AudioProcessor.default_chat_template Jinja template for formatting multimodal chat history with audio and text content']
```

Usage

```
{'create_qwen2audio_model': 'create a Qwen2AudioForConditionalGeneration model for audio-text multimodal tasks', 'run_audio_caption_generation': 'run audio caption generation using Qwen2AudioForConditionalGeneration with audio input and text prompt', 'build_audio_encoder': 'build a Qwen2AudioEncoder to extract audio features from mel spectrogram input features', 'merge_audio_text_embeddings': 'merge audio features with text token embeddings in Qwen2AudioForConditionalGeneration for multimodal processing', 'test_qwen2audio_attention': 'test the Qwen2AudioAttention multi-headed attention mechanism with query, key, and value projections'}
```

## File: huggingface_transformers/src/transformers/models/qwen2_audio/processing_qwen2_audio.py

Prompts

```
['create a Qwen2AudioForConditionalGeneration model for audio-text multimodal tasks', 'run audio caption generation using Qwen2AudioForConditionalGeneration with audio input and text prompt', 'build a Qwen2AudioEncoder to extract audio features from mel spectrogram input features', 'merge audio features with text token embeddings in Qwen2AudioForConditionalGeneration for multimodal processing', 'test the Qwen2AudioAttention multi-headed attention mechanism with query, key, and value projections', 'create a Qwen2AudioProcessor combining a feature extractor and tokenizer for audio-text multimodal processing', 'run the Qwen2AudioProcessor to tokenize text with embedded audio tokens and extract audio features into a BatchFeature', 'build expanded audio token sequences by replacing <|AUDIO|> placeholders with bos/eos-wrapped token chains based on audio lengths', 'test the Qwen2AudioProcessor.__call__ method with text containing audio tokens and corresponding numpy audio arrays', 'review the Qwen2AudioProcessor.default_chat_template Jinja template for formatting multimodal chat history with audio and text content']
```

Usage

```
{'create_qwen2audio_processor': 'create a Qwen2AudioProcessor combining a feature extractor and tokenizer for audio-text multimodal processing', 'run_audio_text_processing': 'run the Qwen2AudioProcessor to tokenize text with embedded audio tokens and extract audio features into a BatchFeature', 'build_audio_token_expansion': 'build expanded audio token sequences by replacing <|AUDIO|> placeholders with bos/eos-wrapped token chains based on audio lengths', 'test_qwen2audio_call': 'test the Qwen2AudioProcessor.__call__ method with text containing audio tokens and corresponding numpy audio arrays', 'review_default_chat_template': 'review the Qwen2AudioProcessor.default_chat_template Jinja template for formatting multimodal chat history with audio and text content'}
```

