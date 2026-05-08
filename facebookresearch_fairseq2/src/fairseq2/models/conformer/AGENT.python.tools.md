# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/conformer/block.py

Prompts

```
['build a ConformerBlock instance with feed-forward networks, self-attention, and convolution modules', 'run the forward pass of a ConformerBlock on sequence tensors with batch layout and attention bias cache', 'review the ConformerBlock _forward_ffn1 method that applies macaron-style feed-forward network with 0.5 scaling and residual connection', 'review the ConformerBlock _forward_self_attn method that applies multihead self-attention with layer normalization and residual connection', 'review the ConformerBlock _forward_conv method that applies conformer convolution with layer normalization and residual connection', 'create a ConformerConvolution module with a specified model dimension and depthwise kernel size', 'build a ConformerConvolution module with causal depthwise convolution enabled for autoregressive sequence processing', 'test the ConformerConvolution forward pass with a batch of sequences and a BatchLayout', 'refactor the ConformerConvolution to switch between batch_norm and layer_norm normalization types', 'review the ConformerConvolution depthwise activation and customize it with a different activation module']
```

Usage

```
{'build_ConformerBlock': 'build a ConformerBlock instance with feed-forward networks, self-attention, and convolution modules', 'run_ConformerBlock_forward': 'run the forward pass of a ConformerBlock on sequence tensors with batch layout and attention bias cache', 'review_ConformerBlock_forward_ffn1': 'review the ConformerBlock _forward_ffn1 method that applies macaron-style feed-forward network with 0.5 scaling and residual connection', 'review_ConformerBlock_forward_self_attn': 'review the ConformerBlock _forward_self_attn method that applies multihead self-attention with layer normalization and residual connection', 'review_ConformerBlock_forward_conv': 'review the ConformerBlock _forward_conv method that applies conformer convolution with layer normalization and residual connection'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/conformer/convolution.py

Prompts

```
['build a ConformerBlock instance with feed-forward networks, self-attention, and convolution modules', 'run the forward pass of a ConformerBlock on sequence tensors with batch layout and attention bias cache', 'review the ConformerBlock _forward_ffn1 method that applies macaron-style feed-forward network with 0.5 scaling and residual connection', 'review the ConformerBlock _forward_self_attn method that applies multihead self-attention with layer normalization and residual connection', 'review the ConformerBlock _forward_conv method that applies conformer convolution with layer normalization and residual connection', 'create a ConformerConvolution module with a specified model dimension and depthwise kernel size', 'build a ConformerConvolution module with causal depthwise convolution enabled for autoregressive sequence processing', 'test the ConformerConvolution forward pass with a batch of sequences and a BatchLayout', 'refactor the ConformerConvolution to switch between batch_norm and layer_norm normalization types', 'review the ConformerConvolution depthwise activation and customize it with a different activation module']
```

Usage

```
{'create_conformer_convolution_module': 'create a ConformerConvolution module with a specified model dimension and depthwise kernel size', 'build_causal_conformer_convolution': 'build a ConformerConvolution module with causal depthwise convolution enabled for autoregressive sequence processing', 'test_conformer_convolution_forward': 'test the ConformerConvolution forward pass with a batch of sequences and a BatchLayout', 'refactor_conformer_convolution_norm': 'refactor the ConformerConvolution to switch between batch_norm and layer_norm normalization types', 'review_conformer_convolution_depthwise_activation': 'review the ConformerConvolution depthwise activation and customize it with a different activation module'}
```

