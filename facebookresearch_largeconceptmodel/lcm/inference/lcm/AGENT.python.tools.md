# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/inference/lcm/generator.py

Prompts

```
['generate sequences from an LCM model by calling LCMGenerator with an EmbeddingsBatch input', 'create LCMGeneratorOptions to set max_seq_len, eos_threshold, temperature, and repetition stopping thresholds', 'review the LCMGenerator __call__ method to understand batch generation with KV caching and EOS stopping', 'refactor the LCMGenerator finalize_step method to customize stopping criteria for EOS similarity or repetition', 'summarize the LCMGenerator prefill method that populates the KV cache with the prompt prefix', 'run the LCMScorer on an EmbeddingsBatch to score sequences in teacher-forcing mode', 'review the LCMScorer finalize_step method to check stopping criteria and record predictions', 'review the LCMScorer finish_sequence method to save completed hypotheses with step scores', 'review the LCMScorer reorder_state method to reorder tensors and state bag by index', 'build a teacher-forcing LCM scorer by subclassing LCMGenerator to score embedding batches']
```

Usage

```
{'generate_lcm_sequences': 'generate sequences from an LCM model by calling LCMGenerator with an EmbeddingsBatch input', 'configure_lcm_generator_options': 'create LCMGeneratorOptions to set max_seq_len, eos_threshold, temperature, and repetition stopping thresholds', 'review_LCMGenerator_call': 'review the LCMGenerator __call__ method to understand batch generation with KV caching and EOS stopping', 'refactor_LCMGenerator_finalize_step': 'refactor the LCMGenerator finalize_step method to customize stopping criteria for EOS similarity or repetition', 'summarize_LCMGenerator_prefill': 'summarize the LCMGenerator prefill method that populates the KV cache with the prompt prefix'}
```

## File: facebookresearch_largeconceptmodel/lcm/inference/lcm/scorer.py

Prompts

```
['generate sequences from an LCM model by calling LCMGenerator with an EmbeddingsBatch input', 'create LCMGeneratorOptions to set max_seq_len, eos_threshold, temperature, and repetition stopping thresholds', 'review the LCMGenerator __call__ method to understand batch generation with KV caching and EOS stopping', 'refactor the LCMGenerator finalize_step method to customize stopping criteria for EOS similarity or repetition', 'summarize the LCMGenerator prefill method that populates the KV cache with the prompt prefix', 'run the LCMScorer on an EmbeddingsBatch to score sequences in teacher-forcing mode', 'review the LCMScorer finalize_step method to check stopping criteria and record predictions', 'review the LCMScorer finish_sequence method to save completed hypotheses with step scores', 'review the LCMScorer reorder_state method to reorder tensors and state bag by index', 'build a teacher-forcing LCM scorer by subclassing LCMGenerator to score embedding batches']
```

Usage

```
{'run_LCMScorer_call': 'run the LCMScorer on an EmbeddingsBatch to score sequences in teacher-forcing mode', 'review_LCMScorer_finalize_step': 'review the LCMScorer finalize_step method to check stopping criteria and record predictions', 'review_LCMScorer_finish_sequence': 'review the LCMScorer finish_sequence method to save completed hypotheses with step scores', 'review_LCMScorer_reorder_state': 'review the LCMScorer reorder_state method to reorder tensors and state bag by index', 'build_LCMScorer_class': 'build a teacher-forcing LCM scorer by subclassing LCMGenerator to score embedding batches'}
```

