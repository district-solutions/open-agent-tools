# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_to_speech/unity/sequence_generator.py

Prompts

```
['build a SequenceGenerator with an ensemble of fairseq models for speech-to-speech translation', 'create an EnsembleModel wrapper around multiple fairseq models for beam search decoding', 'run the generate_decoder method to produce beam search hypotheses from encoder outputs', 'refactor the EnsembleModel forward_decoder to support augmented encoder outputs for multi-task decoding', 'review the reorder_incremental_state method that reorders decoder state across model ensemble beams', 'build a MultiDecoderSequenceGenerator with models, tgt_dict, tgt_dict_mt, and beam size parameters', 'generate translations from a source sample using the MultiDecoderSequenceGenerator generate method', 'configure beam search strategy with custom beam size and length penalty for MT and T2U decoders', 'review the three-stage MT decoder, T2U encoder, and T2U decoder generation pipeline', 'refactor the encoder output handling to support augmented cross attention in the T2U decoder']
```

Usage

```
{'build_sequence_generator': 'build a SequenceGenerator with an ensemble of fairseq models for speech-to-speech translation', 'create_ensemble_model': 'create an EnsembleModel wrapper around multiple fairseq models for beam search decoding', 'run_generate_decoder': 'run the generate_decoder method to produce beam search hypotheses from encoder outputs', 'refactor_forward_decoder': 'refactor the EnsembleModel forward_decoder to support augmented encoder outputs for multi-task decoding', 'review_reorder_incremental_state': 'review the reorder_incremental_state method that reorders decoder state across model ensemble beams'}
```

## File: facebookresearch_fairseq/examples/speech_to_speech/unity/sequence_generator_multi_decoder.py

Prompts

```
['build a SequenceGenerator with an ensemble of fairseq models for speech-to-speech translation', 'create an EnsembleModel wrapper around multiple fairseq models for beam search decoding', 'run the generate_decoder method to produce beam search hypotheses from encoder outputs', 'refactor the EnsembleModel forward_decoder to support augmented encoder outputs for multi-task decoding', 'review the reorder_incremental_state method that reorders decoder state across model ensemble beams', 'build a MultiDecoderSequenceGenerator with models, tgt_dict, tgt_dict_mt, and beam size parameters', 'generate translations from a source sample using the MultiDecoderSequenceGenerator generate method', 'configure beam search strategy with custom beam size and length penalty for MT and T2U decoders', 'review the three-stage MT decoder, T2U encoder, and T2U decoder generation pipeline', 'refactor the encoder output handling to support augmented cross attention in the T2U decoder']
```

Usage

```
{'build_multi_decoder_sequence_generator': 'build a MultiDecoderSequenceGenerator with models, tgt_dict, tgt_dict_mt, and beam size parameters', 'generate_translations': 'generate translations from a source sample using the MultiDecoderSequenceGenerator generate method', 'configure_beam_search': 'configure beam search strategy with custom beam size and length penalty for MT and T2U decoders', 'review_three_stage_pipeline': 'review the three-stage MT decoder, T2U encoder, and T2U decoder generation pipeline', 'refactor_encoder_output_handling': 'refactor the encoder output handling to support augmented cross attention in the T2U decoder'}
```

