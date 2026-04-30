# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-pyo3/py_src/candle/models/bert.py

Prompts

```
['build a BERT model with custom config for sequence classification using candle tensors', 'create word position and token type embeddings for input sequences using BertEmbeddings', 'test the BertEncoder forward pass with attention mask on hidden states', 'refactor BertSelfAttention to support cross-attention with separate key value inputs', 'review the BertLayer class combining attention intermediate and output sublayers', 'build a quantized LLaMA model using QuantizedLlama class with hyperparameters and quantized tensors', 'create a QuantizedLayer transformer block with attention weights and feed-forward network tensors', 'run a forward pass through QuantizedLlama model with token tensor and position index', 'precompute frequency cosines and sines for rotary positional embeddings using precompute_freqs_cis', 'apply RMS normalization to a tensor using the RmsNorm module with quantized weight']
```

Usage

```
{'build_bert_model': 'build a BERT model with custom config for sequence classification using candle tensors', 'create_bert_embeddings': 'create word position and token type embeddings for input sequences using BertEmbeddings', 'test_bert_encoder': 'test the BertEncoder forward pass with attention mask on hidden states', 'refactor_bert_self_attention': 'refactor BertSelfAttention to support cross-attention with separate key value inputs', 'review_bert_layer': 'review the BertLayer class combining attention intermediate and output sublayers'}
```

## File: huggingface_candle/candle-pyo3/py_src/candle/models/llama.py

Prompts

```
['build a BERT model with custom config for sequence classification using candle tensors', 'create word position and token type embeddings for input sequences using BertEmbeddings', 'test the BertEncoder forward pass with attention mask on hidden states', 'refactor BertSelfAttention to support cross-attention with separate key value inputs', 'review the BertLayer class combining attention intermediate and output sublayers', 'build a quantized LLaMA model using QuantizedLlama class with hyperparameters and quantized tensors', 'create a QuantizedLayer transformer block with attention weights and feed-forward network tensors', 'run a forward pass through QuantizedLlama model with token tensor and position index', 'precompute frequency cosines and sines for rotary positional embeddings using precompute_freqs_cis', 'apply RMS normalization to a tensor using the RmsNorm module with quantized weight']
```

Usage

```
{'build_quantized_llama_model': 'build a quantized LLaMA model using QuantizedLlama class with hyperparameters and quantized tensors', 'create_llama_layer': 'create a QuantizedLayer transformer block with attention weights and feed-forward network tensors', 'run_llama_forward_pass': 'run a forward pass through QuantizedLlama model with token tensor and position index', 'precompute_rotary_embeddings': 'precompute frequency cosines and sines for rotary positional embeddings using precompute_freqs_cis', 'apply_rms_norm': 'apply RMS normalization to a tensor using the RmsNorm module with quantized weight'}
```

