# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/debug/asyncio_debug_server.py

Prompts

```
['create a gRPC asyncio server with fault injection and Channelz servicer support', 'run the asyncio debug gRPC server on a configurable address with random failure injection', 'test the FaultInjectGreeter SayHello method that randomly aborts requests based on failure rate', 'review the Channelz servicer integration added to the gRPC server for debugging', 'refactor the FaultInjectGreeter class to support a configurable failure rate for SayHello responses', 'create a gRPC server with Channelz servicer and fault injection on a given address', 'build a GreeterServicer subclass that randomly aborts requests with UNAVAILABLE status', 'review the FaultInjectGreeter SayHello method that injects random failures based on a failure rate', 'test the create_server function that starts a gRPC server with fault injection and Channelz support', 'run a gRPC client to poll server-level statistics from a gRPC server using channelz', 'run a gRPC Channelz GetServers RPC call to retrieve all server metrics and statistics', 'create an insecure gRPC channel to connect to a server address for polling statistics', 'create a ChannelzStub instance from a gRPC channel to make channelz service calls', 'review the GetServers response containing server-level metrics like sent/received messages and RPC stats', 'run the gRPC client to send multiple hello messages to a backend server', 'run a single SayHello gRPC request through a stub and print the response', 'run n greeting messages over an insecure gRPC channel to a given address', 'review the process function that handles SayHello RPC calls and error printing', 'review the run function that creates a gRPC channel and sends repeated requests']
```

Usage

