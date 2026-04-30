# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/testing/_internal/distributed/rpc/jit/dist_autograd_test.py

Prompts

```
['test the JitDistAutogradTest.test_get_gradients method to retrieve gradients from a distributed autograd context', 'test the JitDistAutogradTest.test_dist_backward method to run distributed backward pass via RPC across workers', 'test the JitDistAutogradTest.test_jit_fork_within_context method to use torch.jit._fork and _wait inside a dist_autograd context', 'test the JitDistAutogradTest.test_restore_context_after_swtich_to_jit_thread method to verify autograd context is preserved across JIT thread switches', 'build a torch.jit.script function that performs remote tensor addition via rpc_async across distributed workers', 'test calling RRef.local_value() from a TorchScript function on the owner rank', 'test accessing a remote RRef across workers using rpc_sync and rpc.remote calls', 'test calling TorchScript functions remotely via rpc_async with argument and keyword validation', 'test creating and using ScriptModule RRefs across distributed workers', 'test profiling TorchScript RPC async calls with record_function and profiler callbacks', 'test the script_rpc_async_call function that performs an async RPC from within a TorchScript function', 'test the rpc_async_call_with_timeout function that performs an async RPC with a custom timeout in TorchScript', 'test the rref_to_here_with_timeout function that fetches a remote tensor with a timeout from a TorchScript function', 'test the JitFaultyAgentRpcTest class for RPC timeout and error handling under a faulty agent test fixture', 'test the rpc_async_with_rref_arg function that sends an RRef as an argument in a TorchScript async RPC']
```

Usage

```
{'test_get_gradients': 'test the JitDistAutogradTest.test_get_gradients method to retrieve gradients from a distributed autograd context', 'test_dist_backward': 'test the JitDistAutogradTest.test_dist_backward method to run distributed backward pass via RPC across workers', 'test_jit_fork_within_context': 'test the JitDistAutogradTest.test_jit_fork_within_context method to use torch.jit._fork and _wait inside a dist_autograd context', 'test_restore_context_after_swtich_to_jit_thread': 'test the JitDistAutogradTest.test_restore_context_after_swtich_to_jit_thread method to verify autograd context is preserved across JIT thread switches', 'build_remote_add_script': 'build a torch.jit.script function that performs remote tensor addition via rpc_async across distributed workers'}
```

## File: pytorch_pytorch/torch/testing/_internal/distributed/rpc/jit/rpc_test.py

Prompts

```
['test the JitDistAutogradTest.test_get_gradients method to retrieve gradients from a distributed autograd context', 'test the JitDistAutogradTest.test_dist_backward method to run distributed backward pass via RPC across workers', 'test the JitDistAutogradTest.test_jit_fork_within_context method to use torch.jit._fork and _wait inside a dist_autograd context', 'test the JitDistAutogradTest.test_restore_context_after_swtich_to_jit_thread method to verify autograd context is preserved across JIT thread switches', 'build a torch.jit.script function that performs remote tensor addition via rpc_async across distributed workers', 'test calling RRef.local_value() from a TorchScript function on the owner rank', 'test accessing a remote RRef across workers using rpc_sync and rpc.remote calls', 'test calling TorchScript functions remotely via rpc_async with argument and keyword validation', 'test creating and using ScriptModule RRefs across distributed workers', 'test profiling TorchScript RPC async calls with record_function and profiler callbacks', 'test the script_rpc_async_call function that performs an async RPC from within a TorchScript function', 'test the rpc_async_call_with_timeout function that performs an async RPC with a custom timeout in TorchScript', 'test the rref_to_here_with_timeout function that fetches a remote tensor with a timeout from a TorchScript function', 'test the JitFaultyAgentRpcTest class for RPC timeout and error handling under a faulty agent test fixture', 'test the rpc_async_with_rref_arg function that sends an RRef as an argument in a TorchScript async RPC']
```

Usage

```
{'test_rref_local_value': 'test calling RRef.local_value() from a TorchScript function on the owner rank', 'test_rref_remote_access': 'test accessing a remote RRef across workers using rpc_sync and rpc.remote calls', 'test_torchscript_rpc_async': 'test calling TorchScript functions remotely via rpc_async with argument and keyword validation', 'test_script_module_rref': 'test creating and using ScriptModule RRefs across distributed workers', 'test_rpc_profiling': 'test profiling TorchScript RPC async calls with record_function and profiler callbacks'}
```

## File: pytorch_pytorch/torch/testing/_internal/distributed/rpc/jit/rpc_test_faulty.py

Prompts

```
['test the JitDistAutogradTest.test_get_gradients method to retrieve gradients from a distributed autograd context', 'test the JitDistAutogradTest.test_dist_backward method to run distributed backward pass via RPC across workers', 'test the JitDistAutogradTest.test_jit_fork_within_context method to use torch.jit._fork and _wait inside a dist_autograd context', 'test the JitDistAutogradTest.test_restore_context_after_swtich_to_jit_thread method to verify autograd context is preserved across JIT thread switches', 'build a torch.jit.script function that performs remote tensor addition via rpc_async across distributed workers', 'test calling RRef.local_value() from a TorchScript function on the owner rank', 'test accessing a remote RRef across workers using rpc_sync and rpc.remote calls', 'test calling TorchScript functions remotely via rpc_async with argument and keyword validation', 'test creating and using ScriptModule RRefs across distributed workers', 'test profiling TorchScript RPC async calls with record_function and profiler callbacks', 'test the script_rpc_async_call function that performs an async RPC from within a TorchScript function', 'test the rpc_async_call_with_timeout function that performs an async RPC with a custom timeout in TorchScript', 'test the rref_to_here_with_timeout function that fetches a remote tensor with a timeout from a TorchScript function', 'test the JitFaultyAgentRpcTest class for RPC timeout and error handling under a faulty agent test fixture', 'test the rpc_async_with_rref_arg function that sends an RRef as an argument in a TorchScript async RPC']
```

Usage

```
{'test_script_rpc_async_call': 'test the script_rpc_async_call function that performs an async RPC from within a TorchScript function', 'test_rpc_async_call_with_timeout': 'test the rpc_async_call_with_timeout function that performs an async RPC with a custom timeout in TorchScript', 'test_rref_to_here_with_timeout': 'test the rref_to_here_with_timeout function that fetches a remote tensor with a timeout from a TorchScript function', 'test_jit_faulty_agent_rpc': 'test the JitFaultyAgentRpcTest class for RPC timeout and error handling under a faulty agent test fixture', 'test_rpc_async_with_rref_arg': 'test the rpc_async_with_rref_arg function that sends an RRef as an argument in a TorchScript async RPC'}
```

