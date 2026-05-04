# Agent Python Tools

- repo: facebookresearch/deepconf
- repo_uri: https://github.com/facebookresearch/deepconf

## File: facebookresearch_deepconf/deepconf/outputs.py

Prompts

```
['create a DeepThinkOutput dataclass instance to store deep thinking LLM results with traces and voting data', 'convert a DeepThinkOutput object to a dictionary for JSON serialization with token and timing stats', 'print a formatted summary of DeepThinkOutput results including traces, tokens, timing, and voting answers', 'get a dictionary of voting method names mapped to their answers from a DeepThinkOutput object', 'calculate the overall token generation throughput in tokens per second from a DeepThinkOutput object', 'create a ConfPerReqLogitsProcessor with a confidence threshold, eos token id, group size, and topk value', 'compute the confidence score from a logits tensor using softmax and topk probabilities', 'call the ConfPerReqLogitsProcessor on output ids and logits to mask tokens below confidence threshold', 'create a WrappedPerReqLogitsProcessor with vllm config, device, and pin memory settings for CUDA-based processing', 'get a new request-level logits processor from SamplingParams with confidence threshold and eos token id', 'extract a boxed answer from LLM output text that contains LaTeX boxed notation', 'compute confidence scores from vLLM token logprobs and return a list of float values', 'perform simple majority voting on a list of string answers and return the most common one', 'perform weighted majority voting on answers using confidence weights to select the best answer', 'compute results for all voting methods including majority, weighted, and filtered confidence voting on traces', 'initialize a DeepThinkLLM instance with a model path and optional vLLM keyword arguments', 'run deepthink in offline mode to generate multiple traces and compute majority voting on a prompt', 'run deepthink in online mode with confidence-based early stopping and warmup traces on a prompt', 'call the generate method to perform standard vLLM generation with prompts and sampling parameters', 'perform weighted majority voting on generated traces to select the best answer from candidates']
```

Usage

```
{'create_DeepThinkOutput': 'create a DeepThinkOutput dataclass instance to store deep thinking LLM results with traces and voting data', 'to_dict_DeepThinkOutput': 'convert a DeepThinkOutput object to a dictionary for JSON serialization with token and timing stats', 'print_summary_DeepThinkOutput': 'print a formatted summary of DeepThinkOutput results including traces, tokens, timing, and voting answers', 'get_voting_answers_DeepThinkOutput': 'get a dictionary of voting method names mapped to their answers from a DeepThinkOutput object', 'overall_throughput_DeepThinkOutput': 'calculate the overall token generation throughput in tokens per second from a DeepThinkOutput object'}
```

## File: facebookresearch_deepconf/deepconf/processors.py

Prompts

```
['create a DeepThinkOutput dataclass instance to store deep thinking LLM results with traces and voting data', 'convert a DeepThinkOutput object to a dictionary for JSON serialization with token and timing stats', 'print a formatted summary of DeepThinkOutput results including traces, tokens, timing, and voting answers', 'get a dictionary of voting method names mapped to their answers from a DeepThinkOutput object', 'calculate the overall token generation throughput in tokens per second from a DeepThinkOutput object', 'create a ConfPerReqLogitsProcessor with a confidence threshold, eos token id, group size, and topk value', 'compute the confidence score from a logits tensor using softmax and topk probabilities', 'call the ConfPerReqLogitsProcessor on output ids and logits to mask tokens below confidence threshold', 'create a WrappedPerReqLogitsProcessor with vllm config, device, and pin memory settings for CUDA-based processing', 'get a new request-level logits processor from SamplingParams with confidence threshold and eos token id', 'extract a boxed answer from LLM output text that contains LaTeX boxed notation', 'compute confidence scores from vLLM token logprobs and return a list of float values', 'perform simple majority voting on a list of string answers and return the most common one', 'perform weighted majority voting on answers using confidence weights to select the best answer', 'compute results for all voting methods including majority, weighted, and filtered confidence voting on traces', 'initialize a DeepThinkLLM instance with a model path and optional vLLM keyword arguments', 'run deepthink in offline mode to generate multiple traces and compute majority voting on a prompt', 'run deepthink in online mode with confidence-based early stopping and warmup traces on a prompt', 'call the generate method to perform standard vLLM generation with prompts and sampling parameters', 'perform weighted majority voting on generated traces to select the best answer from candidates']
```

Usage

```
{'create_conf_logits_processor': 'create a ConfPerReqLogitsProcessor with a confidence threshold, eos token id, group size, and topk value', 'compute_confidence_from_logits': 'compute the confidence score from a logits tensor using softmax and topk probabilities', 'call_conf_processor_on_logits': 'call the ConfPerReqLogitsProcessor on output ids and logits to mask tokens below confidence threshold', 'create_wrapped_processor': 'create a WrappedPerReqLogitsProcessor with vllm config, device, and pin memory settings for CUDA-based processing', 'get_new_req_logits_processor': 'get a new request-level logits processor from SamplingParams with confidence threshold and eos token id'}
```

