# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/bart/bart.py

Prompts

```
['build a BART agent using the BartAgent class with --init-model zoo:bart/bart_large/model', 'convert a fairseq BART checkpoint to a ParlAI model using --init-fairseq-model', 'add BART-specific command line arguments like --init-fairseq-model to a ParlaiParser', 'build a BartModel instance with optional pre-trained embeddings via build_model', 'set text vectors with start and end tokens prepended and appended for BART encoding', 'run the conversion script to convert a fairseq transformer model checkpoint to a ParlAI model format', 'load a single fairseq model checkpoint from a file path into memory on CPU', 'load multiple fairseq checkpoints and merge their model weights into a single state dict', 'parse fairseq model arguments and map them to equivalent ParlAI transformer configuration options', 'convert a fairseq model state dict to a ParlAI-compatible state dict with remapped keys and shuffled embeddings', 'create output logits by projecting the tensor back to vocabulary using BartModel output method', 'test the BartModel _get_initial_forced_decoder_input method to seed EOS BOS tokens', 'refactor the BartModel reorder_decoder_incremental_state method to handle two-input decoder seeding', 'review the BartModel decode_forced method to cut off scores for the start token']
```

Usage

```
{'build_bart_agent': 'build a BART agent using the BartAgent class with --init-model zoo:bart/bart_large/model', 'convert_fairseq_to_parlai': 'convert a fairseq BART checkpoint to a ParlAI model using --init-fairseq-model', 'add_bart_cmdline_args': 'add BART-specific command line arguments like --init-fairseq-model to a ParlaiParser', 'build_bart_model': 'build a BartModel instance with optional pre-trained embeddings via build_model', 'set_text_vec_with_tokens': 'set text vectors with start and end tokens prepended and appended for BART encoding'}
```

## File: facebookresearch_parlai/parlai/agents/bart/convert_fairseq_to_parlai.py

Prompts

```
['build a BART agent using the BartAgent class with --init-model zoo:bart/bart_large/model', 'convert a fairseq BART checkpoint to a ParlAI model using --init-fairseq-model', 'add BART-specific command line arguments like --init-fairseq-model to a ParlaiParser', 'build a BartModel instance with optional pre-trained embeddings via build_model', 'set text vectors with start and end tokens prepended and appended for BART encoding', 'run the conversion script to convert a fairseq transformer model checkpoint to a ParlAI model format', 'load a single fairseq model checkpoint from a file path into memory on CPU', 'load multiple fairseq checkpoints and merge their model weights into a single state dict', 'parse fairseq model arguments and map them to equivalent ParlAI transformer configuration options', 'convert a fairseq model state dict to a ParlAI-compatible state dict with remapped keys and shuffled embeddings', 'create output logits by projecting the tensor back to vocabulary using BartModel output method', 'test the BartModel _get_initial_forced_decoder_input method to seed EOS BOS tokens', 'refactor the BartModel reorder_decoder_incremental_state method to handle two-input decoder seeding', 'review the BartModel decode_forced method to cut off scores for the start token']
```

Usage

```
{'convert_fairseq_to_parlai_model': 'run the conversion script to convert a fairseq transformer model checkpoint to a ParlAI model format', 'load_fairseq_checkpoint_single': 'load a single fairseq model checkpoint from a file path into memory on CPU', 'load_fairseq_checkpoint_merged': 'load multiple fairseq checkpoints and merge their model weights into a single state dict', 'get_parlai_opt_from_fairseq': 'parse fairseq model arguments and map them to equivalent ParlAI transformer configuration options', 'convert_model_weight_state_dict': 'convert a fairseq model state dict to a ParlAI-compatible state dict with remapped keys and shuffled embeddings'}
```

## File: facebookresearch_parlai/parlai/agents/bart/modules.py

Prompts

```
['build a BART agent using the BartAgent class with --init-model zoo:bart/bart_large/model', 'convert a fairseq BART checkpoint to a ParlAI model using --init-fairseq-model', 'add BART-specific command line arguments like --init-fairseq-model to a ParlaiParser', 'build a BartModel instance with optional pre-trained embeddings via build_model', 'set text vectors with start and end tokens prepended and appended for BART encoding', 'run the conversion script to convert a fairseq transformer model checkpoint to a ParlAI model format', 'load a single fairseq model checkpoint from a file path into memory on CPU', 'load multiple fairseq checkpoints and merge their model weights into a single state dict', 'parse fairseq model arguments and map them to equivalent ParlAI transformer configuration options', 'convert a fairseq model state dict to a ParlAI-compatible state dict with remapped keys and shuffled embeddings', 'create output logits by projecting the tensor back to vocabulary using BartModel output method', 'test the BartModel _get_initial_forced_decoder_input method to seed EOS BOS tokens', 'refactor the BartModel reorder_decoder_incremental_state method to handle two-input decoder seeding', 'review the BartModel decode_forced method to cut off scores for the start token']
```

Usage

```
{'build_bart_model': 'build a BART model that extends TransformerGeneratorModel for sequence-to-sequence tasks', 'create_output_logits': 'create output logits by projecting the tensor back to vocabulary using BartModel output method', 'test_decoder_input': 'test the BartModel _get_initial_forced_decoder_input method to seed EOS BOS tokens', 'refactor_incremental_state': 'refactor the BartModel reorder_decoder_incremental_state method to handle two-input decoder seeding', 'review_decode_forced': 'review the BartModel decode_forced method to cut off scores for the start token'}
```

