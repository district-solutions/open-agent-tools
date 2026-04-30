# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bloom/convert_bloom_original_checkpoint_to_pytorch.py

Prompts

```
['convert a Megatron-LM BLOOM checkpoint to a PyTorch HuggingFace model checkpoint', 'convert a sharded Megatron-LM BLOOM checkpoint to multiple PyTorch model shard files', 'rename Megatron-DeepSpeed layer keys to HuggingFace transformer layer names', 'calculate the size in bytes of a PyTorch dtype', 'run the BLOOM checkpoint conversion CLI with Megatron-LM checkpoint path and output directory', 'build a Bloom language model for causal language modeling with HuggingFace transformers', 'create a BloomModel forward pass that builds alibi tensors and processes attention masks', 'test the BloomAttention module with fused QKV projection and ALiBi bias computation', 'refactor the BloomMLP block to support pretraining TP splits with slow_but_exact mode', 'summarize BloomForSequenceClassification which pools last-token logits for classification']
```

Usage

```
{'convert_bloom_checkpoint_to_pytorch': 'convert a Megatron-LM BLOOM checkpoint to a PyTorch HuggingFace model checkpoint', 'convert_sharded_bloom_checkpoint': 'convert a sharded Megatron-LM BLOOM checkpoint to multiple PyTorch model shard files', 'rename_megatron_layer_keys': 'rename Megatron-DeepSpeed layer keys to HuggingFace transformer layer names', 'calculate_dtype_size_bytes': 'calculate the size in bytes of a PyTorch dtype', 'run_bloom_checkpoint_conversion_cli': 'run the BLOOM checkpoint conversion CLI with Megatron-LM checkpoint path and output directory'}
```

## File: huggingface_transformers/src/transformers/models/bloom/modeling_bloom.py

Prompts

```
['convert a Megatron-LM BLOOM checkpoint to a PyTorch HuggingFace model checkpoint', 'convert a sharded Megatron-LM BLOOM checkpoint to multiple PyTorch model shard files', 'rename Megatron-DeepSpeed layer keys to HuggingFace transformer layer names', 'calculate the size in bytes of a PyTorch dtype', 'run the BLOOM checkpoint conversion CLI with Megatron-LM checkpoint path and output directory', 'build a Bloom language model for causal language modeling with HuggingFace transformers', 'create a BloomModel forward pass that builds alibi tensors and processes attention masks', 'test the BloomAttention module with fused QKV projection and ALiBi bias computation', 'refactor the BloomMLP block to support pretraining TP splits with slow_but_exact mode', 'summarize BloomForSequenceClassification which pools last-token logits for classification']
```

Usage

```
{'build_bloom_causal_lm': 'build a Bloom language model for causal language modeling with HuggingFace transformers', 'create_bloom_model_forward': 'create a BloomModel forward pass that builds alibi tensors and processes attention masks', 'test_bloom_attention': 'test the BloomAttention module with fused QKV projection and ALiBi bias computation', 'refactor_bloom_mlp': 'refactor the BloomMLP block to support pretraining TP splits with slow_but_exact mode', 'summarize_bloom_for_sequence_classification': 'summarize BloomForSequenceClassification which pools last-token logits for classification'}
```

