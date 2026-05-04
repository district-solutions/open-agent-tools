# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/testing/_dummy_tokenizer.py

Prompts

```
['create a DummyTokenizer instance for testing Gemma model text tokenization', 'test the _DummySentencePieceProcessor EncodeAsIds method to convert text into token IDs', 'test the _DummySentencePieceProcessor DecodeIds method to convert token IDs back into text', 'test the _DummySentencePieceProcessor GetPieceSize method to get the vocabulary size', 'test the pad_id bos_id and eos_id methods of _DummySentencePieceProcessor', 'use the local tokenizer fixture to avoid TFHub calls during gemma tests', 'review the pytest fixture that patches Gemma3Tokenizer to use a local model file', 'test the hermetic tokenizer fixture that redirects Gemma3Tokenizer to a local model path']
```

Usage

```
{'create_DummyTokenizer': 'create a DummyTokenizer instance for testing Gemma model text tokenization', 'test_EncodeAsIds': 'test the _DummySentencePieceProcessor EncodeAsIds method to convert text into token IDs', 'test_DecodeIds': 'test the _DummySentencePieceProcessor DecodeIds method to convert token IDs back into text', 'test_GetPieceSize': 'test the _DummySentencePieceProcessor GetPieceSize method to get the vocabulary size', 'test_special_token_ids': 'test the pad_id bos_id and eos_id methods of _DummySentencePieceProcessor'}
```

## File: google-deepmind_gemma/gemma/gm/testing/_fixtures.py

Prompts

```
['create a DummyTokenizer instance for testing Gemma model text tokenization', 'test the _DummySentencePieceProcessor EncodeAsIds method to convert text into token IDs', 'test the _DummySentencePieceProcessor DecodeIds method to convert token IDs back into text', 'test the _DummySentencePieceProcessor GetPieceSize method to get the vocabulary size', 'test the pad_id bos_id and eos_id methods of _DummySentencePieceProcessor', 'use the local tokenizer fixture to avoid TFHub calls during gemma tests', 'review the pytest fixture that patches Gemma3Tokenizer to use a local model file', 'test the hermetic tokenizer fixture that redirects Gemma3Tokenizer to a local model path']
```

Usage

```
{'use_hermetic_tokenizer': 'use the local tokenizer fixture to avoid TFHub calls during gemma tests', 'review_use_hermetic_tokenizer': 'review the pytest fixture that patches Gemma3Tokenizer to use a local model file', 'test_use_hermetic_tokenizer': 'test the hermetic tokenizer fixture that redirects Gemma3Tokenizer to a local model path'}
```

