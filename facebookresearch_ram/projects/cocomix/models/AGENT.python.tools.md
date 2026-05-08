# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cocomix/models/concept_extractor.py

Prompts

```
['build a TransformerLensSAE model with a specified GPT-2 layer index and activation location', 'run forward and backward passes to capture activation and gradient caches for tokens', 'compute cross-entropy loss between shifted logits and labels for language modeling', 'compute attribute-based latent tokenization using autoencoder activations and gradients', 'run the TransformerLensSAE forward pass to extract concept attributes from input token IDs', 'build a GPT2CoCoMixLMHeadModel from a GPT2Config with concept_dim and insert_layer_idx parameters', 'create a GPT2CoCoMixModel transformer that interleaves continuous concept tokens at a specified layer', 'review the GPT2Attention class forward pass and causal masking logic for self and cross attention', 'test the GPT2Block forward method with optional cross-attention encoder hidden states', 'refactor the GPT2FlashAttention2 forward method to handle float32 autocast dtype casting']
```

Usage

```
{'build_TransformerLensSAE': 'build a TransformerLensSAE model with a specified GPT-2 layer index and activation location', 'run_get_cache_fwd_and_bwd': 'run forward and backward passes to capture activation and gradient caches for tokens', 'run_compute_loss': 'compute cross-entropy loss between shifted logits and labels for language modeling', 'run_compute_attribute': 'compute attribute-based latent tokenization using autoencoder activations and gradients', 'run_forward': 'run the TransformerLensSAE forward pass to extract concept attributes from input token IDs'}
```

## File: facebookresearch_ram/projects/cocomix/models/modeling_gpt2_cocomix.py

Prompts

```
['build a TransformerLensSAE model with a specified GPT-2 layer index and activation location', 'run forward and backward passes to capture activation and gradient caches for tokens', 'compute cross-entropy loss between shifted logits and labels for language modeling', 'compute attribute-based latent tokenization using autoencoder activations and gradients', 'run the TransformerLensSAE forward pass to extract concept attributes from input token IDs', 'build a GPT2CoCoMixLMHeadModel from a GPT2Config with concept_dim and insert_layer_idx parameters', 'create a GPT2CoCoMixModel transformer that interleaves continuous concept tokens at a specified layer', 'review the GPT2Attention class forward pass and causal masking logic for self and cross attention', 'test the GPT2Block forward method with optional cross-attention encoder hidden states', 'refactor the GPT2FlashAttention2 forward method to handle float32 autocast dtype casting']
```

Usage

```
{'build_GPT2CoCoMixLMHeadModel': 'build a GPT2CoCoMixLMHeadModel from a GPT2Config with concept_dim and insert_layer_idx parameters', 'create_GPT2CoCoMixModel': 'create a GPT2CoCoMixModel transformer that interleaves continuous concept tokens at a specified layer', 'review_GPT2Attention': 'review the GPT2Attention class forward pass and causal masking logic for self and cross attention', 'test_GPT2Block': 'test the GPT2Block forward method with optional cross-attention encoder hidden states', 'refactor_GPT2FlashAttention2': 'refactor the GPT2FlashAttention2 forward method to handle float32 autocast dtype casting'}
```

