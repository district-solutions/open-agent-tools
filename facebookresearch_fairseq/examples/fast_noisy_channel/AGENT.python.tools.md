# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/fast_noisy_channel/noisy_channel_beam_search.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'combine forward and backward log-probs using the noisy channel method with step normalization', 'combine forward cumulative and backward log-probs using the lm_only method without normalization', 'run one step of noisy channel beam search selecting top-k hypotheses by combined score', 'initialize score, index, beam, forward, and language model score buffers on the target device', 'build a NoisyChannelSequenceGenerator with channel models, LM models, beam size, and scoring type for noisy channel decoding', 'run the NoisyChannelSequenceGenerator generate method with an ensemble of models and a sample batch to produce translations', 'create a function call to get_lm_scores that computes language model log probabilities for candidate tokens', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary from decoder features', 'review the reorder_all_tokens function that reorders source tokens from padded format to EOS-first format for channel model input', 'build a noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that combines direct translation, channel model, and language model scores', 'setup and load a channel model ensemble with swapped source and target language arguments', 'configure and load a language model ensemble for target language scoring during joint decoding']
```

Usage

```
{'init_NoisyChannelBeamSearch': 'create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'combine_fw_bw_noisy_channel': 'combine forward and backward log-probs using the noisy channel method with step normalization', 'combine_fw_bw_lm_only': 'combine forward cumulative and backward log-probs using the lm_only method without normalization', 'step_beam_search': 'run one step of noisy channel beam search selecting top-k hypotheses by combined score', 'init_buffers': 'initialize score, index, beam, forward, and language model score buffers on the target device'}
```

## File: facebookresearch_fairseq/examples/fast_noisy_channel/noisy_channel_sequence_generator.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'combine forward and backward log-probs using the noisy channel method with step normalization', 'combine forward cumulative and backward log-probs using the lm_only method without normalization', 'run one step of noisy channel beam search selecting top-k hypotheses by combined score', 'initialize score, index, beam, forward, and language model score buffers on the target device', 'build a NoisyChannelSequenceGenerator with channel models, LM models, beam size, and scoring type for noisy channel decoding', 'run the NoisyChannelSequenceGenerator generate method with an ensemble of models and a sample batch to produce translations', 'create a function call to get_lm_scores that computes language model log probabilities for candidate tokens', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary from decoder features', 'review the reorder_all_tokens function that reorders source tokens from padded format to EOS-first format for channel model input', 'build a noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that combines direct translation, channel model, and language model scores', 'setup and load a channel model ensemble with swapped source and target language arguments', 'configure and load a language model ensemble for target language scoring during joint decoding']
```

Usage

```
{'build_NoisyChannelSequenceGenerator': 'build a NoisyChannelSequenceGenerator with channel models, LM models, beam size, and scoring type for noisy channel decoding', 'run_NoisyChannelSequenceGenerator_generate': 'run the NoisyChannelSequenceGenerator generate method with an ensemble of models and a sample batch to produce translations', 'create_get_lm_scores': 'create a function call to get_lm_scores that computes language model log probabilities for candidate tokens', 'refactor_normalized_scores_with_batch_vocab': 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary from decoder features', 'review_reorder_all_tokens': 'review the reorder_all_tokens function that reorders source tokens from padded format to EOS-first format for channel model input'}
```

## File: facebookresearch_fairseq/examples/fast_noisy_channel/noisy_channel_translation.py

Prompts

```
['create a NoisyChannelBeamSearch instance with a target dictionary for noisy channel beam search decoding', 'combine forward and backward log-probs using the noisy channel method with step normalization', 'combine forward cumulative and backward log-probs using the lm_only method without normalization', 'run one step of noisy channel beam search selecting top-k hypotheses by combined score', 'initialize score, index, beam, forward, and language model score buffers on the target device', 'build a NoisyChannelSequenceGenerator with channel models, LM models, beam size, and scoring type for noisy channel decoding', 'run the NoisyChannelSequenceGenerator generate method with an ensemble of models and a sample batch to produce translations', 'create a function call to get_lm_scores that computes language model log probabilities for candidate tokens', 'refactor normalized_scores_with_batch_vocab to compute log probabilities over a batch-specific vocabulary from decoder features', 'review the reorder_all_tokens function that reorders source tokens from padded format to EOS-first format for channel model input', 'build a noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add task-specific CLI arguments for channel model, LM model, and scoring type to the parser', 'build a NoisyChannelSequenceGenerator that combines direct translation, channel model, and language model scores', 'setup and load a channel model ensemble with swapped source and target language arguments', 'configure and load a language model ensemble for target language scoring during joint decoding']
```

Usage

```
{'build_noisy_channel_translation_task': 'build a noisy channel translation task that rescoring beam candidates using noisy channel modeling', 'add_args_noisy_channel_translation': 'add task-specific CLI arguments for channel model, LM model, and scoring type to the parser', 'build_generator_noisy_channel': 'build a NoisyChannelSequenceGenerator that combines direct translation, channel model, and language model scores', 'setup_channel_model_loading': 'setup and load a channel model ensemble with swapped source and target language arguments', 'configure_lm_model_for_decoding': 'configure and load a language model ensemble for target language scoring during joint decoding'}
```

