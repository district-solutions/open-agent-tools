# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cohere/modeling_cohere.py

Prompts

```
['build a CohereForCausalLM model for autoregressive text generation with RoPE embeddings and GQA attention', 'create a CohereModel forward pass that computes causal masked attention over input embeddings', 'test the CohereAttention module with query key value projections and rotary position embeddings', 'review the CohereDecoderLayer with self-attention, MLP, and residual connections', 'summarize the CohereMLP module using gated linear units with gate and up projections', 'create a CohereForCausalLM model for autoregressive text generation with logit scaling', 'build a CohereModel with CohereDecoderLayer blocks, rotary embeddings, and QK normalization', 'review the CohereMLP class with separate gate and up projections instead of a single gate-up projection', 'summarize the CohereRotaryEmbedding forward pass that interleaves frequency embeddings instead of concatenating', 'create a Cohere tokenizer with byte-level BPE encoding and customizable special tokens', 'build a tool-use prompt from a conversation and a list of available tools for the model', 'build a grounded generation prompt from a conversation and reference documents with citations', 'test the CohereTokenizer class with custom vocab, merges, and special token configuration', 'summarize the CohereTokenizer capabilities including BPE encoding, NFC normalization, and ByteLevel pre-tokenization']
```

Usage

```
{'build_cohere_causal_lm': 'build a CohereForCausalLM model for autoregressive text generation with RoPE embeddings and GQA attention', 'create_cohere_model_forward': 'create a CohereModel forward pass that computes causal masked attention over input embeddings', 'test_cohere_attention': 'test the CohereAttention module with query key value projections and rotary position embeddings', 'review_cohere_decoder_layer': 'review the CohereDecoderLayer with self-attention, MLP, and residual connections', 'summarize_cohere_mlp': 'summarize the CohereMLP module using gated linear units with gate and up projections'}
```

## File: huggingface_transformers/src/transformers/models/cohere/modular_cohere.py

Prompts

```
['build a CohereForCausalLM model for autoregressive text generation with RoPE embeddings and GQA attention', 'create a CohereModel forward pass that computes causal masked attention over input embeddings', 'test the CohereAttention module with query key value projections and rotary position embeddings', 'review the CohereDecoderLayer with self-attention, MLP, and residual connections', 'summarize the CohereMLP module using gated linear units with gate and up projections', 'create a CohereForCausalLM model for autoregressive text generation with logit scaling', 'build a CohereModel with CohereDecoderLayer blocks, rotary embeddings, and QK normalization', 'review the CohereMLP class with separate gate and up projections instead of a single gate-up projection', 'summarize the CohereRotaryEmbedding forward pass that interleaves frequency embeddings instead of concatenating', 'create a Cohere tokenizer with byte-level BPE encoding and customizable special tokens', 'build a tool-use prompt from a conversation and a list of available tools for the model', 'build a grounded generation prompt from a conversation and reference documents with citations', 'test the CohereTokenizer class with custom vocab, merges, and special token configuration', 'summarize the CohereTokenizer capabilities including BPE encoding, NFC normalization, and ByteLevel pre-tokenization']
```

Usage

```
{'create_cohere_causal_lm': 'create a CohereForCausalLM model for autoregressive text generation with logit scaling', 'build_cohere_model': 'build a CohereModel with CohereDecoderLayer blocks, rotary embeddings, and QK normalization', 'test_cohere_attention': 'test the CohereAttention module with query-key normalization and rotary position embeddings', 'review_cohere_mlp': 'review the CohereMLP class with separate gate and up projections instead of a single gate-up projection', 'summarize_cohere_rotary_embedding': 'summarize the CohereRotaryEmbedding forward pass that interleaves frequency embeddings instead of concatenating'}
```

## File: huggingface_transformers/src/transformers/models/cohere/tokenization_cohere.py

Prompts

```
['build a CohereForCausalLM model for autoregressive text generation with RoPE embeddings and GQA attention', 'create a CohereModel forward pass that computes causal masked attention over input embeddings', 'test the CohereAttention module with query key value projections and rotary position embeddings', 'review the CohereDecoderLayer with self-attention, MLP, and residual connections', 'summarize the CohereMLP module using gated linear units with gate and up projections', 'create a CohereForCausalLM model for autoregressive text generation with logit scaling', 'build a CohereModel with CohereDecoderLayer blocks, rotary embeddings, and QK normalization', 'review the CohereMLP class with separate gate and up projections instead of a single gate-up projection', 'summarize the CohereRotaryEmbedding forward pass that interleaves frequency embeddings instead of concatenating', 'create a Cohere tokenizer with byte-level BPE encoding and customizable special tokens', 'build a tool-use prompt from a conversation and a list of available tools for the model', 'build a grounded generation prompt from a conversation and reference documents with citations', 'test the CohereTokenizer class with custom vocab, merges, and special token configuration', 'summarize the CohereTokenizer capabilities including BPE encoding, NFC normalization, and ByteLevel pre-tokenization']
```

Usage

```
{'create_CohereTokenizer': 'create a Cohere tokenizer with byte-level BPE encoding and customizable special tokens', 'build_apply_tool_use_template': 'build a tool-use prompt from a conversation and a list of available tools for the model', 'build_apply_grounded_generation_template': 'build a grounded generation prompt from a conversation and reference documents with citations', 'test_CohereTokenizer': 'test the CohereTokenizer class with custom vocab, merges, and special token configuration', 'summarize_CohereTokenizer': 'summarize the CohereTokenizer capabilities including BPE encoding, NFC normalization, and ByteLevel pre-tokenization'}
```

