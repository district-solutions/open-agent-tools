# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/tests/baseline_test.py

Prompts

```
['run the BaselineTest class to validate Traffic Director gRPC setup end to end', 'test the Traffic Director gRPC setup by creating health checks, backend services, and forwarding rules', 'create a health check and backend service via the Traffic Director test driver', 'start an xDS test server and client to verify RPC communication in Kubernetes', 'assert that the test server successfully received RPCs from the test client', 'run the mTLS security test to verify mutual TLS between client and server', 'run the TLS security test to verify one-way TLS between client and server', 'run the plaintext fallback test to verify client and server fallback to plaintext', 'run the mTLS error test to verify client fails when server expects mTLS cert', 'run the AuthZ error test to verify client rejects server with mismatched SAN name']
```

Usage

```
{'run_BaselineTest': 'run the BaselineTest class to validate Traffic Director gRPC setup end to end', 'test_traffic_director_grpc_setup': 'test the Traffic Director gRPC setup by creating health checks, backend services, and forwarding rules', 'create_health_check_backend_service': 'create a health check and backend service via the Traffic Director test driver', 'start_test_server_client': 'start an xDS test server and client to verify RPC communication in Kubernetes', 'assert_successful_rpcs': 'assert that the test server successfully received RPCs from the test client'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/xds_k8s_test_driver/tests/security_test.py

Prompts

```
['run the BaselineTest class to validate Traffic Director gRPC setup end to end', 'test the Traffic Director gRPC setup by creating health checks, backend services, and forwarding rules', 'create a health check and backend service via the Traffic Director test driver', 'start an xDS test server and client to verify RPC communication in Kubernetes', 'assert that the test server successfully received RPCs from the test client', 'run the mTLS security test to verify mutual TLS between client and server', 'run the TLS security test to verify one-way TLS between client and server', 'run the plaintext fallback test to verify client and server fallback to plaintext', 'run the mTLS error test to verify client fails when server expects mTLS cert', 'run the AuthZ error test to verify client rejects server with mismatched SAN name']
```

Usage

```
{'test_mtls_security': 'run the mTLS security test to verify mutual TLS between client and server', 'test_tls_security': 'run the TLS security test to verify one-way TLS between client and server', 'test_plaintext_fallback': 'run the plaintext fallback test to verify client and server fallback to plaintext', 'test_mtls_error': 'run the mTLS error test to verify client fails when server expects mTLS cert', 'test_server_authz_error': 'run the AuthZ error test to verify client rejects server with mismatched SAN name'}
```

