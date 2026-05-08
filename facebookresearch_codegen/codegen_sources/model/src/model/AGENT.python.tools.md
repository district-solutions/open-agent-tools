# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/model/src/model/cape_embeddings.py

Prompts

```
['create a CAPE1d module with a given d_model dimension for continuous positional embeddings', 'run the CAPE1d forward pass to add positional embeddings to input tensor x', 'compute positional embeddings from input tensor x with optional x_lengths and positions_delta', 'augment positions with random global shift, local shift, and scaling during training', 'review the CAPE1d class for continuous positional encoding with augmentation support', 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'create a SentenceEmbedder instance wrapping a TransformerModel with dictionary and pretrain params', 'get single-vector sentence representations from input tensors using the transformer model', 'get trainable parameters for a specified range of transformer layers by layer_range string', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'review the load_embeddings function to understand how it dispatches between text and binary embedding loaders', 'build a TransformerModel encoder or decoder with configurable layers, heads, and embedding dimensions', 'generate text sequences using greedy or sampled decoding with optional source encoder context', 'generate text using beam search decoding with configurable beam size and length penalty', 'create a MultiHeadAttention layer with optional xformers efficient attention for self or cross attention', 'create a TransformerFFN feed-forward network with configurable hidden dimension and gelu or relu activation']
```

Usage

```
{'create_CAPE1d_embeddings': 'create a CAPE1d module with a given d_model dimension for continuous positional embeddings', 'run_CAPE1d_forward': 'run the CAPE1d forward pass to add positional embeddings to input tensor x', 'compute_CAPE1d_pos_emb': 'compute positional embeddings from input tensor x with optional x_lengths and positions_delta', 'augment_CAPE1d_positions': 'augment positions with random global shift, local shift, and scaling during training', 'review_CAPE1d_class': 'review the CAPE1d class for continuous positional encoding with augmentation support'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/model/embedder.py

Prompts

```
['create a CAPE1d module with a given d_model dimension for continuous positional embeddings', 'run the CAPE1d forward pass to add positional embeddings to input tensor x', 'compute positional embeddings from input tensor x with optional x_lengths and positions_delta', 'augment positions with random global shift, local shift, and scaling during training', 'review the CAPE1d class for continuous positional encoding with augmentation support', 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'create a SentenceEmbedder instance wrapping a TransformerModel with dictionary and pretrain params', 'get single-vector sentence representations from input tensors using the transformer model', 'get trainable parameters for a specified range of transformer layers by layer_range string', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'review the load_embeddings function to understand how it dispatches between text and binary embedding loaders', 'build a TransformerModel encoder or decoder with configurable layers, heads, and embedding dimensions', 'generate text sequences using greedy or sampled decoding with optional source encoder context', 'generate text using beam search decoding with configurable beam size and length penalty', 'create a MultiHeadAttention layer with optional xformers efficient attention for self or cross attention', 'create a TransformerFFN feed-forward network with configurable hidden dimension and gelu or relu activation']
```

Usage

```
{'reload_sentence_embedder': 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'create_sentence_embedder': 'create a SentenceEmbedder instance wrapping a TransformerModel with dictionary and pretrain params', 'get_embeddings': 'get single-vector sentence representations from input tensors using the transformer model', 'get_parameters': 'get trainable parameters for a specified range of transformer layers by layer_range string', 'set_eval_mode': 'set the SentenceEmbedder model to evaluation mode for inference'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/model/pretrain.py

Prompts

```
['create a CAPE1d module with a given d_model dimension for continuous positional embeddings', 'run the CAPE1d forward pass to add positional embeddings to input tensor x', 'compute positional embeddings from input tensor x with optional x_lengths and positions_delta', 'augment positions with random global shift, local shift, and scaling during training', 'review the CAPE1d class for continuous positional encoding with augmentation support', 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'create a SentenceEmbedder instance wrapping a TransformerModel with dictionary and pretrain params', 'get single-vector sentence representations from input tensors using the transformer model', 'get trainable parameters for a specified range of transformer layers by layer_range string', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'review the load_embeddings function to understand how it dispatches between text and binary embedding loaders', 'build a TransformerModel encoder or decoder with configurable layers, heads, and embedding dimensions', 'generate text sequences using greedy or sampled decoding with optional source encoder context', 'generate text using beam search decoding with configurable beam size and length penalty', 'create a MultiHeadAttention layer with optional xformers efficient attention for self or cross attention', 'create a TransformerFFN feed-forward network with configurable hidden dimension and gelu or relu activation']
```

Usage

```
{'load_embeddings': 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'load_fasttext_model': 'load a binarized fastText model from a file path using the fastText Python library', 'read_txt_embeddings': 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load_bin_embeddings': 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'review_load_embeddings': 'review the load_embeddings function to understand how it dispatches between text and binary embedding loaders'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/model/transformer.py

Prompts

```
['create a CAPE1d module with a given d_model dimension for continuous positional embeddings', 'run the CAPE1d forward pass to add positional embeddings to input tensor x', 'compute positional embeddings from input tensor x with optional x_lengths and positions_delta', 'augment positions with random global shift, local shift, and scaling during training', 'review the CAPE1d class for continuous positional encoding with augmentation support', 'reload a pretrained SentenceEmbedder model from a checkpoint path and params', 'create a SentenceEmbedder instance wrapping a TransformerModel with dictionary and pretrain params', 'get single-vector sentence representations from input tensors using the transformer model', 'get trainable parameters for a specified range of transformer layers by layer_range string', 'set the SentenceEmbedder model to evaluation mode for inference', 'load pretrained word embeddings from a text or binary fastText file into a PyTorch tensor', 'load a binarized fastText model from a file path using the fastText Python library', 'read pretrained word embeddings from a plain text file and return a word-to-id map and tensor', 'load pretrained word embeddings from a fastText binary model file and return a word-to-id map and tensor', 'review the load_embeddings function to understand how it dispatches between text and binary embedding loaders', 'build a TransformerModel encoder or decoder with configurable layers, heads, and embedding dimensions', 'generate text sequences using greedy or sampled decoding with optional source encoder context', 'generate text using beam search decoding with configurable beam size and length penalty', 'create a MultiHeadAttention layer with optional xformers efficient attention for self or cross attention', 'create a TransformerFFN feed-forward network with configurable hidden dimension and gelu or relu activation']
```

Usage

```
{'build_TransformerModel': 'build a TransformerModel encoder or decoder with configurable layers, heads, and embedding dimensions', 'generate_TransformerModel_generate': 'generate text sequences using greedy or sampled decoding with optional source encoder context', 'generate_TransformerModel_generate_beam': 'generate text using beam search decoding with configurable beam size and length penalty', 'create_MultiHeadAttention': 'create a MultiHeadAttention layer with optional xformers efficient attention for self or cross attention', 'create_TransformerFFN': 'create a TransformerFFN feed-forward network with configurable hidden dimension and gelu or relu activation'}
```

