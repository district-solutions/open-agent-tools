# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/long_context/H2O/utils/cache.py

Prompts

```
['create a DynamicCache instance to store key and value states that grow dynamically during token generation', 'update a SinkCache with new key and value states using RoPE rotation for attention sink token management', 'create an HHCache with heavy-hitter oracle to store only important and recent tokens in the KV cache', 'create a StaticCache with pre-allocated tensors for use with torch.compile for optimized inference performance', 'convert a legacy past_key_values tuple into a DynamicCache or HHCache instance using from_legacy_cache', 'build a H2OLlamaForCausalLM model from a LlamaConfig with heavy-hitter oracle attention for long context', 'create a H2OLlamaAttention module with positional rolling and heavy-hitter cache for a given layer index', 'test the _make_causal_mask function to generate a causal attention mask for self-attention layers', 'review the apply_rotary_pos_emb_single function that applies rotary position embeddings to query or key states', 'refactor the repeat_kv function to expand key-value heads for grouped query attention in Llama models', 'load a pretrained causal language model and tokenizer from a model name or path using Hugging Face transformers', 'download a file from a URL to a local folder and return the file path', 'load a JSONL file and return a list of dictionaries parsed from each line', 'generate tokens greedily from a model using past key values and stream output word by word', 'review the streaming utility functions for loading models, downloading files, parsing JSONL, and greedy token generation']
```

Usage

```
{'create_dynamic_cache': 'create a DynamicCache instance to store key and value states that grow dynamically during token generation', 'update_sink_cache': 'update a SinkCache with new key and value states using RoPE rotation for attention sink token management', 'create_hh_cache': 'create an HHCache with heavy-hitter oracle to store only important and recent tokens in the KV cache', 'create_static_cache': 'create a StaticCache with pre-allocated tensors for use with torch.compile for optimized inference performance', 'convert_legacy_cache': 'convert a legacy past_key_values tuple into a DynamicCache or HHCache instance using from_legacy_cache'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/long_context/H2O/utils/llama.py

Prompts

```
['create a DynamicCache instance to store key and value states that grow dynamically during token generation', 'update a SinkCache with new key and value states using RoPE rotation for attention sink token management', 'create an HHCache with heavy-hitter oracle to store only important and recent tokens in the KV cache', 'create a StaticCache with pre-allocated tensors for use with torch.compile for optimized inference performance', 'convert a legacy past_key_values tuple into a DynamicCache or HHCache instance using from_legacy_cache', 'build a H2OLlamaForCausalLM model from a LlamaConfig with heavy-hitter oracle attention for long context', 'create a H2OLlamaAttention module with positional rolling and heavy-hitter cache for a given layer index', 'test the _make_causal_mask function to generate a causal attention mask for self-attention layers', 'review the apply_rotary_pos_emb_single function that applies rotary position embeddings to query or key states', 'refactor the repeat_kv function to expand key-value heads for grouped query attention in Llama models', 'load a pretrained causal language model and tokenizer from a model name or path using Hugging Face transformers', 'download a file from a URL to a local folder and return the file path', 'load a JSONL file and return a list of dictionaries parsed from each line', 'generate tokens greedily from a model using past key values and stream output word by word', 'review the streaming utility functions for loading models, downloading files, parsing JSONL, and greedy token generation']
```

Usage

```
{'build_H2OLlamaForCausalLM': 'build a H2OLlamaForCausalLM model from a LlamaConfig with heavy-hitter oracle attention for long context', 'create_H2OLlamaAttention': 'create a H2OLlamaAttention module with positional rolling and heavy-hitter cache for a given layer index', 'test_make_causal_mask': 'test the _make_causal_mask function to generate a causal attention mask for self-attention layers', 'review_apply_rotary_pos_emb_single': 'review the apply_rotary_pos_emb_single function that applies rotary position embeddings to query or key states', 'refactor_repeat_kv': 'refactor the repeat_kv function to expand key-value heads for grouped query attention in Llama models'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/long_context/H2O/utils/streaming.py

Prompts

```
['create a DynamicCache instance to store key and value states that grow dynamically during token generation', 'update a SinkCache with new key and value states using RoPE rotation for attention sink token management', 'create an HHCache with heavy-hitter oracle to store only important and recent tokens in the KV cache', 'create a StaticCache with pre-allocated tensors for use with torch.compile for optimized inference performance', 'convert a legacy past_key_values tuple into a DynamicCache or HHCache instance using from_legacy_cache', 'build a H2OLlamaForCausalLM model from a LlamaConfig with heavy-hitter oracle attention for long context', 'create a H2OLlamaAttention module with positional rolling and heavy-hitter cache for a given layer index', 'test the _make_causal_mask function to generate a causal attention mask for self-attention layers', 'review the apply_rotary_pos_emb_single function that applies rotary position embeddings to query or key states', 'refactor the repeat_kv function to expand key-value heads for grouped query attention in Llama models', 'load a pretrained causal language model and tokenizer from a model name or path using Hugging Face transformers', 'download a file from a URL to a local folder and return the file path', 'load a JSONL file and return a list of dictionaries parsed from each line', 'generate tokens greedily from a model using past key values and stream output word by word', 'review the streaming utility functions for loading models, downloading files, parsing JSONL, and greedy token generation']
```

Usage

```
{'load_llm_model': 'load a pretrained causal language model and tokenizer from a model name or path using Hugging Face transformers', 'download_url_file': 'download a file from a URL to a local folder and return the file path', 'load_jsonl_data': 'load a JSONL file and return a list of dictionaries parsed from each line', 'greedy_generate_tokens': 'generate tokens greedily from a model using past key values and stream output word by word', 'review_streaming_utils': 'review the streaming utility functions for loading models, downloading files, parsing JSONL, and greedy token generation'}
```

