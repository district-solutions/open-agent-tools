# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/inference/two_tower_diffusion_lcm/generator.py

Prompts

```
['generate sequences using a TwoTowerDiffusionLCMGenerator with an EmbeddingsBatch input and diffusion options', 'create DiffusionLCMGeneratorOptions to set guidance_scale, ddim_eta, inference_timesteps, and noise parameters', 'run the prefill method to encode a prompt prefix with the context encoder before generation', 'review the finalize_step method to understand EOS similarity and repetition stopping criteria', 'refactor the reorder_state method to reorder internal tensors when active samples change', 'score a batch of embeddings using the TwoTowerDiffusionLCMScorer in teacher-forcing mode', 'decode the next sentence embeddings using the _decode method with a context', 'finalize a decoding step by checking stopping criteria and recording predictions', 'reorder the scoring state and tensors according to a new batch order']
```

Usage

```
{'generate_two_tower_diffusion_lcm': 'generate sequences using a TwoTowerDiffusionLCMGenerator with an EmbeddingsBatch input and diffusion options', 'configure_diffusion_generator_options': 'create DiffusionLCMGeneratorOptions to set guidance_scale, ddim_eta, inference_timesteps, and noise parameters', 'prefill_context_encoder': 'run the prefill method to encode a prompt prefix with the context encoder before generation', 'finalize_generation_step': 'review the finalize_step method to understand EOS similarity and repetition stopping criteria', 'reorder_generator_state': 'refactor the reorder_state method to reorder internal tensors when active samples change'}
```

## File: facebookresearch_largeconceptmodel/lcm/inference/two_tower_diffusion_lcm/scorer.py

Prompts

```
['generate sequences using a TwoTowerDiffusionLCMGenerator with an EmbeddingsBatch input and diffusion options', 'create DiffusionLCMGeneratorOptions to set guidance_scale, ddim_eta, inference_timesteps, and noise parameters', 'run the prefill method to encode a prompt prefix with the context encoder before generation', 'review the finalize_step method to understand EOS similarity and repetition stopping criteria', 'refactor the reorder_state method to reorder internal tensors when active samples change', 'score a batch of embeddings using the TwoTowerDiffusionLCMScorer in teacher-forcing mode', 'decode the next sentence embeddings using the _decode method with a context', 'finalize a decoding step by checking stopping criteria and recording predictions', 'reorder the scoring state and tensors according to a new batch order']
```

Usage

```
{'score_embeddings_batch': 'score a batch of embeddings using the TwoTowerDiffusionLCMScorer in teacher-forcing mode', 'prefill_context_encoder': 'encode the prefix context using the prefill method of TwoTowerDiffusionLCMScorer', 'decode_next_sentence': 'decode the next sentence embeddings using the _decode method with a context', 'finalize_decoding_step': 'finalize a decoding step by checking stopping criteria and recording predictions', 'reorder_scoring_state': 'reorder the scoring state and tensors according to a new batch order'}
```

