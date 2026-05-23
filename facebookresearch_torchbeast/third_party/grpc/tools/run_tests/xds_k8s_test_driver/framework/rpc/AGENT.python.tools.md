# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/rpc/grpc.py

Prompts

```
['call a unary gRPC RPC method with a configurable deadline and wait-for-ready timeout', 'create a GrpcClientHelper instance from a gRPC channel and stub class to make RPC calls', 'make an insecure gRPC channel to a host and port, cached by port number', 'use GrpcApp as a context manager to automatically close all gRPC channels on exit', 'close all cached gRPC channels managed by a GrpcApp instance', 'list all top-level gRPC channels using the ChannelzServiceClient list_channels method', 'list all gRPC servers in the process using the ChannelzServiceClient list_servers method', 'find a gRPC server listening on a specific port using find_server_listening_on_port', 'list all sockets for a given gRPC server using the list_server_sockets method', 'convert a gRPC channelz socket address to a human-readable string using sock_address_to_str', 'create a LoadBalancerStatsServiceClient instance by passing a gRPC channel to the constructor', 'call get_client_stats with num_rpcs to retrieve load balancer statistics from the gRPC service', 'set a custom timeout_sec value when calling get_client_stats to control how long to wait for results', 'review the LoadBalancerStatsServiceClient class that extends GrpcClientHelper for gRPC unary RPC calls', 'summarize the LoadBalancerStatsResponse type alias and its usage in the get_client_stats return type']
```

Usage

```
{'call_unary_rpc_with_deadline': 'call a unary gRPC RPC method with a configurable deadline and wait-for-ready timeout', 'create_grpc_client_helper': 'create a GrpcClientHelper instance from a gRPC channel and stub class to make RPC calls', 'make_insecure_channel': 'make an insecure gRPC channel to a host and port, cached by port number', 'use_grpcapp_context_manager': 'use GrpcApp as a context manager to automatically close all gRPC channels on exit', 'close_grpc_channels': 'close all cached gRPC channels managed by a GrpcApp instance'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/rpc/grpc_channelz.py

Prompts

```
['call a unary gRPC RPC method with a configurable deadline and wait-for-ready timeout', 'create a GrpcClientHelper instance from a gRPC channel and stub class to make RPC calls', 'make an insecure gRPC channel to a host and port, cached by port number', 'use GrpcApp as a context manager to automatically close all gRPC channels on exit', 'close all cached gRPC channels managed by a GrpcApp instance', 'list all top-level gRPC channels using the ChannelzServiceClient list_channels method', 'list all gRPC servers in the process using the ChannelzServiceClient list_servers method', 'find a gRPC server listening on a specific port using find_server_listening_on_port', 'list all sockets for a given gRPC server using the list_server_sockets method', 'convert a gRPC channelz socket address to a human-readable string using sock_address_to_str', 'create a LoadBalancerStatsServiceClient instance by passing a gRPC channel to the constructor', 'call get_client_stats with num_rpcs to retrieve load balancer statistics from the gRPC service', 'set a custom timeout_sec value when calling get_client_stats to control how long to wait for results', 'review the LoadBalancerStatsServiceClient class that extends GrpcClientHelper for gRPC unary RPC calls', 'summarize the LoadBalancerStatsResponse type alias and its usage in the get_client_stats return type']
```

Usage

```
{'list_channels': 'list all top-level gRPC channels using the ChannelzServiceClient list_channels method', 'list_servers': 'list all gRPC servers in the process using the ChannelzServiceClient list_servers method', 'find_server_listening_on_port': 'find a gRPC server listening on a specific port using find_server_listening_on_port', 'list_server_sockets': 'list all sockets for a given gRPC server using the list_server_sockets method', 'sock_address_to_str': 'convert a gRPC channelz socket address to a human-readable string using sock_address_to_str'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/rpc/grpc_testing.py

Prompts

```
['call a unary gRPC RPC method with a configurable deadline and wait-for-ready timeout', 'create a GrpcClientHelper instance from a gRPC channel and stub class to make RPC calls', 'make an insecure gRPC channel to a host and port, cached by port number', 'use GrpcApp as a context manager to automatically close all gRPC channels on exit', 'close all cached gRPC channels managed by a GrpcApp instance', 'list all top-level gRPC channels using the ChannelzServiceClient list_channels method', 'list all gRPC servers in the process using the ChannelzServiceClient list_servers method', 'find a gRPC server listening on a specific port using find_server_listening_on_port', 'list all sockets for a given gRPC server using the list_server_sockets method', 'convert a gRPC channelz socket address to a human-readable string using sock_address_to_str', 'create a LoadBalancerStatsServiceClient instance by passing a gRPC channel to the constructor', 'call get_client_stats with num_rpcs to retrieve load balancer statistics from the gRPC service', 'set a custom timeout_sec value when calling get_client_stats to control how long to wait for results', 'review the LoadBalancerStatsServiceClient class that extends GrpcClientHelper for gRPC unary RPC calls', 'summarize the LoadBalancerStatsResponse type alias and its usage in the get_client_stats return type']
```

Usage

```
{'create_loadbalancer_stats_client': 'create a LoadBalancerStatsServiceClient instance by passing a gRPC channel to the constructor', 'get_client_stats_rpc': 'call get_client_stats with num_rpcs to retrieve load balancer statistics from the gRPC service', 'configure_stats_timeout': 'set a custom timeout_sec value when calling get_client_stats to control how long to wait for results', 'review_grpc_client_helper': 'review the LoadBalancerStatsServiceClient class that extends GrpcClientHelper for gRPC unary RPC calls', 'summarize_loadbalancer_stats_response': 'summarize the LoadBalancerStatsResponse type alias and its usage in the get_client_stats return type'}
```

