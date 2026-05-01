# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/plbart/test_modeling_plbart.py

Prompts

```
['test the PLBartModel using PLBartModelTester to verify encoder-decoder forward passes and save-load behavior', 'test PLBartForConditionalGeneration model generation with fp16 precision and beam search decoding', 'test the PLBartDecoder past key values caching with large inputs and attention masks', 'test the PLBart Java to C# translation integration using the uclanlp/plbart-java-cs checkpoint', 'test the standalone PLBartDecoder model with past key values and attention mask handling', 'test the PLBartTokenizer tokenize method with base language codes and verify token IDs', 'test the PLBartTokenizer batch encode with source and target texts for seq2seq training', 'test the PLBartTokenizer decode method ignores language code tokens and strips EOS tokens', 'test the PLBartTokenizer truncation with max_length and verify EOS and language suffix tokens', 'test the PLBartTokenizer save_pretrained and from_pretrained preserve special tokens']
```

Usage

```
{'test_plbart_model': 'test the PLBartModel using PLBartModelTester to verify encoder-decoder forward passes and save-load behavior', 'test_plbart_conditional_generation': 'test PLBartForConditionalGeneration model generation with fp16 precision and beam search decoding', 'test_plbart_decoder_past': 'test the PLBartDecoder past key values caching with large inputs and attention masks', 'test_plbart_integration_java_cs': 'test the PLBart Java to C# translation integration using the uclanlp/plbart-java-cs checkpoint', 'test_plbart_standalone_decoder': 'test the standalone PLBartDecoder model with past key values and attention mask handling'}
```

## File: huggingface_transformers/tests/models/plbart/test_tokenization_plbart.py

Prompts

```
['test the PLBartModel using PLBartModelTester to verify encoder-decoder forward passes and save-load behavior', 'test PLBartForConditionalGeneration model generation with fp16 precision and beam search decoding', 'test the PLBartDecoder past key values caching with large inputs and attention masks', 'test the PLBart Java to C# translation integration using the uclanlp/plbart-java-cs checkpoint', 'test the standalone PLBartDecoder model with past key values and attention mask handling', 'test the PLBartTokenizer tokenize method with base language codes and verify token IDs', 'test the PLBartTokenizer batch encode with source and target texts for seq2seq training', 'test the PLBartTokenizer decode method ignores language code tokens and strips EOS tokens', 'test the PLBartTokenizer truncation with max_length and verify EOS and language suffix tokens', 'test the PLBartTokenizer save_pretrained and from_pretrained preserve special tokens']
```

Usage

```
{'test_PLBartTokenizer_tokenize': 'test the PLBartTokenizer tokenize method with base language codes and verify token IDs', 'test_PLBartTokenizer_batch_encode': 'test the PLBartTokenizer batch encode with source and target texts for seq2seq training', 'test_PLBartTokenizer_decode': 'test the PLBartTokenizer decode method ignores language code tokens and strips EOS tokens', 'test_PLBartTokenizer_truncation': 'test the PLBartTokenizer truncation with max_length and verify EOS and language suffix tokens', 'test_PLBartTokenizer_save_load': 'test the PLBartTokenizer save_pretrained and from_pretrained preserve special tokens'}
```

