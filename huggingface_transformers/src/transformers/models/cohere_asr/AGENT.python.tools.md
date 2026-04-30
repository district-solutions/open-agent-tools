# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cohere_asr/modeling_cohere_asr.py

Prompts

```
['create a CohereAsrForConditionalGeneration model for automatic speech recognition that transcribes audio to text', 'build a CohereAsrModel seq2seq pipeline that encodes audio input features and decodes text with cross-attention', 'test the CohereAsrDecoder with causal masking and past key value caching for autoregressive text generation', 'refactor the CohereAsrPreTrainedModel to freeze encoder parameters so they are not updated during training', 'summarize the shift_tokens_right function that shifts decoder input IDs right for teacher-forcing during training', 'run CohereAsrForConditionalGeneration to transcribe audio input features into text output', 'create a CohereAsrModel instance with encoder-decoder architecture for speech recognition', 'build a CohereAsrDecoder with self-attention, cross-attention, and MLP layers for sequence generation', 'test CohereAsrSelfAttention and CohereAsrCrossAttention modules with KV caching support', 'review the forward method of CohereAsrForConditionalGeneration with labels for loss computation', 'create a CohereAsrProcessor with a feature_extractor and tokenizer for automatic speech recognition', 'build decoder prompt token IDs for a given language and punctuation settings', 'process audio input with language, punctuation, and optional text labels for ASR training', 'decode ASR output token IDs into text strings with optional chunk reassembly', 'reassemble per-chunk transcription texts back into per-sample strings using audio chunk index mapping']
```

Usage

```
{'create_asr_transcription_model': 'create a CohereAsrForConditionalGeneration model for automatic speech recognition that transcribes audio to text', 'build_seq2seq_asr_pipeline': 'build a CohereAsrModel seq2seq pipeline that encodes audio input features and decodes text with cross-attention', 'test_decoder_autoregressive_generation': 'test the CohereAsrDecoder with causal masking and past key value caching for autoregressive text generation', 'refactor_pretrained_model_freeze_encoder': 'refactor the CohereAsrPreTrainedModel to freeze encoder parameters so they are not updated during training', 'summarize_shift_tokens_right': 'summarize the shift_tokens_right function that shifts decoder input IDs right for teacher-forcing during training'}
```

## File: huggingface_transformers/src/transformers/models/cohere_asr/modular_cohere_asr.py

Prompts

```
['create a CohereAsrForConditionalGeneration model for automatic speech recognition that transcribes audio to text', 'build a CohereAsrModel seq2seq pipeline that encodes audio input features and decodes text with cross-attention', 'test the CohereAsrDecoder with causal masking and past key value caching for autoregressive text generation', 'refactor the CohereAsrPreTrainedModel to freeze encoder parameters so they are not updated during training', 'summarize the shift_tokens_right function that shifts decoder input IDs right for teacher-forcing during training', 'run CohereAsrForConditionalGeneration to transcribe audio input features into text output', 'create a CohereAsrModel instance with encoder-decoder architecture for speech recognition', 'build a CohereAsrDecoder with self-attention, cross-attention, and MLP layers for sequence generation', 'test CohereAsrSelfAttention and CohereAsrCrossAttention modules with KV caching support', 'review the forward method of CohereAsrForConditionalGeneration with labels for loss computation', 'create a CohereAsrProcessor with a feature_extractor and tokenizer for automatic speech recognition', 'build decoder prompt token IDs for a given language and punctuation settings', 'process audio input with language, punctuation, and optional text labels for ASR training', 'decode ASR output token IDs into text strings with optional chunk reassembly', 'reassemble per-chunk transcription texts back into per-sample strings using audio chunk index mapping']
```

Usage

```
{'run_cohere_asr_transcription': 'run CohereAsrForConditionalGeneration to transcribe audio input features into text output', 'create_cohere_asr_model': 'create a CohereAsrModel instance with encoder-decoder architecture for speech recognition', 'build_cohere_asr_decoder': 'build a CohereAsrDecoder with self-attention, cross-attention, and MLP layers for sequence generation', 'test_cohere_asr_attention': 'test CohereAsrSelfAttention and CohereAsrCrossAttention modules with KV caching support', 'review_cohere_asr_forward': 'review the forward method of CohereAsrForConditionalGeneration with labels for loss computation'}
```

## File: huggingface_transformers/src/transformers/models/cohere_asr/processing_cohere_asr.py

Prompts

```
['create a CohereAsrForConditionalGeneration model for automatic speech recognition that transcribes audio to text', 'build a CohereAsrModel seq2seq pipeline that encodes audio input features and decodes text with cross-attention', 'test the CohereAsrDecoder with causal masking and past key value caching for autoregressive text generation', 'refactor the CohereAsrPreTrainedModel to freeze encoder parameters so they are not updated during training', 'summarize the shift_tokens_right function that shifts decoder input IDs right for teacher-forcing during training', 'run CohereAsrForConditionalGeneration to transcribe audio input features into text output', 'create a CohereAsrModel instance with encoder-decoder architecture for speech recognition', 'build a CohereAsrDecoder with self-attention, cross-attention, and MLP layers for sequence generation', 'test CohereAsrSelfAttention and CohereAsrCrossAttention modules with KV caching support', 'review the forward method of CohereAsrForConditionalGeneration with labels for loss computation', 'create a CohereAsrProcessor with a feature_extractor and tokenizer for automatic speech recognition', 'build decoder prompt token IDs for a given language and punctuation settings', 'process audio input with language, punctuation, and optional text labels for ASR training', 'decode ASR output token IDs into text strings with optional chunk reassembly', 'reassemble per-chunk transcription texts back into per-sample strings using audio chunk index mapping']
```

Usage

```
{'create_cohere_asr_processor': 'create a CohereAsrProcessor with a feature_extractor and tokenizer for automatic speech recognition', 'build_decoder_prompt_ids': 'build decoder prompt token IDs for a given language and punctuation settings', 'process_audio_input': 'process audio input with language, punctuation, and optional text labels for ASR training', 'decode_transcription_chunks': 'decode ASR output token IDs into text strings with optional chunk reassembly', 'reassemble_chunk_texts': 'reassemble per-chunk transcription texts back into per-sample strings using audio chunk index mapping'}
```

