# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/preprocessing/bpe_modes/bpe_mode.py

Prompts

```
['learn BPE merge codes from a text file with a specified number of codes', 'apply BPE tokenization to a string of source code and return the tokenized result', 'apply BPE tokenization to an entire file and write the output to a new file', 'repair BPE tokenization artifacts on a single line that contain obfuscated variable names', 'repair BPE tokenization artifacts across an entire file that contain obfuscated variable names', 'learn BPE merge codes from a text file with a specified number of codes using FastBPE', 'apply BPE tokenization to a source code string using a trained FastBPE model', 'apply BPE tokenization to an entire file and write the tokenized output to a new file', 'extract a vocabulary of tokens from a text file and limit it to a specified size', 'repair BPE-tokenized lines that contain obfuscated variable names by removing merge symbols from identifiers', 'apply BPE tokenization using RoBERTa to a source code string and return tokenized output', 'initialize a RobertaBPEMode instance that uses pretrained RoBERTa vocabulary for BPE tokenization']
```

Usage

```
{'learn_bpe_file': 'learn BPE merge codes from a text file with a specified number of codes', 'apply_bpe': 'apply BPE tokenization to a string of source code and return the tokenized result', 'apply_bpe_file': 'apply BPE tokenization to an entire file and write the output to a new file', 'repair_bpe_for_obfuscation_line': 'repair BPE tokenization artifacts on a single line that contain obfuscated variable names', 'repair_bpe_for_obfuscation_file': 'repair BPE tokenization artifacts across an entire file that contain obfuscated variable names'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/bpe_modes/fast_bpe_mode.py

Prompts

```
['learn BPE merge codes from a text file with a specified number of codes', 'apply BPE tokenization to a string of source code and return the tokenized result', 'apply BPE tokenization to an entire file and write the output to a new file', 'repair BPE tokenization artifacts on a single line that contain obfuscated variable names', 'repair BPE tokenization artifacts across an entire file that contain obfuscated variable names', 'learn BPE merge codes from a text file with a specified number of codes using FastBPE', 'apply BPE tokenization to a source code string using a trained FastBPE model', 'apply BPE tokenization to an entire file and write the tokenized output to a new file', 'extract a vocabulary of tokens from a text file and limit it to a specified size', 'repair BPE-tokenized lines that contain obfuscated variable names by removing merge symbols from identifiers', 'apply BPE tokenization using RoBERTa to a source code string and return tokenized output', 'initialize a RobertaBPEMode instance that uses pretrained RoBERTa vocabulary for BPE tokenization']
```

Usage

```
{'learn_bpe_codes_from_file': 'learn BPE merge codes from a text file with a specified number of codes using FastBPE', 'apply_bpe_to_string': 'apply BPE tokenization to a source code string using a trained FastBPE model', 'apply_bpe_to_file': 'apply BPE tokenization to an entire file and write the tokenized output to a new file', 'extract_vocabulary_from_file': 'extract a vocabulary of tokens from a text file and limit it to a specified size', 'repair_bpe_obfuscated_identifiers': 'repair BPE-tokenized lines that contain obfuscated variable names by removing merge symbols from identifiers'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/bpe_modes/roberta_bpe_mode.py

Prompts

```
['learn BPE merge codes from a text file with a specified number of codes', 'apply BPE tokenization to a string of source code and return the tokenized result', 'apply BPE tokenization to an entire file and write the output to a new file', 'repair BPE tokenization artifacts on a single line that contain obfuscated variable names', 'repair BPE tokenization artifacts across an entire file that contain obfuscated variable names', 'learn BPE merge codes from a text file with a specified number of codes using FastBPE', 'apply BPE tokenization to a source code string using a trained FastBPE model', 'apply BPE tokenization to an entire file and write the tokenized output to a new file', 'extract a vocabulary of tokens from a text file and limit it to a specified size', 'repair BPE-tokenized lines that contain obfuscated variable names by removing merge symbols from identifiers', 'apply BPE tokenization using RoBERTa to a source code string and return tokenized output', 'initialize a RobertaBPEMode instance that uses pretrained RoBERTa vocabulary for BPE tokenization']
```

Usage

```
{'apply_bpe_to_code_string': 'apply BPE tokenization using RoBERTa to a source code string and return tokenized output', 'apply_bpe_to_file': 'apply BPE tokenization using RoBERTa to a source code file and write tokenized output to a new file', 'repair_bpe_for_obfuscation_line': 'repair a single line of BPE tokenized text to fix obfuscated identifiers like CLASS_ FUNC_ and VAR_', 'repair_bpe_for_obfuscation_file': 'repair an entire file of BPE tokenized text to fix obfuscated identifiers and special tokens', 'initialize_roberta_bpe_mode': 'initialize a RobertaBPEMode instance that uses pretrained RoBERTa vocabulary for BPE tokenization'}
```

