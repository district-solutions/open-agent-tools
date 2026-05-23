# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/data/text/test_sentencepiece.py

Prompts

```
['test SentencePieceModel initialization with control symbols and verify pad_idx and unk_idx values', 'test SentencePieceEncoder and SentencePieceDecoder to encode text to token indices and decode back', 'test SentencePieceEncoder with reverse=True to produce reversed token indices and decode correctly', 'test SentencePieceEncoder with prefix_tokens and suffix_tokens to prepend and append special tokens', 'test SentencePieceDecoder decode_from_tokens to reconstruct text from a list of token strings', 'test the StrSplitter class to split a tab-separated string into a list of fields', 'test the StrSplitter class with a custom separator to split space-delimited strings', 'test the StrSplitter class with names to return a dictionary mapping column names to values', 'test the StrSplitter class with a single index to extract one field as a string', 'test the StrSplitter class with exclude to omit specified column indices from the output', 'test the StrToIntConverter class to convert decimal string representations to integers', 'test the StrToIntConverter with base 8 to parse octal string representations', 'test the StrToIntConverter raises ValueError when given non-numeric string input', 'test the StrToIntConverter raises ValueError when input exceeds 64-bit integer range', 'test the StrToIntConverter raises ValueError when input is not a string type', 'create a StrToTensorConverter and convert a space-separated string of integers into a PyTorch tensor', 'create a StrToTensorConverter with a size parameter to reshape parsed integers into a 2D tensor', 'create a StrToTensorConverter with -1 in size to infer one dimension from the input string', 'create a StrToTensorConverter and convert an empty string into an empty PyTorch tensor', 'test the StrToTensorConverter to verify it raises errors for unsupported dtypes, non-string input, invalid values, and out-of-range numbers']
```

Usage

```
{'test_SentencePieceModel_init': 'test SentencePieceModel initialization with control symbols and verify pad_idx and unk_idx values', 'test_SentencePieceEncoder_encode_decode': 'test SentencePieceEncoder and SentencePieceDecoder to encode text to token indices and decode back', 'test_SentencePieceEncoder_reverse_mode': 'test SentencePieceEncoder with reverse=True to produce reversed token indices and decode correctly', 'test_SentencePieceEncoder_prefix_suffix_tokens': 'test SentencePieceEncoder with prefix_tokens and suffix_tokens to prepend and append special tokens', 'test_SentencePieceDecoder_decode_from_tokens': 'test SentencePieceDecoder decode_from_tokens to reconstruct text from a list of token strings'}
```

## File: facebookresearch_fairseq2/tests/unit/data/text/test_str_splitter.py

Prompts

```
['test SentencePieceModel initialization with control symbols and verify pad_idx and unk_idx values', 'test SentencePieceEncoder and SentencePieceDecoder to encode text to token indices and decode back', 'test SentencePieceEncoder with reverse=True to produce reversed token indices and decode correctly', 'test SentencePieceEncoder with prefix_tokens and suffix_tokens to prepend and append special tokens', 'test SentencePieceDecoder decode_from_tokens to reconstruct text from a list of token strings', 'test the StrSplitter class to split a tab-separated string into a list of fields', 'test the StrSplitter class with a custom separator to split space-delimited strings', 'test the StrSplitter class with names to return a dictionary mapping column names to values', 'test the StrSplitter class with a single index to extract one field as a string', 'test the StrSplitter class with exclude to omit specified column indices from the output', 'test the StrToIntConverter class to convert decimal string representations to integers', 'test the StrToIntConverter with base 8 to parse octal string representations', 'test the StrToIntConverter raises ValueError when given non-numeric string input', 'test the StrToIntConverter raises ValueError when input exceeds 64-bit integer range', 'test the StrToIntConverter raises ValueError when input is not a string type', 'create a StrToTensorConverter and convert a space-separated string of integers into a PyTorch tensor', 'create a StrToTensorConverter with a size parameter to reshape parsed integers into a 2D tensor', 'create a StrToTensorConverter with -1 in size to infer one dimension from the input string', 'create a StrToTensorConverter and convert an empty string into an empty PyTorch tensor', 'test the StrToTensorConverter to verify it raises errors for unsupported dtypes, non-string input, invalid values, and out-of-range numbers']
```

Usage

```
{'test_StrSplitter_default_split': 'test the StrSplitter class to split a tab-separated string into a list of fields', 'test_StrSplitter_custom_separator': 'test the StrSplitter class with a custom separator to split space-delimited strings', 'test_StrSplitter_named_fields': 'test the StrSplitter class with names to return a dictionary mapping column names to values', 'test_StrSplitter_single_index': 'test the StrSplitter class with a single index to extract one field as a string', 'test_StrSplitter_exclude_indices': 'test the StrSplitter class with exclude to omit specified column indices from the output'}
```

