# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/mpc/context.py

Prompts

```
['run a function across multiple processes using the run_multiprocess decorator with a specified world size', 'launch a multiprocess MPC computation that automatically spawns a TTP server when required by crypten', 'review the run_multiprocess decorator to understand how it manages process lifecycle and return value collection', 'summarize the _launch helper function that initializes crypten, executes a target function, and returns results via a queue', 'test the run_multiprocess decorator by decorating a function and verifying return values are sorted by rank', 'create an MPCTensor from a PyTorch tensor with arithmetic or binary sharing scheme', 'convert an MPCTensor between arithmetic and binary sharing schemes using the to method', 'decrypt and reveal the plaintext value of an MPCTensor to a specified destination party', 'perform equality or inequality comparison on two MPCTensors using eq or ne methods', 'perform add, sub, mul, matmul, or conv operations on MPCTensors via passthrough functions', 'use the ptype arithmetic enum member to represent arithmetic shared tensor type', 'use the ptype binary enum member to represent binary shared tensor type', 'call to_tensor on ptype arithmetic to get the ArithmeticSharedTensor class', 'call to_tensor on ptype binary to get the BinarySharedTensor class', 'review the ptype enum class and its to_tensor method for encrypted tensor types']
```

Usage

```
{'run_multiprocess_decorator': 'run a function across multiple processes using the run_multiprocess decorator with a specified world size', 'launch_multiprocess_with_ttp': 'launch a multiprocess MPC computation that automatically spawns a TTP server when required by crypten', 'review_run_multiprocess': 'review the run_multiprocess decorator to understand how it manages process lifecycle and return value collection', 'summarize_launch_helper': 'summarize the _launch helper function that initializes crypten, executes a target function, and returns results via a queue', 'test_multiprocess_decorator': 'test the run_multiprocess decorator by decorating a function and verifying return values are sorted by rank'}
```

## File: facebookresearch_crypten/crypten/mpc/mpc.py

Prompts

```
['run a function across multiple processes using the run_multiprocess decorator with a specified world size', 'launch a multiprocess MPC computation that automatically spawns a TTP server when required by crypten', 'review the run_multiprocess decorator to understand how it manages process lifecycle and return value collection', 'summarize the _launch helper function that initializes crypten, executes a target function, and returns results via a queue', 'test the run_multiprocess decorator by decorating a function and verifying return values are sorted by rank', 'create an MPCTensor from a PyTorch tensor with arithmetic or binary sharing scheme', 'convert an MPCTensor between arithmetic and binary sharing schemes using the to method', 'decrypt and reveal the plaintext value of an MPCTensor to a specified destination party', 'perform equality or inequality comparison on two MPCTensors using eq or ne methods', 'perform add, sub, mul, matmul, or conv operations on MPCTensors via passthrough functions', 'use the ptype arithmetic enum member to represent arithmetic shared tensor type', 'use the ptype binary enum member to represent binary shared tensor type', 'call to_tensor on ptype arithmetic to get the ArithmeticSharedTensor class', 'call to_tensor on ptype binary to get the BinarySharedTensor class', 'review the ptype enum class and its to_tensor method for encrypted tensor types']
```

Usage

```
{'create_mpc_tensor': 'create an MPCTensor from a PyTorch tensor with arithmetic or binary sharing scheme', 'convert_mpc_tensor_ptype': 'convert an MPCTensor between arithmetic and binary sharing schemes using the to method', 'reveal_mpc_tensor': 'decrypt and reveal the plaintext value of an MPCTensor to a specified destination party', 'compare_mpc_tensor': 'perform equality or inequality comparison on two MPCTensors using eq or ne methods', 'perform_mpc_tensor_arithmetic': 'perform add, sub, mul, matmul, or conv operations on MPCTensors via passthrough functions'}
```

## File: facebookresearch_crypten/crypten/mpc/ptype.py

Prompts

```
['run a function across multiple processes using the run_multiprocess decorator with a specified world size', 'launch a multiprocess MPC computation that automatically spawns a TTP server when required by crypten', 'review the run_multiprocess decorator to understand how it manages process lifecycle and return value collection', 'summarize the _launch helper function that initializes crypten, executes a target function, and returns results via a queue', 'test the run_multiprocess decorator by decorating a function and verifying return values are sorted by rank', 'create an MPCTensor from a PyTorch tensor with arithmetic or binary sharing scheme', 'convert an MPCTensor between arithmetic and binary sharing schemes using the to method', 'decrypt and reveal the plaintext value of an MPCTensor to a specified destination party', 'perform equality or inequality comparison on two MPCTensors using eq or ne methods', 'perform add, sub, mul, matmul, or conv operations on MPCTensors via passthrough functions', 'use the ptype arithmetic enum member to represent arithmetic shared tensor type', 'use the ptype binary enum member to represent binary shared tensor type', 'call to_tensor on ptype arithmetic to get the ArithmeticSharedTensor class', 'call to_tensor on ptype binary to get the BinarySharedTensor class', 'review the ptype enum class and its to_tensor method for encrypted tensor types']
```

Usage

```
{'use_ptype_arithmetic': 'use the ptype arithmetic enum member to represent arithmetic shared tensor type', 'use_ptype_binary': 'use the ptype binary enum member to represent binary shared tensor type', 'call_ptype_to_tensor_arithmetic': 'call to_tensor on ptype arithmetic to get the ArithmeticSharedTensor class', 'call_ptype_to_tensor_binary': 'call to_tensor on ptype binary to get the BinarySharedTensor class', 'review_ptype_enum': 'review the ptype enum class and its to_tensor method for encrypted tensor types'}
```

