# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm4/convert_glm4_weights_to_hf.py

Prompts

```
['convert GLM4 model weights from original format to HuggingFace Transformers format', 'convert GLM4 tokenizer to HuggingFace PreTrainedTokenizerFast with optional post processor', 'convert original GLM4 config dictionary to HuggingFace Glm4Config format', 'convert original GLM4 state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'load model weights from .safetensors or .bin files in a directory', 'run GLM-4 causal language model generation with a tokenizer and prompt input', 'create a GLM-4 base model with embedding, decoder layers, and rotary embeddings', 'test GLM-4 multi-head attention with rotary position embeddings and KV caching', 'build a GLM-4 sequence classification head on top of the base transformer model', 'summarize GLM-4 token classification output for named entity recognition tasks', 'create a GLM-4 MLP layer inheriting from Phi3MLP for transformer feed-forward computation', 'build a GLM-4 decoder layer with attention, MLP, and multiple RMS normalization layers']
```

Usage

```
{'convert_glm4_model': 'convert GLM4 model weights from original format to HuggingFace Transformers format', 'convert_glm4_tokenizer': 'convert GLM4 tokenizer to HuggingFace PreTrainedTokenizerFast with optional post processor', 'convert_config': 'convert original GLM4 config dictionary to HuggingFace Glm4Config format', 'convert_state_dict': 'convert original GLM4 state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'load_weights': 'load model weights from .safetensors or .bin files in a directory'}
```

## File: huggingface_transformers/src/transformers/models/glm4/modeling_glm4.py

Prompts

```
['convert GLM4 model weights from original format to HuggingFace Transformers format', 'convert GLM4 tokenizer to HuggingFace PreTrainedTokenizerFast with optional post processor', 'convert original GLM4 config dictionary to HuggingFace Glm4Config format', 'convert original GLM4 state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'load model weights from .safetensors or .bin files in a directory', 'run GLM-4 causal language model generation with a tokenizer and prompt input', 'create a GLM-4 base model with embedding, decoder layers, and rotary embeddings', 'test GLM-4 multi-head attention with rotary position embeddings and KV caching', 'build a GLM-4 sequence classification head on top of the base transformer model', 'summarize GLM-4 token classification output for named entity recognition tasks', 'create a GLM-4 MLP layer inheriting from Phi3MLP for transformer feed-forward computation', 'build a GLM-4 decoder layer with attention, MLP, and multiple RMS normalization layers']
```

Usage

```
{'run_glm4_causal_lm': 'run GLM-4 causal language model generation with a tokenizer and prompt input', 'create_glm4_model': 'create a GLM-4 base model with embedding, decoder layers, and rotary embeddings', 'test_glm4_attention': 'test GLM-4 multi-head attention with rotary position embeddings and KV caching', 'build_glm4_sequence_classifier': 'build a GLM-4 sequence classification head on top of the base transformer model', 'summarize_glm4_token_classifier': 'summarize GLM-4 token classification output for named entity recognition tasks'}
```

## File: huggingface_transformers/src/transformers/models/glm4/modular_glm4.py

Prompts

```
['convert GLM4 model weights from original format to HuggingFace Transformers format', 'convert GLM4 tokenizer to HuggingFace PreTrainedTokenizerFast with optional post processor', 'convert original GLM4 config dictionary to HuggingFace Glm4Config format', 'convert original GLM4 state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'load model weights from .safetensors or .bin files in a directory', 'run GLM-4 causal language model generation with a tokenizer and prompt input', 'create a GLM-4 base model with embedding, decoder layers, and rotary embeddings', 'test GLM-4 multi-head attention with rotary position embeddings and KV caching', 'build a GLM-4 sequence classification head on top of the base transformer model', 'summarize GLM-4 token classification output for named entity recognition tasks', 'create a GLM-4 MLP layer inheriting from Phi3MLP for transformer feed-forward computation', 'build a GLM-4 decoder layer with attention, MLP, and multiple RMS normalization layers']
```

Usage

```
{'create_glm4_mlp': 'create a GLM-4 MLP layer inheriting from Phi3MLP for transformer feed-forward computation', 'build_glm4_decoder_layer': 'build a GLM-4 decoder layer with attention, MLP, and multiple RMS normalization layers', 'test_glm4_attention': 'test GLM-4 attention layer with rotary position embeddings and KV caching support', 'run_glm4_causal_lm': 'run GLM-4 causal language model generation with a tokenizer and prompt input', 'build_glm4_sequence_classifier': 'build a GLM-4 sequence classification head on top of the base transformer model'}
```

