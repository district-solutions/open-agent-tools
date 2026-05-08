# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/torchscript/tokenizer/bpe.py

Prompts

```
['create a ScriptBPE tokenizer from a vocab file using from_vocab_file with an io.StringIO object', 'create a ScriptBPE tokenizer from a vocab file path using from_vocab_filename', 'tokenize a list of strings into BPE tokens using the ScriptBPE tokenize method', 'tokenize a single string into BPE subword tokens using the bpe_token method', 'load a BPE vocabulary dictionary from a file using the load_vocab static method', 'create a ScriptWordTokenizer and tokenize a raw text string into words with start and end indices', 'create a ScriptBPETokenizer with a ScriptBPE instance and tokenize a raw token into BPE subword tokens', 'create a ScriptDoNothingTokenizer and tokenize a raw token returning it unchanged with -1 indices', 'review the ScriptTokenizerBase class and its tokenize method signature for TorchScript compatibility', 'refactor the ScriptWordTokenizer to toggle lowercase behavior when tokenizing raw text into words']
```

Usage

```
{'create_bpe_tokenizer_from_vocab_file': 'create a ScriptBPE tokenizer from a vocab file using from_vocab_file with an io.StringIO object', 'create_bpe_tokenizer_from_filename': 'create a ScriptBPE tokenizer from a vocab file path using from_vocab_filename', 'tokenize_text_with_bpe': 'tokenize a list of strings into BPE tokens using the ScriptBPE tokenize method', 'tokenize_single_token_bpe': 'tokenize a single string into BPE subword tokens using the bpe_token method', 'load_bpe_vocab_from_file': 'load a BPE vocabulary dictionary from a file using the load_vocab static method'}
```

## File: facebookresearch_pytext/pytext/torchscript/tokenizer/tokenizer.py

Prompts

```
['create a ScriptBPE tokenizer from a vocab file using from_vocab_file with an io.StringIO object', 'create a ScriptBPE tokenizer from a vocab file path using from_vocab_filename', 'tokenize a list of strings into BPE tokens using the ScriptBPE tokenize method', 'tokenize a single string into BPE subword tokens using the bpe_token method', 'load a BPE vocabulary dictionary from a file using the load_vocab static method', 'create a ScriptWordTokenizer and tokenize a raw text string into words with start and end indices', 'create a ScriptBPETokenizer with a ScriptBPE instance and tokenize a raw token into BPE subword tokens', 'create a ScriptDoNothingTokenizer and tokenize a raw token returning it unchanged with -1 indices', 'review the ScriptTokenizerBase class and its tokenize method signature for TorchScript compatibility', 'refactor the ScriptWordTokenizer to toggle lowercase behavior when tokenizing raw text into words']
```

Usage

```
{'tokenize_text_with_word_tokenizer': 'create a ScriptWordTokenizer and tokenize a raw text string into words with start and end indices', 'tokenize_text_with_bpe_tokenizer': 'create a ScriptBPETokenizer with a ScriptBPE instance and tokenize a raw token into BPE subword tokens', 'tokenize_with_do_nothing_tokenizer': 'create a ScriptDoNothingTokenizer and tokenize a raw token returning it unchanged with -1 indices', 'review_tokenizer_base_class': 'review the ScriptTokenizerBase class and its tokenize method signature for TorchScript compatibility', 'refactor_word_tokenizer_lowercase': 'refactor the ScriptWordTokenizer to toggle lowercase behavior when tokenizing raw text into words'}
```

