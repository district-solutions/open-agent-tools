# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/truncated_bptt/transformer_xl_model.py

Prompts

```
['build a Transformer-XL language model using TransformerXLLanguageModel.build_model with a config and task', 'create a TransformerXLConfig dataclass to set d_model, n_head, n_layer, and dropout hyperparameters', 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with memory handling', 'refactor the reorder_incremental_state method to reorder memory tensors during beam search decoding', 'build a fairseq task that loads a dictionary and configures truncated BPTT language model training', 'load a dataset split wrapped in TokenBlockDataset and TruncatedBPTTDataset for truncated BPTT training', 'get an EpochBatchIterator with a custom collate function for truncated BPTT batches', 'run inference generation with prefix tokens and a BOS token using the SequenceGenerator', 'create a TruncatedBPTTDataset that shards data across GPUs for parallel truncated BPTT training']
```

Usage

```
{'build_transformer_xl_model': 'build a Transformer-XL language model using TransformerXLLanguageModel.build_model with a config and task', 'create_transformer_xl_config': 'create a TransformerXLConfig dataclass to set d_model, n_head, n_layer, and dropout hyperparameters', 'run_transformer_xl_forward': 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review_transformer_xl_decoder': 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with memory handling', 'refactor_reorder_incremental_state': 'refactor the reorder_incremental_state method to reorder memory tensors during beam search decoding'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/truncated_bptt/truncated_bptt_lm_task.py

Prompts

```
['build a Transformer-XL language model using TransformerXLLanguageModel.build_model with a config and task', 'create a TransformerXLConfig dataclass to set d_model, n_head, n_layer, and dropout hyperparameters', 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review the TransformerXLDecoder class that wraps HuggingFace TransfoXLLMHeadModel with memory handling', 'refactor the reorder_incremental_state method to reorder memory tensors during beam search decoding', 'build a fairseq task that loads a dictionary and configures truncated BPTT language model training', 'load a dataset split wrapped in TokenBlockDataset and TruncatedBPTTDataset for truncated BPTT training', 'get an EpochBatchIterator with a custom collate function for truncated BPTT batches', 'run inference generation with prefix tokens and a BOS token using the SequenceGenerator', 'create a TruncatedBPTTDataset that shards data across GPUs for parallel truncated BPTT training']
```

Usage

```
{'build_truncated_bptt_lm_task': 'build a fairseq task that loads a dictionary and configures truncated BPTT language model training', 'load_dataset_truncated_bptt': 'load a dataset split wrapped in TokenBlockDataset and TruncatedBPTTDataset for truncated BPTT training', 'get_batch_iterator_truncated_bptt': 'get an EpochBatchIterator with a custom collate function for truncated BPTT batches', 'inference_step_generate': 'run inference generation with prefix tokens and a BOS token using the SequenceGenerator', 'create_truncated_bptt_dataset': 'create a TruncatedBPTTDataset that shards data across GPUs for parallel truncated BPTT training'}
```

