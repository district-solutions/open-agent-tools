# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/speech_dlm/sequence_generator/multichannel_search.py

Prompts

```
['build a MultichannelBeamSearch instance with target dictionaries for multi-channel beam search decoding', 'run ContiguousMultichannelBeamSearch step with contiguous tensor lprobs for multi-channel beam search', 'create a ContiguousMultichannelSampling instance with top-k or top-P sampling parameters for generation', 'test the topk_sum function to find top-k summed log-probabilities across multiple channel tensors', 'review the unravel_index function that converts flat indices to multi-dimensional tensor indices', 'generate multi-channel parallel token sequences using a SpeechDLM model with beam search and configurable temperature', 'build a MultichannelSequenceGenerator with an ensemble of SpeechDLM models, target dictionaries, and beam search parameters', 'forward pass through a MultichannelEnsembleModel decoder to get log probabilities and attention scores for each channel', 'finalize beam search hypotheses by computing per-position scores, normalizing, and storing tokens with attention for each sentence', 'reorder incremental decoder states and encoder outputs according to a new beam ordering during multichannel generation']
```

Usage

```
{'build_multichannel_beam_search': 'build a MultichannelBeamSearch instance with target dictionaries for multi-channel beam search decoding', 'run_contiguous_multichannel_beam_search': 'run ContiguousMultichannelBeamSearch step with contiguous tensor lprobs for multi-channel beam search', 'create_multichannel_sampling': 'create a ContiguousMultichannelSampling instance with top-k or top-P sampling parameters for generation', 'test_topk_sum': 'test the topk_sum function to find top-k summed log-probabilities across multiple channel tensors', 'review_unravel_index': 'review the unravel_index function that converts flat indices to multi-dimensional tensor indices'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_dlm/sequence_generator/multichannel_sequence_generator.py

Prompts

```
['build a MultichannelBeamSearch instance with target dictionaries for multi-channel beam search decoding', 'run ContiguousMultichannelBeamSearch step with contiguous tensor lprobs for multi-channel beam search', 'create a ContiguousMultichannelSampling instance with top-k or top-P sampling parameters for generation', 'test the topk_sum function to find top-k summed log-probabilities across multiple channel tensors', 'review the unravel_index function that converts flat indices to multi-dimensional tensor indices', 'generate multi-channel parallel token sequences using a SpeechDLM model with beam search and configurable temperature', 'build a MultichannelSequenceGenerator with an ensemble of SpeechDLM models, target dictionaries, and beam search parameters', 'forward pass through a MultichannelEnsembleModel decoder to get log probabilities and attention scores for each channel', 'finalize beam search hypotheses by computing per-position scores, normalizing, and storing tokens with attention for each sentence', 'reorder incremental decoder states and encoder outputs according to a new beam ordering during multichannel generation']
```

Usage

```
{'generate_multichannel_sequences': 'generate multi-channel parallel token sequences using a SpeechDLM model with beam search and configurable temperature', 'build_multichannel_sequence_generator': 'build a MultichannelSequenceGenerator with an ensemble of SpeechDLM models, target dictionaries, and beam search parameters', 'forward_multichannel_ensemble_decoder': 'forward pass through a MultichannelEnsembleModel decoder to get log probabilities and attention scores for each channel', 'finalize_multichannel_hypos': 'finalize beam search hypotheses by computing per-position scores, normalizing, and storing tokens with attention for each sentence', 'reorder_multichannel_incremental_state': 'reorder incremental decoder states and encoder outputs according to a new beam ordering during multichannel generation'}
```

