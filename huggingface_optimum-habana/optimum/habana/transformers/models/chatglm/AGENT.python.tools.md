# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/chatglm/modeling_chatglm.py

Prompts

```
['build a ChatGLM chatbot using ChatGLMForConditionalGeneration that supports multi-turn conversations with history', 'create a sequence classification model using ChatGLMForSequenceClassification for single or multi-label classification tasks', 'run streaming chat generation using stream_chat to yield responses token by token with past key values', 'refactor the CoreAttention forward method to toggle flash attention parameters like causal mask and fast softmax', 'review the KVCache and SelfAttention allocate_kv_cache methods for pre-allocating key-value cache memory on HPU', 'build chat input tokens from a query and history using ChatGLMTokenizer build_chat_input method', 'tokenize text into SentencePiece tokens using SPTokenizer tokenize method with special token support', 'encode text to token IDs or decode token IDs back to text using SPTokenizer encode and decode', 'pad tokenized inputs on the left with attention mask and position IDs using ChatGLMTokenizer _pad method', 'build token IDs for a single chat message with role metadata using ChatGLMTokenizer build_single_message']
```

Usage

```
{'build_chatglm_chat': 'build a ChatGLM chatbot using ChatGLMForConditionalGeneration that supports multi-turn conversations with history', 'create_chatglm_sequence_classifier': 'create a sequence classification model using ChatGLMForSequenceClassification for single or multi-label classification tasks', 'run_chatglm_stream_chat': 'run streaming chat generation using stream_chat to yield responses token by token with past key values', 'refactor_chatglm_flash_attention': 'refactor the CoreAttention forward method to toggle flash attention parameters like causal mask and fast softmax', 'review_chatglm_kv_cache': 'review the KVCache and SelfAttention allocate_kv_cache methods for pre-allocating key-value cache memory on HPU'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/models/chatglm/tokenization_chatglm.py

Prompts

```
['build a ChatGLM chatbot using ChatGLMForConditionalGeneration that supports multi-turn conversations with history', 'create a sequence classification model using ChatGLMForSequenceClassification for single or multi-label classification tasks', 'run streaming chat generation using stream_chat to yield responses token by token with past key values', 'refactor the CoreAttention forward method to toggle flash attention parameters like causal mask and fast softmax', 'review the KVCache and SelfAttention allocate_kv_cache methods for pre-allocating key-value cache memory on HPU', 'build chat input tokens from a query and history using ChatGLMTokenizer build_chat_input method', 'tokenize text into SentencePiece tokens using SPTokenizer tokenize method with special token support', 'encode text to token IDs or decode token IDs back to text using SPTokenizer encode and decode', 'pad tokenized inputs on the left with attention mask and position IDs using ChatGLMTokenizer _pad method', 'build token IDs for a single chat message with role metadata using ChatGLMTokenizer build_single_message']
```

Usage

```
{'build_chat_input': 'build chat input tokens from a query and history using ChatGLMTokenizer build_chat_input method', 'tokenize_text': 'tokenize text into SentencePiece tokens using SPTokenizer tokenize method with special token support', 'encode_decode_tokens': 'encode text to token IDs or decode token IDs back to text using SPTokenizer encode and decode', 'pad_encoded_inputs': 'pad tokenized inputs on the left with attention mask and position IDs using ChatGLMTokenizer _pad method', 'build_single_message': 'build token IDs for a single chat message with role metadata using ChatGLMTokenizer build_single_message'}
```

