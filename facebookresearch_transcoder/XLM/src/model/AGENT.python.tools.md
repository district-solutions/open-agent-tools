# Agent Python Tools

- repo: facebookresearch/transcoder
- repo_uri: https://github.com/facebookresearch/transcoder

## File: facebookresearch_transcoder/XLM/src/model/embedder.py

Prompts

```
['reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'get single-vector sentence embeddings from tokenized input tensors using the embedder', 'get trainable parameters for a specified layer range of the transformer model', 'set the SentenceEmbedder model to training mode for fine-tuning', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'review the pretrain module functions for loading fastText and text-based word embeddings', 'create an initialized PyTorch Embedding layer with normal weight initialization and optional padding index', 'create sinusoidal positional embeddings for a given number of positions and embedding dimension', 'generate padding and causal attention masks for transformer encoder or decoder forward passes', 'run a forward pass through the TransformerModel encoder or decoder with optional source encoding and caching', 'generate a translated or continued sentence using greedy or temperature-sampled autoregressive decoding with encoder context']
```

Usage

```
{'reload_SentenceEmbedder': 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'get_embeddings': 'get single-vector sentence embeddings from tokenized input tensors using the embedder', 'get_parameters': 'get trainable parameters for a specified layer range of the transformer model', 'train_SentenceEmbedder': 'set the SentenceEmbedder model to training mode for fine-tuning', 'eval_SentenceEmbedder': 'set the SentenceEmbedder model to evaluation mode for inference'}
```

## File: facebookresearch_transcoder/XLM/src/model/pretrain.py

Prompts

```
['reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'get single-vector sentence embeddings from tokenized input tensors using the embedder', 'get trainable parameters for a specified layer range of the transformer model', 'set the SentenceEmbedder model to training mode for fine-tuning', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'review the pretrain module functions for loading fastText and text-based word embeddings', 'create an initialized PyTorch Embedding layer with normal weight initialization and optional padding index', 'create sinusoidal positional embeddings for a given number of positions and embedding dimension', 'generate padding and causal attention masks for transformer encoder or decoder forward passes', 'run a forward pass through the TransformerModel encoder or decoder with optional source encoding and caching', 'generate a translated or continued sentence using greedy or temperature-sampled autoregressive decoding with encoder context']
```

Usage

```
{'load_embeddings': 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'read_txt_embeddings': 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load_bin_embeddings': 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'load_fasttext_model': 'load a binarized fastText model from a file path using the fastText Python library', 'review_pretrain': 'review the pretrain module functions for loading fastText and text-based word embeddings'}
```

## File: facebookresearch_transcoder/XLM/src/model/transformer.py

Prompts

```
['reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'get single-vector sentence embeddings from tokenized input tensors using the embedder', 'get trainable parameters for a specified layer range of the transformer model', 'set the SentenceEmbedder model to training mode for fine-tuning', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'review the pretrain module functions for loading fastText and text-based word embeddings', 'create an initialized PyTorch Embedding layer with normal weight initialization and optional padding index', 'create sinusoidal positional embeddings for a given number of positions and embedding dimension', 'generate padding and causal attention masks for transformer encoder or decoder forward passes', 'run a forward pass through the TransformerModel encoder or decoder with optional source encoding and caching', 'generate a translated or continued sentence using greedy or temperature-sampled autoregressive decoding with encoder context']
```

Usage

```
{'create_embedding_layer': 'create an initialized PyTorch Embedding layer with normal weight initialization and optional padding index', 'create_sinusoidal_positional_embeddings': 'create sinusoidal positional embeddings for a given number of positions and embedding dimension', 'generate_attention_masks': 'generate padding and causal attention masks for transformer encoder or decoder forward passes', 'run_transformer_forward_pass': 'run a forward pass through the TransformerModel encoder or decoder with optional source encoding and caching', 'generate_sentence_autoregressively': 'generate a translated or continued sentence using greedy or temperature-sampled autoregressive decoding with encoder context'}
```

