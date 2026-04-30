# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/sampling/custom_logit_processor.py

Prompts

```
['build a logit processor that blocks specified token IDs by setting their logits to negative infinity', 'build a logit processor that controls the length of model thinking based on a token budget', 'build a logit processor that blocks n-gram repetitions within a sliding window for OCR outputs', 'create a CustomLogitProcessor and serialize it to a JSON-compatible string for later deserialization', 'test deserializing a CustomLogitProcessor from a JSON string using from_str', 'create a SamplingBatchInfo instance from a ScheduleBatch with given vocab_size', 'build and accumulate additive and scaling penalties for a batch of sampling requests', 'apply logits bias, penalties, vocab masks, and logit bias tensors to a logits tensor', 'filter a SamplingBatchInfo batch to keep only specified request indices', 'merge two SamplingBatchInfo instances into one combined batch', 'create SamplingParams with temperature, top_p, top_k, max_new_tokens, and stop sequences for text generation', 'verify SamplingParams validates temperature, top_p, top_k, penalties, and mutually exclusive grammar constraints against vocab_size', 'normalize SamplingParams stop strings and stop regex patterns using a tokenizer to compute max sequence lengths', 'create SamplingParams with a json_schema constraint to enforce structured JSON output from text generation', 'get_max_seq_length computes the maximum token buffer needed to evaluate a regex stop pattern']
```

Usage

```
{'build_DisallowedTokensLogitsProcessor': 'build a logit processor that blocks specified token IDs by setting their logits to negative infinity', 'build_ThinkingBudgetLogitProcessor': 'build a logit processor that controls the length of model thinking based on a token budget', 'build_DeepseekOCRNoRepeatNGramLogitProcessor': 'build a logit processor that blocks n-gram repetitions within a sliding window for OCR outputs', 'create_CustomLogitProcessor_serialize': 'create a CustomLogitProcessor and serialize it to a JSON-compatible string for later deserialization', 'test_from_str_deserialize': 'test deserializing a CustomLogitProcessor from a JSON string using from_str'}
```

## File: sgl-project_sglang/python/sglang/srt/sampling/sampling_batch_info.py

Prompts

```
['build a logit processor that blocks specified token IDs by setting their logits to negative infinity', 'build a logit processor that controls the length of model thinking based on a token budget', 'build a logit processor that blocks n-gram repetitions within a sliding window for OCR outputs', 'create a CustomLogitProcessor and serialize it to a JSON-compatible string for later deserialization', 'test deserializing a CustomLogitProcessor from a JSON string using from_str', 'create a SamplingBatchInfo instance from a ScheduleBatch with given vocab_size', 'build and accumulate additive and scaling penalties for a batch of sampling requests', 'apply logits bias, penalties, vocab masks, and logit bias tensors to a logits tensor', 'filter a SamplingBatchInfo batch to keep only specified request indices', 'merge two SamplingBatchInfo instances into one combined batch', 'create SamplingParams with temperature, top_p, top_k, max_new_tokens, and stop sequences for text generation', 'verify SamplingParams validates temperature, top_p, top_k, penalties, and mutually exclusive grammar constraints against vocab_size', 'normalize SamplingParams stop strings and stop regex patterns using a tokenizer to compute max sequence lengths', 'create SamplingParams with a json_schema constraint to enforce structured JSON output from text generation', 'get_max_seq_length computes the maximum token buffer needed to evaluate a regex stop pattern']
```

Usage

```
{'create_SamplingBatchInfo': 'create a SamplingBatchInfo instance from a ScheduleBatch with given vocab_size', 'build_penalties_accumulate': 'build and accumulate additive and scaling penalties for a batch of sampling requests', 'apply_logits_bias': 'apply logits bias, penalties, vocab masks, and logit bias tensors to a logits tensor', 'filter_batch_requests': 'filter a SamplingBatchInfo batch to keep only specified request indices', 'merge_batch_infos': 'merge two SamplingBatchInfo instances into one combined batch'}
```

## File: sgl-project_sglang/python/sglang/srt/sampling/sampling_params.py

Prompts

```
['build a logit processor that blocks specified token IDs by setting their logits to negative infinity', 'build a logit processor that controls the length of model thinking based on a token budget', 'build a logit processor that blocks n-gram repetitions within a sliding window for OCR outputs', 'create a CustomLogitProcessor and serialize it to a JSON-compatible string for later deserialization', 'test deserializing a CustomLogitProcessor from a JSON string using from_str', 'create a SamplingBatchInfo instance from a ScheduleBatch with given vocab_size', 'build and accumulate additive and scaling penalties for a batch of sampling requests', 'apply logits bias, penalties, vocab masks, and logit bias tensors to a logits tensor', 'filter a SamplingBatchInfo batch to keep only specified request indices', 'merge two SamplingBatchInfo instances into one combined batch', 'create SamplingParams with temperature, top_p, top_k, max_new_tokens, and stop sequences for text generation', 'verify SamplingParams validates temperature, top_p, top_k, penalties, and mutually exclusive grammar constraints against vocab_size', 'normalize SamplingParams stop strings and stop regex patterns using a tokenizer to compute max sequence lengths', 'create SamplingParams with a json_schema constraint to enforce structured JSON output from text generation', 'get_max_seq_length computes the maximum token buffer needed to evaluate a regex stop pattern']
```

Usage

```
{'create_SamplingParams': 'create SamplingParams with temperature, top_p, top_k, max_new_tokens, and stop sequences for text generation', 'verify_SamplingParams': 'verify SamplingParams validates temperature, top_p, top_k, penalties, and mutually exclusive grammar constraints against vocab_size', 'normalize_SamplingParams': 'normalize SamplingParams stop strings and stop regex patterns using a tokenizer to compute max sequence lengths', 'create_SamplingParams_json_schema': 'create SamplingParams with a json_schema constraint to enforce structured JSON output from text generation', 'get_max_seq_length': 'get_max_seq_length computes the maximum token buffer needed to evaluate a regex stop pattern'}
```

