# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/truncated_bptt/transformer_xl_model.py

Prompts

```
['build a Transformer-XL language model using fairseq with configurable memory length and cutoffs', 'create a TransformerXLConfig dataclass with d_model, n_head, n_layer, and dropout settings', 'run the TransformerXLDecoder forward pass with source tokens and optional incremental state', 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with checkpoint activations', 'refactor the TransformerXLDecoder reorder_incremental_state method to handle beam search memory reordering', 'build a fairseq task for truncated BPTT language model training with configurable tokens per sample', 'create a TruncatedBPTTDataset that shards data across GPUs for distributed truncated BPTT training', 'load a train valid or test dataset split using TokenBlockDataset with configurable block size', 'run language model inference with prefix tokens and bos token using the SequenceGenerator', 'review the _collate_fn method that shifts tokens and creates source target pairs for BPTT training']
```

Usage

```
{'build_transformer_xl_model': 'build a Transformer-XL language model using fairseq with configurable memory length and cutoffs', 'create_transformer_xl_config': 'create a TransformerXLConfig dataclass with d_model, n_head, n_layer, and dropout settings', 'run_transformer_xl_forward': 'run the TransformerXLDecoder forward pass with source tokens and optional incremental state', 'review_transformer_xl_decoder': 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with checkpoint activations', 'refactor_reorder_incremental_state': 'refactor the TransformerXLDecoder reorder_incremental_state method to handle beam search memory reordering'}
```

## File: facebookresearch_fairseq/examples/truncated_bptt/truncated_bptt_lm_task.py

Prompts

```
['build a Transformer-XL language model using fairseq with configurable memory length and cutoffs', 'create a TransformerXLConfig dataclass with d_model, n_head, n_layer, and dropout settings', 'run the TransformerXLDecoder forward pass with source tokens and optional incremental state', 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with checkpoint activations', 'refactor the TransformerXLDecoder reorder_incremental_state method to handle beam search memory reordering', 'build a fairseq task for truncated BPTT language model training with configurable tokens per sample', 'create a TruncatedBPTTDataset that shards data across GPUs for distributed truncated BPTT training', 'load a train valid or test dataset split using TokenBlockDataset with configurable block size', 'run language model inference with prefix tokens and bos token using the SequenceGenerator', 'review the _collate_fn method that shifts tokens and creates source target pairs for BPTT training']
```

Usage

```
{'build_truncated_bptt_lm_task': 'build a fairseq task for truncated BPTT language model training with configurable tokens per sample', 'create_truncated_bptt_dataset': 'create a TruncatedBPTTDataset that shards data across GPUs for distributed truncated BPTT training', 'load_dataset_truncated_bptt': 'load a train valid or test dataset split using TokenBlockDataset with configurable block size', 'run_inference_truncated_bptt_lm': 'run language model inference with prefix tokens and bos token using the SequenceGenerator', 'review_collate_fn': 'review the _collate_fn method that shifts tokens and creates source target pairs for BPTT training'}
```

