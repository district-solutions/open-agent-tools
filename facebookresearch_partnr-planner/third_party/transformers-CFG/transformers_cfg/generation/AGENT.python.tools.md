# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/transformers-CFG/transformers_cfg/generation/logits_process.py

Prompts

```
['create a GrammarConstrainedLogitsProcessor instance with a grammar constraint object for CFG-constrained text generation', 'call the GrammarConstrainedLogitsProcessor with input_ids and scores tensors to get masked logits', 'mask logits by setting invalid tokens to negative infinity based on grammar acceptance', 'process logits by updating batch parsing states and masking scores according to grammar constraints', 'use batch_filter_vocab to get a boolean tensor of accepted tokens per batch from parsing states']
```

Usage

```
{'create_GrammarConstrainedLogitsProcessor': 'create a GrammarConstrainedLogitsProcessor instance with a grammar constraint object for CFG-constrained text generation', 'call_GrammarConstrainedLogitsProcessor': 'call the GrammarConstrainedLogitsProcessor with input_ids and scores tensors to get masked logits', 'mask_logits_method': 'mask logits by setting invalid tokens to negative infinity based on grammar acceptance', 'process_logits_method': 'process logits by updating batch parsing states and masking scores according to grammar constraints', 'batch_filter_vocab_usage': 'use batch_filter_vocab to get a boolean tensor of accepted tokens per batch from parsing states'}
```

