# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/huggingface/canon_helper.py

Prompts

```
['create a ShortConvolution layer with a given hidden size, kernel size, and silu activation', 'call the forward method of ShortConvolution on a tensor with optional mask and cache', 'call the step method of ShortConvolution to decode one token at a time using cache', 'create a canon ShortConvolution module from a dimension and config object with kernel and bias settings', 'apply a canon convolution to hidden states with caching, masking, and optional residual connection', 'build a LlamaCanonForCausalLM model with canon layers, Q/K norm, and partial RoPE from a config', 'build a LlamaCanonModel transformer backbone with embedding, decoder layers, and RMSNorm', 'create a LlamaCanonDecoderLayer with optional canonA and canonC layers for a given layer index', 'create a LlamaCanonAttention module with optional Q/K normalization and canonB applied to QKV', 'create a LlamaCanonMLP with gated linear units and optional canonD on concatenated gate and up projections', 'apply rotary position embeddings to query and key tensors using huggingface or lingua RoPE version', 'load a lingua checkpoint state dict into a LlamaCanonForCausalLM model with key mapping', 'load a pretrained lingua model from a params.json and consolidated.pth using from_pretrained', 'create a LlamaRotaryEmbedding with dynamic frequency update support and configurable rope type']
```

Usage

```
{'create_ShortConvolution': 'create a ShortConvolution layer with a given hidden size, kernel size, and silu activation', 'call_ShortConvolution_forward': 'call the forward method of ShortConvolution on a tensor with optional mask and cache', 'call_ShortConvolution_step': 'call the step method of ShortConvolution to decode one token at a time using cache', 'create_canon': 'create a canon ShortConvolution module from a dimension and config object with kernel and bias settings', 'apply_canon': 'apply a canon convolution to hidden states with caching, masking, and optional residual connection'}
```

## File: facebookresearch_physicslm4/huggingface/modeling_llama_canon.py

Prompts

```
['create a ShortConvolution layer with a given hidden size, kernel size, and silu activation', 'call the forward method of ShortConvolution on a tensor with optional mask and cache', 'call the step method of ShortConvolution to decode one token at a time using cache', 'create a canon ShortConvolution module from a dimension and config object with kernel and bias settings', 'apply a canon convolution to hidden states with caching, masking, and optional residual connection', 'build a LlamaCanonForCausalLM model with canon layers, Q/K norm, and partial RoPE from a config', 'build a LlamaCanonModel transformer backbone with embedding, decoder layers, and RMSNorm', 'create a LlamaCanonDecoderLayer with optional canonA and canonC layers for a given layer index', 'create a LlamaCanonAttention module with optional Q/K normalization and canonB applied to QKV', 'create a LlamaCanonMLP with gated linear units and optional canonD on concatenated gate and up projections', 'apply rotary position embeddings to query and key tensors using huggingface or lingua RoPE version', 'load a lingua checkpoint state dict into a LlamaCanonForCausalLM model with key mapping', 'load a pretrained lingua model from a params.json and consolidated.pth using from_pretrained', 'create a LlamaRotaryEmbedding with dynamic frequency update support and configurable rope type']
```

Usage

```
{'build_causal_lm_model': 'build a LlamaCanonForCausalLM model with canon layers, Q/K norm, and partial RoPE from a config', 'build_base_model': 'build a LlamaCanonModel transformer backbone with embedding, decoder layers, and RMSNorm', 'create_decoder_layer': 'create a LlamaCanonDecoderLayer with optional canonA and canonC layers for a given layer index', 'create_attention_with_canonB': 'create a LlamaCanonAttention module with optional Q/K normalization and canonB applied to QKV', 'create_mlp_with_canonD': 'create a LlamaCanonMLP with gated linear units and optional canonD on concatenated gate and up projections', 'apply_rotary_pos_emb': 'apply rotary position embeddings to query and key tensors using huggingface or lingua RoPE version', 'load_from_lingua_state': 'load a lingua checkpoint state dict into a LlamaCanonForCausalLM model with key mapping', 'load_pretrained_lingua_model': 'load a pretrained lingua model from a params.json and consolidated.pth using from_pretrained', 'create_rotary_embedding': 'create a LlamaRotaryEmbedding with dynamic frequency update support and configurable rope type'}
```

