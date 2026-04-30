# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xlstm/configuration_xlstm.py

Prompts

```
['create an xLSTMConfig instance with custom hidden_size, num_hidden_layers, and num_heads', 'build an xLSTMModel from xLSTMConfig with random weights for initialization', 'initialize hidden_size and embedding_dim from xLSTMConfig with mutual fallback', 'get computed qk_head_dim and v_head_dim properties from xLSTMConfig', 'convert xLSTMConfig to xLSTMLargeConfig when external xlstm library is available', 'create an xLSTMForCausalLM model for next-token prediction with generation support', 'use xLSTMCache to manage RNN states across inference steps for autoregressive generation', 'run xLSTM inference with chunkwise parallel processing and arbitrary sequence length handling', 'configure an xLSTMLayer with multi-head QKV projections, gating, and mLSTM backend']
```

Usage

```
{'create_xlstm_config': 'create an xLSTMConfig instance with custom hidden_size, num_hidden_layers, and num_heads', 'build_xlstm_model': 'build an xLSTMModel from xLSTMConfig with random weights for initialization', 'initialize_hidden_embedding_dims': 'initialize hidden_size and embedding_dim from xLSTMConfig with mutual fallback', 'get_qk_v_head_dimensions': 'get computed qk_head_dim and v_head_dim properties from xLSTMConfig', 'convert_to_xlstm_block_config': 'convert xLSTMConfig to xLSTMLargeConfig when external xlstm library is available'}
```

## File: huggingface_transformers/src/transformers/models/xlstm/modeling_xlstm.py

Prompts

```
['create an xLSTMConfig instance with custom hidden_size, num_hidden_layers, and num_heads', 'build an xLSTMModel from xLSTMConfig with random weights for initialization', 'initialize hidden_size and embedding_dim from xLSTMConfig with mutual fallback', 'get computed qk_head_dim and v_head_dim properties from xLSTMConfig', 'convert xLSTMConfig to xLSTMLargeConfig when external xlstm library is available', 'create an xLSTMForCausalLM model for next-token prediction with generation support', 'use xLSTMCache to manage RNN states across inference steps for autoregressive generation', 'run xLSTM inference with chunkwise parallel processing and arbitrary sequence length handling', 'configure an xLSTMLayer with multi-head QKV projections, gating, and mLSTM backend']
```

Usage

```
{'create_xlstm_causal_lm': 'create an xLSTMForCausalLM model for next-token prediction with generation support', 'build_xlstm_model': 'build an xLSTMModel encoder with embedding, stacked xLSTM blocks, and output normalization', 'use_xlstm_cache': 'use xLSTMCache to manage RNN states across inference steps for autoregressive generation', 'run_xlstm_inference': 'run xLSTM inference with chunkwise parallel processing and arbitrary sequence length handling', 'configure_xlstm_layer': 'configure an xLSTMLayer with multi-head QKV projections, gating, and mLSTM backend'}
```

