# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/features/logits_processor/custom.py

Prompts

```
['create a custom logits processor class that masks all tokens except a specified target token', 'run vLLM LLM generation with a custom DummyLogitsProcessor to force specific token output', 'validate that SamplingParams extra_args target_token is an integer before processing', 'apply logits masking to keep only target token values and set others to negative infinity', 'update the logits processor state by extracting target_token from each request sampling params', 'run the custom request-level logits processor example that masks tokens using target_token parameter', 'create a DummyPerReqLogitsProcessor that masks all logits except a specified target token id', 'build a WrappedPerReqLogitsProcessor adapter that wraps request-level logits processors for batch-level vLLM processing', 'validate that the target_token extra argument is an integer before applying the logits processor', 'generate text with an LLM using custom logits processors that force specific token output per request', 'create an adapter logits processor that conditionally applies per-request processing based on device type', 'validate that the target_token extra argument is an integer in sampling params', 'review the new_req_logits_processor method that returns a per-request logits processor or None']
```

Usage

```
{'create_custom_logits_processor': 'create a custom logits processor class that masks all tokens except a specified target token', 'run_llm_with_logits_processor': 'run vLLM LLM generation with a custom DummyLogitsProcessor to force specific token output', 'validate_sampling_params_target_token': 'validate that SamplingParams extra_args target_token is an integer before processing', 'apply_logits_masking': 'apply logits masking to keep only target token values and set others to negative infinity', 'update_processor_state': 'update the logits processor state by extracting target_token from each request sampling params'}
```

## File: vllm-project_vllm/examples/features/logits_processor/custom_req.py

Prompts

```
['create a custom logits processor class that masks all tokens except a specified target token', 'run vLLM LLM generation with a custom DummyLogitsProcessor to force specific token output', 'validate that SamplingParams extra_args target_token is an integer before processing', 'apply logits masking to keep only target token values and set others to negative infinity', 'update the logits processor state by extracting target_token from each request sampling params', 'run the custom request-level logits processor example that masks tokens using target_token parameter', 'create a DummyPerReqLogitsProcessor that masks all logits except a specified target token id', 'build a WrappedPerReqLogitsProcessor adapter that wraps request-level logits processors for batch-level vLLM processing', 'validate that the target_token extra argument is an integer before applying the logits processor', 'generate text with an LLM using custom logits processors that force specific token output per request', 'create an adapter logits processor that conditionally applies per-request processing based on device type', 'validate that the target_token extra argument is an integer in sampling params', 'review the new_req_logits_processor method that returns a per-request logits processor or None']
```

Usage

```
{'run_custom_logits_processor': 'run the custom request-level logits processor example that masks tokens using target_token parameter', 'create_DummyPerReqLogitsProcessor': 'create a DummyPerReqLogitsProcessor that masks all logits except a specified target token id', 'build_WrappedPerReqLogitsProcessor': 'build a WrappedPerReqLogitsProcessor adapter that wraps request-level logits processors for batch-level vLLM processing', 'validate_target_token_params': 'validate that the target_token extra argument is an integer before applying the logits processor', 'generate_with_custom_logits': 'generate text with an LLM using custom logits processors that force specific token output per request'}
```

## File: vllm-project_vllm/examples/features/logits_processor/custom_req_init.py

Prompts

```
['create a custom logits processor class that masks all tokens except a specified target token', 'run vLLM LLM generation with a custom DummyLogitsProcessor to force specific token output', 'validate that SamplingParams extra_args target_token is an integer before processing', 'apply logits masking to keep only target token values and set others to negative infinity', 'update the logits processor state by extracting target_token from each request sampling params', 'run the custom request-level logits processor example that masks tokens using target_token parameter', 'create a DummyPerReqLogitsProcessor that masks all logits except a specified target token id', 'build a WrappedPerReqLogitsProcessor adapter that wraps request-level logits processors for batch-level vLLM processing', 'validate that the target_token extra argument is an integer before applying the logits processor', 'generate text with an LLM using custom logits processors that force specific token output per request', 'create an adapter logits processor that conditionally applies per-request processing based on device type', 'validate that the target_token extra argument is an integer in sampling params', 'review the new_req_logits_processor method that returns a per-request logits processor or None']
```

Usage

```
{'run_custom_logits_processor': 'run the vLLM example that uses a custom request-level logits processor with wrapped adapter', 'create_DummyPerReqLogitsProcessor': 'create a request-level logits processor that masks all logits except a target token id', 'create_WrappedPerReqLogitsProcessor': 'create an adapter logits processor that conditionally applies per-request processing based on device type', 'validate_WrappedPerReqLogitsProcessor_params': 'validate that the target_token extra argument is an integer in sampling params', 'review_new_req_logits_processor': 'review the new_req_logits_processor method that returns a per-request logits processor or None'}
```

