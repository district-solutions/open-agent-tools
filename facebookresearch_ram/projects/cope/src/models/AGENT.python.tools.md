# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cope/src/models/base.py

Prompts

```
['build a value head MLP with configurable layers and embedding dimension for value estimation', 'build a single linear layer value head with zero-initialized weights and biases', 'create a subclass of the abstract Model class implementing forward and generate methods', 'review the abstract Model forward method signature for tensor input and optional pad mask', 'review the abstract Model generate method for list of tensor prompts and train mode', 'create a RelPosEmb module with emb_dim, past_len, and optional npos_max parameters for relative position embeddings', 'run the RelPosEmb forward pass with query and key tensors to compute relative position logits', 'test the rel2abs function to convert relative position tensors to absolute position format', 'review the RelPosEmb extend mode that pads position logits using replicate padding for far away positions', 'refactor the rel2abs function to handle the L equals 1 case currently marked as not implemented', 'build a TransformerDecoder model with configurable layers, hidden size, heads, and position embeddings', 'generate new tokens from a list of prompt tensors using greedy or sampled decoding', 'add transformer decoder arguments like nlayers, hid-sz, nheads, and pos-emb to an ArgumentParser', 'preprocess a config object to set default ff-sz and head-dim values', 'review the TransformerDecoder forward pass that computes log-probabilities over the vocabulary', 'build a Transformer encoder using EncoderCore with config for self-attention layers and padding masks', 'build a Transformer decoder using DecoderCore with optional encoder output for cross-attention', 'create a MultiHeadAttn module with CPE or standard self-attention and key-value caching for generation', 'create a Feedforward module with two linear layers, ReLU activation, and dropout for Transformer blocks', 'create an attention mask from padding masks using pad2attn_mask for self or cross-attention']
```

Usage

```
{'build_value_head_mlp': 'build a value head MLP with configurable layers and embedding dimension for value estimation', 'build_value_head_linear': 'build a single linear layer value head with zero-initialized weights and biases', 'create_model_subclass': 'create a subclass of the abstract Model class implementing forward and generate methods', 'review_model_forward': 'review the abstract Model forward method signature for tensor input and optional pad mask', 'review_model_generate': 'review the abstract Model generate method for list of tensor prompts and train mode'}
```

## File: facebookresearch_ram/projects/cope/src/models/relative_position.py

Prompts

```
['build a value head MLP with configurable layers and embedding dimension for value estimation', 'build a single linear layer value head with zero-initialized weights and biases', 'create a subclass of the abstract Model class implementing forward and generate methods', 'review the abstract Model forward method signature for tensor input and optional pad mask', 'review the abstract Model generate method for list of tensor prompts and train mode', 'create a RelPosEmb module with emb_dim, past_len, and optional npos_max parameters for relative position embeddings', 'run the RelPosEmb forward pass with query and key tensors to compute relative position logits', 'test the rel2abs function to convert relative position tensors to absolute position format', 'review the RelPosEmb extend mode that pads position logits using replicate padding for far away positions', 'refactor the rel2abs function to handle the L equals 1 case currently marked as not implemented', 'build a TransformerDecoder model with configurable layers, hidden size, heads, and position embeddings', 'generate new tokens from a list of prompt tensors using greedy or sampled decoding', 'add transformer decoder arguments like nlayers, hid-sz, nheads, and pos-emb to an ArgumentParser', 'preprocess a config object to set default ff-sz and head-dim values', 'review the TransformerDecoder forward pass that computes log-probabilities over the vocabulary', 'build a Transformer encoder using EncoderCore with config for self-attention layers and padding masks', 'build a Transformer decoder using DecoderCore with optional encoder output for cross-attention', 'create a MultiHeadAttn module with CPE or standard self-attention and key-value caching for generation', 'create a Feedforward module with two linear layers, ReLU activation, and dropout for Transformer blocks', 'create an attention mask from padding masks using pad2attn_mask for self or cross-attention']
```

Usage

```
{'create_RelPosEmb': 'create a RelPosEmb module with emb_dim, past_len, and optional npos_max parameters for relative position embeddings', 'run_RelPosEmb_forward': 'run the RelPosEmb forward pass with query and key tensors to compute relative position logits', 'test_rel2abs': 'test the rel2abs function to convert relative position tensors to absolute position format', 'review_RelPosEmb_extend': 'review the RelPosEmb extend mode that pads position logits using replicate padding for far away positions', 'refactor_rel2abs': 'refactor the rel2abs function to handle the L equals 1 case currently marked as not implemented'}
```

