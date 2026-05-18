# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/tests/rpc_test.py

Prompts

```
['run the RPCTest unit test to verify torchbeast RPC server and client communication', 'test the test_rpc_simple method to validate RPC calls between a torchbeast server and client process', 'create a torchbeast Client instance and connect to a server at localhost:12345', 'bind a python function to a torchbeast Server so it can be called remotely via RPC', 'run the _run_client function to invoke a remote first_function on the torchbeast server', 'test the vtrace.action_log_probs function to compute log probabilities of actions from policy logits', 'test the vtrace.from_importance_weights function to compute V-trace returns using log importance weights', 'test the vtrace.from_logits function to compute V-trace returns directly from behavior and target policy logits', 'review the VTraceReturns dataclass structure holding computed vs values and pg_advantages for V-trace', 'run the ground truth V-trace calculation in NumPy to verify correctness of the PyTorch implementation']
```

Usage

```
{'run_rpc_test': 'run the RPCTest unit test to verify torchbeast RPC server and client communication', 'test_rpc_simple': 'test the test_rpc_simple method to validate RPC calls between a torchbeast server and client process', 'create_torchbeast_client': 'create a torchbeast Client instance and connect to a server at localhost:12345', 'bind_server_function': 'bind a python function to a torchbeast Server so it can be called remotely via RPC', 'run_client_rpc_call': 'run the _run_client function to invoke a remote first_function on the torchbeast server'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/tests/vtrace_test.py

Prompts

```
['run the RPCTest unit test to verify torchbeast RPC server and client communication', 'test the test_rpc_simple method to validate RPC calls between a torchbeast server and client process', 'create a torchbeast Client instance and connect to a server at localhost:12345', 'bind a python function to a torchbeast Server so it can be called remotely via RPC', 'run the _run_client function to invoke a remote first_function on the torchbeast server', 'test the vtrace.action_log_probs function to compute log probabilities of actions from policy logits', 'test the vtrace.from_importance_weights function to compute V-trace returns using log importance weights', 'test the vtrace.from_logits function to compute V-trace returns directly from behavior and target policy logits', 'review the VTraceReturns dataclass structure holding computed vs values and pg_advantages for V-trace', 'run the ground truth V-trace calculation in NumPy to verify correctness of the PyTorch implementation']
```

Usage

```
{'test_vtrace_action_log_probs': 'test the vtrace.action_log_probs function to compute log probabilities of actions from policy logits', 'test_vtrace_from_importance_weights': 'test the vtrace.from_importance_weights function to compute V-trace returns using log importance weights', 'test_vtrace_from_logits': 'test the vtrace.from_logits function to compute V-trace returns directly from behavior and target policy logits', 'review_vtrace_returns': 'review the VTraceReturns dataclass structure holding computed vs values and pg_advantages for V-trace', 'run_vtrace_ground_truth_calculation': 'run the ground truth V-trace calculation in NumPy to verify correctness of the PyTorch implementation'}
```

