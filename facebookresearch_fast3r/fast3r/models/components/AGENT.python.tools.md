# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/models/components/llama.py

Prompts

```
['build a Llama-style Transformer model from ModelArgs config with rotary embeddings and flash attention', 'create a ModelArgs dataclass to configure dim, n_layers, n_heads, vocab_size, and max_seq_len', 'run a forward pass through the Transformer with token indices to get output logits', 'apply rotary position embeddings to query and key tensors using precomputed frequency cis', 'precompute the frequency tensor for complex exponentials used in rotary positional encoding', 'build a SimpleDenseNet model with configurable layer sizes for classification tasks', 'create a SimpleDenseNet with custom input_size, lin1_size, lin2_size, lin3_size, and output_size parameters', 'run a forward pass through SimpleDenseNet with a 4D input tensor of shape (batch, channels, width, height)', 'test the SimpleDenseNet class by instantiating it with default parameters and verifying model structure', 'review the SimpleDenseNet architecture which uses three Linear layers with BatchNorm1d and ReLU activations']
```

Usage

```
{'build_transformer_model': 'build a Llama-style Transformer model from ModelArgs config with rotary embeddings and flash attention', 'create_model_args_config': 'create a ModelArgs dataclass to configure dim, n_layers, n_heads, vocab_size, and max_seq_len', 'run_transformer_forward_pass': 'run a forward pass through the Transformer with token indices to get output logits', 'apply_rotary_embeddings': 'apply rotary position embeddings to query and key tensors using precomputed frequency cis', 'precompute_frequency_cis': 'precompute the frequency tensor for complex exponentials used in rotary positional encoding'}
```

## File: facebookresearch_fast3r/fast3r/models/components/simple_dense_net.py

Prompts

```
['build a Llama-style Transformer model from ModelArgs config with rotary embeddings and flash attention', 'create a ModelArgs dataclass to configure dim, n_layers, n_heads, vocab_size, and max_seq_len', 'run a forward pass through the Transformer with token indices to get output logits', 'apply rotary position embeddings to query and key tensors using precomputed frequency cis', 'precompute the frequency tensor for complex exponentials used in rotary positional encoding', 'build a SimpleDenseNet model with configurable layer sizes for classification tasks', 'create a SimpleDenseNet with custom input_size, lin1_size, lin2_size, lin3_size, and output_size parameters', 'run a forward pass through SimpleDenseNet with a 4D input tensor of shape (batch, channels, width, height)', 'test the SimpleDenseNet class by instantiating it with default parameters and verifying model structure', 'review the SimpleDenseNet architecture which uses three Linear layers with BatchNorm1d and ReLU activations']
```

Usage

```
{'build_SimpleDenseNet': 'build a SimpleDenseNet model with configurable layer sizes for classification tasks', 'create_SimpleDenseNet_custom_sizes': 'create a SimpleDenseNet with custom input_size, lin1_size, lin2_size, lin3_size, and output_size parameters', 'run_SimpleDenseNet_forward': 'run a forward pass through SimpleDenseNet with a 4D input tensor of shape (batch, channels, width, height)', 'test_SimpleDenseNet': 'test the SimpleDenseNet class by instantiating it with default parameters and verifying model structure', 'review_SimpleDenseNet_architecture': 'review the SimpleDenseNet architecture which uses three Linear layers with BatchNorm1d and ReLU activations'}
```