```
{'create_server': 'create a gRPC asyncio server with fault injection and Channelz servicer support', 'run_debug_server': 'run the asyncio debug gRPC server on a configurable address with random failure injection', 'faultinjectgreeter_sayhello': 'test the FaultInjectGreeter SayHello method that randomly aborts requests based on failure rate', 'channelz_servicer': 'review the Channelz servicer integration added to the gRPC server for debugging', 'refactor_failure_rate': 'refactor the FaultInjectGreeter class to support a configurable failure rate for SayHello responses'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/debug/debug_server.py

Prompts

```
['create a gRPC asyncio server with fault injection and Channelz servicer support', 'run the asyncio debug gRPC server on a configurable address with random failure injection', 'test the FaultInjectGreeter SayHello method that randomly aborts requests based on failure rate', 'review the Channelz servicer integration added to the gRPC server for debugging', 'refactor the FaultInjectGreeter class to support a configurable failure rate for SayHello responses', 'create a gRPC server with Channelz servicer and fault injection on a given address', 'build a GreeterServicer subclass that randomly aborts requests with UNAVAILABLE status', 'review the FaultInjectGreeter SayHello method that injects random failures based on a failure rate', 'test the create_server function that starts a gRPC server with fault injection and Channelz support', 'run a gRPC client to poll server-level statistics from a gRPC server using channelz', 'run a gRPC Channelz GetServers RPC call to retrieve all server metrics and statistics', 'create an insecure gRPC channel to connect to a server address for polling statistics', 'create a ChannelzStub instance from a gRPC channel to make channelz service calls', 'review the GetServers response containing server-level metrics like sent/received messages and RPC stats', 'run the gRPC client to send multiple hello messages to a backend server', 'run a single SayHello gRPC request through a stub and print the response', 'run n greeting messages over an insecure gRPC channel to a given address', 'review the process function that handles SayHello RPC calls and error printing', 'review the run function that creates a gRPC channel and sends repeated requests']
```

Usage

```
{'run_debug_server': 'run a gRPC debug server with configurable address and random failure injection rate', 'create_server_with_channelz': 'create a gRPC server with Channelz servicer and fault injection on a given address', 'build_fault_inject_greeter': 'build a GreeterServicer subclass that randomly aborts requests with UNAVAILABLE status', 'review_fault_inject_greeter_sayhello': 'review the FaultInjectGreeter SayHello method that injects random failures based on a failure rate', 'test_create_server': 'test the create_server function that starts a gRPC server with fault injection and Channelz support'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/debug/get_stats.py

Prompts

```
['create a gRPC asyncio server with fault injection and Channelz servicer support', 'run the asyncio debug gRPC server on a configurable address with random failure injection', 'test the FaultInjectGreeter SayHello method that randomly aborts requests based on failure rate', 'review the Channelz servicer integration added to the gRPC server for debugging', 'refactor the FaultInjectGreeter class to support a configurable failure rate for SayHello responses', 'create a gRPC server with Channelz servicer and fault injection on a given address', 'build a GreeterServicer subclass that randomly aborts requests with UNAVAILABLE status', 'review the FaultInjectGreeter SayHello method that injects random failures based on a failure rate', 'test the create_server function that starts a gRPC server with fault injection and Channelz support', 'run a gRPC client to poll server-level statistics from a gRPC server using channelz', 'run a gRPC Channelz GetServers RPC call to retrieve all server metrics and statistics', 'create an insecure gRPC channel to connect to a server address for polling statistics', 'create a ChannelzStub instance from a gRPC channel to make channelz service calls', 'review the GetServers response containing server-level metrics like sent/received messages and RPC stats', 'run the gRPC client to send multiple hello messages to a backend server', 'run a single SayHello gRPC request through a stub and print the response', 'run n greeting messages over an insecure gRPC channel to a given address', 'review the process function that handles SayHello RPC calls and error printing', 'review the run function that creates a gRPC channel and sends repeated requests']
```

Usage

```
{'run_get_stats': 'run a gRPC client to poll server-level statistics from a gRPC server using channelz', 'run_channelz_getservers': 'run a gRPC Channelz GetServers RPC call to retrieve all server metrics and statistics', 'create_grpc_insecure_channel': 'create an insecure gRPC channel to connect to a server address for polling statistics', 'create_channelz_stub': 'create a ChannelzStub instance from a gRPC channel to make channelz service calls', 'review_getservers_response': 'review the GetServers response containing server-level metrics like sent/received messages and RPC stats'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/debug/send_message.py

Prompts

```
['create a gRPC asyncio server with fault injection and Channelz servicer support', 'run the asyncio debug gRPC server on a configurable address with random failure injection', 'test the FaultInjectGreeter SayHello method that randomly aborts requests based on failure rate', 'review the Channelz servicer integration added to the gRPC server for debugging', 'refactor the FaultInjectGreeter class to support a configurable failure rate for SayHello responses', 'create a gRPC server with Channelz servicer and fault injection on a given address', 'build a GreeterServicer subclass that randomly aborts requests with UNAVAILABLE status', 'review the FaultInjectGreeter SayHello method that injects random failures based on a failure rate', 'test the create_server function that starts a gRPC server with fault injection and Channelz support', 'run a gRPC client to poll server-level statistics from a gRPC server using channelz', 'run a gRPC Channelz GetServers RPC call to retrieve all server metrics and statistics', 'create an insecure gRPC channel to connect to a server address for polling statistics', 'create a ChannelzStub instance from a gRPC channel to make channelz service calls', 'review the GetServers response containing server-level metrics like sent/received messages and RPC stats', 'run the gRPC client to send multiple hello messages to a backend server', 'run a single SayHello gRPC request through a stub and print the response', 'run n greeting messages over an insecure gRPC channel to a given address', 'review the process function that handles SayHello RPC calls and error printing', 'review the run function that creates a gRPC channel and sends repeated requests']
```

Usage

```
{'run_send_message': 'run the gRPC client to send multiple hello messages to a backend server', 'run_process': 'run a single SayHello gRPC request through a stub and print the response', 'run_run': 'run n greeting messages over an insecure gRPC channel to a given address', 'review_process': 'review the process function that handles SayHello RPC calls and error printing', 'review_run': 'review the run function that creates a gRPC channel and sends repeated requests'}
```

