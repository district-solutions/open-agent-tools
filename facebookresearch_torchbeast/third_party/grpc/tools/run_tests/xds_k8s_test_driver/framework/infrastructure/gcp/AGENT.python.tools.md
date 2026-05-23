# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/gcp/api.py

Prompts

```
['build a GcpApiManager to lazily load compute, networksecurity, and secrets APIs from GCP discovery documents', 'create a GcpStandardCloudApiResource subclass to manage GCP cloud resources with CRUD operations', 'wait for a long-running GCP API operation to complete using tenacity retry logic', 'access a private API key from GCP Secret Manager via the GcpApiManager private_api_key property', 'delete a GCP resource by full name and handle 404 errors gracefully with logging', 'create a TCP health check resource on GCP Compute for backend service monitoring', 'create a Traffic Director backend service with health checks and protocol configuration', 'create a GCP URL map to route host rules to backend services', 'create a global forwarding rule for Traffic Director load balancing on a network', 'wait for all backends in a backend service to report healthy status', 'create a GCP server TLS policy with a given name and configuration body', 'get an existing GCP server TLS policy by name and return its details', 'delete an existing GCP server TLS policy by its name', 'create a GCP client TLS policy with a given name and configuration body', 'get an existing GCP client TLS policy by name and return its details', 'create an endpoint config selector resource in GCP Network Services with a given name and body', 'get an endpoint config selector by name and return its configuration details as an EndpointConfigSelector object', 'delete an endpoint config selector resource from GCP Network Services by its name', 'review the NetworkServicesV1Alpha1 class and its retry logic for handling throttled GCP operations reported as internal errors', 'summarize the EndpointConfigSelector frozen dataclass fields including url, name, type, server_tls_policy, and http_filters']
```

Usage

