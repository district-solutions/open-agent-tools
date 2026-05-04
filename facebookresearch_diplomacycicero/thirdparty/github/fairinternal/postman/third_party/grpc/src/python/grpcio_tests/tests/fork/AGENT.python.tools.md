# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/fork/_fork_interop_test.py

Prompts

```
['run the ForkInteropTest suite to verify gRPC fork compatibility on Linux with Python 2', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity watching after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method to verify async unary calls on the same channel after fork', 'test the ForkInteropTest testBlockingUnaryNewChannel method to verify blocking unary calls on a new channel after fork', 'test the ForkInteropTest testInProgressBidiContinueCall method to verify in-progress bidi calls continue after fork', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the test_fork function to run all or a specific gRPC test case via CLI arguments', 'run a specific test case by name using the _test_case_from_arg function to resolve it', 'review the _args function to understand CLI argument parsing for server_host, server_port, test_case, and use_tls', 'run all gRPC test cases by passing --test_case all to the test_fork entry point', 'run a gRPC fork support test case by calling TestCase enum run_test method with server args', 'create a gRPC secure or insecure channel using the _channel helper with server host and port args', 'test async unary RPC calls in a child process after fork using _async_unary_new_channel', 'test blocking unary RPC calls in a child process after fork using _blocking_unary_new_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_fork_interop_tests': 'run the ForkInteropTest suite to verify gRPC fork compatibility on Linux with Python 2', 'test_connectivity_watch': 'test the ForkInteropTest testConnectivityWatch method to verify connectivity watching after fork', 'test_async_unary_same_channel': 'test the ForkInteropTest testAsyncUnarySameChannel method to verify async unary calls on the same channel after fork', 'test_blocking_unary_new_channel': 'test the ForkInteropTest testBlockingUnaryNewChannel method to verify blocking unary calls on a new channel after fork', 'test_in_progress_bidi_continue_call': 'test the ForkInteropTest testInProgressBidiContinueCall method to verify in-progress bidi calls continue after fork'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/fork/client.py

Prompts

```
['run the ForkInteropTest suite to verify gRPC fork compatibility on Linux with Python 2', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity watching after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method to verify async unary calls on the same channel after fork', 'test the ForkInteropTest testBlockingUnaryNewChannel method to verify blocking unary calls on a new channel after fork', 'test the ForkInteropTest testInProgressBidiContinueCall method to verify in-progress bidi calls continue after fork', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the test_fork function to run all or a specific gRPC test case via CLI arguments', 'run a specific test case by name using the _test_case_from_arg function to resolve it', 'review the _args function to understand CLI argument parsing for server_host, server_port, test_case, and use_tls', 'run all gRPC test cases by passing --test_case all to the test_fork entry point', 'run a gRPC fork support test case by calling TestCase enum run_test method with server args', 'create a gRPC secure or insecure channel using the _channel helper with server host and port args', 'test async unary RPC calls in a child process after fork using _async_unary_new_channel', 'test blocking unary RPC calls in a child process after fork using _blocking_unary_new_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_grpc_interop_test_client': 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test_fork_function': 'test the test_fork function to run all or a specific gRPC test case via CLI arguments', 'run_test_case_from_arg': 'run a specific test case by name using the _test_case_from_arg function to resolve it', 'review_args_parser': 'review the _args function to understand CLI argument parsing for server_host, server_port, test_case, and use_tls', 'run_all_grpc_test_cases': 'run all gRPC test cases by passing --test_case all to the test_fork entry point'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/fork/methods.py

Prompts

```
['run the ForkInteropTest suite to verify gRPC fork compatibility on Linux with Python 2', 'test the ForkInteropTest testConnectivityWatch method to verify connectivity watching after fork', 'test the ForkInteropTest testAsyncUnarySameChannel method to verify async unary calls on the same channel after fork', 'test the ForkInteropTest testBlockingUnaryNewChannel method to verify blocking unary calls on a new channel after fork', 'test the ForkInteropTest testInProgressBidiContinueCall method to verify in-progress bidi calls continue after fork', 'run the gRPC interoperability test client against a server with --server_port and --test_case args', 'test the test_fork function to run all or a specific gRPC test case via CLI arguments', 'run a specific test case by name using the _test_case_from_arg function to resolve it', 'review the _args function to understand CLI argument parsing for server_host, server_port, test_case, and use_tls', 'run all gRPC test cases by passing --test_case all to the test_fork entry point', 'run a gRPC fork support test case by calling TestCase enum run_test method with server args', 'create a gRPC secure or insecure channel using the _channel helper with server host and port args', 'test async unary RPC calls in a child process after fork using _async_unary_new_channel', 'test blocking unary RPC calls in a child process after fork using _blocking_unary_new_channel', 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response']
```

Usage

```
{'run_fork_test_case': 'run a gRPC fork support test case by calling TestCase enum run_test method with server args', 'create_grpc_channel': 'create a gRPC secure or insecure channel using the _channel helper with server host and port args', 'test_async_unary_after_fork': 'test async unary RPC calls in a child process after fork using _async_unary_new_channel', 'test_blocking_unary_after_fork': 'test blocking unary RPC calls in a child process after fork using _blocking_unary_new_channel', 'test_bidi_stream_after_fork': 'test in-progress bidirectional streaming calls across forked child processes using _ping_pong_with_child_processes_after_first_response'}
```

