# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/marian/test_modeling_marian.py

Prompts

```
['test the Marian encoder-decoder model with configurable batch size, sequence length, and vocab size', 'test the MarianDecoder standalone model with past key values for autoregressive generation', 'test saving and loading MarianModel encoder and decoder separately from pretrained checkpoint', 'test MarianMTModel generation in FP16 precision with beam search and sampling', 'test MarianModel encoder-decoder embedding sharing configuration and save/load behavior', 'test Marian translation from English to German using Helsinki-NLP opus-mt model', 'test Marian translation from English to French using opus-mt model', 'test Marian translation from French to English using opus-mt model', 'test Marian translation from Maltese to English for low-resource high-perplexity setting', 'test resizing MarianModel decoder token embeddings when encoder-decoder embeddings are not shared', 'test the MarianTokenizer class for sentencepiece-based translation tokenization', 'create a MarianTokenizer from a pretrained model name or local directory path', 'test saving and reloading a MarianTokenizer with save_pretrained and from_pretrained', 'test encoding text to input_ids and decoding input_ids back to text with MarianTokenizer', 'test batch encoding of input texts with padding, truncation, and return_tensors options']
```

Usage

```
{'test_modeling_marian': 'test the Marian encoder-decoder model with configurable batch size, sequence length, and vocab size', 'test_decoder_model_past': 'test the MarianDecoder standalone model with past key values for autoregressive generation', 'test_encoder_decoder_model_standalone': 'test saving and loading MarianModel encoder and decoder separately from pretrained checkpoint', 'test_generate_fp16': 'test MarianMTModel generation in FP16 precision with beam search and sampling', 'test_share_encoder_decoder_embeddings': 'test MarianModel encoder-decoder embedding sharing configuration and save/load behavior', 'test_batch_generation_en_de': 'test Marian translation from English to German using Helsinki-NLP opus-mt model', 'test_batch_generation_en_fr': 'test Marian translation from English to French using opus-mt model', 'test_batch_generation_fr_en': 'test Marian translation from French to English using opus-mt model', 'test_batch_generation_mt_en': 'test Marian translation from Maltese to English for low-resource high-perplexity setting', 'test_resize_decoder_token_embeddings': 'test resizing MarianModel decoder token embeddings when encoder-decoder embeddings are not shared'}
```

## File: huggingface_transformers/tests/models/marian/test_tokenization_marian.py

Prompts

```
['test the Marian encoder-decoder model with configurable batch size, sequence length, and vocab size', 'test the MarianDecoder standalone model with past key values for autoregressive generation', 'test saving and loading MarianModel encoder and decoder separately from pretrained checkpoint', 'test MarianMTModel generation in FP16 precision with beam search and sampling', 'test MarianModel encoder-decoder embedding sharing configuration and save/load behavior', 'test Marian translation from English to German using Helsinki-NLP opus-mt model', 'test Marian translation from English to French using opus-mt model', 'test Marian translation from French to English using opus-mt model', 'test Marian translation from Maltese to English for low-resource high-perplexity setting', 'test resizing MarianModel decoder token embeddings when encoder-decoder embeddings are not shared', 'test the MarianTokenizer class for sentencepiece-based translation tokenization', 'create a MarianTokenizer from a pretrained model name or local directory path', 'test saving and reloading a MarianTokenizer with save_pretrained and from_pretrained', 'test encoding text to input_ids and decoding input_ids back to text with MarianTokenizer', 'test batch encoding of input texts with padding, truncation, and return_tensors options']
```

Usage

```
{'test_tokenization_marian': 'test the MarianTokenizer class for sentencepiece-based translation tokenization', 'create_tokenizer_from_pretrained': 'create a MarianTokenizer from a pretrained model name or local directory path', 'test_tokenizer_save_load': 'test saving and reloading a MarianTokenizer with save_pretrained and from_pretrained', 'test_tokenizer_encode_decode': 'test encoding text to input_ids and decoding input_ids back to text with MarianTokenizer', 'test_tokenizer_batch_encoding': 'test batch encoding of input texts with padding, truncation, and return_tensors options'}
```

