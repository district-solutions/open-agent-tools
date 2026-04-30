# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/baichuan/generation_utils.py

Prompts

```
['build chat input token ids from a list of messages using a model and tokenizer for Baichuan generation', 'create a TextIterStreamer that decodes generated tokens into streaming text output from a tokenizer', 'use the TextIterStreamer put method to feed generated token values into the streamer queue', 'use the TextIterStreamer end method to signal completion by putting None into the text queue', 'iterate over a TextIterStreamer instance to receive decoded text chunks as they are produced', 'build a BaichuanForCausalLM model from pretrained weights using from_pretrained for HPU inference', 'run the BaichuanForCausalLM chat method with a tokenizer and list of message dicts', 'create an ALiBi positional bias tensor using gaudi_baichuan_build_alibi_tensor for the 13B model', 'review the KVCache class allocate and update methods for key-value cache management during generation', 'refactor the Attention class to toggle flash attention with use_flash_attention and fused SDPA kernels', 'create a BaichuanTokenizer instance from a SentencePiece vocab file with custom special tokens', 'tokenize text into token IDs using the BaichuanTokenizer with bos and eos token options', 'convert a list of Baichuan token strings back into a decoded text string', 'build input sequences with bos and eos special tokens for single or paired sequences', 'save the Baichuan tokenizer vocabulary file to a specified directory']
```

Usage

```
{'build_chat_input_token_ids': 'build chat input token ids from a list of messages using a model and tokenizer for Baichuan generation', 'create_text_iter_streamer': 'create a TextIterStreamer that decodes generated tokens into streaming text output from a tokenizer', 'use_text_iter_streamer_put': 'use the TextIterStreamer put method to feed generated token values into the streamer queue', 'use_text_iter_streamer_end': 'use the TextIterStreamer end method to signal completion by putting None into the text queue', 'iterate_text_iter_streamer': 'iterate over a TextIterStreamer instance to receive decoded text chunks as they are produced'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/models/baichuan/modeling_baichuan.py

Prompts

```
['build chat input token ids from a list of messages using a model and tokenizer for Baichuan generation', 'create a TextIterStreamer that decodes generated tokens into streaming text output from a tokenizer', 'use the TextIterStreamer put method to feed generated token values into the streamer queue', 'use the TextIterStreamer end method to signal completion by putting None into the text queue', 'iterate over a TextIterStreamer instance to receive decoded text chunks as they are produced', 'build a BaichuanForCausalLM model from pretrained weights using from_pretrained for HPU inference', 'run the BaichuanForCausalLM chat method with a tokenizer and list of message dicts', 'create an ALiBi positional bias tensor using gaudi_baichuan_build_alibi_tensor for the 13B model', 'review the KVCache class allocate and update methods for key-value cache management during generation', 'refactor the Attention class to toggle flash attention with use_flash_attention and fused SDPA kernels', 'create a BaichuanTokenizer instance from a SentencePiece vocab file with custom special tokens', 'tokenize text into token IDs using the BaichuanTokenizer with bos and eos token options', 'convert a list of Baichuan token strings back into a decoded text string', 'build input sequences with bos and eos special tokens for single or paired sequences', 'save the Baichuan tokenizer vocabulary file to a specified directory']
```

Usage

```
{'build_baichuan_causal_lm': 'build a BaichuanForCausalLM model from pretrained weights using from_pretrained for HPU inference', 'run_baichuan_chat': 'run the BaichuanForCausalLM chat method with a tokenizer and list of message dicts', 'create_alibi_tensor': 'create an ALiBi positional bias tensor using gaudi_baichuan_build_alibi_tensor for the 13B model', 'review_kv_cache': 'review the KVCache class allocate and update methods for key-value cache management during generation', 'refactor_attention_flash': 'refactor the Attention class to toggle flash attention with use_flash_attention and fused SDPA kernels'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/models/baichuan/tokenization_baichuan.py

Prompts

```
['build chat input token ids from a list of messages using a model and tokenizer for Baichuan generation', 'create a TextIterStreamer that decodes generated tokens into streaming text output from a tokenizer', 'use the TextIterStreamer put method to feed generated token values into the streamer queue', 'use the TextIterStreamer end method to signal completion by putting None into the text queue', 'iterate over a TextIterStreamer instance to receive decoded text chunks as they are produced', 'build a BaichuanForCausalLM model from pretrained weights using from_pretrained for HPU inference', 'run the BaichuanForCausalLM chat method with a tokenizer and list of message dicts', 'create an ALiBi positional bias tensor using gaudi_baichuan_build_alibi_tensor for the 13B model', 'review the KVCache class allocate and update methods for key-value cache management during generation', 'refactor the Attention class to toggle flash attention with use_flash_attention and fused SDPA kernels', 'create a BaichuanTokenizer instance from a SentencePiece vocab file with custom special tokens', 'tokenize text into token IDs using the BaichuanTokenizer with bos and eos token options', 'convert a list of Baichuan token strings back into a decoded text string', 'build input sequences with bos and eos special tokens for single or paired sequences', 'save the Baichuan tokenizer vocabulary file to a specified directory']
```

Usage

```
{'create_BaichuanTokenizer': 'create a BaichuanTokenizer instance from a SentencePiece vocab file with custom special tokens', 'tokenize_with_BaichuanTokenizer': 'tokenize text into token IDs using the BaichuanTokenizer with bos and eos token options', 'convert_tokens_to_string': 'convert a list of Baichuan token strings back into a decoded text string', 'build_inputs_with_special_tokens': 'build input sequences with bos and eos special tokens for single or paired sequences', 'save_vocabulary': 'save the Baichuan tokenizer vocabulary file to a specified directory'}
```

