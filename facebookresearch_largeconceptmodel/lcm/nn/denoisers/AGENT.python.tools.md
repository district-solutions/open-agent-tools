# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/nn/denoisers/factory.py

Prompts

```
['build an LCMDenoiser model using LCMDenoiserTransformerFactory with DenoiserConfig and model dimensions', 'create a DenoiserConfig dataclass with pos_embedding_style, timestep_embed_dim, and projection settings', 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network components', 'build a DiTTimestepEncoder for diffusion timestep embeddings using the factory method', 'build the initial Projection layer mapping input_dim to model_dim for the denoiser', 'create an LCMDenoiser instance with timestep encoder, decoder layers, and projection modules for diffusion denoising', 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network sub-modules with AdaLN modulation', 'run the AdaLNModulator forward pass to compute shift, scale, and gate modulators for self-attention, cross-attention, and FFN', 'review the LCMDenoiser forward method that processes latent sequences through transformer layers with timestep conditioning', 'refactor the LCMDenoiserLayer forward_self_attn, forward_cross_attention, and forward_ffn methods to use AdaLN shift-scale-gate modulation']
```

Usage

```
{'build_denoiser_model': 'build an LCMDenoiser model using LCMDenoiserTransformerFactory with DenoiserConfig and model dimensions', 'create_denoiser_config': 'create a DenoiserConfig dataclass with pos_embedding_style, timestep_embed_dim, and projection settings', 'build_denoiser_layer': 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network components', 'build_timestep_embedder': 'build a DiTTimestepEncoder for diffusion timestep embeddings using the factory method', 'build_initial_projection': 'build the initial Projection layer mapping input_dim to model_dim for the denoiser'}
```

## File: facebookresearch_largeconceptmodel/lcm/nn/denoisers/lcm_denoiser.py

Prompts

```
['build an LCMDenoiser model using LCMDenoiserTransformerFactory with DenoiserConfig and model dimensions', 'create a DenoiserConfig dataclass with pos_embedding_style, timestep_embed_dim, and projection settings', 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network components', 'build a DiTTimestepEncoder for diffusion timestep embeddings using the factory method', 'build the initial Projection layer mapping input_dim to model_dim for the denoiser', 'create an LCMDenoiser instance with timestep encoder, decoder layers, and projection modules for diffusion denoising', 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network sub-modules with AdaLN modulation', 'run the AdaLNModulator forward pass to compute shift, scale, and gate modulators for self-attention, cross-attention, and FFN', 'review the LCMDenoiser forward method that processes latent sequences through transformer layers with timestep conditioning', 'refactor the LCMDenoiserLayer forward_self_attn, forward_cross_attention, and forward_ffn methods to use AdaLN shift-scale-gate modulation']
```

Usage

```
{'create_LCMDenoiser': 'create an LCMDenoiser instance with timestep encoder, decoder layers, and projection modules for diffusion denoising', 'build_LCMDenoiserLayer': 'build an LCMDenoiserLayer with self-attention, cross-attention, and feed-forward network sub-modules with AdaLN modulation', 'run_AdaLNModulator_forward': 'run the AdaLNModulator forward pass to compute shift, scale, and gate modulators for self-attention, cross-attention, and FFN', 'review_LCMDenoiser_forward': 'review the LCMDenoiser forward method that processes latent sequences through transformer layers with timestep conditioning', 'refactor_LCMDenoiserLayer_modulation': 'refactor the LCMDenoiserLayer forward_self_attn, forward_cross_attention, and forward_ffn methods to use AdaLN shift-scale-gate modulation'}
```