## File: facebookresearch_deepconf/deepconf/utils.py

Prompts

```
['create a DeepThinkOutput dataclass instance to store deep thinking LLM results with traces and voting data', 'convert a DeepThinkOutput object to a dictionary for JSON serialization with token and timing stats', 'print a formatted summary of DeepThinkOutput results including traces, tokens, timing, and voting answers', 'get a dictionary of voting method names mapped to their answers from a DeepThinkOutput object', 'calculate the overall token generation throughput in tokens per second from a DeepThinkOutput object', 'create a ConfPerReqLogitsProcessor with a confidence threshold, eos token id, group size, and topk value', 'compute the confidence score from a logits tensor using softmax and topk probabilities', 'call the ConfPerReqLogitsProcessor on output ids and logits to mask tokens below confidence threshold', 'create a WrappedPerReqLogitsProcessor with vllm config, device, and pin memory settings for CUDA-based processing', 'get a new request-level logits processor from SamplingParams with confidence threshold and eos token id', 'extract a boxed answer from LLM output text that contains LaTeX boxed notation', 'compute confidence scores from vLLM token logprobs and return a list of float values', 'perform simple majority voting on a list of string answers and return the most common one', 'perform weighted majority voting on answers using confidence weights to select the best answer', 'compute results for all voting methods including majority, weighted, and filtered confidence voting on traces', 'initialize a DeepThinkLLM instance with a model path and optional vLLM keyword arguments', 'run deepthink in offline mode to generate multiple traces and compute majority voting on a prompt', 'run deepthink in online mode with confidence-based early stopping and warmup traces on a prompt', 'call the generate method to perform standard vLLM generation with prompts and sampling parameters', 'perform weighted majority voting on generated traces to select the best answer from candidates']
```

Usage

```
{'extract_answer_from_text': 'extract a boxed answer from LLM output text that contains LaTeX boxed notation', 'compute_confidence_from_logprobs': 'compute confidence scores from vLLM token logprobs and return a list of float values', 'simple_majority_vote': 'perform simple majority voting on a list of string answers and return the most common one', 'weighted_majority_vote': 'perform weighted majority voting on answers using confidence weights to select the best answer', 'compute_all_voting_results': 'compute results for all voting methods including majority, weighted, and filtered confidence voting on traces'}
```

## File: facebookresearch_deepconf/deepconf/wrapper.py

Prompts

```
['create a DeepThinkOutput dataclass instance to store deep thinking LLM results with traces and voting data', 'convert a DeepThinkOutput object to a dictionary for JSON serialization with token and timing stats', 'print a formatted summary of DeepThinkOutput results including traces, tokens, timing, and voting answers', 'get a dictionary of voting method names mapped to their answers from a DeepThinkOutput object', 'calculate the overall token generation throughput in tokens per second from a DeepThinkOutput object', 'create a ConfPerReqLogitsProcessor with a confidence threshold, eos token id, group size, and topk value', 'compute the confidence score from a logits tensor using softmax and topk probabilities', 'call the ConfPerReqLogitsProcessor on output ids and logits to mask tokens below confidence threshold', 'create a WrappedPerReqLogitsProcessor with vllm config, device, and pin memory settings for CUDA-based processing', 'get a new request-level logits processor from SamplingParams with confidence threshold and eos token id', 'extract a boxed answer from LLM output text that contains LaTeX boxed notation', 'compute confidence scores from vLLM token logprobs and return a list of float values', 'perform simple majority voting on a list of string answers and return the most common one', 'perform weighted majority voting on answers using confidence weights to select the best answer', 'compute results for all voting methods including majority, weighted, and filtered confidence voting on traces', 'initialize a DeepThinkLLM instance with a model path and optional vLLM keyword arguments', 'run deepthink in offline mode to generate multiple traces and compute majority voting on a prompt', 'run deepthink in online mode with confidence-based early stopping and warmup traces on a prompt', 'call the generate method to perform standard vLLM generation with prompts and sampling parameters', 'perform weighted majority voting on generated traces to select the best answer from candidates']
```

Usage

```
{'init_DeepThinkLLM': 'initialize a DeepThinkLLM instance with a model path and optional vLLM keyword arguments', 'deepthink_offline': 'run deepthink in offline mode to generate multiple traces and compute majority voting on a prompt', 'deepthink_online': 'run deepthink in online mode with confidence-based early stopping and warmup traces on a prompt', 'generate_vllm': 'call the generate method to perform standard vLLM generation with prompts and sampling parameters', 'perform_basic_voting': 'perform weighted majority voting on generated traces to select the best answer from candidates'}
```

