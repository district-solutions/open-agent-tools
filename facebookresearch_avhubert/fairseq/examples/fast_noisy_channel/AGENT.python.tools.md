# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/fast_noisy_channel/noisy_channel_beam_search.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'review the NoisyChannelBeamSearch step method that selects top-k hypotheses using combined forward and backward scores', 'review the combine_fw_bw method that merges forward cumulative and backward log probabilities using noisy_channel or lm_only strategy', 'test the NoisyChannelBeamSearch step method with torch tensors for forward and backward log probabilities', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search with forward and backward scoring', 'build a NoisyChannelSequenceGenerator with beam search, channel models, and LM models for noisy channel decoding', 'run the generate method on an ensemble of models to produce translations using noisy channel beam search', 'review the noisy_channel_rescoring inner function that rescors top-k hypotheses using channel and language model scores', 'summarize the normalized_scores_with_batch_vocab function that computes log probabilities over a batch-specific vocabulary', 'refactor the combine_ch_lm function to change how channel model and language model scores are combined and normalized', 'build a fairseq task that rescores top k candidates using noisy channel modeling for machine translation', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models, LM models, and configures beam search parameters', 'setup and load a channel model ensemble with swapped source-target languages for backward translation scoring', 'configure and load a language model ensemble for target language probability scoring during noisy channel decoding']
```

Usage

```
{'create_NoisyChannelBeamSearch': 'create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'review_NoisyChannelBeamSearch_step': 'review the NoisyChannelBeamSearch step method that selects top-k hypotheses using combined forward and backward scores', 'review_NoisyChannelBeamSearch_combine_fw_bw': 'review the combine_fw_bw method that merges forward cumulative and backward log probabilities using noisy_channel or lm_only strategy', 'test_NoisyChannelBeamSearch_step': 'test the NoisyChannelBeamSearch step method with torch tensors for forward and backward log probabilities', 'summarize_NoisyChannelBeamSearch': 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search with forward and backward scoring'}
```

## File: facebookresearch_avhubert/fairseq/examples/fast_noisy_channel/noisy_channel_sequence_generator.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'review the NoisyChannelBeamSearch step method that selects top-k hypotheses using combined forward and backward scores', 'review the combine_fw_bw method that merges forward cumulative and backward log probabilities using noisy_channel or lm_only strategy', 'test the NoisyChannelBeamSearch step method with torch tensors for forward and backward log probabilities', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search with forward and backward scoring', 'build a NoisyChannelSequenceGenerator with beam search, channel models, and LM models for noisy channel decoding', 'run the generate method on an ensemble of models to produce translations using noisy channel beam search', 'review the noisy_channel_rescoring inner function that rescors top-k hypotheses using channel and language model scores', 'summarize the normalized_scores_with_batch_vocab function that computes log probabilities over a batch-specific vocabulary', 'refactor the combine_ch_lm function to change how channel model and language model scores are combined and normalized', 'build a fairseq task that rescores top k candidates using noisy channel modeling for machine translation', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models, LM models, and configures beam search parameters', 'setup and load a channel model ensemble with swapped source-target languages for backward translation scoring', 'configure and load a language model ensemble for target language probability scoring during noisy channel decoding']
```

Usage

```
{'build_NoisyChannelSequenceGenerator': 'build a NoisyChannelSequenceGenerator with beam search, channel models, and LM models for noisy channel decoding', 'run_NoisyChannelSequenceGenerator_generate': 'run the generate method on an ensemble of models to produce translations using noisy channel beam search', 'review_noisy_channel_rescoring': 'review the noisy_channel_rescoring inner function that rescors top-k hypotheses using channel and language model scores', 'summarize_normalized_scores_with_batch_vocab': 'summarize the normalized_scores_with_batch_vocab function that computes log probabilities over a batch-specific vocabulary', 'refactor_combine_ch_lm': 'refactor the combine_ch_lm function to change how channel model and language model scores are combined and normalized'}
```

## File: facebookresearch_avhubert/fairseq/examples/fast_noisy_channel/noisy_channel_translation.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'review the NoisyChannelBeamSearch step method that selects top-k hypotheses using combined forward and backward scores', 'review the combine_fw_bw method that merges forward cumulative and backward log probabilities using noisy_channel or lm_only strategy', 'test the NoisyChannelBeamSearch step method with torch tensors for forward and backward log probabilities', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search with forward and backward scoring', 'build a NoisyChannelSequenceGenerator with beam search, channel models, and LM models for noisy channel decoding', 'run the generate method on an ensemble of models to produce translations using noisy channel beam search', 'review the noisy_channel_rescoring inner function that rescors top-k hypotheses using channel and language model scores', 'summarize the normalized_scores_with_batch_vocab function that computes log probabilities over a batch-specific vocabulary', 'refactor the combine_ch_lm function to change how channel model and language model scores are combined and normalized', 'build a fairseq task that rescores top k candidates using noisy channel modeling for machine translation', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models, LM models, and configures beam search parameters', 'setup and load a channel model ensemble with swapped source-target languages for backward translation scoring', 'configure and load a language model ensemble for target language probability scoring during noisy channel decoding']
```

Usage

```
{'build_noisy_channel_translation_task': 'build a fairseq task that rescores top k candidates using noisy channel modeling for machine translation', 'add_args_noisy_channel_translation': 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build_generator_noisy_channel': 'build a NoisyChannelSequenceGenerator that loads channel models, LM models, and configures beam search parameters', 'setup_channel_model_loading': 'setup and load a channel model ensemble with swapped source-target languages for backward translation scoring', 'configure_lm_model_for_decoding': 'configure and load a language model ensemble for target language probability scoring during noisy channel decoding'}
```

