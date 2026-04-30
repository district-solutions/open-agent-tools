# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm_moe_dsa/modeling_glm_moe_dsa.py

Prompts

```
['create a GlmMoeDsaForCausalLM model with a config for autoregressive text generation', 'build a GlmMoeDsaAttention layer with multi-head latent attention and dynamic sparse attention indexing', 'run the GlmMoeDsaMoE module to route tokens through top-k experts with shared MLP experts', 'test the GlmMoeDsaRotaryEmbedding module for applying rotary position embeddings to transformer layers', 'review the GlmMoeDsaIndexer class for selecting top-k tokens in dynamic sparse attention', 'create a GlmMoeDsaConfig instance for GLM-MoE-DSA model configuration with custom hidden size and expert count', 'build a GlmMoeDsaModel from a GlmMoeDsaConfig for causal language modeling with dynamic sparse attention', 'test the GlmMoeDsaIndexer forward pass to compute top-k token indices for dynamic sparse attention scoring', 'run the GlmMoeDsaAttention module with MLA projections and DSA indexer to produce sparse attention outputs', 'review the GlmMoeDsaForCausalLM class which inherits from Glm4MoeForCausalLM with DSA-aware attention']
```

Usage

```
{'create_model_glm_moe_dsa_causal_lm': 'create a GlmMoeDsaForCausalLM model with a config for autoregressive text generation', 'build_moe_attention_layer': 'build a GlmMoeDsaAttention layer with multi-head latent attention and dynamic sparse attention indexing', 'run_moe_expert_routing': 'run the GlmMoeDsaMoE module to route tokens through top-k experts with shared MLP experts', 'test_rotary_embedding': 'test the GlmMoeDsaRotaryEmbedding module for applying rotary position embeddings to transformer layers', 'review_dsa_indexer': 'review the GlmMoeDsaIndexer class for selecting top-k tokens in dynamic sparse attention'}
```

## File: huggingface_transformers/src/transformers/models/glm_moe_dsa/modular_glm_moe_dsa.py

Prompts

```
['create a GlmMoeDsaForCausalLM model with a config for autoregressive text generation', 'build a GlmMoeDsaAttention layer with multi-head latent attention and dynamic sparse attention indexing', 'run the GlmMoeDsaMoE module to route tokens through top-k experts with shared MLP experts', 'test the GlmMoeDsaRotaryEmbedding module for applying rotary position embeddings to transformer layers', 'review the GlmMoeDsaIndexer class for selecting top-k tokens in dynamic sparse attention', 'create a GlmMoeDsaConfig instance for GLM-MoE-DSA model configuration with custom hidden size and expert count', 'build a GlmMoeDsaModel from a GlmMoeDsaConfig for causal language modeling with dynamic sparse attention', 'test the GlmMoeDsaIndexer forward pass to compute top-k token indices for dynamic sparse attention scoring', 'run the GlmMoeDsaAttention module with MLA projections and DSA indexer to produce sparse attention outputs', 'review the GlmMoeDsaForCausalLM class which inherits from Glm4MoeForCausalLM with DSA-aware attention']
```

Usage

```
{'create_GlmMoeDsaConfig': 'create a GlmMoeDsaConfig instance for GLM-MoE-DSA model configuration with custom hidden size and expert count', 'build_GlmMoeDsaModel': 'build a GlmMoeDsaModel from a GlmMoeDsaConfig for causal language modeling with dynamic sparse attention', 'test_GlmMoeDsaIndexer': 'test the GlmMoeDsaIndexer forward pass to compute top-k token indices for dynamic sparse attention scoring', 'run_GlmMoeDsaAttention': 'run the GlmMoeDsaAttention module with MLA projections and DSA indexer to produce sparse attention outputs', 'review_GlmMoeDsaForCausalLM': 'review the GlmMoeDsaForCausalLM class which inherits from Glm4MoeForCausalLM with DSA-aware attention'}
```

