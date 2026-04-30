# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/fused_moe/runner/moe_runner.py

Prompts

```
['run the MoERunner forward method with hidden_states and router_logits tensors', 'test the MoERunner must_reduce_shared_expert_outputs method returns a boolean', 'review the MoERunner maybe_all_reduce_tensor_model_parallel method for tensor parallel operations', 'summarize the MoERunner is_internal_router method that checks for internal router usage', 'refactor the MoERunner shared_experts property to return SharedExperts or None', 'run the forward pass of a MoE runner with hidden_states and router_logits tensors', 'test whether a MoE runner uses an internal router', 'review the shared_experts property of a MoE runner that returns SharedExperts or None', 'refactor the _replace_quant_method method to swap the quantization method on a MoE runner', 'create a concrete MoE runner class implementing the MoERunnerInterface abstract base class', 'create a SharedExperts instance to manage fused MoE shared expert execution with CUDA stream overlap', 'test the SharedExpertsOrder enum with NONE, NO_OVERLAP, MK_INTERNAL_OVERLAPPED, and MULTI_STREAM_OVERLAPPED values', 'run the SharedExperts.apply method to execute shared experts on hidden states with a specified execution order', 'refactor the maybe_sync_shared_experts_stream method to handle tensor stream recording and aux stream synchronization', 'review the _determine_shared_experts_order method to determine execution strategy based on quant method and tensor size']
```

Usage

```
{'run_MoERunner_forward': 'run the MoERunner forward method with hidden_states and router_logits tensors', 'test_MoERunner_must_reduce_shared_expert_outputs': 'test the MoERunner must_reduce_shared_expert_outputs method returns a boolean', 'review_MoERunner_maybe_all_reduce_tensor_model_parallel': 'review the MoERunner maybe_all_reduce_tensor_model_parallel method for tensor parallel operations', 'summarize_MoERunner_is_internal_router': 'summarize the MoERunner is_internal_router method that checks for internal router usage', 'refactor_MoERunner_shared_experts': 'refactor the MoERunner shared_experts property to return SharedExperts or None'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/fused_moe/runner/moe_runner_interface.py

Prompts

```
['run the MoERunner forward method with hidden_states and router_logits tensors', 'test the MoERunner must_reduce_shared_expert_outputs method returns a boolean', 'review the MoERunner maybe_all_reduce_tensor_model_parallel method for tensor parallel operations', 'summarize the MoERunner is_internal_router method that checks for internal router usage', 'refactor the MoERunner shared_experts property to return SharedExperts or None', 'run the forward pass of a MoE runner with hidden_states and router_logits tensors', 'test whether a MoE runner uses an internal router', 'review the shared_experts property of a MoE runner that returns SharedExperts or None', 'refactor the _replace_quant_method method to swap the quantization method on a MoE runner', 'create a concrete MoE runner class implementing the MoERunnerInterface abstract base class', 'create a SharedExperts instance to manage fused MoE shared expert execution with CUDA stream overlap', 'test the SharedExpertsOrder enum with NONE, NO_OVERLAP, MK_INTERNAL_OVERLAPPED, and MULTI_STREAM_OVERLAPPED values', 'run the SharedExperts.apply method to execute shared experts on hidden states with a specified execution order', 'refactor the maybe_sync_shared_experts_stream method to handle tensor stream recording and aux stream synchronization', 'review the _determine_shared_experts_order method to determine execution strategy based on quant method and tensor size']
```

Usage

```
{'run_MoERunnerInterface_forward': 'run the forward pass of a MoE runner with hidden_states and router_logits tensors', 'test_MoERunnerInterface_is_internal_router': 'test whether a MoE runner uses an internal router', 'review_MoERunnerInterface_shared_experts': 'review the shared_experts property of a MoE runner that returns SharedExperts or None', 'refactor_MoERunnerInterface__replace_quant_method': 'refactor the _replace_quant_method method to swap the quantization method on a MoE runner', 'create_MoERunnerInterface': 'create a concrete MoE runner class implementing the MoERunnerInterface abstract base class'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/fused_moe/runner/shared_experts.py

Prompts

```
['run the MoERunner forward method with hidden_states and router_logits tensors', 'test the MoERunner must_reduce_shared_expert_outputs method returns a boolean', 'review the MoERunner maybe_all_reduce_tensor_model_parallel method for tensor parallel operations', 'summarize the MoERunner is_internal_router method that checks for internal router usage', 'refactor the MoERunner shared_experts property to return SharedExperts or None', 'run the forward pass of a MoE runner with hidden_states and router_logits tensors', 'test whether a MoE runner uses an internal router', 'review the shared_experts property of a MoE runner that returns SharedExperts or None', 'refactor the _replace_quant_method method to swap the quantization method on a MoE runner', 'create a concrete MoE runner class implementing the MoERunnerInterface abstract base class', 'create a SharedExperts instance to manage fused MoE shared expert execution with CUDA stream overlap', 'test the SharedExpertsOrder enum with NONE, NO_OVERLAP, MK_INTERNAL_OVERLAPPED, and MULTI_STREAM_OVERLAPPED values', 'run the SharedExperts.apply method to execute shared experts on hidden states with a specified execution order', 'refactor the maybe_sync_shared_experts_stream method to handle tensor stream recording and aux stream synchronization', 'review the _determine_shared_experts_order method to determine execution strategy based on quant method and tensor size']
```

Usage

```
{'create_class_shared_experts': 'create a SharedExperts instance to manage fused MoE shared expert execution with CUDA stream overlap', 'test_enum_shared_experts_order': 'test the SharedExpertsOrder enum with NONE, NO_OVERLAP, MK_INTERNAL_OVERLAPPED, and MULTI_STREAM_OVERLAPPED values', 'run_method_apply': 'run the SharedExperts.apply method to execute shared experts on hidden states with a specified execution order', 'refactor_method_maybe_sync_stream': 'refactor the maybe_sync_shared_experts_stream method to handle tensor stream recording and aux stream synchronization', 'review_method_determine_order': 'review the _determine_shared_experts_order method to determine execution strategy based on quant method and tensor size'}
```