## File: facebookresearch_ram/projects/cope/src/models/simple_transformer.py

Prompts

```
['build a value head MLP with configurable layers and embedding dimension for value estimation', 'build a single linear layer value head with zero-initialized weights and biases', 'create a subclass of the abstract Model class implementing forward and generate methods', 'review the abstract Model forward method signature for tensor input and optional pad mask', 'review the abstract Model generate method for list of tensor prompts and train mode', 'create a RelPosEmb module with emb_dim, past_len, and optional npos_max parameters for relative position embeddings', 'run the RelPosEmb forward pass with query and key tensors to compute relative position logits', 'test the rel2abs function to convert relative position tensors to absolute position format', 'review the RelPosEmb extend mode that pads position logits using replicate padding for far away positions', 'refactor the rel2abs function to handle the L equals 1 case currently marked as not implemented', 'build a TransformerDecoder model with configurable layers, hidden size, heads, and position embeddings', 'generate new tokens from a list of prompt tensors using greedy or sampled decoding', 'add transformer decoder arguments like nlayers, hid-sz, nheads, and pos-emb to an ArgumentParser', 'preprocess a config object to set default ff-sz and head-dim values', 'review the TransformerDecoder forward pass that computes log-probabilities over the vocabulary', 'build a Transformer encoder using EncoderCore with config for self-attention layers and padding masks', 'build a Transformer decoder using DecoderCore with optional encoder output for cross-attention', 'create a MultiHeadAttn module with CPE or standard self-attention and key-value caching for generation', 'create a Feedforward module with two linear layers, ReLU activation, and dropout for Transformer blocks', 'create an attention mask from padding masks using pad2attn_mask for self or cross-attention']
```

Usage

```
{'build_transformer_decoder': 'build a TransformerDecoder model with configurable layers, hidden size, heads, and position embeddings', 'generate_text_from_prompts': 'generate new tokens from a list of prompt tensors using greedy or sampled decoding', 'add_args_parser': 'add transformer decoder arguments like nlayers, hid-sz, nheads, and pos-emb to an ArgumentParser', 'preprocess_config_defaults': 'preprocess a config object to set default ff-sz and head-dim values', 'review_forward_pass': 'review the TransformerDecoder forward pass that computes log-probabilities over the vocabulary'}
```

## File: facebookresearch_ram/projects/cope/src/models/transformer.py

Prompts

```
['build a value head MLP with configurable layers and embedding dimension for value estimation', 'build a single linear layer value head with zero-initialized weights and biases', 'create a subclass of the abstract Model class implementing forward and generate methods', 'review the abstract Model forward method signature for tensor input and optional pad mask', 'review the abstract Model generate method for list of tensor prompts and train mode', 'create a RelPosEmb module with emb_dim, past_len, and optional npos_max parameters for relative position embeddings', 'run the RelPosEmb forward pass with query and key tensors to compute relative position logits', 'test the rel2abs function to convert relative position tensors to absolute position format', 'review the RelPosEmb extend mode that pads position logits using replicate padding for far away positions', 'refactor the rel2abs function to handle the L equals 1 case currently marked as not implemented', 'build a TransformerDecoder model with configurable layers, hidden size, heads, and position embeddings', 'generate new tokens from a list of prompt tensors using greedy or sampled decoding', 'add transformer decoder arguments like nlayers, hid-sz, nheads, and pos-emb to an ArgumentParser', 'preprocess a config object to set default ff-sz and head-dim values', 'review the TransformerDecoder forward pass that computes log-probabilities over the vocabulary', 'build a Transformer encoder using EncoderCore with config for self-attention layers and padding masks', 'build a Transformer decoder using DecoderCore with optional encoder output for cross-attention', 'create a MultiHeadAttn module with CPE or standard self-attention and key-value caching for generation', 'create a Feedforward module with two linear layers, ReLU activation, and dropout for Transformer blocks', 'create an attention mask from padding masks using pad2attn_mask for self or cross-attention']
```

Usage

```
{'build_encoder_core': 'build a Transformer encoder using EncoderCore with config for self-attention layers and padding masks', 'build_decoder_core': 'build a Transformer decoder using DecoderCore with optional encoder output for cross-attention', 'create_multihead_attention': 'create a MultiHeadAttn module with CPE or standard self-attention and key-value caching for generation', 'create_feedforward_layer': 'create a Feedforward module with two linear layers, ReLU activation, and dropout for Transformer blocks', 'create_attention_mask': 'create an attention mask from padding masks using pad2attn_mask for self or cross-attention'}
```

