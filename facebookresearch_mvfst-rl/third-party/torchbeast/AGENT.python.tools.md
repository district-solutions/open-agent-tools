# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/notebook.py

Prompts

```
['read a CSV or TSV log file and return rolling-averaged x/y data for plotting', 'plot a dictionary of log data as multi-panel matplotlib charts with rolling averages', 'compute a moving average of a numeric array using convolution with a window size', 'aggregate an iterator of x/y pairs by averaging y values that share the same x', 'map a string to a hex color from the Tableau20 palette using a hash function', 'build the torchbeast C++ RPC extension module using python setup.py build develop', 'install the torchbeast package with C++ extensions via pip install . -vv', 'build protobuf and gRPC C++ code from rpc.proto using the protoc compiler', 'run the torchbeast test suite by discovering all *_test.py files in the tests directory', 'configure the torchbeast build prefix via TORCHBEAST_LIBS_PREFIX or CONDA_PREFIX environment variables', 'run a torchbeast Server on localhost:12345 that serves bound functions and modules', 'bind a torch.jit.script module to the torchbeast Server under a named endpoint', 'bind a plain Python function to the torchbeast Server for remote invocation', 'bind a function to the torchbeast Server with a specified batch_size for batched execution', 'stop the running torchbeast Server and wait for it to fully shut down']
```

Usage

```
{'read_csv_tsv_log': 'read a CSV or TSV log file and return rolling-averaged x/y data for plotting', 'plot_log_data': 'plot a dictionary of log data as multi-panel matplotlib charts with rolling averages', 'moving_average_smooth': 'compute a moving average of a numeric array using convolution with a window size', 'mean_xs_ys_aggregate': 'aggregate an iterator of x/y pairs by averaging y values that share the same x', 'str2color_hash': 'map a string to a hex color from the Tableau20 palette using a hash function'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/setup.py

Prompts

```
['read a CSV or TSV log file and return rolling-averaged x/y data for plotting', 'plot a dictionary of log data as multi-panel matplotlib charts with rolling averages', 'compute a moving average of a numeric array using convolution with a window size', 'aggregate an iterator of x/y pairs by averaging y values that share the same x', 'map a string to a hex color from the Tableau20 palette using a hash function', 'build the torchbeast C++ RPC extension module using python setup.py build develop', 'install the torchbeast package with C++ extensions via pip install . -vv', 'build protobuf and gRPC C++ code from rpc.proto using the protoc compiler', 'run the torchbeast test suite by discovering all *_test.py files in the tests directory', 'configure the torchbeast build prefix via TORCHBEAST_LIBS_PREFIX or CONDA_PREFIX environment variables', 'run a torchbeast Server on localhost:12345 that serves bound functions and modules', 'bind a torch.jit.script module to the torchbeast Server under a named endpoint', 'bind a plain Python function to the torchbeast Server for remote invocation', 'bind a function to the torchbeast Server with a specified batch_size for batched execution', 'stop the running torchbeast Server and wait for it to fully shut down']
```

Usage

```
{'build_torchbeast_cpp_extension': 'build the torchbeast C++ RPC extension module using python setup.py build develop', 'install_torchbeast_package': 'install the torchbeast package with C++ extensions via pip install . -vv', 'build_protobuf_code': 'build protobuf and gRPC C++ code from rpc.proto using the protoc compiler', 'run_torchbeast_tests': 'run the torchbeast test suite by discovering all *_test.py files in the tests directory', 'configure_torchbeast_prefix': 'configure the torchbeast build prefix via TORCHBEAST_LIBS_PREFIX or CONDA_PREFIX environment variables'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/test_server.py

Prompts

```
['read a CSV or TSV log file and return rolling-averaged x/y data for plotting', 'plot a dictionary of log data as multi-panel matplotlib charts with rolling averages', 'compute a moving average of a numeric array using convolution with a window size', 'aggregate an iterator of x/y pairs by averaging y values that share the same x', 'map a string to a hex color from the Tableau20 palette using a hash function', 'build the torchbeast C++ RPC extension module using python setup.py build develop', 'install the torchbeast package with C++ extensions via pip install . -vv', 'build protobuf and gRPC C++ code from rpc.proto using the protoc compiler', 'run the torchbeast test suite by discovering all *_test.py files in the tests directory', 'configure the torchbeast build prefix via TORCHBEAST_LIBS_PREFIX or CONDA_PREFIX environment variables', 'run a torchbeast Server on localhost:12345 that serves bound functions and modules', 'bind a torch.jit.script module to the torchbeast Server under a named endpoint', 'bind a plain Python function to the torchbeast Server for remote invocation', 'bind a function to the torchbeast Server with a specified batch_size for batched execution', 'stop the running torchbeast Server and wait for it to fully shut down']
```

Usage

```
{'run_torchbeast_server': 'run a torchbeast Server on localhost:12345 that serves bound functions and modules', 'bind_torchscript_module': 'bind a torch.jit.script module to the torchbeast Server under a named endpoint', 'bind_python_function': 'bind a plain Python function to the torchbeast Server for remote invocation', 'bind_batched_function': 'bind a function to the torchbeast Server with a specified batch_size for batched execution', 'stop_and_wait_server': 'stop the running torchbeast Server and wait for it to fully shut down'}
```

