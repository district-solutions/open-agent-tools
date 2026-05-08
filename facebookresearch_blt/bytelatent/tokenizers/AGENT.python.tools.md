# Agent Python Tools

- repo: facebookresearch/blt
- repo_uri: https://github.com/facebookresearch/blt

## File: facebookresearch_blt/bytelatent/tokenizers/abstract_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'implement_tokenizer_subclass': 'implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode_text_to_tokens': 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode_tokens_to_text': 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get_token_offsets': 'get the character offsets of each token in the original text for evaluation purposes', 'get_vocab_size': 'get the vocabulary size as an integer from a Tokenizer subclass instance'}
```

## File: facebookresearch_blt/bytelatent/tokenizers/blt_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'create_blt_tokenizer': 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'encode_text_to_tokens': 'encode a text string into a list of integer tokens using the BltTokenizer', 'decode_tokens_to_text': 'decode a list of integer tokens back into a UTF-8 text string using BltTokenizer', 'get_vocab_size': 'get the total vocabulary size of the BltTokenizer including offsetting special characters', 'convert_hex_bytes': 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes'}
```

## File: facebookresearch_blt/bytelatent/tokenizers/build_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'build_blt_tokenizer': 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build_mock_tokenizer': 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build_sentencepiece_tokenizer': 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build_tiktoken_tokenizer': 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review_tokenizerargs_build': 'review the TokenizerArgs build method to understand tokenizer factory logic'}
```

## File: facebookresearch_blt/bytelatent/tokenizers/sentence_piece_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'create_SentencePieceTokenizer': 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'encode_text_to_tokens': 'encode a string into a list of integer token IDs using the SentencePiece tokenizer', 'decode_tokens_to_text': 'decode a list of integer token IDs back into a string using the SentencePiece tokenizer', 'get_vocab_size': 'get the vocabulary size of the loaded SentencePiece tokenizer model', 'get_token_offsets': 'get the substring surfaces and byte offsets for each token piece in the input text'}
```

## File: facebookresearch_blt/bytelatent/tokenizers/test_blt_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'test_BltTokenizer_encode_bytes': 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test_BltTokenizer_encode_bpe': 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test_TokenizerArgs_build': 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test_tokenizer_fixture_validation': 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test_tokenizer_init_kwargs': 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build'}
```

## File: facebookresearch_blt/bytelatent/tokenizers/tiktoken_tokenizer.py

Prompts

```
['implement a concrete subclass of the Tokenizer ABC that provides encode, decode, get_token_offsets, and get_vocab_size methods', 'encode a string into a list of integer tokens with optional BOS and EOS markers using a Tokenizer subclass', 'decode a list of integer tokens back into the original text string using a Tokenizer subclass', 'get the character offsets of each token in the original text for evaluation purposes', 'get the vocabulary size as an integer from a Tokenizer subclass instance', 'create a BltTokenizer instance with optional BPE delimiter and BOS/EOS token settings', 'convert a hex string like <0x4865> or plain text into raw bytes using convert_to_bytes', 'build a BltTokenizer instance using TokenizerArgs with name set to blt', 'build a MockTokenizer instance using TokenizerArgs with name set to mock', 'build a SentencePieceTokenizer instance using TokenizerArgs with name set to sp', 'build a TikTokenTokenizer instance using TokenizerArgs with name set to tiktoken', 'review the TokenizerArgs build method to understand tokenizer factory logic', 'create a SentencePieceTokenizer instance from a SentencePiece model file path with BOS and EOS options', 'test BltTokenizer encoding text to tokens with bpe_delim set to False', 'test BltTokenizer encoding text to tokens with bpe_delim set to True', 'test building a BltTokenizer from TokenizerArgs with a BPE tokenizer model path', 'test tokenizer encoding against expected token lists loaded from a JSON fixture file', 'test passing init_kwargs with bpe_tokenizer_path to TokenizerArgs before calling build', 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode a list of integer token IDs back into text using TikTokenTokenizer']
```

Usage

```
{'create_TikTokenTokenizer': 'create a TikTokenTokenizer instance by loading a tiktoken BPE model from a file path', 'encode_text': 'encode a string into token IDs using TikTokenTokenizer with optional BOS and EOS tokens', 'decode_tokens': 'decode a list of integer token IDs back into text using TikTokenTokenizer', 'get_vocab_size': 'get the vocabulary size of a TikTokenTokenizer instance', 'get_token_offsets': 'get token substrings and their byte offsets in the original text using TikTokenTokenizer'}
```

