# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mbart/test_modeling_mbart.py

Prompts

```
['test the MBartModel class with encoder-decoder architecture using MBartModelTester to verify config and inputs', 'test MBartForConditionalGeneration model for sequence-to-sequence translation with beam search and sampling', 'test the MBartDecoder past key-values caching mechanism with large inputs and attention masks', 'test the facebook/mbart-large-en-ro checkpoint for English to Romanian translation generation', 'test the standalone MBartDecoder model with causal language modeling using MBartStandaloneDecoderModelTester', 'test the MBartTokenizer batch encoding with English to Romanian source text and verify expected token IDs', 'test that MBartTokenizer decode ignores language code tokens when skip_special_tokens is True', 'test MBartTokenizer truncation with max_length and verify EOS and language code suffix tokens', 'test that MBartTokenizer special tokens persist correctly across save_pretrained and from_pretrained cycles', 'test MBartTokenizer _build_translation_inputs method for English to Arabic translation with forced BOS token']
```

Usage

```
{'test_mbart_model': 'test the MBartModel class with encoder-decoder architecture using MBartModelTester to verify config and inputs', 'test_mbart_conditional_generation': 'test MBartForConditionalGeneration model for sequence-to-sequence translation with beam search and sampling', 'test_mbart_decoder_past': 'test the MBartDecoder past key-values caching mechanism with large inputs and attention masks', 'test_mbart_integration_enro': 'test the facebook/mbart-large-en-ro checkpoint for English to Romanian translation generation', 'test_mbart_standalone_decoder': 'test the standalone MBartDecoder model with causal language modeling using MBartStandaloneDecoderModelTester'}
```

## File: huggingface_transformers/tests/models/mbart/test_tokenization_mbart.py

Prompts

```
['test the MBartModel class with encoder-decoder architecture using MBartModelTester to verify config and inputs', 'test MBartForConditionalGeneration model for sequence-to-sequence translation with beam search and sampling', 'test the MBartDecoder past key-values caching mechanism with large inputs and attention masks', 'test the facebook/mbart-large-en-ro checkpoint for English to Romanian translation generation', 'test the standalone MBartDecoder model with causal language modeling using MBartStandaloneDecoderModelTester', 'test the MBartTokenizer batch encoding with English to Romanian source text and verify expected token IDs', 'test that MBartTokenizer decode ignores language code tokens when skip_special_tokens is True', 'test MBartTokenizer truncation with max_length and verify EOS and language code suffix tokens', 'test that MBartTokenizer special tokens persist correctly across save_pretrained and from_pretrained cycles', 'test MBartTokenizer _build_translation_inputs method for English to Arabic translation with forced BOS token']
```

Usage

```
{'test_mbart_tokenizer_batch_encode': 'test the MBartTokenizer batch encoding with English to Romanian source text and verify expected token IDs', 'test_mbart_tokenizer_decode_language_codes': 'test that MBartTokenizer decode ignores language code tokens when skip_special_tokens is True', 'test_mbart_tokenizer_truncation': 'test MBartTokenizer truncation with max_length and verify EOS and language code suffix tokens', 'test_mbart_tokenizer_save_load_special_tokens': 'test that MBartTokenizer special tokens persist correctly across save_pretrained and from_pretrained cycles', 'test_mbart_tokenizer_translation_inputs': 'test MBartTokenizer _build_translation_inputs method for English to Arabic translation with forced BOS token'}
```

