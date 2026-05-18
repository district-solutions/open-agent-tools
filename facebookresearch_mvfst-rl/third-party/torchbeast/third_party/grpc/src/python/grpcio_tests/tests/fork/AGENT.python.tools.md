# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/fork/_fork_interop_test.py

Prompts

```
['run the ForkInteropTest unittest suite to verify gRPC fork compatibility on Linux', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method for async unary calls on the same channel', 'test the ForkInteropTest testBlockingUnaryNewChannel method for blocking unary calls on a new channel', 'test the ForkInteropTest testInProgressBidiContinueCall method for in-progress bidi streaming calls', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the gRPC fork client by running test_fork to execute test cases against a server', 'run all gRPC test cases by passing --test_case all to the fork client CLI', 'parse a boolean CLI argument that accepts only true or false string values', 'lookup a TestCase enum member by its string value using _test_case_from_arg', 'run a gRPC fork support test case by calling TestCase enum run_test method with args dict', 'create a gRPC secure or insecure channel using the _channel function with server host and port args', 'test async unary RPC calls in child processes after fork using _async_unary_new_channel or _async_unary_same_channel', 'test blocking unary RPC calls in child processes after fork using _blocking_unary_new_channel or _blocking_unary_same_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_fork_interop_tests': 'run the ForkInteropTest unittest suite to verify gRPC fork compatibility on Linux', 'test_connectivity_watch': 'test the ForkInteropTest testConnectivityWatch method to verify connectivity after fork', 'test_async_unary_same_channel': 'test the ForkInteropTest testAsyncUnarySameChannel method for async unary calls on the same channel', 'test_blocking_unary_new_channel': 'test the ForkInteropTest testBlockingUnaryNewChannel method for blocking unary calls on a new channel', 'test_in_progress_bidi_continue_call': 'test the ForkInteropTest testInProgressBidiContinueCall method for in-progress bidi streaming calls'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/fork/client.py

Prompts

```
['run the ForkInteropTest unittest suite to verify gRPC fork compatibility on Linux', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method for async unary calls on the same channel', 'test the ForkInteropTest testBlockingUnaryNewChannel method for blocking unary calls on a new channel', 'test the ForkInteropTest testInProgressBidiContinueCall method for in-progress bidi streaming calls', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the gRPC fork client by running test_fork to execute test cases against a server', 'run all gRPC test cases by passing --test_case all to the fork client CLI', 'parse a boolean CLI argument that accepts only true or false string values', 'lookup a TestCase enum member by its string value using _test_case_from_arg', 'run a gRPC fork support test case by calling TestCase enum run_test method with args dict', 'create a gRPC secure or insecure channel using the _channel function with server host and port args', 'test async unary RPC calls in child processes after fork using _async_unary_new_channel or _async_unary_same_channel', 'test blocking unary RPC calls in child processes after fork using _blocking_unary_new_channel or _blocking_unary_same_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_grpc_interop_test_client': 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test_fork_function': 'test the gRPC fork client by running test_fork to execute test cases against a server', 'run_all_test_cases': 'run all gRPC test cases by passing --test_case all to the fork client CLI', 'parse_bool_argument': 'parse a boolean CLI argument that accepts only true or false string values', 'lookup_test_case_by_name': 'lookup a TestCase enum member by its string value using _test_case_from_arg'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/fork/methods.py

Prompts

```
['run the ForkInteropTest unittest suite to verify gRPC fork compatibility on Linux', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method for async unary calls on the same channel', 'test the ForkInteropTest testBlockingUnaryNewChannel method for blocking unary calls on a new channel', 'test the ForkInteropTest testInProgressBidiContinueCall method for in-progress bidi streaming calls', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the gRPC fork client by running test_fork to execute test cases against a server', 'run all gRPC test cases by passing --test_case all to the fork client CLI', 'parse a boolean CLI argument that accepts only true or false string values', 'lookup a TestCase enum member by its string value using _test_case_from_arg', 'run a gRPC fork support test case by calling TestCase enum run_test method with args dict', 'create a gRPC secure or insecure channel using the _channel function with server host and port args', 'test async unary RPC calls in child processes after fork using _async_unary_new_channel or _async_unary_same_channel', 'test blocking unary RPC calls in child processes after fork using _blocking_unary_new_channel or _blocking_unary_same_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_fork_test_case': 'run a gRPC fork support test case by calling TestCase enum run_test method with args dict', 'create_grpc_channel': 'create a gRPC secure or insecure channel using the _channel function with server host and port args', 'test_async_unary_after_fork': 'test async unary RPC calls in child processes after fork using _async_unary_new_channel or _async_unary_same_channel', 'test_blocking_unary_after_fork': 'test blocking unary RPC calls in child processes after fork using _blocking_unary_new_channel or _blocking_unary_same_channel', 'test_bidi_stream_after_fork': 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response'}
```

