# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/scripts/convert_model.py

Prompts

```
['run the script to convert a speech-text joint model checkpoint into a BART-compatible format', 'load a PyTorch model checkpoint from a file path using PathManager and torch.load', 'save model states to a checkpoint file using PathManager and torch.save', 'rename encoder.text_encoder and decoder.text_decoder keys in a model state dict to encoder and decoder', 'check if a module name substring exists within a parameter name string', 'run the g2p_encode script to convert text sentences to phoneme sequences using g2p_en', 'run the g2p_encode script with submitit parallel processing to convert large text datasets to phonemes', 'run g2p_encode with options like --lower-case, --no-punc, --dup-vowel, and --use-word-start flags', 'review the process_sent function that preprocesses text, applies G2P conversion, and handles phoneme duplication', 'review the dup_pho function that duplicates vowel and consonant phonemes based on CMUdict conventions']
```

Usage

```
{'convert_speech_text_model_to_bart': 'run the script to convert a speech-text joint model checkpoint into a BART-compatible format', 'load_checkpoint_from_file': 'load a PyTorch model checkpoint from a file path using PathManager and torch.load', 'save_checkpoint_to_file': 'save model states to a checkpoint file using PathManager and torch.save', 'rename_encoder_decoder_keys': 'rename encoder.text_encoder and decoder.text_decoder keys in a model state dict to encoder and decoder', 'check_param_module_match': 'check if a module name substring exists within a parameter name string'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/scripts/g2p_encode.py

Prompts

```
['run the script to convert a speech-text joint model checkpoint into a BART-compatible format', 'load a PyTorch model checkpoint from a file path using PathManager and torch.load', 'save model states to a checkpoint file using PathManager and torch.save', 'rename encoder.text_encoder and decoder.text_decoder keys in a model state dict to encoder and decoder', 'check if a module name substring exists within a parameter name string', 'run the g2p_encode script to convert text sentences to phoneme sequences using g2p_en', 'run the g2p_encode script with submitit parallel processing to convert large text datasets to phonemes', 'run g2p_encode with options like --lower-case, --no-punc, --dup-vowel, and --use-word-start flags', 'review the process_sent function that preprocesses text, applies G2P conversion, and handles phoneme duplication', 'review the dup_pho function that duplicates vowel and consonant phonemes based on CMUdict conventions']
```

Usage

```
{'run_g2p_encode_cli': 'run the g2p_encode script to convert text sentences to phoneme sequences using g2p_en', 'run_g2p_encode_parallel': 'run the g2p_encode script with submitit parallel processing to convert large text datasets to phonemes', 'run_g2p_encode_with_options': 'run g2p_encode with options like --lower-case, --no-punc, --dup-vowel, and --use-word-start flags', 'review_process_sent': 'review the process_sent function that preprocesses text, applies G2P conversion, and handles phoneme duplication', 'review_dup_pho': 'review the dup_pho function that duplicates vowel and consonant phonemes based on CMUdict conventions'}
```