```
{'build_gcp_api_manager': 'build a GcpApiManager to lazily load compute, networksecurity, and secrets APIs from GCP discovery documents', 'create_gcp_resource': 'create a GcpStandardCloudApiResource subclass to manage GCP cloud resources with CRUD operations', 'wait_for_operation': 'wait for a long-running GCP API operation to complete using tenacity retry logic', 'access_private_api_key': 'access a private API key from GCP Secret Manager via the GcpApiManager private_api_key property', 'delete_gcp_resource': 'delete a GCP resource by full name and handle 404 errors gracefully with logging'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/gcp/compute.py

Prompts

```
['build a GcpApiManager to lazily load compute, networksecurity, and secrets APIs from GCP discovery documents', 'create a GcpStandardCloudApiResource subclass to manage GCP cloud resources with CRUD operations', 'wait for a long-running GCP API operation to complete using tenacity retry logic', 'access a private API key from GCP Secret Manager via the GcpApiManager private_api_key property', 'delete a GCP resource by full name and handle 404 errors gracefully with logging', 'create a TCP health check resource on GCP Compute for backend service monitoring', 'create a Traffic Director backend service with health checks and protocol configuration', 'create a GCP URL map to route host rules to backend services', 'create a global forwarding rule for Traffic Director load balancing on a network', 'wait for all backends in a backend service to report healthy status', 'create a GCP server TLS policy with a given name and configuration body', 'get an existing GCP server TLS policy by name and return its details', 'delete an existing GCP server TLS policy by its name', 'create a GCP client TLS policy with a given name and configuration body', 'get an existing GCP client TLS policy by name and return its details', 'create an endpoint config selector resource in GCP Network Services with a given name and body', 'get an endpoint config selector by name and return its configuration details as an EndpointConfigSelector object', 'delete an endpoint config selector resource from GCP Network Services by its name', 'review the NetworkServicesV1Alpha1 class and its retry logic for handling throttled GCP operations reported as internal errors', 'summarize the EndpointConfigSelector frozen dataclass fields including url, name, type, server_tls_policy, and http_filters']
```

Usage

```
{'create_health_check_tcp': 'create a TCP health check resource on GCP Compute for backend service monitoring', 'create_backend_service_traffic_director': 'create a Traffic Director backend service with health checks and protocol configuration', 'create_url_map': 'create a GCP URL map to route host rules to backend services', 'create_forwarding_rule': 'create a global forwarding rule for Traffic Director load balancing on a network', 'wait_for_backends_healthy_status': 'wait for all backends in a backend service to report healthy status'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/gcp/network_security.py

Prompts

```
['build a GcpApiManager to lazily load compute, networksecurity, and secrets APIs from GCP discovery documents', 'create a GcpStandardCloudApiResource subclass to manage GCP cloud resources with CRUD operations', 'wait for a long-running GCP API operation to complete using tenacity retry logic', 'access a private API key from GCP Secret Manager via the GcpApiManager private_api_key property', 'delete a GCP resource by full name and handle 404 errors gracefully with logging', 'create a TCP health check resource on GCP Compute for backend service monitoring', 'create a Traffic Director backend service with health checks and protocol configuration', 'create a GCP URL map to route host rules to backend services', 'create a global forwarding rule for Traffic Director load balancing on a network', 'wait for all backends in a backend service to report healthy status', 'create a GCP server TLS policy with a given name and configuration body', 'get an existing GCP server TLS policy by name and return its details', 'delete an existing GCP server TLS policy by its name', 'create a GCP client TLS policy with a given name and configuration body', 'get an existing GCP client TLS policy by name and return its details', 'create an endpoint config selector resource in GCP Network Services with a given name and body', 'get an endpoint config selector by name and return its configuration details as an EndpointConfigSelector object', 'delete an endpoint config selector resource from GCP Network Services by its name', 'review the NetworkServicesV1Alpha1 class and its retry logic for handling throttled GCP operations reported as internal errors', 'summarize the EndpointConfigSelector frozen dataclass fields including url, name, type, server_tls_policy, and http_filters']
```

Usage

```
{'create_server_tls_policy': 'create a GCP server TLS policy with a given name and configuration body', 'get_server_tls_policy': 'get an existing GCP server TLS policy by name and return its details', 'delete_server_tls_policy': 'delete an existing GCP server TLS policy by its name', 'create_client_tls_policy': 'create a GCP client TLS policy with a given name and configuration body', 'get_client_tls_policy': 'get an existing GCP client TLS policy by name and return its details'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/framework/infrastructure/gcp/network_services.py

Prompts

```
['build a GcpApiManager to lazily load compute, networksecurity, and secrets APIs from GCP discovery documents', 'create a GcpStandardCloudApiResource subclass to manage GCP cloud resources with CRUD operations', 'wait for a long-running GCP API operation to complete using tenacity retry logic', 'access a private API key from GCP Secret Manager via the GcpApiManager private_api_key property', 'delete a GCP resource by full name and handle 404 errors gracefully with logging', 'create a TCP health check resource on GCP Compute for backend service monitoring', 'create a Traffic Director backend service with health checks and protocol configuration', 'create a GCP URL map to route host rules to backend services', 'create a global forwarding rule for Traffic Director load balancing on a network', 'wait for all backends in a backend service to report healthy status', 'create a GCP server TLS policy with a given name and configuration body', 'get an existing GCP server TLS policy by name and return its details', 'delete an existing GCP server TLS policy by its name', 'create a GCP client TLS policy with a given name and configuration body', 'get an existing GCP client TLS policy by name and return its details', 'create an endpoint config selector resource in GCP Network Services with a given name and body', 'get an endpoint config selector by name and return its configuration details as an EndpointConfigSelector object', 'delete an endpoint config selector resource from GCP Network Services by its name', 'review the NetworkServicesV1Alpha1 class and its retry logic for handling throttled GCP operations reported as internal errors', 'summarize the EndpointConfigSelector frozen dataclass fields including url, name, type, server_tls_policy, and http_filters']
```

Usage

```
{'create_endpoint_config_selector': 'create an endpoint config selector resource in GCP Network Services with a given name and body', 'get_endpoint_config_selector': 'get an endpoint config selector by name and return its configuration details as an EndpointConfigSelector object', 'delete_endpoint_config_selector': 'delete an endpoint config selector resource from GCP Network Services by its name', 'review_NetworkServicesV1Alpha1_class': 'review the NetworkServicesV1Alpha1 class and its retry logic for handling throttled GCP operations reported as internal errors', 'summarize_EndpointConfigSelector_dataclass': 'summarize the EndpointConfigSelector frozen dataclass fields including url, name, type, server_tls_policy, and http_filters'}
```

