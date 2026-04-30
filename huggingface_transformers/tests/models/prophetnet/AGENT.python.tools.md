# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/prophetnet/test_modeling_prophetnet.py

Prompts

```
['test the ProphetNetModel forward pass with input_ids and decoder_input_ids to verify encoder and decoder output shapes', 'test ProphetNetForConditionalGeneration with labels to verify logits shape and scalar loss output', 'test ProphetNetForCausalLM decoder-only causal language model generation with past key value states', 'test ProphetNetDecoder past key value caching produces identical outputs to full sequence forward pass', 'test ProphetNetModel encoder decoder and cross attention output shapes when output_attentions is enabled', 'test the ProphetNetTokenizer tokenizes input text and converts tokens to IDs correctly', 'create a ProphetNetTokenizer from a vocab file and tokenize input strings', 'test BasicTokenizer lowercases text and handles whitespace and special characters', 'test WordpieceTokenizer splits words into subword pieces using a vocab dictionary', 'test the ProphetNetTokenizer encodes a batch of source texts into padded input IDs with attention masks']
```

Usage

```
{'test_ProphetNetModel': 'test the ProphetNetModel forward pass with input_ids and decoder_input_ids to verify encoder and decoder output shapes', 'test_ProphetNetForConditionalGeneration': 'test ProphetNetForConditionalGeneration with labels to verify logits shape and scalar loss output', 'test_ProphetNetForCausalLM': 'test ProphetNetForCausalLM decoder-only causal language model generation with past key value states', 'test_ProphetNetDecoder_past_key_values': 'test ProphetNetDecoder past key value caching produces identical outputs to full sequence forward pass', 'test_ProphetNet_attention_outputs': 'test ProphetNetModel encoder decoder and cross attention output shapes when output_attentions is enabled'}
```

## File: huggingface_transformers/tests/models/prophetnet/test_tokenization_prophetnet.py

Prompts

```
['test the ProphetNetModel forward pass with input_ids and decoder_input_ids to verify encoder and decoder output shapes', 'test ProphetNetForConditionalGeneration with labels to verify logits shape and scalar loss output', 'test ProphetNetForCausalLM decoder-only causal language model generation with past key value states', 'test ProphetNetDecoder past key value caching produces identical outputs to full sequence forward pass', 'test ProphetNetModel encoder decoder and cross attention output shapes when output_attentions is enabled', 'test the ProphetNetTokenizer tokenizes input text and converts tokens to IDs correctly', 'create a ProphetNetTokenizer from a vocab file and tokenize input strings', 'test BasicTokenizer lowercases text and handles whitespace and special characters', 'test WordpieceTokenizer splits words into subword pieces using a vocab dictionary', 'test the ProphetNetTokenizer encodes a batch of source texts into padded input IDs with attention masks']
```

Usage

```
{'test_full_tokenizer': 'test the ProphetNetTokenizer tokenizes input text and converts tokens to IDs correctly', 'create_tokenizer_basic': 'create a ProphetNetTokenizer from a vocab file and tokenize input strings', 'test_basic_tokenizer_lower': 'test BasicTokenizer lowercases text and handles whitespace and special characters', 'test_wordpiece_tokenizer': 'test WordpieceTokenizer splits words into subword pieces using a vocab dictionary', 'test_prepare_batch': 'test the ProphetNetTokenizer encodes a batch of source texts into padded input IDs with attention masks'}
```