## File: facebookresearch_fairseq2/tests/unit/data/text/test_str_to_int_converter.py

Prompts

```
['test SentencePieceModel initialization with control symbols and verify pad_idx and unk_idx values', 'test SentencePieceEncoder and SentencePieceDecoder to encode text to token indices and decode back', 'test SentencePieceEncoder with reverse=True to produce reversed token indices and decode correctly', 'test SentencePieceEncoder with prefix_tokens and suffix_tokens to prepend and append special tokens', 'test SentencePieceDecoder decode_from_tokens to reconstruct text from a list of token strings', 'test the StrSplitter class to split a tab-separated string into a list of fields', 'test the StrSplitter class with a custom separator to split space-delimited strings', 'test the StrSplitter class with names to return a dictionary mapping column names to values', 'test the StrSplitter class with a single index to extract one field as a string', 'test the StrSplitter class with exclude to omit specified column indices from the output', 'test the StrToIntConverter class to convert decimal string representations to integers', 'test the StrToIntConverter with base 8 to parse octal string representations', 'test the StrToIntConverter raises ValueError when given non-numeric string input', 'test the StrToIntConverter raises ValueError when input exceeds 64-bit integer range', 'test the StrToIntConverter raises ValueError when input is not a string type', 'create a StrToTensorConverter and convert a space-separated string of integers into a PyTorch tensor', 'create a StrToTensorConverter with a size parameter to reshape parsed integers into a 2D tensor', 'create a StrToTensorConverter with -1 in size to infer one dimension from the input string', 'create a StrToTensorConverter and convert an empty string into an empty PyTorch tensor', 'test the StrToTensorConverter to verify it raises errors for unsupported dtypes, non-string input, invalid values, and out-of-range numbers']
```

Usage

```
{'test_StrToIntConverter_basic': 'test the StrToIntConverter class to convert decimal string representations to integers', 'test_StrToIntConverter_base8': 'test the StrToIntConverter with base 8 to parse octal string representations', 'test_StrToIntConverter_invalid_input': 'test the StrToIntConverter raises ValueError when given non-numeric string input', 'test_StrToIntConverter_out_of_range': 'test the StrToIntConverter raises ValueError when input exceeds 64-bit integer range', 'test_StrToIntConverter_type_check': 'test the StrToIntConverter raises ValueError when input is not a string type'}
```

## File: facebookresearch_fairseq2/tests/unit/data/text/test_str_to_tensor_converter.py

Prompts

```
['test SentencePieceModel initialization with control symbols and verify pad_idx and unk_idx values', 'test SentencePieceEncoder and SentencePieceDecoder to encode text to token indices and decode back', 'test SentencePieceEncoder with reverse=True to produce reversed token indices and decode correctly', 'test SentencePieceEncoder with prefix_tokens and suffix_tokens to prepend and append special tokens', 'test SentencePieceDecoder decode_from_tokens to reconstruct text from a list of token strings', 'test the StrSplitter class to split a tab-separated string into a list of fields', 'test the StrSplitter class with a custom separator to split space-delimited strings', 'test the StrSplitter class with names to return a dictionary mapping column names to values', 'test the StrSplitter class with a single index to extract one field as a string', 'test the StrSplitter class with exclude to omit specified column indices from the output', 'test the StrToIntConverter class to convert decimal string representations to integers', 'test the StrToIntConverter with base 8 to parse octal string representations', 'test the StrToIntConverter raises ValueError when given non-numeric string input', 'test the StrToIntConverter raises ValueError when input exceeds 64-bit integer range', 'test the StrToIntConverter raises ValueError when input is not a string type', 'create a StrToTensorConverter and convert a space-separated string of integers into a PyTorch tensor', 'create a StrToTensorConverter with a size parameter to reshape parsed integers into a 2D tensor', 'create a StrToTensorConverter with -1 in size to infer one dimension from the input string', 'create a StrToTensorConverter and convert an empty string into an empty PyTorch tensor', 'test the StrToTensorConverter to verify it raises errors for unsupported dtypes, non-string input, invalid values, and out-of-range numbers']
```

Usage

```
{'convert_string_to_tensor': 'create a StrToTensorConverter and convert a space-separated string of integers into a PyTorch tensor', 'convert_string_to_shaped_tensor': 'create a StrToTensorConverter with a size parameter to reshape parsed integers into a 2D tensor', 'convert_string_with_inferred_dim': 'create a StrToTensorConverter with -1 in size to infer one dimension from the input string', 'convert_empty_string_to_tensor': 'create a StrToTensorConverter and convert an empty string into an empty PyTorch tensor', 'test_converter_error_handling': 'test the StrToTensorConverter to verify it raises errors for unsupported dtypes, non-string input, invalid values, and out-of-range numbers'}
```

