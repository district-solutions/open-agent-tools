# Agent Python Tools

- repo: facebookresearch/longseqmae
- repo_uri: https://github.com/facebookresearch/long_seq_mae

## File: facebookresearch_longseqmae/tools/convert_model_ckpt_k_bias.py

Prompts

```
['convert a model state dict by merging q_bias and v_bias into qkv.bias with a zero k_bias', 'convert a model state dict by splitting qkv.bias into separate q_bias and v_bias tensors', 'run the script to add k_bias to a PyTorch checkpoint by merging q and v bias into qkv.bias', 'run the script to remove k_bias from a PyTorch checkpoint by splitting qkv.bias into q and v bias', 'review the convert_model_state_dict function for merging or splitting attention bias tensors in a model checkpoint']
```

Usage

```
{'convert_model_state_dict_add_k_bias': 'convert a model state dict by merging q_bias and v_bias into qkv.bias with a zero k_bias', 'convert_model_state_dict_remove_k_bias': 'convert a model state dict by splitting qkv.bias into separate q_bias and v_bias tensors', 'run_convert_ckpt_add_k_bias': 'run the script to add k_bias to a PyTorch checkpoint by merging q and v bias into qkv.bias', 'run_convert_ckpt_remove_k_bias': 'run the script to remove k_bias from a PyTorch checkpoint by splitting qkv.bias into q and v bias', 'review_convert_model_state_dict': 'review the convert_model_state_dict function for merging or splitting attention bias tensors in a model checkpoint'}
```

