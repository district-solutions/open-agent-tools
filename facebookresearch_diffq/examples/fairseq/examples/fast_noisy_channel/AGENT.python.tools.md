# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/fast_noisy_channel/noisy_channel_beam_search.py

Prompts

```
['build a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'create a method that combines forward and backward log probabilities using noisy_channel or lm_only strategy', 'run a beam search step combining forward backward and language model log probabilities to select top k candidates', 'review the NoisyChannelBeamSearch step method that performs topk selection on combined noisy channel scores', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search decoding', 'build a NoisyChannelSequenceGenerator with beam search and noisy channel decoding for machine translation', 'run the generate method on a NoisyChannelSequenceGenerator to produce translations from a source batch', 'create language model scores by gathering next-word probabilities from an LM ensemble model', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary subset', 'review reorder_all_tokens to reorder source tokens from padded format to EOS-first format for channel scoring', 'build a Fairseq noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models and language models for joint decoding', 'configure the channel model scoring type with options like log_norm, unnormalized, or src_vocab batched', 'setup a language modeling task and load LM models to score target hypotheses during noisy channel decoding']
```

Usage

```
{'build_NoisyChannelBeamSearch': 'build a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'create_combine_fw_bw': 'create a method that combines forward and backward log probabilities using noisy_channel or lm_only strategy', 'run_step': 'run a beam search step combining forward backward and language model log probabilities to select top k candidates', 'review_NoisyChannelBeamSearch_step': 'review the NoisyChannelBeamSearch step method that performs topk selection on combined noisy channel scores', 'summarize_NoisyChannelBeamSearch': 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search decoding'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/fast_noisy_channel/noisy_channel_sequence_generator.py

Prompts

```
['build a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'create a method that combines forward and backward log probabilities using noisy_channel or lm_only strategy', 'run a beam search step combining forward backward and language model log probabilities to select top k candidates', 'review the NoisyChannelBeamSearch step method that performs topk selection on combined noisy channel scores', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search decoding', 'build a NoisyChannelSequenceGenerator with beam search and noisy channel decoding for machine translation', 'run the generate method on a NoisyChannelSequenceGenerator to produce translations from a source batch', 'create language model scores by gathering next-word probabilities from an LM ensemble model', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary subset', 'review reorder_all_tokens to reorder source tokens from padded format to EOS-first format for channel scoring', 'build a Fairseq noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models and language models for joint decoding', 'configure the channel model scoring type with options like log_norm, unnormalized, or src_vocab batched', 'setup a language modeling task and load LM models to score target hypotheses during noisy channel decoding']
```

Usage

```
{'build_NoisyChannelSequenceGenerator': 'build a NoisyChannelSequenceGenerator with beam search and noisy channel decoding for machine translation', 'run_NoisyChannelSequenceGenerator_generate': 'run the generate method on a NoisyChannelSequenceGenerator to produce translations from a source batch', 'create_get_lm_scores': 'create language model scores by gathering next-word probabilities from an LM ensemble model', 'refactor_normalized_scores_with_batch_vocab': 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary subset', 'review_reorder_all_tokens': 'review reorder_all_tokens to reorder source tokens from padded format to EOS-first format for channel scoring'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/fast_noisy_channel/noisy_channel_translation.py

Prompts

```
['build a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'create a method that combines forward and backward log probabilities using noisy_channel or lm_only strategy', 'run a beam search step combining forward backward and language model log probabilities to select top k candidates', 'review the NoisyChannelBeamSearch step method that performs topk selection on combined noisy channel scores', 'summarize the NoisyChannelBeamSearch class that extends fairseq Search for noisy channel beam search decoding', 'build a NoisyChannelSequenceGenerator with beam search and noisy channel decoding for machine translation', 'run the generate method on a NoisyChannelSequenceGenerator to produce translations from a source batch', 'create language model scores by gathering next-word probabilities from an LM ensemble model', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary subset', 'review reorder_all_tokens to reorder source tokens from padded format to EOS-first format for channel scoring', 'build a Fairseq noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that loads channel models and language models for joint decoding', 'configure the channel model scoring type with options like log_norm, unnormalized, or src_vocab batched', 'setup a language modeling task and load LM models to score target hypotheses during noisy channel decoding']
```

Usage

```
{'build_noisy_channel_translation_task': 'build a Fairseq noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add_noisy_channel_args': 'add task-specific CLI arguments for channel model, LM model, combine method, and scoring type to the parser', 'build_noisy_channel_generator': 'build a NoisyChannelSequenceGenerator that loads channel models and language models for joint decoding', 'configure_channel_model_scoring': 'configure the channel model scoring type with options like log_norm, unnormalized, or src_vocab batched', 'setup_language_model_for_decoding': 'setup a language modeling task and load LM models to score target hypotheses during noisy channel decoding'}
```

