# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/inputs/engine.py

Prompts

```
['build a token-based engine input from a list of prompt token IDs with optional prompt text and cache salt', 'build an embeddings-based engine input from a torch tensor of prompt embeddings with optional prompt text', 'build a multi-modal engine input with prompt token IDs, multi-modal kwargs, hashes, and placeholder ranges', 'build an encoder-decoder engine input from separate encoder and decoder singleton inputs with a decoder start token id', 'split an encoder-decoder engine input into separate encoder and decoder singleton inputs', 'create an InputPreprocessor instance with a VllmConfig to preprocess prompts for a vLLM model', 'build engine inputs from a text prompt using InputPreprocessor.preprocess for decoder-only models', 'build engine inputs from encoder and decoder prompts using InputPreprocessor.preprocess for encoder-decoder models', 'build a list of token IDs from a text string using InputPreprocessor._tokenize_prompt', 'build multi-modal engine inputs from text and multimodal data using InputPreprocessor._process_multimodal']
```

Usage

```
{'build_tokens_input': 'build a token-based engine input from a list of prompt token IDs with optional prompt text and cache salt', 'build_embeds_input': 'build an embeddings-based engine input from a torch tensor of prompt embeddings with optional prompt text', 'build_mm_input': 'build a multi-modal engine input with prompt token IDs, multi-modal kwargs, hashes, and placeholder ranges', 'build_enc_dec_input': 'build an encoder-decoder engine input from separate encoder and decoder singleton inputs with a decoder start token id', 'split_enc_dec_input': 'split an encoder-decoder engine input into separate encoder and decoder singleton inputs'}
```

## File: vllm-project_vllm/vllm/inputs/preprocess.py

Prompts

```
['build a token-based engine input from a list of prompt token IDs with optional prompt text and cache salt', 'build an embeddings-based engine input from a torch tensor of prompt embeddings with optional prompt text', 'build a multi-modal engine input with prompt token IDs, multi-modal kwargs, hashes, and placeholder ranges', 'build an encoder-decoder engine input from separate encoder and decoder singleton inputs with a decoder start token id', 'split an encoder-decoder engine input into separate encoder and decoder singleton inputs', 'create an InputPreprocessor instance with a VllmConfig to preprocess prompts for a vLLM model', 'build engine inputs from a text prompt using InputPreprocessor.preprocess for decoder-only models', 'build engine inputs from encoder and decoder prompts using InputPreprocessor.preprocess for encoder-decoder models', 'build a list of token IDs from a text string using InputPreprocessor._tokenize_prompt', 'build multi-modal engine inputs from text and multimodal data using InputPreprocessor._process_multimodal']
```

Usage

```
{'create_InputPreprocessor': 'create an InputPreprocessor instance with a VllmConfig to preprocess prompts for a vLLM model', 'build_preprocess_text': 'build engine inputs from a text prompt using InputPreprocessor.preprocess for decoder-only models', 'build_preprocess_encoder_decoder': 'build engine inputs from encoder and decoder prompts using InputPreprocessor.preprocess for encoder-decoder models', 'build_tokenize_prompt': 'build a list of token IDs from a text string using InputPreprocessor._tokenize_prompt', 'build_process_multimodal': 'build multi-modal engine inputs from text and multimodal data using InputPreprocessor._process_multimodal'}
```

