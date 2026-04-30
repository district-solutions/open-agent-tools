# Agent Python Tools

- repo: tanishqkumar/ssd
- repo_uri: https://github.com/tanishqkumar/ssd

## File: tanishqkumar_ssd/ssd/models/eagle3_draft_llama3.py

Prompts

```
['create an Eagle3DraftForCausalLM model with draft speculative decoding and Eagle3 attention layers', 'build an Eagle3DecoderLayer with Eagle3Attention and LlamaMLP conditioned on target hidden states', 'build an Eagle3Attention module with QKV parallel linear projection and Eagle speculative attention', 'run the Eagle3DraftModel forward pass with input ids, projected hidden states, and positions', 'compute full vocab logits from draft hidden states using d2t index mapping', 'build a LlamaForCausalLM model from a LlamaConfig with optional speculative decoding and tensor parallelism', 'create a LlamaDecoderLayer with attention, MLP, and RMS norm configured from a LlamaConfig', 'build a LlamaAttention module with QKV projection, rotary embeddings, and multi-head attention', 'create a LlamaMLP with merged gate-up projection, SiLU activation, and row-parallel down projection', 'build a LlamaModel with token embeddings, stacked decoder layers, and final RMS normalization', 'create a Qwen3ForCausalLM model with draft speculation and tensor parallelism support', 'build a Qwen3DecoderLayer with attention, MLP, and residual normalization for transformer inference', 'test Qwen3Attention with query-key-value projection, rotary embeddings, and RMS normalization', 'refactor Qwen3MLP to use merged gate-up projection with SiLU activation and row-parallel down projection', 'run Qwen3Model forward pass with token embeddings, stacked decoder layers, and RMS output normalization']
```

Usage

```
{'create_Eagle3DraftForCausalLM': 'create an Eagle3DraftForCausalLM model with draft speculative decoding and Eagle3 attention layers', 'build_Eagle3DecoderLayer': 'build an Eagle3DecoderLayer with Eagle3Attention and LlamaMLP conditioned on target hidden states', 'build_Eagle3Attention': 'build an Eagle3Attention module with QKV parallel linear projection and Eagle speculative attention', 'run_Eagle3DraftModel_forward': 'run the Eagle3DraftModel forward pass with input ids, projected hidden states, and positions', 'compute_Eagle3DraftForCausalLM_logits': 'compute full vocab logits from draft hidden states using d2t index mapping'}
```

## File: tanishqkumar_ssd/ssd/models/llama3.py

Prompts

```
['create an Eagle3DraftForCausalLM model with draft speculative decoding and Eagle3 attention layers', 'build an Eagle3DecoderLayer with Eagle3Attention and LlamaMLP conditioned on target hidden states', 'build an Eagle3Attention module with QKV parallel linear projection and Eagle speculative attention', 'run the Eagle3DraftModel forward pass with input ids, projected hidden states, and positions', 'compute full vocab logits from draft hidden states using d2t index mapping', 'build a LlamaForCausalLM model from a LlamaConfig with optional speculative decoding and tensor parallelism', 'create a LlamaDecoderLayer with attention, MLP, and RMS norm configured from a LlamaConfig', 'build a LlamaAttention module with QKV projection, rotary embeddings, and multi-head attention', 'create a LlamaMLP with merged gate-up projection, SiLU activation, and row-parallel down projection', 'build a LlamaModel with token embeddings, stacked decoder layers, and final RMS normalization', 'create a Qwen3ForCausalLM model with draft speculation and tensor parallelism support', 'build a Qwen3DecoderLayer with attention, MLP, and residual normalization for transformer inference', 'test Qwen3Attention with query-key-value projection, rotary embeddings, and RMS normalization', 'refactor Qwen3MLP to use merged gate-up projection with SiLU activation and row-parallel down projection', 'run Qwen3Model forward pass with token embeddings, stacked decoder layers, and RMS output normalization']
```

Usage

```
{'build_LlamaForCausalLM': 'build a LlamaForCausalLM model from a LlamaConfig with optional speculative decoding and tensor parallelism', 'create_LlamaDecoderLayer': 'create a LlamaDecoderLayer with attention, MLP, and RMS norm configured from a LlamaConfig', 'build_LlamaAttention': 'build a LlamaAttention module with QKV projection, rotary embeddings, and multi-head attention', 'create_LlamaMLP': 'create a LlamaMLP with merged gate-up projection, SiLU activation, and row-parallel down projection', 'build_LlamaModel': 'build a LlamaModel with token embeddings, stacked decoder layers, and final RMS normalization'}
```

## File: tanishqkumar_ssd/ssd/models/qwen3.py

Prompts

```
['create an Eagle3DraftForCausalLM model with draft speculative decoding and Eagle3 attention layers', 'build an Eagle3DecoderLayer with Eagle3Attention and LlamaMLP conditioned on target hidden states', 'build an Eagle3Attention module with QKV parallel linear projection and Eagle speculative attention', 'run the Eagle3DraftModel forward pass with input ids, projected hidden states, and positions', 'compute full vocab logits from draft hidden states using d2t index mapping', 'build a LlamaForCausalLM model from a LlamaConfig with optional speculative decoding and tensor parallelism', 'create a LlamaDecoderLayer with attention, MLP, and RMS norm configured from a LlamaConfig', 'build a LlamaAttention module with QKV projection, rotary embeddings, and multi-head attention', 'create a LlamaMLP with merged gate-up projection, SiLU activation, and row-parallel down projection', 'build a LlamaModel with token embeddings, stacked decoder layers, and final RMS normalization', 'create a Qwen3ForCausalLM model with draft speculation and tensor parallelism support', 'build a Qwen3DecoderLayer with attention, MLP, and residual normalization for transformer inference', 'test Qwen3Attention with query-key-value projection, rotary embeddings, and RMS normalization', 'refactor Qwen3MLP to use merged gate-up projection with SiLU activation and row-parallel down projection', 'run Qwen3Model forward pass with token embeddings, stacked decoder layers, and RMS output normalization']
```

Usage

```
{'create_Qwen3ForCausalLM': 'create a Qwen3ForCausalLM model with draft speculation and tensor parallelism support', 'build_Qwen3DecoderLayer': 'build a Qwen3DecoderLayer with attention, MLP, and residual normalization for transformer inference', 'test_Qwen3Attention': 'test Qwen3Attention with query-key-value projection, rotary embeddings, and RMS normalization', 'refactor_Qwen3MLP': 'refactor Qwen3MLP to use merged gate-up projection with SiLU activation and row-parallel down projection', 'run_Qwen3Model': 'run Qwen3Model forward pass with token embeddings, stacked decoder layers, and RMS output normalization'}
```

