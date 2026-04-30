# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/lfm2_moe/modeling_lfm2_moe.py

Prompts

```
['create an Lfm2MoeForCausalLM model with a given config for autoregressive text generation', 'build an Lfm2MoeModel with embedding tokens, rotary embeddings, and decoder layers for forward pass inference', 'run Lfm2MoeAttention multi-headed attention with query key value projections and rotary position embeddings', 'build Lfm2MoeSparseMoeBlock with expert routing, gating, and token-to-expert assignment for mixture-of-experts inference', 'run Lfm2MoeShortConv causal convolution with past key value caching and CUDA kernel fast path for state space style processing', 'build an Lfm2MoeForCausalLM model from config for autoregressive text generation with sparse MoE', 'create an Lfm2MoeModel with rotary embeddings, causal masking, and mixed dense-sparse decoder layers', 'initialize Lfm2MoePreTrainedModel weights with normal distribution for experts and zeros for expert bias', 'route tokens through Lfm2MoeSparseMoeBlock using sigmoid gating, top-k expert selection, and weighted aggregation', 'configure Lfm2MoeDecoderLayer to use dense MLP for early layers and sparse MoE for deeper layers']
```

Usage

```
{'create_lfm2_moe_causal_lm': 'create an Lfm2MoeForCausalLM model with a given config for autoregressive text generation', 'build_lfm2_moe_model': 'build an Lfm2MoeModel with embedding tokens, rotary embeddings, and decoder layers for forward pass inference', 'run_lfm2_moe_attention': 'run Lfm2MoeAttention multi-headed attention with query key value projections and rotary position embeddings', 'build_lfm2_moe_sparse_moe': 'build Lfm2MoeSparseMoeBlock with expert routing, gating, and token-to-expert assignment for mixture-of-experts inference', 'run_lfm2_moe_conv': 'run Lfm2MoeShortConv causal convolution with past key value caching and CUDA kernel fast path for state space style processing'}
```

## File: huggingface_transformers/src/transformers/models/lfm2_moe/modular_lfm2_moe.py

Prompts

```
['create an Lfm2MoeForCausalLM model with a given config for autoregressive text generation', 'build an Lfm2MoeModel with embedding tokens, rotary embeddings, and decoder layers for forward pass inference', 'run Lfm2MoeAttention multi-headed attention with query key value projections and rotary position embeddings', 'build Lfm2MoeSparseMoeBlock with expert routing, gating, and token-to-expert assignment for mixture-of-experts inference', 'run Lfm2MoeShortConv causal convolution with past key value caching and CUDA kernel fast path for state space style processing', 'build an Lfm2MoeForCausalLM model from config for autoregressive text generation with sparse MoE', 'create an Lfm2MoeModel with rotary embeddings, causal masking, and mixed dense-sparse decoder layers', 'initialize Lfm2MoePreTrainedModel weights with normal distribution for experts and zeros for expert bias', 'route tokens through Lfm2MoeSparseMoeBlock using sigmoid gating, top-k expert selection, and weighted aggregation', 'configure Lfm2MoeDecoderLayer to use dense MLP for early layers and sparse MoE for deeper layers']
```

Usage

```
{'build_lfm2moe_causal_lm': 'build an Lfm2MoeForCausalLM model from config for autoregressive text generation with sparse MoE', 'create_lfm2moe_model': 'create an Lfm2MoeModel with rotary embeddings, causal masking, and mixed dense-sparse decoder layers', 'initialize_lfm2moe_weights': 'initialize Lfm2MoePreTrainedModel weights with normal distribution for experts and zeros for expert bias', 'route_tokens_sparse_moe': 'route tokens through Lfm2MoeSparseMoeBlock using sigmoid gating, top-k expert selection, and weighted aggregation', 'configure_moe_decoder_layer': 'configure Lfm2MoeDecoderLayer to use dense MLP for early layers and sparse MoE for deeper layers'}
```

