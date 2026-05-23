# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/test_app/base_runner.py

Prompts

```
['create a Kubernetes namespace from a Mako template YAML manifest file', 'create a Kubernetes deployment from a Mako template YAML manifest file', 'create a Kubernetes service from a Mako template YAML manifest file', 'cleanup and delete a Kubernetes namespace and all its resources', 'wait for a Kubernetes deployment to have the expected number of available replicas', 'get load balancer stats by calling get_client_stats with num_rpcs and optional timeout_sec parameters', 'wait for the gRPC channel to the server to transition to READY state using exponential backoff retry', 'retrieve the active client to server socket by traversing channel subchannels and sockets via channelz', 'find a server channel matching a specific ChannelzChannelState and optionally verify subchannel state', 'run a Kubernetes client deployment with configurable QPS, RPC type, server target, and optional port forwarding', 'create an XdsTestServer instance with ip, rpc_port, and optional maintenance_port for xDS testing', 'run a KubernetesServerRunner to deploy an xDS test server on Kubernetes with specified image and namespace', 'get all sockets of the test server using get_test_server_sockets to inspect active connections', 'find the server socket matching a client socket using get_server_socket_matching_client by TCP endpoints', 'cleanup Kubernetes deployment, service, and service account resources using the cleanup method']
```

Usage

```
{'create_k8s_namespace_from_template': 'create a Kubernetes namespace from a Mako template YAML manifest file', 'create_k8s_deployment_from_template': 'create a Kubernetes deployment from a Mako template YAML manifest file', 'create_k8s_service_from_template': 'create a Kubernetes service from a Mako template YAML manifest file', 'cleanup_k8s_namespace': 'cleanup and delete a Kubernetes namespace and all its resources', 'wait_for_k8s_deployment_replicas': 'wait for a Kubernetes deployment to have the expected number of available replicas'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/test_app/client_app.py

Prompts

```
['create a Kubernetes namespace from a Mako template YAML manifest file', 'create a Kubernetes deployment from a Mako template YAML manifest file', 'create a Kubernetes service from a Mako template YAML manifest file', 'cleanup and delete a Kubernetes namespace and all its resources', 'wait for a Kubernetes deployment to have the expected number of available replicas', 'get load balancer stats by calling get_client_stats with num_rpcs and optional timeout_sec parameters', 'wait for the gRPC channel to the server to transition to READY state using exponential backoff retry', 'retrieve the active client to server socket by traversing channel subchannels and sockets via channelz', 'find a server channel matching a specific ChannelzChannelState and optionally verify subchannel state', 'run a Kubernetes client deployment with configurable QPS, RPC type, server target, and optional port forwarding', 'create an XdsTestServer instance with ip, rpc_port, and optional maintenance_port for xDS testing', 'run a KubernetesServerRunner to deploy an xDS test server on Kubernetes with specified image and namespace', 'get all sockets of the test server using get_test_server_sockets to inspect active connections', 'find the server socket matching a client socket using get_server_socket_matching_client by TCP endpoints', 'cleanup Kubernetes deployment, service, and service account resources using the cleanup method']
```

Usage

```
{'get_load_balancer_stats': 'get load balancer stats by calling get_client_stats with num_rpcs and optional timeout_sec parameters', 'wait_for_active_server_channel': 'wait for the gRPC channel to the server to transition to READY state using exponential backoff retry', 'get_active_server_channel_socket': 'retrieve the active client to server socket by traversing channel subchannels and sockets via channelz', 'find_server_channel_with_state': 'find a server channel matching a specific ChannelzChannelState and optionally verify subchannel state', 'run_kubernetes_client_deployment': 'run a Kubernetes client deployment with configurable QPS, RPC type, server target, and optional port forwarding'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/test_app/server_app.py

Prompts

```
['create a Kubernetes namespace from a Mako template YAML manifest file', 'create a Kubernetes deployment from a Mako template YAML manifest file', 'create a Kubernetes service from a Mako template YAML manifest file', 'cleanup and delete a Kubernetes namespace and all its resources', 'wait for a Kubernetes deployment to have the expected number of available replicas', 'get load balancer stats by calling get_client_stats with num_rpcs and optional timeout_sec parameters', 'wait for the gRPC channel to the server to transition to READY state using exponential backoff retry', 'retrieve the active client to server socket by traversing channel subchannels and sockets via channelz', 'find a server channel matching a specific ChannelzChannelState and optionally verify subchannel state', 'run a Kubernetes client deployment with configurable QPS, RPC type, server target, and optional port forwarding', 'create an XdsTestServer instance with ip, rpc_port, and optional maintenance_port for xDS testing', 'run a KubernetesServerRunner to deploy an xDS test server on Kubernetes with specified image and namespace', 'get all sockets of the test server using get_test_server_sockets to inspect active connections', 'find the server socket matching a client socket using get_server_socket_matching_client by TCP endpoints', 'cleanup Kubernetes deployment, service, and service account resources using the cleanup method']
```

Usage

```
{'create_xds_test_server': 'create an XdsTestServer instance with ip, rpc_port, and optional maintenance_port for xDS testing', 'run_kubernetes_server_runner': 'run a KubernetesServerRunner to deploy an xDS test server on Kubernetes with specified image and namespace', 'get_test_server_sockets': 'get all sockets of the test server using get_test_server_sockets to inspect active connections', 'find_matching_server_socket': 'find the server socket matching a client socket using get_server_socket_matching_client by TCP endpoints', 'cleanup_kubernetes_resources': 'cleanup Kubernetes deployment, service, and service account resources using the cleanup method'}
```

