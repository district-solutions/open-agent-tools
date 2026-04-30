# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/model_repo_f5_tts/f5_tts/1/f5_tts_trtllm.py

Prompts

```
['build a F5TTS inference engine from a TensorRT-LLM serialized engine file for audio generation', 'create a TextEmbedding module that converts text tokens into embeddings with rotary position encodings', 'run the F5TTS sample method to generate mel spectrograms from text and reference audio conditioning', 'test the remove_tensor_padding function to strip padded tokens from batched audio tensors', 'summarize the precompute_freqs_cis function that computes rotary embedding frequencies for positional encoding', 'create a tokenizer that loads a vocab file and returns a char-to-index map with vocab size', 'build a function that converts Chinese text to pinyin using rjieba segmentation and polyphone handling', 'test the function that converts a list of character strings to padded index tensors using a vocab map', 'review the TritonPythonModel initialize method that loads the F5TTS model, tokenizer, resampler, and vocoder', 'summarize the TritonPythonModel execute method that processes audio inference requests with mel spectrogram extraction and vocoder synthesis']
```

Usage

```
{'build_f5_tts_inference_engine': 'build a F5TTS inference engine from a TensorRT-LLM serialized engine file for audio generation', 'create_text_embedding': 'create a TextEmbedding module that converts text tokens into embeddings with rotary position encodings', 'run_f5_tts_sampling': 'run the F5TTS sample method to generate mel spectrograms from text and reference audio conditioning', 'test_remove_tensor_padding': 'test the remove_tensor_padding function to strip padded tokens from batched audio tensors', 'summarize_precompute_freqs_cis': 'summarize the precompute_freqs_cis function that computes rotary embedding frequencies for positional encoding'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/model_repo_f5_tts/f5_tts/1/model.py

Prompts

```
['build a F5TTS inference engine from a TensorRT-LLM serialized engine file for audio generation', 'create a TextEmbedding module that converts text tokens into embeddings with rotary position encodings', 'run the F5TTS sample method to generate mel spectrograms from text and reference audio conditioning', 'test the remove_tensor_padding function to strip padded tokens from batched audio tensors', 'summarize the precompute_freqs_cis function that computes rotary embedding frequencies for positional encoding', 'create a tokenizer that loads a vocab file and returns a char-to-index map with vocab size', 'build a function that converts Chinese text to pinyin using rjieba segmentation and polyphone handling', 'test the function that converts a list of character strings to padded index tensors using a vocab map', 'review the TritonPythonModel initialize method that loads the F5TTS model, tokenizer, resampler, and vocoder', 'summarize the TritonPythonModel execute method that processes audio inference requests with mel spectrogram extraction and vocoder synthesis']
```

Usage

```
{'create_get_tokenizer': 'create a tokenizer that loads a vocab file and returns a char-to-index map with vocab size', 'build_convert_char_to_pinyin': 'build a function that converts Chinese text to pinyin using rjieba segmentation and polyphone handling', 'test_list_str_to_idx': 'test the function that converts a list of character strings to padded index tensors using a vocab map', 'review_tritonpythonmodel_initialize': 'review the TritonPythonModel initialize method that loads the F5TTS model, tokenizer, resampler, and vocoder', 'summarize_tritonpythonmodel_execute': 'summarize the TritonPythonModel execute method that processes audio inference requests with mel spectrogram extraction and vocoder synthesis'}
```

