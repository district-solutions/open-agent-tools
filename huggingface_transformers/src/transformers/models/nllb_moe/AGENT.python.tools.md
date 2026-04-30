# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/nllb_moe/convert_nllb_moe_sharded_original_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq NLLB-MoE sharded checkpoint to HuggingFace PyTorch format using CLI arguments', 'shard MoE checkpoint weights into PyTorch bin files with an index and metadata JSON', 'rename fairseq state dict keys to HuggingFace NLLB-MoE naming conventions', 'remove ignored keys like version strings and float tensors from a state dict', "create a Linear layer from an embedding layer's weight matrix", 'build an NLLB-MoE seq2seq model with top-2 expert routing and sparse MLP layers for translation', 'create an NLLB-MoE model with language modeling head for conditional text generation', 'test the top-2 router that assigns tokens to experts using softmax probabilities and expert capacity', 'review the auxiliary load balancing loss function that penalizes unbalanced expert routing', 'summarize the sparse MLP module combining the top-2 router with a dictionary of expert feedforward networks']
```

Usage

```
{'convert_nllb_moe_checkpoint': 'convert a fairseq NLLB-MoE sharded checkpoint to HuggingFace PyTorch format using CLI arguments', 'shard_moe_weights': 'shard MoE checkpoint weights into PyTorch bin files with an index and metadata JSON', 'rename_fairseq_keys': 'rename fairseq state dict keys to HuggingFace NLLB-MoE naming conventions', 'remove_ignore_keys': 'remove ignored keys like version strings and float tensors from a state dict', 'create_linear_from_embedding': "create a Linear layer from an embedding layer's weight matrix"}
```

## File: huggingface_transformers/src/transformers/models/nllb_moe/modeling_nllb_moe.py

Prompts

```
['convert a fairseq NLLB-MoE sharded checkpoint to HuggingFace PyTorch format using CLI arguments', 'shard MoE checkpoint weights into PyTorch bin files with an index and metadata JSON', 'rename fairseq state dict keys to HuggingFace NLLB-MoE naming conventions', 'remove ignored keys like version strings and float tensors from a state dict', "create a Linear layer from an embedding layer's weight matrix", 'build an NLLB-MoE seq2seq model with top-2 expert routing and sparse MLP layers for translation', 'create an NLLB-MoE model with language modeling head for conditional text generation', 'test the top-2 router that assigns tokens to experts using softmax probabilities and expert capacity', 'review the auxiliary load balancing loss function that penalizes unbalanced expert routing', 'summarize the sparse MLP module combining the top-2 router with a dictionary of expert feedforward networks']
```

Usage

```
{'build_nllb_moe_model': 'build an NLLB-MoE seq2seq model with top-2 expert routing and sparse MLP layers for translation', 'create_conditional_generation': 'create an NLLB-MoE model with language modeling head for conditional text generation', 'test_top2_router': 'test the top-2 router that assigns tokens to experts using softmax probabilities and expert capacity', 'review_load_balancing_loss': 'review the auxiliary load balancing loss function that penalizes unbalanced expert routing', 'summarize_sparse_mlp': 'summarize the sparse MLP module combining the top-2 router with a dictionary of expert feedforward networks'}
```

