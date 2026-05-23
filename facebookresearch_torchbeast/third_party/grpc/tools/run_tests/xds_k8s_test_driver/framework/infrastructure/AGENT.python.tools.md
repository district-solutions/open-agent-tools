# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/k8s.py

Prompts

```
['create a KubernetesApiManager instance to manage AppsV1Api and CoreV1Api clients for a given kubeconfig context', 'apply a Kubernetes manifest dictionary to a namespace using the KubernetesNamespace apply_manifest method', 'wait for a Kubernetes deployment to reach a specified number of available replicas with retry logic', 'forward a local port to a remote pod port using kubectl port-forward and return a Popen process', 'delete a Kubernetes namespace with foreground propagation policy and wait for it to be fully deleted', 'create a TrafficDirectorManager to set up gRPC backend services, health checks, and forwarding rules on GCP', 'setup a gRPC backend service with health check and routing rules using TrafficDirectorManager', 'create a TrafficDirectorSecureManager to configure TLS and mTLS policies for secure gRPC traffic on GCP', 'create a URL map and target proxy to route traffic from a host and port to a backend service', 'cleanup all Traffic Director resources including forwarding rules, proxies, URL maps, and backend services']
```

Usage

```
{'create_kubernetes_api_manager': 'create a KubernetesApiManager instance to manage AppsV1Api and CoreV1Api clients for a given kubeconfig context', 'apply_k8s_manifest': 'apply a Kubernetes manifest dictionary to a namespace using the KubernetesNamespace apply_manifest method', 'wait_for_deployment_replicas': 'wait for a Kubernetes deployment to reach a specified number of available replicas with retry logic', 'port_forward_pod': 'forward a local port to a remote pod port using kubectl port-forward and return a Popen process', 'delete_k8s_namespace': 'delete a Kubernetes namespace with foreground propagation policy and wait for it to be fully deleted'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/traffic_director.py

Prompts

```
['create a KubernetesApiManager instance to manage AppsV1Api and CoreV1Api clients for a given kubeconfig context', 'apply a Kubernetes manifest dictionary to a namespace using the KubernetesNamespace apply_manifest method', 'wait for a Kubernetes deployment to reach a specified number of available replicas with retry logic', 'forward a local port to a remote pod port using kubectl port-forward and return a Popen process', 'delete a Kubernetes namespace with foreground propagation policy and wait for it to be fully deleted', 'create a TrafficDirectorManager to set up gRPC backend services, health checks, and forwarding rules on GCP', 'setup a gRPC backend service with health check and routing rules using TrafficDirectorManager', 'create a TrafficDirectorSecureManager to configure TLS and mTLS policies for secure gRPC traffic on GCP', 'create a URL map and target proxy to route traffic from a host and port to a backend service', 'cleanup all Traffic Director resources including forwarding rules, proxies, URL maps, and backend services']
```

Usage

```
{'create_traffic_director_manager': 'create a TrafficDirectorManager to set up gRPC backend services, health checks, and forwarding rules on GCP', 'setup_grpc_backend_service': 'setup a gRPC backend service with health check and routing rules using TrafficDirectorManager', 'create_secure_traffic_director': 'create a TrafficDirectorSecureManager to configure TLS and mTLS policies for secure gRPC traffic on GCP', 'manage_url_map_and_proxy': 'create a URL map and target proxy to route traffic from a host and port to a backend service', 'cleanup_traffic_director_resources': 'cleanup all Traffic Director resources including forwarding rules, proxies, URL maps, and backend services'}
```

