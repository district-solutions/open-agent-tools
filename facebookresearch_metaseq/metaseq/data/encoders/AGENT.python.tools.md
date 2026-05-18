# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/data/encoders/gpt2_bpe.py

Prompts

```
['encode a string into GPT-2 BPE token IDs using the GPT2BPE encode method', 'decode a space-separated string of GPT-2 BPE token IDs back into text', 'check if a GPT-2 BPE token is the beginning of a word using is_beginning_of_word', 'configure the GPT2BPEConfig dataclass with custom encoder.json and vocab.bpe file paths', 'initialize a GPT2BPE instance with a config to load the GPT-2 BPE encoder and vocabulary', 'load a GPT-2 BPE encoder from an encoder JSON and vocab BPE file path', 'encode a string of text into a list of GPT-2 BPE token integers', 'decode a list of GPT-2 BPE token integers back into a string of text', 'apply byte pair encoding merges to a token string using the encoder BPE ranks', 'generate a mapping from UTF-8 byte values to Unicode characters for BPE encoding', 'create a HuggingFaceByteLevelBPE tokenizer and encode a string into space-separated token IDs', 'create a HuggingFaceByteLevelBPE tokenizer and decode space-separated token IDs back into text', 'use HuggingFaceByteLevelBPE to check if a token is the beginning of a word', 'create a HuggingFaceByteLevelBPEConfig dataclass with bpe_vocab, bpe_merges, and hf_tokenizer paths', 'initialize HuggingFaceByteLevelBPE by loading a pre-saved HuggingFace tokenizer file via hf_tokenizer config']
```

Usage

```
{'encode_text_with_gpt2_bpe': 'encode a string into GPT-2 BPE token IDs using the GPT2BPE encode method', 'decode_gpt2_bpe_tokens': 'decode a space-separated string of GPT-2 BPE token IDs back into text', 'check_beginning_of_word': 'check if a GPT-2 BPE token is the beginning of a word using is_beginning_of_word', 'configure_gpt2_bpe_encoder': 'configure the GPT2BPEConfig dataclass with custom encoder.json and vocab.bpe file paths', 'initialize_gpt2_bpe': 'initialize a GPT2BPE instance with a config to load the GPT-2 BPE encoder and vocabulary'}
```

## File: facebookresearch_metaseq/metaseq/data/encoders/gpt2_bpe_utils.py

Prompts

```
['encode a string into GPT-2 BPE token IDs using the GPT2BPE encode method', 'decode a space-separated string of GPT-2 BPE token IDs back into text', 'check if a GPT-2 BPE token is the beginning of a word using is_beginning_of_word', 'configure the GPT2BPEConfig dataclass with custom encoder.json and vocab.bpe file paths', 'initialize a GPT2BPE instance with a config to load the GPT-2 BPE encoder and vocabulary', 'load a GPT-2 BPE encoder from an encoder JSON and vocab BPE file path', 'encode a string of text into a list of GPT-2 BPE token integers', 'decode a list of GPT-2 BPE token integers back into a string of text', 'apply byte pair encoding merges to a token string using the encoder BPE ranks', 'generate a mapping from UTF-8 byte values to Unicode characters for BPE encoding', 'create a HuggingFaceByteLevelBPE tokenizer and encode a string into space-separated token IDs', 'create a HuggingFaceByteLevelBPE tokenizer and decode space-separated token IDs back into text', 'use HuggingFaceByteLevelBPE to check if a token is the beginning of a word', 'create a HuggingFaceByteLevelBPEConfig dataclass with bpe_vocab, bpe_merges, and hf_tokenizer paths', 'initialize HuggingFaceByteLevelBPE by loading a pre-saved HuggingFace tokenizer file via hf_tokenizer config']
```

Usage

```
{'get_encoder_from_files': 'load a GPT-2 BPE encoder from an encoder JSON and vocab BPE file path', 'encode_text_to_tokens': 'encode a string of text into a list of GPT-2 BPE token integers', 'decode_tokens_to_text': 'decode a list of GPT-2 BPE token integers back into a string of text', 'apply_bpe_merges': 'apply byte pair encoding merges to a token string using the encoder BPE ranks', 'bytes_to_unicode_mapping': 'generate a mapping from UTF-8 byte values to Unicode characters for BPE encoding'}
```

## File: facebookresearch_metaseq/metaseq/data/encoders/hf_byte_bpe.py

Prompts

```
['encode a string into GPT-2 BPE token IDs using the GPT2BPE encode method', 'decode a space-separated string of GPT-2 BPE token IDs back into text', 'check if a GPT-2 BPE token is the beginning of a word using is_beginning_of_word', 'configure the GPT2BPEConfig dataclass with custom encoder.json and vocab.bpe file paths', 'initialize a GPT2BPE instance with a config to load the GPT-2 BPE encoder and vocabulary', 'load a GPT-2 BPE encoder from an encoder JSON and vocab BPE file path', 'encode a string of text into a list of GPT-2 BPE token integers', 'decode a list of GPT-2 BPE token integers back into a string of text', 'apply byte pair encoding merges to a token string using the encoder BPE ranks', 'generate a mapping from UTF-8 byte values to Unicode characters for BPE encoding', 'create a HuggingFaceByteLevelBPE tokenizer and encode a string into space-separated token IDs', 'create a HuggingFaceByteLevelBPE tokenizer and decode space-separated token IDs back into text', 'use HuggingFaceByteLevelBPE to check if a token is the beginning of a word', 'create a HuggingFaceByteLevelBPEConfig dataclass with bpe_vocab, bpe_merges, and hf_tokenizer paths', 'initialize HuggingFaceByteLevelBPE by loading a pre-saved HuggingFace tokenizer file via hf_tokenizer config']
```

Usage

```
{'encode_text_with_hf_byte_bpe': 'create a HuggingFaceByteLevelBPE tokenizer and encode a string into space-separated token IDs', 'decode_token_ids_with_hf_byte_bpe': 'create a HuggingFaceByteLevelBPE tokenizer and decode space-separated token IDs back into text', 'check_beginning_of_word_with_hf_byte_bpe': 'use HuggingFaceByteLevelBPE to check if a token is the beginning of a word', 'configure_hf_byte_bpe_with_config': 'create a HuggingFaceByteLevelBPEConfig dataclass with bpe_vocab, bpe_merges, and hf_tokenizer paths', 'load_hf_byte_bpe_from_tokenizer_file': 'initialize HuggingFaceByteLevelBPE by loading a pre-saved HuggingFace tokenizer file via hf_tokenizer config'}
```

