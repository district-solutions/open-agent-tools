# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/truncated_bptt/transformer_xl_model.py

Prompts

```
['build a Transformer-XL language model using the TransformerXLLanguageModel build_model class method', 'create a TransformerXLConfig dataclass with custom hyperparameters like d_model, n_head, and n_layer', 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review the TransformerXLDecoder init to understand HuggingFace TransfoXLLMHeadModel integration and checkpoint wrapping', 'reorder the TransformerXLDecoder incremental state mems tensor for beam search decoding', 'build a fairseq task using TruncatedBPTTLMTask to train a language model with truncated backpropagation through time', 'create a TruncatedBPTTDataset to shard token sequences across multiple GPUs for distributed training', 'load a train valid or test dataset split using TruncatedBPTTLMTask load_dataset method with token blocking', 'run language model inference using TruncatedBPTTLMTask inference_step with prefix tokens and a sequence generator', 'review the TruncatedBPTTLMTask _collate_fn method that shifts tokens and pads targets for language modeling']
```

Usage

```
{'build_transformer_xl_model': 'build a Transformer-XL language model using the TransformerXLLanguageModel build_model class method', 'create_transformer_xl_config': 'create a TransformerXLConfig dataclass with custom hyperparameters like d_model, n_head, and n_layer', 'run_transformer_xl_forward': 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review_transformer_xl_decoder_init': 'review the TransformerXLDecoder init to understand HuggingFace TransfoXLLMHeadModel integration and checkpoint wrapping', 'reorder_transformer_xl_incremental_state': 'reorder the TransformerXLDecoder incremental state mems tensor for beam search decoding'}
```

## File: facebookresearch_avhubert/fairseq/examples/truncated_bptt/truncated_bptt_lm_task.py

Prompts

```
['build a Transformer-XL language model using the TransformerXLLanguageModel build_model class method', 'create a TransformerXLConfig dataclass with custom hyperparameters like d_model, n_head, and n_layer', 'run the TransformerXLDecoder forward pass with src_tokens and optional incremental state for inference', 'review the TransformerXLDecoder init to understand HuggingFace TransfoXLLMHeadModel integration and checkpoint wrapping', 'reorder the TransformerXLDecoder incremental state mems tensor for beam search decoding', 'build a fairseq task using TruncatedBPTTLMTask to train a language model with truncated backpropagation through time', 'create a TruncatedBPTTDataset to shard token sequences across multiple GPUs for distributed training', 'load a train valid or test dataset split using TruncatedBPTTLMTask load_dataset method with token blocking', 'run language model inference using TruncatedBPTTLMTask inference_step with prefix tokens and a sequence generator', 'review the TruncatedBPTTLMTask _collate_fn method that shifts tokens and pads targets for language modeling']
```

Usage

```
{'build_truncated_bptt_lm_task': 'build a fairseq task using TruncatedBPTTLMTask to train a language model with truncated backpropagation through time', 'create_truncated_bptt_dataset': 'create a TruncatedBPTTDataset to shard token sequences across multiple GPUs for distributed training', 'load_dataset_split': 'load a train valid or test dataset split using TruncatedBPTTLMTask load_dataset method with token blocking', 'run_inference_step': 'run language model inference using TruncatedBPTTLMTask inference_step with prefix tokens and a sequence generator', 'review_collate_fn': 'review the TruncatedBPTTLMTask _collate_fn method that shifts tokens and pads targets for language modeling'}
```

